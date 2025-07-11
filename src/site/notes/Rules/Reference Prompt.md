---
{"dg-publish":true,"permalink":"/rules/reference-prompt/"}
---

# Obsidian Content Creation Prompt (D&D 5e Vault)

This prompt is designed to ensure that any new pages you create follow the same structure, linking logic, and organizational style as the existing vault. Use it when generating new spells, features, races, items, or reference entries.

---

## 🧱 Folder Structure

Organize content into these top-level folders:
- `Spells/`
- `Schools of Magic/`
- `Fighting Styles/`
- `Maneuvers/`
- `Invocations/`
- `References/`
    - `Actions/`
    - `Conditions/`
    - `Skills/`
    - `Senses/`
    - `Abilities/`
    - `Mechanics/`
    - `Quickref/`

Each item in a subfolder should be a dedicated `.md` file titled with the name of the concept (e.g., `Darkvision.md`, `Attack.md`).

---

## 🧙 Spell Page Format

- **Title**: Do not repeat the name in the content; use the filename as the page name.
- **No tags or YAML headers**
- **No frontmatter**
- Display fields:
  - **Level**, **Casting Time**, **Range**, **Components**, **Duration**, **School** (link to `[[School Name]]`)
- Full description with:
  - Bullets preserved
  - Linked references per below
  - `Range:` and `Duration:` parsed cleanly from raw JSON (e.g., "Sight", "Instantaneous", "1 hour")
- End with **no tags** or summaries.

---

## 🔗 Linking Rules (apply to all content types)

### Magic Schools
- Link like `[[Evocation]]`, `[[Necromancy]]` inside `Schools of Magic/`

### Actions
- Link terms like `Attack`, `Hide`, `Cast a Spell` as `[[Attack]]` inside `References/Actions/`

### Skills
- Always link skills like `[[Athletics]]`, `[[Arcana]]`, etc. to `References/Skills/`

### Senses
- Link like `[[Darkvision]]`, `[[Blindsight]]`, `[[Tremorsense]]` in `References/Senses/`

### Conditions
- Link like `[[Stunned]]`, `[[Grappled]]`, `[[Invisible]]` in `References/Conditions/`

### Abilities
- Link `Strength`, `Dexterity`, etc. to `[[Strength]]` in `References/Abilities/`

### Mechanics (new rules)
- Link terms like:
  - `[[Superiority Die]]`
  - `[[Initiative]]`
  - `[[Advantage and Disadvantage]]`
  - `[[Bonus Action]]`
  - `[[Reaction]]`
  - `[[Unarmed Strike]]`
  - `[[Opportunity Attack]]`

### Spell & Maneuver Linking
- If a spell or maneuver name matches another page, link like `[[Misty Step]]`, `[[Precision Attack]]`

### Item References
- Make item names **bold** (not links)

### Damage, Dice, DC, Chance
- `@damage`, `@dice`, `@dc`, `@chance` → **bold text**, or translated:
  - `"5|||Effect ends|Effect continues"` becomes: “Roll a d20: On a 5 or lower, the effect ends; otherwise, it continues.”

### Notes and Quickref
- `@note Something important` → `_“Something important”_` (quoted + underlined)
- `@quickref cover` → `[[Cover]]` or similar existing reference

### Filters
- Link filter categories only if they exist (e.g., `@filter sense` → `[[Senses]]`)
- If no match, leave as plain text

### Hexblade/Hex references
- Replace any mention of “Hexblade’s Curse” or “Hex” → `[[Hex]]`

---

## ✅ Summary
Any new content must:
- Match folder structure and naming
- Follow the reference and link conventions
- Create new reference pages if a linked concept doesn't yet exist

---

Use this document as a system prompt for future generation, or to instruct an AI to follow the vault rules exactly.