---
cssclasses:
  - dnd-sheet
  - tab-spells
character_name: Template PC
class: Ranger / Warlock
subclass: Gloom Stalker / Hexblade
class_levels:
  Ranger: 6
  Warlock: 2
level: 8
rules_edition: "2024"
race: Ice Genasi
background: Cloistered Scholar
alignment: Neutral
player: ""
cover: player.png
armor_class: "15"
initiative: "+8"
str_mod: "+1"
str_score: 12
dex_mod: "+4"
dex_score: 19
con_mod: "+2"
con_score: 15
int_mod: "+2"
int_score: 15
wis_mod: "+4"
wis_score: 18
cha_mod: "+2"
cha_score: 14
special_senses_list:
  - Darkvision 60 ft.
spells:
  - "[[Ray of Frost]]"
  - "[[Armor of Agathys]]"
  - "[[Cure Wounds]]"
  - "[[Disguise Self]]"
  - "[[Hail of Thorns]]"
  - "[[Hunter’s Mark]]"
  - "[[Rime’s Binding Ice]]"
  - "[[Rope Trick]]"
hp_current: 61
hp_max: 69
temp_hp: 0
dmg_amount: 0
temp_hp_input: 0
actions_list:
  - name: Dagger
    type: Action
    hit: "+7"
    damage: 1d4+4
    damage_type: Piercing
  - name: Longbow
    type: Action
    hit: "+9"
    damage: 1d8+4
    damage_type: Piercing
  - name: Shortsword
    type: Action
    hit: "+7"
    damage: 1d6+4
    damage_type: Piercing
  - name:
      - - Ray of Frost
    type: Action
    hit: "+3"
    damage: 2d8
    damage_type: Cold
  - name: Unnarmed Strike
    type: Action
    hit: "+4"
    damage: 2
    damage_type: Bludgeoning
  - name: Opportunity Attack
    type: Reaction
    hit: ""
    damage: ""
    max: 0
    used: 0
    rest: Short
  - name: Two-Weapon Fighting
    type: Bonus Action
    hit: ""
    damage: ""
    max: 0
    used: 0
    rest: Short
  - name: Hail of Thorns
    type: Bonus Action
    hit: ""
    damage: ""
    max: 0
    used: 0
    rest: Short
  - name: Hunter's Mark
    type: Bonus Action
    hit: ""
    damage: ""
    max: 0
    used: 0
    rest: Short
new_action_name: ""
new_action_type: Bonus Action
new_action_max: 0
new_action_range: ""
new_action_rest: Short
new_action_hit: ""
new_action_damage: ""
new_action_damage_type: ""
inventory_list:
  - name: Bedroll
    weight: 7 lb.
    qty: 1
    cost: "1"
  - name: Mess Kit
    weight: 1 lb.
    qty: 1
    cost: "0.2"
  - name: Rations (1 day)
    weight: 20 lb.
    qty: 10
    cost: "5"
  - name: Rope, Hempen (50 feet)
    weight: 10 lb.
    qty: 1
    cost: "1"
  - name: Tinderbox
    weight: 1 lb.
    qty: 1
    cost: "0.5"
  - name: Torch
    weight: 10 lb.
    qty: 10
    cost: "0.1"
  - name: Waterskin
    weight: 5 lb.
    qty: 1
    cost: "0.2"
new_item_name: ""
new_item_weight: ""
new_item_qty: ""
new_item_cost: ""
limited_uses:
  - name: Favored Foe
    description: When you hit a creature with an attack roll, you can mark the target as your favored enemy for 1 minute or until you lose your concentration (as if you were concentrating on a spell). The first time on each of your turns that you hit the favored enemy and deal damage to it, including when you mark it, you can increase that damage by 1d6.
    max: 3
    used: 0
    rest: Long
  - name: "Fighting Style: Archery"
    description: You gain a +2 bonus to attack rolls you make with ranged weapons.
    max: 0
    used: 0
    rest: Short
  - name: Umbral Sight
    description: You gain darkvision out to a range of 60 ft. (+30 ft. if you already have it). While in darkness, you are invisible to any creature that relies on darkvision to see you in the darkness.
    max: 0
    used: 0
    rest: Short
conditions_active: []
player_notes: ""
base_speed: 35 ft.
movement_types: Walking, Climbing, Swimming
exhaustion_level: 0
new_condition_name: ""
saves_list:
  - ability: STR
    mod: "+4"
    prof: true
  - ability: DEX
    mod: "+7"
    prof: true
  - ability: CON
    mod: "+2"
    prof: false
  - ability: INT
    mod: "+2"
    prof: false
  - ability: WIS
    mod: "+7"
    prof: true
  - ability: CHA
    mod: "+2"
    prof: false
senses_list:
  - name: Passive Perception
    value: "17"
  - name: Passive Investigation
    value: "15"
  - name: Passive Insight
    value: "14"
skills_list:
  - ability: DEX
    name: Acrobatics
    mod: "+4"
    prof: false
  - ability: WIS
    name: Animal Handling
    mod: "+4"
    prof: false
  - ability: INT
    name: Arcana
    mod: "+2"
    prof: false
  - ability: STR
    name: Athletics
    mod: "+1"
    prof: false
  - ability: CHA
    name: Deception
    mod: "+2"
    prof: false
  - ability: INT
    name: History
    mod: "+5"
    prof: true
  - ability: WIS
    name: Insight
    mod: "+4"
    prof: false
  - ability: CHA
    name: Intimidation
    mod: "+2"
    prof: false
  - ability: INT
    name: Investigation
    mod: "+5"
    prof: true
  - ability: WIS
    name: Medicine
    mod: "+4"
    prof: false
  - ability: INT
    name: Nature
    mod: "+2"
    prof: false
  - ability: WIS
    name: Perception
    mod: "+7"
    prof: true
  - ability: CHA
    name: Performance
    mod: "+2"
    prof: false
  - ability: CHA
    name: Persuasion
    mod: "+2"
    prof: false
  - ability: INT
    name: Religion
    mod: "+5"
    prof: true
  - ability: DEX
    name: Sleight of Hand
    mod: "+4"
    prof: false
  - ability: DEX
    name: Stealth
    mod: "+4"
    prof: false
  - ability: WIS
    name: Survival
    mod: "+7"
    prof: true
defenses_active: []
spellcasting_modifier: "+4"
spell_attack_bonus: "+7"
spell_save_dc: "15"
spell_slots_used:
  "1": 3
  "2": 2
heroic_inspiration: false
death_saves_success:
  - false
  - false
  - false
death_saves_fail:
  - false
  - false
  - false
---

# Template PC

> [!row]
>
>> [!charinfo] Overview
>>
>> <div class="overview-flex-row">
>>
>> <div class="overview-left-col">
>>
>> **Race:** `VIEW[{race}][text]`<br>
>> **Class:** `VIEW[{class}][text]`<br>
>> **Subclass:** `VIEW[{subclass}][text]`<br>
>> **Level:** `VIEW[{level}][text]`<br>
>> **Background:** `VIEW[{background}][text]`<br>
>> **Alignment:** `VIEW[{alignment}][text]`<br>
>> **Player:** `VIEW[{player}][text]`<br>
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>>
>> const overviewBtnRow = dv.container.createEl("div", {cls: "hp-extra-row"});
>> const updateBtn = overviewBtnRow.createEl("button", {cls: "action-btn-update", text: "Update Character Sheet"});
>> updateBtn.onclick = () => {
>>   const freshPage = app.metadataCache.getFileCache(file)?.frontmatter || page;
>>   openCharSheetModal(freshPage, file);
>> };
>>
>> const copyBtn = overviewBtnRow.createEl("button", {cls: "action-btn-update", text: "Copy Blank Template"});
>> copyBtn.onclick = async () => {
>>   try {
>>     const content = await app.vault.read(file);
>>
>>     const fmMatch = content.match(/^---\n([\s\S]*?)\n---\n/);
>>     let body = fmMatch ? content.slice(fmMatch[0].length) : content;
>>
>>     const blankFrontmatter = `---
>> cssclasses:
>>   - dnd-sheet
>>   - tab-actions
>> character_name: New Character
>> class: ""
>> subclass: ""
>> class_levels: {}
>> level: 1
>> rules_edition: "2024"
>> race: ""
>> background: ""
>> alignment: ""
>> player: ""
>> armor_class: 10
>> initiative: "+0"
>> str_mod: "+0"
>> str_score: 10
>> dex_mod: "+0"
>> dex_score: 10
>> con_mod: "+0"
>> con_score: 10
>> int_mod: "+0"
>> int_score: 10
>> wis_mod: "+0"
>> wis_score: 10
>> cha_mod: "+0"
>> cha_score: 10
>> special_senses_list: []
>> spells: []
>> hp_current: 10
>> hp_max: 10
>> temp_hp: 0
>> dmg_amount: 0
>> temp_hp_input: 0
>> actions_list: []
>> new_action_name: ""
>> new_action_type: Action
>> new_action_max: 0
>> new_action_range: ""
>> new_action_rest: Short
>> new_action_hit: ""
>> new_action_damage: ""
>> new_action_damage_type: ""
>> inventory_list: []
>> new_item_name: ""
>> new_item_weight: ""
>> new_item_qty: ""
>> new_item_cost: ""
>> limited_uses: []
>> conditions_active: []
>> player_notes: ""
>> base_speed: "30 ft."
>> movement_types: Walking
>> exhaustion_level: 0
>> new_condition_name: ""
>> saves_list:
>>   - {ability: STR, mod: "+0", prof: false}
>>   - {ability: DEX, mod: "+0", prof: false}
>>   - {ability: CON, mod: "+0", prof: false}
>>   - {ability: INT, mod: "+0", prof: false}
>>   - {ability: WIS, mod: "+0", prof: false}
>>   - {ability: CHA, mod: "+0", prof: false}
>> senses_list:
>>   - {name: Passive Perception, value: 10}
>>   - {name: Passive Investigation, value: 10}
>>   - {name: Passive Insight, value: 10}
>> skills_list:
>>   - {ability: DEX, name: Acrobatics, mod: "+0", prof: false}
>>   - {ability: WIS, name: Animal Handling, mod: "+0", prof: false}
>>   - {ability: INT, name: Arcana, mod: "+0", prof: false}
>>   - {ability: STR, name: Athletics, mod: "+0", prof: false}
>>   - {ability: CHA, name: Deception, mod: "+0", prof: false}
>>   - {ability: INT, name: History, mod: "+0", prof: false}
>>   - {ability: WIS, name: Insight, mod: "+0", prof: false}
>>   - {ability: CHA, name: Intimidation, mod: "+0", prof: false}
>>   - {ability: INT, name: Investigation, mod: "+0", prof: false}
>>   - {ability: WIS, name: Medicine, mod: "+0", prof: false}
>>   - {ability: INT, name: Nature, mod: "+0", prof: false}
>>   - {ability: WIS, name: Perception, mod: "+0", prof: false}
>>   - {ability: CHA, name: Performance, mod: "+0", prof: false}
>>   - {ability: CHA, name: Persuasion, mod: "+0", prof: false}
>>   - {ability: INT, name: Religion, mod: "+0", prof: false}
>>   - {ability: DEX, name: Sleight of Hand, mod: "+0", prof: false}
>>   - {ability: DEX, name: Stealth, mod: "+0", prof: false}
>>   - {ability: WIS, name: Survival, mod: "+0", prof: false}
>> defenses_active: []
>> spellcasting_modifier: "+0"
>> spell_attack_bonus: "+0"
>> spell_save_dc: "10"
>> spell_slots_used: {}
>> heroic_inspiration: false
>> death_saves_success:
>>   - false
>>   - false
>>   - false
>> death_saves_fail:
>>   - false
>>   - false
>>   - false
>> ---
>> `;
>>
>>     await navigator.clipboard.writeText(blankFrontmatter + body);
>>     copyBtn.textContent = "Copied!";
>>   } catch (e) {
>>     copyBtn.textContent = "Copy failed";
>>   }
>>   setTimeout(() => { copyBtn.textContent = "Copy Blank Template"; }, 1500);
>> };
>>
>> function textField(container, label, value) {
>>   const row = container.createEl("div", {cls: "action-modal-row"});
>>   row.createEl("span", {cls: "action-modal-label", text: label});
>>   const input = row.createEl("input", {type: "text", cls: "action-modal-name"});
>>   input.value = value ?? "";
>>   return input;
>> }
>>
>> function openCharSheetModal(page, file) {
>>   const overlay = document.createElement("div");
>>   overlay.className = "action-modal-overlay";
>>   const modal = overlay.createEl("div", {cls: "action-modal action-modal-wide"});
>>   modal.createEl("h3", {text: "Update Character Sheet"});
>>
>>   const colWrap = modal.createEl("div", {cls: "modal-columns"});
>>   const leftCol = colWrap.createEl("div", {cls: "modal-col"});
>>   const rightCol = colWrap.createEl("div", {cls: "modal-col"});
>>
>>   // Option lists mirrored from the "PC" Modal Form, so the Update
>>   // modal offers the same choices as character creation.
>>   const RACE_OPTIONS = ["Aarakocra","Aasimar","Bugbear","Centaur","Changeling","Dragonborn","Dwarf","Elf","Fairy","Firbolg","Genasi","Gnome","Goblin","Goliath","Grung","Halfling","Half-Elf","Half-Orc","Hobgoblin","Human","Kalashtar","Kenku","Kobold","Leonin","Lizardfolk","Loxodon","Minotaur","Orc","Owlfolk","Satyr","Shifter","Simic Hybrid","Tabaxi","Tiefling","Tortle","Triton","Vedalken","Verdan","Warforged","Yuan-Ti Pureblood"];
>>   const CLASS_OPTIONS = ["Artificer","Barbarian","Bard","Cleric","Druid","Fighter","Monk","Paladin","Ranger","Rogue","Sorcerer","Warlock","Wizard"];
>>   const SUBCLASS_MAP = {
>>     "Artificer": ["Alchemist","Armorer","Artillerist","Battle Smith"],
>>     "Barbarian": ["Ancestral Guardian","Battlerager","Berserker","Storm Herald","Totem Warrior","Zealot"],
>>     "Bard": ["College of Creation","College of Eloquence","College of Glamour","College of Lore","College of Swords","College of Valor","College of Whispers"],
>>     "Cleric": ["Arcana Domain","Death Domain","Forge Domain","Grave Domain","Knowledge Domain","Life Domain","Light Domain","Nature Domain","Order Domain","Peace Domain","Tempest Domain","Trickery Domain","Twilight Domain","War Domain"],
>>     "Druid": ["Circle of Dreams","Circle of Spores","Circle of Stars","Circle of the Land","Circle of the Moon","Circle of the Shepherd","Circle of Wildfire"],
>>     "Fighter": ["Arcane Archer","Battle Master","Cavalier","Champion","Echo Knight","Eldritch Knight","Psi Warrior","Purple Dragon Knight","Rune Knight","Samurai"],
>>     "Monk": ["Drunken Master","Four Elements","Kensei","Long Death","Mercy","Open Hand","Shadow","Sun Soul"],
>>     "Paladin": ["Ancients","Conquest","Crown","Devotion","Glory","Oathbreaker","Redemption","Vengeance","Watchers"],
>>     "Ranger": ["Beast Master","Fey Wanderer","Gloom Stalker","Horizon Walker","Hunter","Monster Slayer","Swarmkeeper"],
>>     "Rogue": ["Arcane Trickster","Assassin","Inquisitive","Mastermind","Phantom","Scout","Soulknife","Swashbuckler","Thief"],
>>     "Sorcerer": ["Aberrant Mind","Clockwork Soul","Divine Soul","Draconic Bloodline","Shadow Magic","Storm Sorcery","Wild Magic"],
>>     "Warlock": ["Archfey","Celestial","Fathomless","Fiend","Genie","Great Old One","Hexblade","Undead","Undying"],
>>     "Wizard": ["Bladesinging","Chronurgy","Graviturgy","Lore Mastery","Order of Scribes","School of Abjuration","School of Conjuration","School of Divination","School of Enchantment","School of Evocation","School of Illusion","School of Necromancy","School of Transmutation","War Magic"],
>>   };
>>   const ALIGNMENT_OPTIONS = ["Lawfull Good","Neutral Good","Chaotic Good","Lawfull Neutral","True Neutral","Chaotic Neutral","Lawfull Evil","Neutral Evil","Chaotic Evil"];
>>
>>   function selectField(container, label, value, options) {
>>     const row = container.createEl("div", {cls: "action-modal-row"});
>>     row.createEl("span", {cls: "action-modal-label", text: label});
>>     const select = row.createEl("select", {cls: "action-modal-name"});
>>     const opts = [...options];
>>     if (value && !opts.includes(value)) opts.unshift(value);
>>     for (const o of opts) {
>>       const opt = select.createEl("option", {text: o});
>>       opt.value = o;
>>       if (o === value) opt.selected = true;
>>     }
>>     return select;
>>   }
>>
>>   function checklistField(container, label) {
>>     const wrap = container.createEl("div", {cls: "action-modal-row"});
>>     wrap.createEl("span", {cls: "action-modal-label", text: label});
>>     const box = wrap.createEl("div", {cls: "checklist-box"});
>>     return box;
>>   }
>>
>>   // ---- LEFT COLUMN: Overview, Senses, Combat Values, Hit Points ----
>>   leftCol.createEl("div", {cls: "stat-subheader", text: "Overview"});
>>   const raceSelect = selectField(leftCol, "Race", page.race, RACE_OPTIONS);
>>
>>   const currentClasses = String(page.class || "").split(" / ").map(s => s.trim()).filter(Boolean);
>>   const classBox = checklistField(leftCol, "Class");
>>   const classChecks = [];
>>   const classOptsWithCustom = [...CLASS_OPTIONS];
>>   for (const v of currentClasses) if (!classOptsWithCustom.includes(v)) classOptsWithCustom.push(v);
>>   for (const opt of classOptsWithCustom) {
>>     const lbl = classBox.createEl("label", {cls: "checklist-item"});
>>     const cb = lbl.createEl("input", {type: "checkbox"});
>>     cb.value = opt;
>>     cb.checked = currentClasses.includes(opt);
>>     lbl.appendText(" " + opt);
>>     classChecks.push(cb);
>>   }
>>
>>   const currentSubclasses = String(page.subclass || "").split(" / ").map(s => s.trim()).filter(Boolean);
>>   const selectedSubclasses = new Set(currentSubclasses);
>>   const subclassBox = checklistField(leftCol, "Subclass");
>>   function renderSubclassOptions() {
>>     subclassBox.empty();
>>     const selectedClasses = classChecks.filter(cb => cb.checked).map(cb => cb.value);
>>     let opts = selectedClasses.length
>>       ? selectedClasses.flatMap(c => SUBCLASS_MAP[c] || [])
>>       : Object.values(SUBCLASS_MAP).flat();
>>     for (const v of selectedSubclasses) if (!opts.includes(v)) opts.push(v);
>>     for (const opt of opts) {
>>       const lbl = subclassBox.createEl("label", {cls: "checklist-item"});
>>       const cb = lbl.createEl("input", {type: "checkbox"});
>>       cb.value = opt;
>>       cb.checked = selectedSubclasses.has(opt);
>>       cb.addEventListener("change", () => {
>>         if (cb.checked) selectedSubclasses.add(opt); else selectedSubclasses.delete(opt);
>>       });
>>       lbl.appendText(" " + opt);
>>     }
>>   }
>>   renderSubclassOptions();
>>   for (const cb of classChecks) cb.addEventListener("change", renderSubclassOptions);
>>
>>   // Per-class level breakdown - only shown/relevant for multiclass
>>   // characters, since spell slots need to know how many levels are in
>>   // each class (Warlock's Pact Magic in particular is calculated from
>>   // Warlock level alone, never combined with other classes).
>>   const currentClassLevels = page.class_levels || {};
>>   const levelsBox = checklistField(leftCol, "Levels per Class");
>>   const classLevelInputs = {};
>>   function renderClassLevels() {
>>     levelsBox.empty();
>>     for (const key of Object.keys(classLevelInputs)) delete classLevelInputs[key];
>>     const checked = classChecks.filter(cb => cb.checked).map(cb => cb.value);
>>     if (checked.length <= 1) {
>>       levelsBox.createEl("span", {cls: "action-modal-hint", text: "Only needed for multiclass - single class uses Level below."});
>>       return;
>>     }
>>     for (const cname of checked) {
>>       const row = levelsBox.createEl("div", {cls: "checklist-item"});
>>       row.createEl("span", {text: cname + ": "});
>>       const inp = row.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>       inp.value = currentClassLevels[cname] || "";
>>       classLevelInputs[cname] = inp;
>>     }
>>   }
>>   renderClassLevels();
>>   for (const cb of classChecks) cb.addEventListener("change", renderClassLevels);
>>
>>   const levelInput = textField(leftCol, "Level", page.level);
>>   const backgroundInput = textField(leftCol, "Background", page.background);
>>   const alignmentSelect = selectField(leftCol, "Alignment", page.alignment, ALIGNMENT_OPTIONS);
>>   const playerInput = textField(leftCol, "Player", page.player);
>>   const portraitRow = leftCol.createEl("div", {cls: "action-modal-row"});
>>   portraitRow.createEl("span", {cls: "action-modal-label", text: "Portrait"});
>>   const portraitFileInput = portraitRow.createEl("input", {type: "file", attr: {accept: "image/*"}});
>>   portraitFileInput.style.display = "none";
>>   const portraitBrowseBtn = portraitRow.createEl("button", {cls: "action-btn-update", text: "Browse..."});
>>   portraitBrowseBtn.onclick = () => portraitFileInput.click();
>>   const portraitStatus = portraitRow.createEl("span", {cls: "condition-desc", text: page.cover || "player.png"});
>>   let selectedPortraitFile = null;
>>   portraitFileInput.onchange = () => {
>>     if (portraitFileInput.files && portraitFileInput.files[0]) {
>>       selectedPortraitFile = portraitFileInput.files[0];
>>       portraitStatus.textContent = `New: ${selectedPortraitFile.name} (saved on Save)`;
>>     }
>>   };
>>
>>   leftCol.createEl("div", {cls: "stat-subheader", text: "Ability Scores"});
>>   const ABILITY_KEYS = ["str", "dex", "con", "int", "wis", "cha"];
>>   function calcModifier(score) {
>>     const s = Number(score);
>>     if (isNaN(s)) return "+0";
>>     const mod = Math.floor((s - 10) / 2);
>>     return mod >= 0 ? `+${mod}` : `${mod}`;
>>   }
>>   const abilityRows = ABILITY_KEYS.map((key) => {
>>     const row = leftCol.createEl("div", {cls: "ability-edit-row"});
>>     row.createEl("span", {cls: "action-modal-label", text: key.toUpperCase()});
>>     const scoreInput = row.createEl("input", {type: "text"});
>>     scoreInput.value = page[`${key}_score`] ?? "";
>>     scoreInput.title = "Score";
>>     const modPreview = row.createEl("span", {cls: "condition-desc", text: calcModifier(scoreInput.value)});
>>     scoreInput.oninput = () => {
>>       modPreview.textContent = calcModifier(scoreInput.value);
>>     };
>>     return {key, scoreInput};
>>   });
>>
>>   leftCol.createEl("div", {cls: "stat-subheader", text: "Passive Senses"});
>>   const senses = page.senses_list || [];
>>   const senseRows = senses.map((item) => {
>>     const row = leftCol.createEl("div", {cls: "action-modal-row"});
>>     row.createEl("span", {cls: "action-modal-label", text: item.name});
>>     const valInput = row.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>     valInput.value = item.value;
>>     return {name: item.name, valInput};
>>   });
>>
>>   leftCol.createEl("div", {cls: "stat-subheader", text: "Special Senses"});
>>   const specialSenseRows = [];
>>   const specialSensesContainer = leftCol.createEl("div");
>>   function addSpecialSenseRow(value) {
>>     const row = specialSensesContainer.createEl("div", {cls: "action-modal-row"});
>>     const input = row.createEl("input", {type: "text", cls: "action-modal-name"});
>>     input.value = value ?? "";
>>     input.placeholder = "e.g. Truesight 30 ft.";
>>     const delBtn = row.createEl("button", {text: "✕"});
>>     const state = {deleted: false};
>>     delBtn.onclick = () => {
>>       state.deleted = true;
>>       row.style.opacity = "0.35";
>>       row.style.textDecoration = "line-through";
>>     };
>>     specialSenseRows.push({state, input});
>>   }
>>   for (const s of (page.special_senses_list || [])) addSpecialSenseRow(s);
>>   const addSenseBtn = leftCol.createEl("button", {cls: "action-btn-update", text: "+ Add Sense"});
>>   addSenseBtn.onclick = () => addSpecialSenseRow("");
>>
>>   leftCol.createEl("div", {cls: "stat-subheader", text: "Combat Values"});
>>   const acInput = textField(leftCol, "Armor Class", page.armor_class);
>>   const initInput = textField(leftCol, "Initiative", page.initiative);
>>   const speedInput = textField(leftCol, "Base Speed", page.base_speed);
>>   const movementInput = textField(leftCol, "Movement Types", page.movement_types);
>>
>>   leftCol.createEl("div", {cls: "stat-subheader", text: "Hit Points"});
>>   const hpMaxInput = textField(leftCol, "HP Max", page.hp_max);
>>   const hpCurrentInput = textField(leftCol, "HP Current", page.hp_current);
>>   const tempHpInput = textField(leftCol, "Temp HP", page.temp_hp);
>>
>>   // ---- RIGHT COLUMN: Saving Throws, Skills (grid-aligned) ----
>>   rightCol.createEl("div", {cls: "stat-subheader", text: "Saving Throws"});
>>   const saves = page.saves_list || [];
>>   const saveRows = saves.map((s) => {
>>     const row = rightCol.createEl("div", {cls: "save-edit-row"});
>>     row.createEl("span", {cls: "action-modal-label", text: s.ability});
>>     const profCb = row.createEl("input", {type: "checkbox"});
>>     profCb.checked = !!s.prof;
>>     const modInput = row.createEl("input", {type: "text"});
>>     modInput.value = s.mod;
>>     return {ability: s.ability, profCb, modInput};
>>   });
>>
>>   rightCol.createEl("div", {cls: "stat-subheader", text: "Skills"});
>>   const skills = page.skills_list || [];
>>   const skillRows = skills.map((item) => {
>>     const row = rightCol.createEl("div", {cls: "skill-edit-row"});
>>     row.createEl("span", {cls: "action-modal-label", text: item.ability});
>>     row.createEl("span", {cls: "action-modal-label", text: item.name});
>>     const profCb = row.createEl("input", {type: "checkbox"});
>>     profCb.checked = !!item.prof;
>>     const modInput = row.createEl("input", {type: "text"});
>>     modInput.value = item.mod;
>>     return {ability: item.ability, name: item.name, profCb, modInput};
>>   });
>>
>>   // Recalculate button: fills in save/skill mods from ability score +
>>   // proficiency + level-based proficiency bonus. Fields stay normal
>>   // editable text inputs, so anything typed after clicking (or instead
>>   // of clicking) is fully preserved - this never runs automatically.
>>   const recalcRow = rightCol.createEl("div", {cls: "action-modal-btnrow"});
>>   const recalcBtn = recalcRow.createEl("button", {cls: "action-btn-update", text: "Recalculate from Ability Scores"});
>>   recalcBtn.onclick = () => {
>>     const lvl = Number(levelInput.value) || 1;
>>     const profBonus = Math.floor((lvl - 1) / 4) + 2;
>>     function abilityMod(abilityLetters) {
>>       const row = abilityRows.find((r) => r.key === abilityLetters.toLowerCase());
>>       if (!row) return 0;
>>       return parseInt(calcModifier(row.scoreInput.value), 10) || 0;
>>     }
>>     for (const s of saveRows) {
>>       const total = abilityMod(s.ability) + (s.profCb.checked ? profBonus : 0);
>>       s.modInput.value = total >= 0 ? `+${total}` : `${total}`;
>>     }
>>     for (const sk of skillRows) {
>>       const total = abilityMod(sk.ability) + (sk.profCb.checked ? profBonus : 0);
>>       sk.modInput.value = total >= 0 ? `+${total}` : `${total}`;
>>     }
>>   };
>>
>>   const btnRow = modal.createEl("div", {cls: "action-modal-btnrow"});
>>   const saveBtn = btnRow.createEl("button", {cls: "action-btn-update", text: "Save"});
>>   const cancelBtn = btnRow.createEl("button", {text: "Cancel"});
>>
>>   cancelBtn.onclick = () => overlay.remove();
>>   saveBtn.onclick = async () => {
>>     let newPortraitPath = page.cover || "player.png";
>>     if (selectedPortraitFile) {
>>       const arrayBuffer = await selectedPortraitFile.arrayBuffer();
>>       const targetPath = await app.fileManager.getAvailablePathForAttachment(selectedPortraitFile.name, file.path);
>>       const newImageFile = await app.vault.createBinary(targetPath, arrayBuffer);
>>       newPortraitPath = newImageFile.path;
>>     }
>>
>>     const newSpecialSenses = specialSenseRows
>>       .filter((r) => !r.state.deleted && r.input.value.trim())
>>       .map((r) => r.input.value.trim());
>>     const newSaves = saveRows.map((r) => ({ability: r.ability, mod: r.modInput.value, prof: r.profCb.checked}));
>>     const newSenses = senseRows.map((r) => ({name: r.name, value: r.valInput.value}));
>>     const newSkills = skillRows.map((r) => ({ability: r.ability, name: r.name, mod: r.modInput.value, prof: r.profCb.checked}));
>>
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.race = raceSelect.value;
>>       const checkedClassNames = classChecks.filter(cb => cb.checked).map(cb => cb.value);
>>       fm.class = checkedClassNames.join(" / ");
>>       fm.subclass = [...selectedSubclasses].join(" / ");
>>       if (checkedClassNames.length > 1) {
>>         const classLevelsOut = {};
>>         let sum = 0;
>>         for (const cname of checkedClassNames) {
>>           const v = Number(classLevelInputs[cname]?.value) || 0;
>>           classLevelsOut[cname] = v;
>>           sum += v;
>>         }
>>         fm.class_levels = classLevelsOut;
>>         fm.level = sum || (isNaN(Number(levelInput.value)) ? levelInput.value : Number(levelInput.value));
>>       } else {
>>         fm.class_levels = {};
>>         fm.level = isNaN(Number(levelInput.value)) ? levelInput.value : Number(levelInput.value);
>>       }
>>       fm.background = backgroundInput.value;
>>       fm.alignment = alignmentSelect.value;
>>       fm.player = playerInput.value;
>>       fm.cover = newPortraitPath;
>>       for (const r of abilityRows) {
>>         fm[`${r.key}_score`] = isNaN(Number(r.scoreInput.value)) ? r.scoreInput.value : Number(r.scoreInput.value);
>>         fm[`${r.key}_mod`] = calcModifier(r.scoreInput.value);
>>       }
>>       fm.special_senses_list = newSpecialSenses;
>>       fm.armor_class = acInput.value;
>>       fm.initiative = initInput.value;
>>       fm.base_speed = speedInput.value;
>>       fm.movement_types = movementInput.value;
>>       fm.hp_max = Number(hpMaxInput.value) || 0;
>>       fm.hp_current = Number(hpCurrentInput.value) || 0;
>>       fm.temp_hp = Number(tempHpInput.value) || 0;
>>       fm.saves_list = newSaves;
>>       fm.senses_list = newSenses;
>>       fm.skills_list = newSkills;
>>     });
>>     overlay.remove();
>>   };
>>
>>   document.body.appendChild(overlay);
>> }
>> ```
>>
>> </div>
>>
>> <div class="overview-right-col">
>>
>> ```dataviewjs
>> const portraitPage = dv.current();
>> const imgPath = portraitPage.cover || "player.png";
>> const imgFile = app.metadataCache.getFirstLinkpathDest(imgPath, portraitPage.file.path);
>> if (imgFile) {
>>   dv.container.createEl("img", {attr: {src: app.vault.getResourcePath(imgFile)}});
>> } else {
>>   dv.container.createEl("div", {cls: "condition-desc", text: `Image not found: ${imgPath}`});
>> }
>> ```
>>
>> </div>
>>
>> </div>
>
>> [!combat] Combat Values
>>
>>> [!ministat] Armor Class
>>> <span class="ministat-value">`VIEW[{armor_class}][text]`</span>
>>
>>> [!ministat] Initiative
>>> <span class="ministat-value">`VIEW[{initiative}][text]`</span>
>>
>>> [!ministat] Speed 
>>> `VIEW[{movement_types}][text]`
>>>
>>> ```dataviewjs
>>> const page = dv.current();
>>> const ZERO_SPEED_CONDITIONS = ["Grappled", "Paralyzed", "Petrified", "Restrained", "Stunned", "Unconscious"];
>>> const active = page.conditions_active || [];
>>> const isZeroed = active.some((c) => ZERO_SPEED_CONDITIONS.includes(c));
>>> const baseMatch = String(page.base_speed || "0 ft.").match(/(\d+)/);
>>> const baseNum = baseMatch ? Number(baseMatch[1]) : 0;
>>> const exhaustion = Number(page.exhaustion_level || 0);
>>> const effective = isZeroed ? 0 : Math.max(0, baseNum - 5 * exhaustion);
>>> dv.container.createEl("span", {cls: "ministat-value", text: `${effective} ft.`});
>>> if (effective !== baseNum) {
>>>   const note = isZeroed ? "reduced by condition" : `-${baseNum - effective} ft. exhaustion`;
>>>   dv.container.createEl("div", {cls: "condition-desc", text: note});
>>> }
>>> ```
>
>> [!hp] Hit Points
>> <span class="hp-big">`VIEW[{hp_current}][text]`/`VIEW[{hp_max}][text]`</span><span class="dead-hp-text">DEAD</span>
>>
>> Temp HP: `VIEW[{temp_hp}][text]`
>>
>> Amount: `INPUT[number(class(narrow-input)):dmg_amount]`
>>
>> Set Temp HP: `INPUT[number(class(narrow-input)):temp_hp_input]` `BUTTON[set-temp-hp]`
>>
>> ```meta-bind-button
>> label: "Set"
>> style: "default"
>> hidden: true
>> id: "set-temp-hp"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: temp_hp
>>     evaluate: true
>>     value: "getMetadata('temp_hp_input')"
>>   - type: updateMetadata
>>     bindTarget: temp_hp_input
>>     evaluate: false
>>     value: 0
>> ```
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>>
>> const dmgHealRow = dv.container.createEl("div", {cls: "hp-extra-row"});
>> const damageBtn = dmgHealRow.createEl("button", {cls: "action-btn-update", text: "Damage"});
>> const healBtn = dmgHealRow.createEl("button", {cls: "action-btn-update", text: "Heal"});
>>
>> function addConditionIfMissing(fm, name) {
>>   fm.conditions_active = fm.conditions_active || [];
>>   if (!fm.conditions_active.includes(name)) fm.conditions_active.push(name);
>> }
>> function swapCondition(fm, fromName, toName) {
>>   fm.conditions_active = fm.conditions_active || [];
>>   const idx = fm.conditions_active.indexOf(fromName);
>>   if (idx !== -1) fm.conditions_active[idx] = toName;
>> }
>>
>> damageBtn.onclick = async () => {
>>   await app.fileManager.processFrontMatter(file, (fm) => {
>>     const dmgAmt = Number(fm.dmg_amount || 0);
>>     const tempHp = Number(fm.temp_hp || 0);
>>     const overflow = Math.max(0, dmgAmt - tempHp);
>>     fm.hp_current = Math.max(0, Number(fm.hp_current || 0) - overflow);
>>     fm.temp_hp = Math.max(0, tempHp - dmgAmt);
>>     fm.dmg_amount = 0;
>>     const classes = new Set(fm.cssclasses || ["dnd-sheet"]);
>>     if (fm.hp_current <= 0) {
>>       classes.add("dying");
>>       addConditionIfMissing(fm, "Unconscious");
>>     }
>>     fm.cssclasses = Array.from(classes);
>>   });
>> };
>> healBtn.onclick = async () => {
>>   await app.fileManager.processFrontMatter(file, (fm) => {
>>     const dmgAmt = Number(fm.dmg_amount || 0);
>>     fm.hp_current = Math.min(Number(fm.hp_max || 0), Number(fm.hp_current || 0) + dmgAmt);
>>     fm.dmg_amount = 0;
>>     if (fm.hp_current > 0) {
>>       const classes = new Set(fm.cssclasses || ["dnd-sheet"]);
>>       classes.delete("dying");
>>       classes.delete("dead");
>>       fm.cssclasses = Array.from(classes);
>>       fm.death_saves_success = [false, false, false];
>>       fm.death_saves_fail = [false, false, false];
>>       swapCondition(fm, "Unconscious", "Prone");
>>     }
>>   });
>> };
>>
>> const hiRow = dv.container.createEl("div", {cls: "hp-extra-row"});
>> hiRow.createEl("span", {cls: "hp-extra-label", text: "Heroic Inspiration"});
>> const hiBox = hiRow.createEl("input", {type: "checkbox"});
>> hiBox.checked = !!page.heroic_inspiration;
>> hiBox.onclick = async () => {
>>   const val = hiBox.checked;
>>   await app.fileManager.processFrontMatter(file, (fm) => { fm.heroic_inspiration = val; });
>> };
>>
>> if (Number(page.hp_current || 0) <= 0) {
>>   dv.container.createEl("div", {cls: "hp-extra-label", text: "Death Saves"});
>>   const dsRow = dv.container.createEl("div", {cls: "death-saves-row"});
>>
>>   dsRow.createEl("span", {cls: "death-saves-icon death-saves-fail-icon", text: "✕"});
>>   const fails = page.death_saves_fail || [false, false, false];
>>   fails.forEach((val, i) => {
>>     const cb = dsRow.createEl("input", {type: "checkbox", cls: "death-saves-fail"});
>>     cb.checked = val;
>>     cb.onclick = async () => {
>>       const v = cb.checked;
>>       await app.fileManager.processFrontMatter(file, (fm) => {
>>         fm.death_saves_fail = fm.death_saves_fail || [false, false, false];
>>         fm.death_saves_fail[i] = v;
>>         const failCount = fm.death_saves_fail.filter(Boolean).length;
>>         const exhausted = Number(fm.exhaustion_level || 0) >= 6;
>>         // Sticky: this handler can only trigger "dead", never clear it -
>>         // unchecking a failure box shouldn't undo a death. Only actually
>>         // regaining HP (Heal button) or stabilizing (3 successes) revives.
>>         if (failCount >= 3 || exhausted) {
>>           const classes = new Set(fm.cssclasses || ["dnd-sheet"]);
>>           classes.add("dead");
>>           classes.delete("dying");
>>           fm.cssclasses = Array.from(classes);
>>         }
>>       });
>>     };
>>   });
>>
>>   dsRow.createEl("span", {cls: "death-saves-icon death-saves-success-icon", text: "✓"});
>>   const successes = page.death_saves_success || [false, false, false];
>>   successes.forEach((val, i) => {
>>     const cb = dsRow.createEl("input", {type: "checkbox", cls: "death-saves-success"});
>>     cb.checked = val;
>>     cb.onclick = async () => {
>>       const v = cb.checked;
>>       await app.fileManager.processFrontMatter(file, (fm) => {
>>         fm.death_saves_success = fm.death_saves_success || [false, false, false];
>>         fm.death_saves_success[i] = v;
>>         if (fm.death_saves_success.filter(Boolean).length >= 3) {
>>           // Stabilized: same recovery as the Heal button, just landing
>>           // at 1 HP instead of however much was healed
>>           fm.hp_current = 1;
>>           const classes = new Set(fm.cssclasses || ["dnd-sheet"]);
>>           classes.delete("dying");
>>           classes.delete("dead");
>>           fm.cssclasses = Array.from(classes);
>>           fm.death_saves_success = [false, false, false];
>>           fm.death_saves_fail = [false, false, false];
>>           swapCondition(fm, "Unconscious", "Prone");
>>         }
>>       });
>>     };
>>   });
>> }
>>
>>
>> const restRow = dv.container.createEl("div", {cls: "hp-extra-row"});
>> const longRestBtn = restRow.createEl("button", {cls: "action-btn-update", text: "Long Rest"});
>> const shortRestBtn = restRow.createEl("button", {cls: "action-btn-update", text: "Short Rest"});
>>
>> longRestBtn.onclick = async () => {
>>   await app.fileManager.processFrontMatter(file, (fm) => {
>>     fm.hp_current = fm.hp_max;
>>     fm.death_saves_success = [false, false, false];
>>     fm.death_saves_fail = [false, false, false];
>>     fm.spell_slots_used = {};
>>     fm.limited_uses = (fm.limited_uses || []).map((u) => ({...u, used: 0}));
>>     fm.actions_list = (fm.actions_list || []).map((a) =>
>>       a.max ? {...a, used: 0} : a
>>     );
>>     const stillExhausted = Number(fm.exhaustion_level || 0) >= 6;
>>     const classes = new Set(fm.cssclasses || ["dnd-sheet"]);
>>     classes.delete("dying");
>>     if (stillExhausted) classes.add("dead");
>>     else classes.delete("dead");
>>     fm.cssclasses = Array.from(classes);
>>   });
>> };
>> shortRestBtn.onclick = async () => {
>>   await app.fileManager.processFrontMatter(file, (fm) => {
>>     // Warlock pact magic is the one caster type that recharges on a
>>     // short rest rather than a long rest
>>     if (String(fm.class || "").trim().toLowerCase() === "warlock") {
>>       fm.spell_slots_used = {};
>>     }
>>     fm.limited_uses = (fm.limited_uses || []).map((u) =>
>>       u.rest === "Short" ? {...u, used: 0} : u
>>     );
>>     fm.actions_list = (fm.actions_list || []).map((a) =>
>>       a.max && a.rest === "Short" ? {...a, used: 0} : a
>>     );
>>   });
>> };
>> ```




> [!row]
>
>> [!defenses] Defenses
>>
>> <div class="add-spell-form">
>>
>> <input type="text" class="defense-add-input" list="damage-type-datalist" placeholder="Damage type...">
>> <select class="defense-type-select">
>>   <option value="Resistance">Resistance</option>
>>   <option value="Immunity">Immunity</option>
>>   <option value="Vulnerability">Vulnerability</option>
>> </select>
>> <button class="action-btn-update defense-add-btn">Add</button>
>> <datalist id="damage-type-datalist">
>>   <option value="Acid"></option>
>>   <option value="Bludgeoning"></option>
>>   <option value="Cold"></option>
>>   <option value="Fire"></option>
>>   <option value="Force"></option>
>>   <option value="Lightning"></option>
>>   <option value="Necrotic"></option>
>>   <option value="Piercing"></option>
>>   <option value="Poison"></option>
>>   <option value="Psychic"></option>
>>   <option value="Radiant"></option>
>>   <option value="Slashing"></option>
>>   <option value="Thunder"></option>
>> </datalist>
>>
>> </div>
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>> const defenses = page.defenses_active || [];
>>
>> const formEl = dv.container.parentElement.querySelector(".add-spell-form") || dv.container;
>> const nameInput = formEl.querySelector(".defense-add-input");
>> const typeSelect = formEl.querySelector(".defense-type-select");
>> const addBtn = formEl.querySelector(".defense-add-btn");
>> if (addBtn) {
>>   addBtn.onclick = async () => {
>>     const typed = (nameInput.value || "").trim();
>>     if (!typed) return;
>>     const type = typeSelect.value;
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.defenses_active = fm.defenses_active || [];
>>       if (!fm.defenses_active.some((d) => d.name === typed && d.type === type)) {
>>         fm.defenses_active.push({name: typed, type});
>>       }
>>     });
>>     nameInput.value = "";
>>   };
>> }
>>
>> for (const category of ["Resistance", "Immunity", "Vulnerability"]) {
>>   const items = defenses.filter((d) => d.type === category);
>>   if (items.length === 0) continue;
>>   const row = dv.container.createEl("div", {cls: "spell-slots-row feature-row"});
>>   row.createEl("span", {cls: "spell-slots-label", text: category + "s"});
>>   const chips = row.createEl("span", {cls: "condition-desc"});
>>   for (const item of items) {
>>     const chip = chips.createEl("span", {cls: "defense-chip", text: item.name});
>>     const rm = chip.createEl("button", {cls: "action-btn", text: "✕"});
>>     rm.onclick = async () => {
>>       await app.fileManager.processFrontMatter(file, (fm) => {
>>         fm.defenses_active = (fm.defenses_active || []).filter(
>>           (d) => !(d.name === item.name && d.type === item.type)
>>         );
>>       });
>>     };
>>   }
>> }
>> ```
>
>> [!conditions] Conditions
>>
>> <div class="add-spell-form">
>>
>> <input type="text" class="condition-add-input" list="condition-datalist" placeholder="Condition name...">
>> <button class="action-btn-update condition-add-btn">Add Condition</button>
>> <datalist id="condition-datalist"></datalist>
>>
>> </div>
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>>
>> // Short mechanical reminders, standard 5e 2024 rules. These are my
>> // own summaries for a quick glance - the full authoritative text
>> // lives in your own Condition notes; click a condition's name to
>> // open it. zeroSpeed marks conditions that explicitly set Speed to 0.
>> const CONDITION_INFO = {
>>   "Blinded": {text: "Can't see; attacks vs you have advantage, yours have disadvantage", zeroSpeed: false},
>>   "Charmed": {text: "Can't attack the charmer; charmer has advantage on social checks vs you", zeroSpeed: false},
>>   "Deafened": {text: "Can't hear; auto-fail hearing-based checks", zeroSpeed: false},
>>   "Frightened": {text: "Disadvantage on checks/attacks while source in sight; can't move closer to it", zeroSpeed: false},
>>   "Grappled": {text: "Speed 0", zeroSpeed: true},
>>   "Incapacitated": {text: "Can't take actions or reactions", zeroSpeed: false},
>>   "Invisible": {text: "Attacks vs you have disadvantage, yours have advantage", zeroSpeed: false},
>>   "Paralyzed": {text: "Speed 0, incapacitated; auto-fail STR/DEX saves; hits within 5 ft crit", zeroSpeed: true},
>>   "Petrified": {text: "Turned to stone, incapacitated; resistant to all damage; immune to poison", zeroSpeed: true},
>>   "Poisoned": {text: "Disadvantage on attack rolls and ability checks", zeroSpeed: false},
>>   "Prone": {text: "Disadvantage on attacks; melee attacks vs you have advantage", zeroSpeed: false},
>>   "Restrained": {text: "Speed 0; disadvantage on attacks/DEX saves; attacks vs you have advantage", zeroSpeed: true},
>>   "Stunned": {text: "Speed 0, incapacitated; auto-fail STR/DEX saves; attacks vs you have advantage", zeroSpeed: true},
>>   "Suprised": {text: "Can't move or take an action/reaction on your first turn", zeroSpeed: false},
>>   "Unconscious": {text: "Speed 0, incapacitated, prone; auto-fail STR/DEX saves; hits within 5 ft crit", zeroSpeed: true},
>> };
>>
>> // ---- Exhaustion: 2024 rules, matching your own Exhaustion note -
>> // -2 to d20 tests per level, -5 ft speed per level, dead at 6 ----
>> const level = Number(page.exhaustion_level || 0);
>> const exRow = dv.container.createEl("div", {cls: "spell-slots-row"});
>> exRow.createEl("span", {cls: "spell-slots-label", text: "Exhaustion"});
>> for (let i = 0; i < 6; i++) {
>>   const cb = exRow.createEl("input", {type: "checkbox"});
>>   cb.checked = i < level;
>>   cb.onclick = async () => {
>>     const newLevel = cb.checked ? i + 1 : i;
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.exhaustion_level = newLevel;
>>       const fails = fm.death_saves_fail || [false, false, false];
>>       const diedFromSaves = fails.filter(Boolean).length >= 3;
>>       // Sticky: only adds "dead", never removes it - see death-saves-fail
>>       // handler for the same reasoning.
>>       if (newLevel >= 6 || diedFromSaves) {
>>         const classes = new Set(fm.cssclasses || ["dnd-sheet"]);
>>         classes.add("dead");
>>         classes.delete("dying");
>>         fm.cssclasses = Array.from(classes);
>>       }
>>     });
>>   };
>> }
>> if (level > 0) {
>>   dv.container.createEl("div", {
>>     cls: "condition-desc",
>>     text: `-${level * 2} to d20 tests, -${level * 5} ft. speed${level >= 6 ? " — DEAD" : ""}`,
>>   });
>> }
>>
>> // ---- Add-condition autocomplete, sourced from your #Condition notes ----
>> const allConditionPages = dv.pages('#Condition')
>>   .where((p) => p.file.name !== "Exhaustion" && p.file.name !== "Stavy (Conditions)")
>>   .array();
>> const formEl = dv.container.parentElement.querySelector(".add-spell-form") || dv.container;
>> const datalistEl = formEl.querySelector("#condition-datalist");
>> if (datalistEl) {
>>   datalistEl.innerHTML = "";
>>   for (const cp of allConditionPages) {
>>     datalistEl.createEl("option", {attr: {value: cp.file.name}});
>>   }
>> }
>> const inputEl = formEl.querySelector(".condition-add-input");
>> const addBtnEl = formEl.querySelector(".condition-add-btn");
>> if (addBtnEl) {
>>   addBtnEl.onclick = async () => {
>>     const typed = (inputEl.value || "").trim();
>>     if (!typed) return;
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.conditions_active = fm.conditions_active || [];
>>       if (!fm.conditions_active.includes(typed)) fm.conditions_active.push(typed);
>>     });
>>     inputEl.value = "";
>>   };
>> }
>>
>> // ---- Active conditions list ----
>> const active = page.conditions_active || [];
>> for (const name of active) {
>>   const info = CONDITION_INFO[name] || {text: "", zeroSpeed: false};
>>   const row = dv.container.createEl("div", {cls: "spell-slots-row feature-row"});
>>   const nameSpan = row.createEl("span", {cls: "spell-slots-label"});
>>   const match = allConditionPages.find((cp) => cp.file.name === name);
>>   if (match) {
>>     nameSpan.createEl("a", {text: name, cls: "internal-link", href: match.file.path});
>>   } else {
>>     nameSpan.setText(name);
>>   }
>>   row.createEl("span", {cls: "condition-desc", text: info.text});
>>   const rm = row.createEl("button", {cls: "action-btn", text: "✕"});
>>   rm.onclick = async () => {
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.conditions_active = (fm.conditions_active || []).filter((c) => c !== name);
>>     });
>>   };
>> }
>> ```


> [!row]
>
>> [!stat] STR
>> <span class="stat-mod">`VIEW[{str_mod}][text]`</span><br><span class="stat-score">(`VIEW[{str_score}][text]`)</span>
>
>> [!stat] DEX
>> <span class="stat-mod">`VIEW[{dex_mod}][text]`</span><br><span class="stat-score">(`VIEW[{dex_score}][text]`)</span>
>
>> [!stat] CON
>> <span class="stat-mod">`VIEW[{con_mod}][text]`</span><br><span class="stat-score">(`VIEW[{con_score}][text]`)</span>
>
>> [!stat] INT
>> <span class="stat-mod">`VIEW[{int_mod}][text]`</span><br><span class="stat-score">(`VIEW[{int_score}][text]`)</span>
>
>> [!stat] WIS
>> <span class="stat-mod">`VIEW[{wis_mod}][text]`</span><br><span class="stat-score">(`VIEW[{wis_score}][text]`)</span>
>
>> [!stat] CHA
>> <span class="stat-mod">`VIEW[{cha_mod}][text]`</span><br><span class="stat-score">(`VIEW[{cha_score}][text]`)</span>


> [!row]
>
>> [!colstack]
>>
>>> [!saves] Saving Throws
>>>
>>> ```dataviewjs
>>> const page = dv.current();
>>> const saves = page.saves_list || [];
>>>
>>> const wrap = dv.container.createEl("div", {cls: "saves-columns"});
>>> const leftCol = wrap.createEl("div", {cls: "saves-col"});
>>> const rightCol = wrap.createEl("div", {cls: "saves-col"});
>>>
>>> saves.forEach((s, i) => {
>>>   const target = i < 3 ? leftCol : rightCol;
>>>   const row = target.createEl("div", {cls: "stat-row"});
>>>   row.createEl("span", {cls: "stat-dot", text: s.prof ? "●" : "○"});
>>>   row.createEl("span", {cls: "stat-ability", text: s.ability});
>>>   row.createEl("span", {cls: "stat-value", text: s.mod});
>>> });
>>> ```
>>
>>> [!senses] Senses
>>>
>>> ```dataviewjs
>>> const page = dv.current();
>>> const senses = page.senses_list || [];
>>>
>>> for (const item of senses) {
>>>   const row = dv.container.createEl("div", {cls: "stat-row"});
>>>   row.createEl("span", {cls: "stat-name", text: item.name});
>>>   row.createEl("span", {cls: "stat-value", text: String(item.value)});
>>> }
>>> const specialWrap = dv.container.createEl("div", {cls: "special-senses"});
>>> for (const s of (page.special_senses_list || [])) {
>>>   const row = specialWrap.createEl("div", {cls: "stat-row"});
>>>   row.createEl("span", {cls: "stat-name", text: s});
>>> }
>>> ```
>>
>>> [!profbonus] Proficiency Bonus
>>>
>>> ```dataviewjs
>>> const page = dv.current();
>>> const lvl = Number(page.level) || 1;
>>> const profBonus = Math.floor((lvl - 1) / 4) + 2;
>>> dv.container.createEl("div", {cls: "profbonus-value", text: `+${profBonus}`});
>>> ```
>
>> [!skills] Skills
>>
>> ```dataviewjs
>> const page = dv.current();
>> const skills = page.skills_list || [];
>>
>> for (const item of skills) {
>>   const row = dv.container.createEl("div", {cls: "stat-row"});
>>   row.createEl("span", {cls: "stat-dot", text: item.prof ? "●" : "○"});
>>   row.createEl("span", {cls: "stat-ability", text: item.ability});
>>   row.createEl("span", {cls: "stat-name", text: item.name});
>>   row.createEl("span", {cls: "stat-value", text: item.mod});
>> }
>> ```
>
>> [!details] Character Details
>>
>> ```meta-bind-button
>> label: "Actions"
>> style: "default"
>> hidden: true
>> id: "tab-actions-btn"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: cssclasses
>>     evaluate: true
>>     value: "['dnd-sheet', 'tab-actions']"
>> ```
>>
>> ```meta-bind-button
>> label: "Spells"
>> style: "default"
>> hidden: true
>> id: "tab-spells-btn"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: cssclasses
>>     evaluate: true
>>     value: "['dnd-sheet', 'tab-spells']"
>> ```
>>
>> ```meta-bind-button
>> label: "Inventory"
>> style: "default"
>> hidden: true
>> id: "tab-inventory-btn"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: cssclasses
>>     evaluate: true
>>     value: "['dnd-sheet', 'tab-inventory']"
>> ```
>>
>> ```meta-bind-button
>> label: "Features"
>> style: "default"
>> hidden: true
>> id: "tab-features-btn"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: cssclasses
>>     evaluate: true
>>     value: "['dnd-sheet', 'tab-features']"
>> ```
>>
>> ```meta-bind-button
>> label: "Notes"
>> style: "default"
>> hidden: true
>> id: "tab-notes-btn"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: cssclasses
>>     evaluate: true
>>     value: "['dnd-sheet', 'tab-notes']"
>> ```
>>
>> `BUTTON[tab-actions-btn, tab-spells-btn, tab-inventory-btn, tab-features-btn, tab-notes-btn]`
>>
>> <div class="tab-panel actions-panel">
>>
>> <div class="add-action-form">
>>
>> Name: `INPUT[text(class(medium-input)):new_action_name]` Range: `INPUT[text(class(narrow-input)):new_action_range]` Hit: `INPUT[text(class(narrow-input)):new_action_hit]` Dmg: `INPUT[text(class(narrow-input)):new_action_damage]` Dmg Type: `INPUT[text(class(dmgtype-input)):new_action_damage_type]`
>>
>> Type: `INPUT[inlineSelect(option(Action), option(Bonus Action), option(Reaction), option(Other)):new_action_type]` Max Uses: `INPUT[number(class(narrow-input)):new_action_max]` Resets: `INPUT[inlineSelect(option(Short), option(Long)):new_action_rest]` `BUTTON[add-action-btn]`
>>
>> ```meta-bind-button
>> label: "Add"
>> style: "primary"
>> hidden: true
>> id: "add-action-btn"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: actions_list
>>     evaluate: true
>>     value: "[...getMetadata('actions_list'), {name: getMetadata('new_action_name'), type: getMetadata('new_action_type'), range: getMetadata('new_action_range'), hit: getMetadata('new_action_hit'), damage: getMetadata('new_action_damage'), damage_type: getMetadata('new_action_damage_type'), max: getMetadata('new_action_max'), used: 0, rest: getMetadata('new_action_rest')}]"
>>   - type: updateMetadata
>>     bindTarget: new_action_name
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_action_range
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_action_hit
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_action_damage
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_action_damage_type
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_action_max
>>     evaluate: false
>>     value: 0
>> ```
>>
>> </div>
>>
>> ```dataviewjs
>> const page = dv.current();
>> const items = page.actions_list || [];
>> const groups = ["Action", "Bonus Action", "Reaction", "Other"];
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>>
>> const updateBtn = dv.container.createEl("button", {cls: "action-btn-update", text: "Update All"});
>> updateBtn.onclick = () => openActionsModal(items, file);
>>
>> for (const g of groups) {
>>   const withIdx = items.map((it, idx) => ({...it, idx})).filter(i => i.type === g);
>>   if (withIdx.length === 0) continue;
>>   dv.container.createEl("div", {cls: "action-category", text: g});
>>   const header = dv.container.createEl("div", {cls: "action-card action-card-header"});
>>   for (const h of ["Name", "Range", "Hit/DC", "Damage", "Type"]) {
>>     header.createEl("span", {text: h});
>>   }
>>   header.createEl("span", {text: ""});
>>   for (const item of withIdx) {
>>     const card = dv.container.createEl("div", {cls: "action-card"});
>>     card.createEl("span", {cls: "action-name", text: item.name});
>>     const range = card.createEl("span", {cls: "action-stat"});
>>     range.createEl("b", {text: item.range || ""});
>>     const hit = card.createEl("span", {cls: "action-stat"});
>>     hit.createEl("b", {text: item.hit});
>>     const dmg = card.createEl("span", {cls: "action-stat"});
>>     dmg.createEl("b", {text: item.damage});
>>     const dmgType = card.createEl("span", {cls: "action-stat"});
>>     dmgType.createEl("b", {text: item.damage_type || ""});
>>     const delBtn = card.createEl("button", {cls: "action-btn", text: "✕"});
>>     delBtn.onclick = async () => {
>>       await app.fileManager.processFrontMatter(file, (fm) => {
>>         fm.actions_list.splice(item.idx, 1);
>>       });
>>     };
>>
>>     if (item.max && Number(item.max) > 0) {
>>       const usesRow = dv.container.createEl("div", {cls: "spell-slots-row feature-row action-uses-row"});
>>       usesRow.createEl("span", {cls: "spell-slots-label", text: "Uses"});
>>       for (let i = 0; i < Number(item.max); i++) {
>>         const cb = usesRow.createEl("input", {type: "checkbox"});
>>         cb.checked = i < (item.used || 0);
>>         cb.onclick = async () => {
>>           const nowUsed = cb.checked;
>>           await app.fileManager.processFrontMatter(file, (fm) => {
>>             const cur = fm.actions_list[item.idx].used || 0;
>>             fm.actions_list[item.idx].used = nowUsed
>>               ? Math.min(Number(item.max), cur + 1)
>>               : Math.max(0, cur - 1);
>>           });
>>         };
>>       }
>>       usesRow.createEl("span", {cls: "feature-rest-badge", text: item.rest});
>>     }
>>   }
>> }
>>
>> function openActionsModal(items, file) {
>>   const overlay = document.createElement("div");
>>   overlay.className = "action-modal-overlay";
>>   const modal = overlay.createEl("div", {cls: "action-modal action-modal-actions"});
>>   modal.createEl("h3", {text: "Edit Actions"});
>>
>>   const headerRow = modal.createEl("div", {cls: "action-modal-row action-modal-header-row"});
>>   headerRow.createEl("span", {cls: "action-modal-name", text: "Name"});
>>   headerRow.createEl("span", {cls: "action-modal-category", text: "Category"});
>>   headerRow.createEl("span", {cls: "action-modal-range", text: "Range"});
>>   headerRow.createEl("span", {cls: "action-modal-stat", text: "Hit/DC"});
>>   headerRow.createEl("span", {cls: "action-modal-dmg", text: "Damage"});
>>   headerRow.createEl("span", {cls: "action-modal-dmgtype", text: "Type"});
>>   headerRow.createEl("span", {cls: "action-modal-narrow", text: "Uses"});
>>   headerRow.createEl("span", {cls: "action-modal-restselect", text: "Rest"});
>>   headerRow.createEl("span", {cls: "action-modal-header-spacer"});
>>
>>   const rows = items.map((item) => {
>>     const row = modal.createEl("div", {cls: "action-modal-row"});
>>     const nameInput = row.createEl("input", {type: "text", cls: "action-modal-name"});
>>     nameInput.value = item.name;
>>     const typeSelect = row.createEl("select", {cls: "action-modal-category"});
>>     for (const t of ["Action", "Bonus Action", "Reaction", "Other"]) {
>>       const opt = typeSelect.createEl("option", {text: t});
>>       opt.value = t;
>>       if (t === item.type) opt.selected = true;
>>     }
>>     const rangeInput = row.createEl("input", {type: "text", cls: "action-modal-range"});
>>     rangeInput.value = item.range || "";
>>     rangeInput.title = "Range";
>>     const hitInput = row.createEl("input", {type: "text", cls: "action-modal-stat"});
>>     hitInput.value = item.hit;
>>     hitInput.title = "Hit/DC";
>>     const dmgInput = row.createEl("input", {type: "text", cls: "action-modal-dmg"});
>>     dmgInput.value = item.damage;
>>     dmgInput.title = "Damage";
>>     const dmgTypeInput = row.createEl("input", {type: "text", cls: "action-modal-dmgtype"});
>>     dmgTypeInput.value = item.damage_type || "";
>>     dmgTypeInput.title = "Damage Type";
>>     const maxInput = row.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>     maxInput.value = item.max || 0;
>>     maxInput.title = "Max Uses (0 = none)";
>>     const restSelect = row.createEl("select", {cls: "action-modal-restselect"});
>>     for (const r of ["Short", "Long"]) {
>>       const opt = restSelect.createEl("option", {text: r});
>>       opt.value = r;
>>       if (r === item.rest) opt.selected = true;
>>     }
>>     const delBtn = row.createEl("button", {text: "✕"});
>>     const state = {deleted: false};
>>     delBtn.onclick = () => {
>>       state.deleted = true;
>>       row.style.opacity = "0.35";
>>       row.style.textDecoration = "line-through";
>>     };
>>     return {state, nameInput, typeSelect, rangeInput, hitInput, dmgInput, dmgTypeInput, maxInput, restSelect, prevUsed: item.used || 0};
>>   });
>>
>>   const btnRow = modal.createEl("div", {cls: "action-modal-btnrow"});
>>   const saveBtn = btnRow.createEl("button", {cls: "action-btn-update", text: "Save"});
>>   const cancelBtn = btnRow.createEl("button", {text: "Cancel"});
>>
>>   cancelBtn.onclick = () => overlay.remove();
>>   saveBtn.onclick = async () => {
>>     const newList = rows
>>       .filter(r => !r.state.deleted)
>>       .map(r => ({
>>         name: r.nameInput.value,
>>         type: r.typeSelect.value,
>>         range: r.rangeInput.value,
>>         hit: r.hitInput.value,
>>         damage: r.dmgInput.value,
>>         damage_type: r.dmgTypeInput.value,
>>         max: Number(r.maxInput.value) || 0,
>>         used: Math.min(r.prevUsed, Number(r.maxInput.value) || 0),
>>         rest: r.restSelect.value,
>>       }));
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.actions_list = newList;
>>     });
>>     overlay.remove();
>>   };
>>
>>   document.body.appendChild(overlay);
>> }
>> ```
>>
>> </div>
>>
>> <div class="tab-panel spells-panel">
>>
>> Modifier: `INPUT[text(class(narrow-input)):spellcasting_modifier]` &nbsp; Spell Attack: `INPUT[text(class(narrow-input)):spell_attack_bonus]` &nbsp; Save DC: `INPUT[text(class(narrow-input)):spell_save_dc]`
>>
>> <div class="add-spell-form">
>>
>> <input type="text" class="spell-add-input" list="spell-datalist" placeholder="Spell name...">
>> <button class="action-btn-update spell-add-btn">Add Spell</button>
>> <datalist id="spell-datalist"></datalist>
>>
>> </div>
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>> const suffix = (n) => (n === 1 ? "st" : n === 2 ? "nd" : n === 3 ? "rd" : "th");
>> const levelName = (n) => (n === 0 ? "Cantrips" : `${n}${suffix(n)} Level`);
>> const allSpellPages = dv.pages('#Spell').array();
>>
>> // ---- Add Spell widget: native datalist autocomplete over every
>> // #Spell note in the vault, "Add Spell" appends its link to `spells` ----
>> const formEl = dv.container.parentElement.querySelector(".add-spell-form") || dv.container;
>> const datalistEl = formEl.querySelector("#spell-datalist");
>> if (datalistEl) {
>>   datalistEl.innerHTML = "";
>>   for (const sp of allSpellPages) {
>>     datalistEl.createEl("option", {attr: {value: sp.file.name}});
>>   }
>> }
>> const spellInputEl = formEl.querySelector(".spell-add-input");
>> const addSpellBtnEl = formEl.querySelector(".spell-add-btn");
>> if (addSpellBtnEl) {
>>   addSpellBtnEl.onclick = async () => {
>>     const typed = (spellInputEl.value || "").trim();
>>     if (!typed) return;
>>     const match = allSpellPages.find(sp => sp.file.name.toLowerCase() === typed.toLowerCase());
>>     if (!match) {
>>       new Notice(`No spell note found named "${typed}".`);
>>       return;
>>     }
>>     const linkStr = `[[${match.file.name}]]`;
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.spells = fm.spells || [];
>>       if (!fm.spells.includes(linkStr)) fm.spells.push(linkStr);
>>     });
>>     spellInputEl.value = "";
>>   };
>> }
>>
>> // Leveled, class-aware spell slot tracker, with real multiclass support.
>> // Each class in `class` gets its own level (from `class_levels` when
>> // there's more than one class, or the plain `level` field for a single
>> // class) and its own progression type (full/half/third/artificer/pact).
>> // Warlock's Pact Magic is ALWAYS calculated on its own from Warlock
>> // level alone - it never combines with other classes, per actual 5e
>> // multiclass rules. Every other spellcasting class combines into one
>> // shared multiclass slot pool: full casters contribute their whole
>> // level, half casters (Paladin/Ranger) contribute half rounded down,
>> // third-casters (Eldritch Knight/Arcane Trickster) a third rounded
>> // down, and Artificer half rounded UP (the one exception). That combined
>> // level is looked up in the "full" table, since the official multiclass
>> // slot table is numerically identical to a full caster's own progression.
>> // A solo non-Warlock caster (the common case) still just uses its own
>> // table directly, unchanged from before. Used-slot tracking only splits
>> // into separate namespaces when Warlock AND another caster class are
>> // both active at once - a solo class of any kind keeps using the same
>> // plain keys as before, so existing sheets' tracked slot usage isn't
>> // disturbed by this change.
>> const CLASS_PROGRESSION = {
>>   bard: "full", cleric: "full", druid: "full", sorcerer: "full", wizard: "full",
>>   paladin: "half", ranger: "half",
>>   artificer: "artificer",
>>   warlock: "pact",
>> };
>> const THIRD_CASTER_SUBCLASSES = ["eldritch knight", "arcane trickster"];
>>
>> const classNames = String(page.class || "").split(" / ").map(s => s.trim()).filter(Boolean);
>> const subclassNames = String(page.subclass || "").split(" / ").map(s => s.trim()).filter(Boolean);
>> const classLevelsFm = page.class_levels || {};
>> const isThirdCasterSheet = subclassNames.some(s => THIRD_CASTER_SUBCLASSES.includes(s.toLowerCase()));
>> function levelForClass(cname) {
>>   return classNames.length <= 1 ? (Number(page.level) || 0) : (Number(classLevelsFm[cname]) || 0);
>> }
>> const classProgressions = classNames.map((cname) => {
>>   const key = cname.toLowerCase();
>>   const type = CLASS_PROGRESSION[key] || (isThirdCasterSheet ? "third" : undefined);
>>   return {name: cname, type, level: levelForClass(cname)};
>> }).filter((c) => c.type);
>>
>> const warlockEntry = classProgressions.find((c) => c.type === "pact");
>> const otherCasters = classProgressions.filter((c) => c.type !== "pact");
>>
>> const edition = String(page.rules_edition || "2024").trim();
>> const referenceNote = dv.page("Spell Slot Tables");
>> if (!referenceNote && classProgressions.length > 0) {
>>   dv.container.createEl("div", {
>>     cls: "condition-desc",
>>     text: '⚠ "Spell Slot Tables" reference note not found - spell slots can\'t be calculated. Make sure that note exists in your vault with its exact name.',
>>   });
>> }
>> function lookupTable(type, level) {
>>   if (!referenceNote || !type || level <= 0) return {};
>>   const key = type === "half" ? `half_${edition}` : type;
>>   return ((referenceNote.spell_slots_tables || {})[key] || {})[String(level)] || {};
>> }
>>
>> let combinedTable = {};
>> let combinedTitle = "";
>> if (otherCasters.length === 1 && !warlockEntry) {
>>   const only = otherCasters[0];
>>   combinedTable = lookupTable(only.type, only.level);
>>   const label = only.type === "third"
>>     ? (subclassNames.find((s) => THIRD_CASTER_SUBCLASSES.includes(s.toLowerCase())) || only.name)
>>     : only.name;
>>   combinedTitle = label;
>> } else if (otherCasters.length >= 1) {
>>   let combinedLevel = 0;
>>   for (const c of otherCasters) {
>>     if (c.type === "full") combinedLevel += c.level;
>>     else if (c.type === "half") combinedLevel += Math.floor(c.level / 2);
>>     else if (c.type === "third") combinedLevel += Math.floor(c.level / 3);
>>     else if (c.type === "artificer") combinedLevel += Math.ceil(c.level / 2);
>>   }
>>   combinedTable = lookupTable("full", combinedLevel);
>>   combinedTitle = otherCasters.map((c) => c.name).join(" / ");
>> }
>> const pactTable = warlockEntry ? lookupTable("pact", warlockEntry.level) : {};
>> const pactTitle = warlockEntry ? "Warlock" : "";
>>
>> const needsSplitNamespace = !!warlockEntry && otherCasters.length > 0;
>> const usedSlots = page.spell_slots_used || {};
>>
>> function renderSlotSection(title, table, usedKeyPrefix) {
>>   const slotLevels = Object.keys(table)
>>     .filter((k) => (table[k] || 0) > 0)
>>     .sort((a, b) => Number(a) - Number(b));
>>   if (!slotLevels.length) return;
>>   dv.container.createEl("div", {cls: "spell-slots-title", text: `Spell Slots — ${title}`});
>>   for (const lvlKey of slotLevels) {
>>     const max = table[lvlKey];
>>     const usedKey = usedKeyPrefix ? `${usedKeyPrefix}${lvlKey}` : lvlKey;
>>     const usedCount = Math.min(usedSlots[usedKey] || 0, max);
>>     const row = dv.container.createEl("div", {cls: "spell-slots-row"});
>>     row.createEl("span", {cls: "spell-slots-label", text: levelName(Number(lvlKey))});
>>     for (let i = 0; i < max; i++) {
>>       const cb = row.createEl("input", {type: "checkbox"});
>>       cb.checked = i < usedCount; // checked = used/depleted
>>       cb.onclick = async () => {
>>         const nowUsed = cb.checked;
>>         await app.fileManager.processFrontMatter(file, (fm) => {
>>           fm.spell_slots_used = fm.spell_slots_used || {};
>>           const cur = fm.spell_slots_used[usedKey] || 0;
>>           fm.spell_slots_used[usedKey] = nowUsed ? Math.min(max, cur + 1) : Math.max(0, cur - 1);
>>         });
>>       };
>>     }
>>   }
>> }
>>
>> if (Object.keys(combinedTable).length) {
>>   renderSlotSection(combinedTitle, combinedTable, needsSplitNamespace ? "std_" : "");
>> }
>> if (Object.keys(pactTable).length) {
>>   renderSlotSection(pactTitle, pactTable, needsSplitNamespace ? "pact_" : "");
>> }
>>
>> // ---- Upcast math: auto-calculates when Upscale is a clean dice
>> // increment (e.g. "+ 1d6") or a flat number ("+ 5 per slot level
>> // above"). Anything else (duration/range/concentration text that
>> // doesn't change the numeric effect) just shows the spell unchanged
>> // at that level - no raw sentence dumped into the table anymore. ----
>> function substituteModifier(text) {
>>   const mod = String(page.spellcasting_modifier ?? "").trim();
>>   if (!mod) return text;
>>   const signed = mod.startsWith("+") || mod.startsWith("-") ? mod : `+${mod}`;
>>   return String(text || "").replace(
>>     /\+\s*(your\s+)?spellcasting\s+ability\s+modifier/gi,
>>     signed
>>   );
>> }
>> function parseUpscaleDice(str) {
>>   const m = String(str || "").trim().match(/^\+?\s*(\d+)\s*d\s*(\d+)$/i);
>>   return m ? {count: Number(m[1]), die: Number(m[2])} : null;
>> }
>> function parseUpscaleFlat(str) {
>>   const m = String(str || "").trim().match(/^\+\s*(\d+)\s+per\s+slot\s+level\s+above/i);
>>   return m ? Number(m[1]) : null;
>> }
>> function computeUpcastEffect(baseEffectRaw, upscaleStr, levelsAbove) {
>>   const baseEffect = substituteModifier(baseEffectRaw);
>>
>>   const dice = parseUpscaleDice(upscaleStr);
>>   const diceMatch = baseEffect.match(/^(\d+)d(\d+)(.*)$/);
>>   if (dice && diceMatch && Number(diceMatch[2]) === dice.die) {
>>     const newCount = Number(diceMatch[1]) + dice.count * levelsAbove;
>>     return `${newCount}d${diceMatch[2]}${diceMatch[3]}`;
>>   }
>>
>>   const flatInc = parseUpscaleFlat(upscaleStr);
>>   const flatMatch = baseEffect.match(/^(\d+)(\s.*)?$/);
>>   if (flatInc !== null && flatMatch) {
>>     const newVal = Number(flatMatch[1]) + flatInc * levelsAbove;
>>     return `${newVal}${flatMatch[2] ?? ""}`;
>>   }
>>
>>   // Not a numeric upcast (e.g. extended concentration, added targets
>>   // with no fixed count) - the effect itself doesn't change, so just
>>   // show it as-is rather than dumping the raw upcast sentence
>>   return baseEffect;
>> }
>>
>> const spellPaths = (page.spells || []).map(l => (l && l.path) ? l.path : l);
>> const pages = allSpellPages.filter(p => spellPaths.includes(p.file.path));
>> const allSlotLevelKeys = [...new Set([...Object.keys(combinedTable), ...Object.keys(pactTable)])]
>>   .filter((k) => (combinedTable[k] || pactTable[k] || 0) > 0);
>> const maxSlotLevel = allSlotLevelKeys.length > 0 ? Math.max(...allSlotLevelKeys.map(Number)) : 0;
>>
>> const grouped = {};
>> for (const p of pages) {
>>   const baseLvl = p["Spell level"] ?? 0;
>>   const baseEffect = p["Damage / Effect"] ?? "";
>>   const upscaleText = String(p["Upscale"] ?? "").trim();
>>   const hasUpscale = baseLvl > 0 && upscaleText && upscaleText !== "...";
>>
>>   (grouped[baseLvl] = grouped[baseLvl] || []).push({
>>     page: p, effectText: substituteModifier(baseEffect), isUpcast: false,
>>   });
>>
>>   if (hasUpscale && maxSlotLevel > baseLvl) {
>>     for (let lvl = baseLvl + 1; lvl <= maxSlotLevel; lvl++) {
>>       const effectText = computeUpcastEffect(baseEffect, upscaleText, lvl - baseLvl);
>>       (grouped[lvl] = grouped[lvl] || []).push({page: p, effectText, isUpcast: true});
>>     }
>>   }
>> }
>> const levels = Object.keys(grouped).map(Number).sort((a, b) => a - b);
>> for (const lvl of levels) {
>>   grouped[lvl].sort((a, b) => a.page.file.name.localeCompare(b.page.file.name));
>> }
>>
>> function abbrevTime(t) {
>>   const val = String(t || "").trim();
>>   const star = val.endsWith("*") ? "*" : "";
>>   const core = val.replace(/\*$/, "").trim();
>>   if (/^action$/i.test(core)) return "1A" + star;
>>   if (/^bonus action$/i.test(core)) return "1BA" + star;
>>   if (/^reaction$/i.test(core)) return "1R" + star;
>>   return val;
>> }
>> function formatHitDC(attackSave) {
>>   const val = String(attackSave || "").trim();
>>   if (!val || /^none$/i.test(val)) return "–";
>>   const saveMatch = val.match(/^(STR|DEX|CON|INT|WIS|CHA)\b.*Save/i);
>>   if (saveMatch) return `${saveMatch[1].toUpperCase()} ${page.spell_save_dc ?? "–"}`;
>>   if (/^(melee|ranged)$/i.test(val)) {
>>     const bonus = String(page.spell_attack_bonus ?? "").trim();
>>     return bonus ? (bonus.startsWith("+") ? bonus : `+${bonus}`) : "–";
>>   }
>>   if (/^\+?\d+$/.test(val)) return val.startsWith("+") ? val : `+${val}`;
>>   return val;
>> }
>> function shortRange(r) {
>>   // "Self (30 ft. Cone)" -> "Self", "150 ft. (20 ft. Sphere)" -> "150 ft."
>>   // - drops the trailing area-shape descriptor, keeps just the range itself
>>   return String(r || "").replace(/\s*\(.*?\)\s*$/, "").trim();
>> }
>>
>> for (const lvl of levels) {
>>   dv.container.createEl("h4", {cls: "spell-level-header", text: levelName(lvl)});
>>   const header = dv.container.createEl("div", {cls: "spell-row spell-row-header"});
>>   for (const h of ["Spell", "Time", "Range", "Hit/DC", "Effect"]) {
>>     header.createEl("span", {text: h});
>>   }
>>   header.createEl("span", {text: ""});
>>   for (const entry of grouped[lvl]) {
>>     const p = entry.page;
>>     const row = dv.container.createEl("div", {cls: "spell-row"});
>>     const nameSpan = row.createEl("span", {cls: "action-name"});
>>     nameSpan.createEl("a", {text: p.file.name, cls: "internal-link", href: p.file.path});
>>     if (entry.isUpcast) nameSpan.createEl("span", {cls: "spell-upcast-tag", text: " ↑"});
>>     row.createEl("span", {cls: "action-stat", text: abbrevTime(p["Casting Time"])});
>>     row.createEl("span", {cls: "action-stat", text: shortRange(p["Range / Area"])});
>>     row.createEl("span", {cls: "action-stat", text: formatHitDC(p["Attack / Save"])});
>>     row.createEl("span", {cls: "action-stat", text: entry.effectText});
>>     if (!entry.isUpcast) {
>>       const rm = row.createEl("button", {cls: "action-btn", text: "✕"});
>>       rm.onclick = async () => {
>>         await app.fileManager.processFrontMatter(file, (fm) => {
>>           fm.spells = (fm.spells || []).filter(s => s !== `[[${p.file.name}]]`);
>>         });
>>       };
>>     } else {
>>       row.createEl("span", {text: ""});
>>     }
>>   }
>> }
>> ```
>>
>> </div>
>>
>> <div class="tab-panel inventory-panel">
>>
>> <div class="add-action-form">
>>
>> Name: `INPUT[text(class(medium-input)):new_item_name]` Weight: `INPUT[text(class(narrow-input)):new_item_weight]` QTY: `INPUT[text(class(narrow-input)):new_item_qty]` Cost: `INPUT[text(class(narrow-input)):new_item_cost]` `BUTTON[add-item-btn]`
>>
>> ```meta-bind-button
>> label: "Add"
>> style: "primary"
>> hidden: true
>> id: "add-item-btn"
>> actions:
>>   - type: updateMetadata
>>     bindTarget: inventory_list
>>     evaluate: true
>>     value: "[...getMetadata('inventory_list'), {name: getMetadata('new_item_name'), weight: getMetadata('new_item_weight'), qty: getMetadata('new_item_qty'), cost: getMetadata('new_item_cost')}]"
>>   - type: updateMetadata
>>     bindTarget: new_item_name
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_item_weight
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_item_qty
>>     evaluate: false
>>     value: ""
>>   - type: updateMetadata
>>     bindTarget: new_item_cost
>>     evaluate: false
>>     value: ""
>> ```
>>
>> </div>
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>> const items = page.inventory_list || [];
>>
>> const updateBtn = dv.container.createEl("button", {cls: "action-btn-update", text: "Update All"});
>> updateBtn.onclick = () => openInventoryModal(items, file);
>>
>> const header = dv.container.createEl("div", {cls: "inventory-row inventory-row-header"});
>> for (const h of ["Name", "Weight", "QTY", "Cost"]) header.createEl("span", {text: h});
>> header.createEl("span", {text: ""});
>>
>> items.forEach((item, idx) => {
>>   const row = dv.container.createEl("div", {cls: "inventory-row"});
>>   row.createEl("span", {cls: "action-name", text: item.name});
>>   row.createEl("span", {cls: "action-stat", text: String(item.weight ?? "")});
>>   row.createEl("span", {cls: "action-stat", text: String(item.qty ?? "")});
>>   row.createEl("span", {cls: "action-stat", text: String(item.cost ?? "")});
>>   const rm = row.createEl("button", {cls: "action-btn", text: "✕"});
>>   rm.onclick = async () => {
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.inventory_list.splice(idx, 1);
>>     });
>>   };
>> });
>>
>> function openInventoryModal(items, file) {
>>   const overlay = document.createElement("div");
>>   overlay.className = "action-modal-overlay";
>>   const modal = overlay.createEl("div", {cls: "action-modal"});
>>   modal.createEl("h3", {text: "Edit Inventory"});
>>
>>   const rows = items.map((item) => {
>>     const row = modal.createEl("div", {cls: "action-modal-row"});
>>     const nameInput = row.createEl("input", {type: "text", cls: "action-modal-name"});
>>     nameInput.value = item.name ?? "";
>>     const weightInput = row.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>     weightInput.value = item.weight ?? "";
>>     const qtyInput = row.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>     qtyInput.value = item.qty ?? "";
>>     const costInput = row.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>     costInput.value = item.cost ?? "";
>>     const delBtn = row.createEl("button", {text: "✕"});
>>     const state = {deleted: false};
>>     delBtn.onclick = () => {
>>       state.deleted = true;
>>       row.style.opacity = "0.35";
>>       row.style.textDecoration = "line-through";
>>     };
>>     return {state, nameInput, weightInput, qtyInput, costInput};
>>   });
>>
>>   const btnRow = modal.createEl("div", {cls: "action-modal-btnrow"});
>>   const saveBtn = btnRow.createEl("button", {cls: "action-btn-update", text: "Save"});
>>   const cancelBtn = btnRow.createEl("button", {text: "Cancel"});
>>
>>   cancelBtn.onclick = () => overlay.remove();
>>   saveBtn.onclick = async () => {
>>     const newList = rows
>>       .filter(r => !r.state.deleted)
>>       .map(r => ({
>>         name: r.nameInput.value,
>>         weight: r.weightInput.value,
>>         qty: r.qtyInput.value,
>>         cost: r.costInput.value,
>>       }));
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.inventory_list = newList;
>>     });
>>     overlay.remove();
>>   };
>>
>>   document.body.appendChild(overlay);
>> }
>> ```
>>
>> </div>
>>
>> <div class="tab-panel features-panel">
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>> const uses = page.limited_uses || [];
>>
>> const btnRow = dv.container.createEl("div", {cls: "hp-extra-row"});
>> const addBtn = btnRow.createEl("button", {cls: "action-btn-update", text: "Add Feature"});
>> const editBtn = btnRow.createEl("button", {cls: "action-btn-update", text: "Edit"});
>>
>> addBtn.onclick = () => openAddFeatureModal(file);
>> editBtn.onclick = () => openEditFeaturesModal(uses, file);
>>
>> uses.forEach((item, idx) => {
>>   const entry = dv.container.createEl("div", {cls: "feature-entry"});
>>   entry.createEl("div", {cls: "feature-name", text: item.name});
>>   if (item.description) {
>>     entry.createEl("div", {cls: "feature-description", text: item.description});
>>   }
>>   if (item.max && Number(item.max) > 0) {
>>     const usesRow = entry.createEl("div", {cls: "spell-slots-row feature-row"});
>>     usesRow.createEl("span", {cls: "spell-slots-label", text: "Uses"});
>>     for (let i = 0; i < Number(item.max); i++) {
>>       const cb = usesRow.createEl("input", {type: "checkbox"});
>>       cb.checked = i < (item.used || 0);
>>       cb.onclick = async () => {
>>         const nowUsed = cb.checked;
>>         await app.fileManager.processFrontMatter(file, (fm) => {
>>           const cur = fm.limited_uses[idx].used || 0;
>>           fm.limited_uses[idx].used = nowUsed
>>             ? Math.min(Number(item.max), cur + 1)
>>             : Math.max(0, cur - 1);
>>         });
>>       };
>>     }
>>     usesRow.createEl("span", {cls: "feature-rest-badge", text: item.rest});
>>   }
>> });
>>
>> function openAddFeatureModal(file) {
>>   const overlay = document.createElement("div");
>>   overlay.className = "action-modal-overlay";
>>   const modal = overlay.createEl("div", {cls: "action-modal action-modal-feature"});
>>   modal.createEl("h3", {text: "Add Feature"});
>>
>>   const nameRow = modal.createEl("div", {cls: "action-modal-row"});
>>   nameRow.createEl("span", {cls: "action-modal-label", text: "Name"});
>>   const nameInput = nameRow.createEl("input", {type: "text", cls: "feature-name-input"});
>>
>>   const descBlock = modal.createEl("div", {cls: "feature-desc-block"});
>>   descBlock.createEl("span", {cls: "action-modal-label", text: "Description"});
>>   const descInput = descBlock.createEl("textarea", {cls: "feature-desc-textarea"});
>>
>>   const maxRow = modal.createEl("div", {cls: "action-modal-row"});
>>   maxRow.createEl("span", {cls: "action-modal-label", text: "Max Uses"});
>>   const maxInput = maxRow.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>   maxInput.value = "0";
>>
>>   const restRow = modal.createEl("div", {cls: "action-modal-row"});
>>   restRow.createEl("span", {cls: "action-modal-label", text: "Resets"});
>>   const restSelect = restRow.createEl("select");
>>   for (const r of ["Short", "Long"]) {
>>     const opt = restSelect.createEl("option", {text: r});
>>     opt.value = r;
>>   }
>>
>>   const btnRow2 = modal.createEl("div", {cls: "action-modal-btnrow"});
>>   const saveBtn = btnRow2.createEl("button", {cls: "action-btn-update", text: "Save"});
>>   const cancelBtn = btnRow2.createEl("button", {text: "Cancel"});
>>
>>   cancelBtn.onclick = () => overlay.remove();
>>   saveBtn.onclick = async () => {
>>     const name = nameInput.value.trim();
>>     if (!name) { overlay.remove(); return; }
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.limited_uses = fm.limited_uses || [];
>>       fm.limited_uses.push({
>>         name,
>>         description: descInput.value,
>>         max: Number(maxInput.value) || 0,
>>         used: 0,
>>         rest: restSelect.value,
>>       });
>>     });
>>     overlay.remove();
>>   };
>>
>>   document.body.appendChild(overlay);
>> }
>>
>> function openEditFeaturesModal(items, file) {
>>   const overlay = document.createElement("div");
>>   overlay.className = "action-modal-overlay";
>>   const modal = overlay.createEl("div", {cls: "action-modal action-modal-feature"});
>>   modal.createEl("h3", {text: "Edit Features"});
>>
>>   const rows = items.map((item) => {
>>     const row = modal.createEl("div", {cls: "action-modal-row"});
>>     const nameInput = row.createEl("input", {type: "text", cls: "feature-name-input"});
>>     nameInput.value = item.name;
>>     const delBtn = row.createEl("button", {text: "✕"});
>>
>>     const descBlock = modal.createEl("div", {cls: "feature-desc-block"});
>>     descBlock.createEl("span", {cls: "action-modal-label", text: "Description"});
>>     const descInput = descBlock.createEl("textarea", {cls: "feature-desc-textarea"});
>>     descInput.value = item.description || "";
>>
>>     const statsRow = modal.createEl("div", {cls: "action-modal-row"});
>>     statsRow.createEl("span", {cls: "action-modal-label", text: "Max Uses"});
>>     const maxInput = statsRow.createEl("input", {type: "text", cls: "action-modal-narrow"});
>>     maxInput.value = item.max || 0;
>>     statsRow.createEl("span", {cls: "action-modal-label", text: "Resets"});
>>     const restSelect = statsRow.createEl("select");
>>     for (const r of ["Short", "Long"]) {
>>       const opt = restSelect.createEl("option", {text: r});
>>       opt.value = r;
>>       if (r === item.rest) opt.selected = true;
>>     }
>>
>>     const state = {deleted: false};
>>     delBtn.onclick = () => {
>>       state.deleted = true;
>>       row.style.opacity = "0.35";
>>       descBlock.style.opacity = "0.35";
>>       statsRow.style.opacity = "0.35";
>>       row.style.textDecoration = "line-through";
>>     };
>>     return {state, nameInput, descInput, maxInput, restSelect, prevUsed: item.used || 0};
>>   });
>>
>>   const btnRow2 = modal.createEl("div", {cls: "action-modal-btnrow"});
>>   const saveBtn = btnRow2.createEl("button", {cls: "action-btn-update", text: "Save"});
>>   const cancelBtn = btnRow2.createEl("button", {text: "Cancel"});
>>
>>   cancelBtn.onclick = () => overlay.remove();
>>   saveBtn.onclick = async () => {
>>     const newList = rows
>>       .filter((r) => !r.state.deleted)
>>       .map((r) => ({
>>         name: r.nameInput.value,
>>         description: r.descInput.value,
>>         max: Number(r.maxInput.value) || 0,
>>         used: Math.min(r.prevUsed, Number(r.maxInput.value) || 0),
>>         rest: r.restSelect.value,
>>       }));
>>     await app.fileManager.processFrontMatter(file, (fm) => {
>>       fm.limited_uses = newList;
>>     });
>>     overlay.remove();
>>   };
>>
>>   document.body.appendChild(overlay);
>> }
>> ```
>>
>> </div>
>>
>> <div class="tab-panel notes-panel">
>>
>> ```dataviewjs
>> const page = dv.current();
>> const file = app.vault.getAbstractFileByPath(page.file.path);
>>
>> const notesArea = dv.container.createEl("textarea", {cls: "player-notes-textarea"});
>> notesArea.value = page.player_notes || "";
>> notesArea.placeholder = "Player secrets, reminders, anything you want to keep track of...";
>>
>> const saveBtn = dv.container.createEl("button", {cls: "action-btn-update", text: "Save"});
>> saveBtn.onclick = async () => {
>>   await app.fileManager.processFrontMatter(file, (fm) => {
>>     fm.player_notes = notesArea.value;
>>   });
>> };
>> ```
>>
>> </div>

---

> [!quote|no-t]
> A short, evocative line capturing who this character is.

> [!column|flex 2]
>> [!important]- DĚJOVÁ LINIE:
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Name
>>     filters:
>>       and:
>>         - file.inFolder("Dungeons & Dragons/01. Kampaň/2. Hráči/Úkoly")
>>         - file.hasLink(this.file)
>>     order:
>>       - file.name
>> ```
>
>> [!note]- HISTORIE
>> ```base
>> properties:
>>   file.name:
>>     displayName: Name
>> views:
>>   - type: table
>>     name: Session Notes
>>     filters:
>>       and:
>>         - file.inFolder("Dungeons & Dragons/01. Kampaň/1. Master Plan/Deník")
>>         - file.hasLink(this.file)
>> ```

# Backstory
Write the character's backstory here.

# DnD Beyond
<iframe src="" allow="fullscreen" allowfullscreen="" style="height: 100%; width: 100%; aspect-ratio: 1 / 1;"></iframe>
---

# Life Events

- 

# Cíle
- 

# Plány DM
- 
