# D&D Character Sheet System for Obsidian

A fully interactive Dungeons & Dragons character sheet built entirely in Obsidian using DataviewJS, Meta Bind, and Bases — no external character sheet app needed. Character creation, ability scores, saving throws, skills, actions, spells (with automatic slot tracking, including proper multiclass support), inventory, features, and conditions all live and update directly inside your vault.

## Features

- Interactive tabbed layout (Actions / Spells / Inventory / Features / Notes)
- Live-editable ability scores, saving throws, skills, and senses
- Actions tab with Name / Category / Range / Hit-DC / Damage / Damage Type columns, plus a per-row edit modal
- Spell slot tracking with real multiclass support — Warlock's Pact Magic is always calculated separately from other spellcasting classes, matching actual 5e rules
- Spell upcast display, calculated automatically from each spell's own note
- Inventory and Features tabs with add / edit / remove
- "Copy Blank Template" button to spin up a new blank sheet from an existing one
- "Update Character Sheet" modal with dropdowns matching your Modal Forms creation options (Race / Class / Subclass / Alignment)

## Requirements

### Obsidian plugins

| Plugin | Why it's needed |
|---|---|
| **Dataview** | The entire sheet is built with DataviewJS. **You must turn on "Enable JavaScript Queries" in Dataview's settings — it's off by default**, and the sheet won't render at all without it. |
| **Meta Bind** | Powers the live `VIEW`/`INPUT` fields (ability scores, add-action/add-item forms, etc.) and the `BUTTON[...]` widgets. |
| **Bases** | Used for the two small linked-notes tables (quest log / session log) on each sheet. Built into newer versions of Obsidian; install as a community plugin on older versions. |
| **Templater** | Required only for `PLAYER.md`, the character-creation script. |
| **Modal Forms** | Required only for `PLAYER.md`. You'll need to import the included `PC` form definition (see Setup below) for the creation button to work. |

### Theme

Built and tested against **ITS Theme**. The card drop-shadows specifically rely on the `--shadow-l` CSS variable, which ITS Theme defines. If you use a different theme, either install ITS Theme alongside it or add your own fallback value for `--shadow-l` near the top of `dnd-sheet.css`.

### CSS snippets

Enable all five in Settings → Appearance → CSS snippets:

| Snippet | What it's for |
|---|---|
| `dnd-sheet.css` | The core stylesheet — nearly all of the sheet's look lives here. |
| `Callouts.css` | Base callout skin (border, icon, color) that the DĚJOVÁ LINIE/HISTORIE buttons and the backstory quote box build on. |
| `TTRPG-Index-Callouts.css` | A few vault-wide callout rules that `dnd-sheet.css` has to specifically counteract — required despite the name. |
| `Columns.css` | Lays the two buttons out side-by-side. |
| `Buttons.css` | Styles the button widgets, including their centering. |

## Setup

1. Copy the files from `snippets/` into your vault's `.obsidian/snippets/` folder and enable all five listed above.
2. Copy `character-sheet-template.md` and `PLAYER.md` into your vault, anywhere Dataview can see them.
3. Copy `Spell Slot Tables.md` into your vault **without renaming it**. The Spells tab looks it up by this exact name (`dv.page("Spell Slot Tables")`). If it's missing or renamed, spellcasters show a warning and lose slot tracking — nothing else on the sheet breaks.
4. Import the included Modal Forms `PC` form definition (Settings → Modal Forms, or merge it into your plugin's own `data.json` — see Modal Forms' own docs for importing a form) so the creation flow has Race / Class / Subclass / Alignment options to offer.
5. Re-create the Meta Bind button templates referenced by ID throughout the sheet in Meta Bind's own settings: `add-action-btn`, `add-item-btn`, `set-temp-hp`, and `tab-actions-btn` / `tab-spells-btn` / `tab-inventory-btn` / `tab-features-btn` / `tab-notes-btn`. These aren't stored in the markdown files — they live in the plugin's own configuration.

## Optional: spell notes

The Spells tab reads any note tagged `#Spell`, optionally using this frontmatter schema:

```yaml
Spell level: 3
Damage / Effect: "3d8 Fire"
Upscale: "+ 1d8 per slot level above 3rd"
Casting Time: Action
Range / Area: "150 ft. (20 ft. Sphere)"
Attack / Save: DEX Save
```

None of these properties are strictly required — a spell still shows up in the list and works fine if a property is missing, it just displays that column blank (or treats a missing `Spell level` as a Cantrip). A couple of example spell notes are included as a starting point for the schema.

## Creating a character

- **Via the button**: use the `pc` button to open the Modal Forms creation flow in `PLAYER.md`, which prompts for Race, Class(es), Subclass(es), ability scores, and more.
- **Via a blank copy**: open any existing sheet, click "Copy Blank Template," and paste the result into a new note.

Either way, ongoing edits after creation — level-ups, new gear, a changed alignment — go through the "Update Character Sheet" button on the sheet itself.

## Multiclassing

Check more than one class in the "Update Character Sheet" modal and a "Levels per Class" field appears — fill in each class's own level there; a single-class character never sees this and just uses the plain Level field as normal.

Warlock's Pact Magic is always calculated on its own from Warlock level alone, and tracked completely separately from other spellcasting classes. Every other spellcasting class combines into one shared slot pool using the standard 5e multiclass conversion: full casters count their whole level, half-casters and third-casters round down (÷2 and ÷3 respectively), and Artificer is the one exception, rounding up.

## Known limitations

- The Race / Class / Subclass / Alignment dropdowns are built from a fixed list matching the included Modal Forms setup. Homebrew values still work — if a character's *current* value isn't on the list, it's automatically added and pre-selected rather than lost, so opening the modal on an existing homebrew character never silently overwrites their data.
- Background stays a free-text field, matching the creation form.
- Third-caster detection (Eldritch Knight, Arcane Trickster) is based on subclass name matching. Other homebrew third-caster subclasses would need to be added to the `THIRD_CASTER_SUBCLASSES` list in both `character-sheet-template.md` and `PLAYER.md`.

Example screenshots:
<img width="1171" height="936" alt="Snímek obrazovky 2026-09-02 144849" src="https://github.com/user-attachments/assets/571853b6-41fd-4a03-8669-cb56c0a802a8" />
<img width="1128" height="805" alt="Snímek obrazovky 2026-09-02 144915" src="https://github.com/user-attachments/assets/dee7757b-54ab-4300-95b8-b3d581f75a01" />
<img width="1116" height="711" alt="Snímek obrazovky 2026-09-02 144902" src="https://github.com/user-attachments/assets/00be72f9-be00-411f-879b-3edb01d88bb5" />
