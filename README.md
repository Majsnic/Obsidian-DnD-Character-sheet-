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
| **Meta Bind** | Powers the live `VIEW`/`INPUT` fields (ability scores, add-action/add-item forms, etc.) and the `BUTTON[...]` widgets. **You must also turn on "Enable JavaScript" in Meta Bind's own settings** — separate from Dataview's setting above, and also off by default. Without it, buttons that run a JS action (tab switching, Add Action, Add Item, Set Temp HP) fail with an error like `[MB_JS] Can't run button action that requires JS evaluation`. |
| **JS Engine** | A separate plugin that Meta Bind depends on for any button using `evaluate: true` — install and enable this *before* trying the buttons above, or the same JS evaluation error occurs. |
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

## What's in this repo

```
character-sheet-template.md      the blank character sheet itself
PLAYER.md                        Templater script - creates a new character via a button
Spell Slot Tables.md             reference data the Spells tab needs (see Setup #4)
Modal Forms - PC.json            the "PC" form definition for the creation flow
snippets/
  dnd-sheet.css
  Callouts.css
  TTRPG-Index-Callouts.css
  Columns.css
  Buttons.css
examples/
  Fire Bolt.md                   example cantrip note
  Cure Wounds.md                 example leveled spell note, with upcast
```

## Setup

1. Install and enable **Dataview**, **Meta Bind**, **JS Engine**, **Bases** (if not built into your Obsidian version), **Templater**, and **Modal Forms**. Then, before doing anything else:
   - In **Dataview's** settings, turn on **"Enable JavaScript Queries."**
   - In **Meta Bind's** settings, turn on **"Enable JavaScript."**
   
   Both are off by default and both are required — skipping either one causes the sheet to either not render at all (Dataview) or throw a `[MB_JS] Can't run button action that requires JS evaluation` error the moment you click any button (Meta Bind). JS Engine has no setting to toggle, it just needs to be installed and enabled for Meta Bind's JS actions to work at all.
2. Copy everything in `snippets/` into your vault's `.obsidian/snippets/` folder and enable all five in Settings → Appearance → CSS snippets.
3. Copy `character-sheet-template.md` and `PLAYER.md` into your vault, anywhere Dataview can see them.
4. Copy `Spell Slot Tables.md` into your vault **without renaming it**. The Spells tab looks it up by this exact name (`dv.page("Spell Slot Tables")`). If it's missing or renamed, spellcasters show a warning and lose slot tracking — nothing else on the sheet breaks.
5. Import `Modal Forms - PC.json` as the "PC" form in Modal Forms' settings (see that plugin's own docs for importing a form definition) so the creation flow has Race / Class / Subclass / Alignment options to offer.
6. **Not included**: the Meta Bind button templates referenced by ID throughout the sheet — `add-action-btn`, `add-item-btn`, `set-temp-hp`, and `tab-actions-btn` / `tab-spells-btn` / `tab-inventory-btn` / `tab-features-btn` / `tab-notes-btn`. These live entirely in Meta Bind's own plugin configuration, not in any markdown file, so they can't be packaged the same way as the Modal Form above. You'll need to build these yourself in Meta Bind's Button Builder — each just needs to perform the obvious action its ID suggests (switch to the matching tab, run the matching "add" logic, etc.), matching whatever button ID the template calls.
7. By default, new characters save into a `Characters/` folder, and the built-in quest/session-log tables look inside `Quests/` and `Session Notes/` respectively — plain top-level folders so the sheet works out of the box. Rename these to match your own vault structure by editing the matching `file.inFolder(...)` lines in `character-sheet-template.md` and `PLAYER.md` (two lines each), and the save path near the top of `PLAYER.md`.

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

None of these properties are strictly required — a spell still shows up in the list and works fine if a property is missing, it just displays that column blank (or treats a missing `Spell level` as a Cantrip). Two example notes are included in `examples/`: `Fire Bolt.md` (a simple cantrip) and `Cure Wounds.md` (a leveled spell demonstrating both the `+ spellcasting ability modifier` auto-substitution and the automatic upcast display via `Upscale`).

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

<img width="1173" height="905" alt="Example" src="https://github.com/user-attachments/assets/9e925519-1800-4889-ae4f-b39fe72fdc45" />
