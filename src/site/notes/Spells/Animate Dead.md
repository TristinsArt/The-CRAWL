---
{"dg-publish":true,"permalink":"/spells/animate-dead/"}
---

**Level:** 3rd-level
**Casting Time:** 1 minute
**Range:** 10 feet
**Components:** V, S, M (a drop of blood, a piece of flesh, and a pinch of bone dust)
**Duration:** Instantaneous
**School:** [[Spells/Schools of Magic/Necromancy\|Necromancy]]

This spell creates an undead servant. Choose a pile of bones or a corpse of a Medium or Small humanoid within range. Your spell imbues the target with a foul mimicry of life, raising it as an undead creature. The target becomes a skeleton if you chose bones or a zombie if you chose a corpse (the DM has the creature's game statistics).
On each of your turns, you can use a bonus action to mentally command any creature you made with this spell if the creature is within 60 feet of you (if you control multiple creatures, you can command any or all of them at the same time, issuing the same command to each one). You decide what action the creature will take and where it will move during its next turn, or you can issue a general command, such as to guard a particular chamber or corridor. If you issue no commands, the creature only defends itself against hostile creatures. Once given an order, the creature continues to follow it until its task is complete.
The creature is under your control for 24 hours, after which it stops obeying any command you've given it. To maintain control of the creature for another 24 hours, you must cast this spell on the creature again before the current 24-hour period ends. This use of the spell reasserts your control over up to four creatures you have animated with this spell, rather than animating a new one.
**_At Higher Levels_**
When you cast this spell using a spell slot of 4th level or higher, you animate or reassert control over two additional undead creatures for each slot level above 3rd. Each of the creatures must come from a different corpse or pile of bones.


```statblock
image: 
bestiary: true
name: Zombie
source:
  - XMM
  - XPHB
  - HBTD
  - DrDe
type: undead
size: Medium
alignment: neutral evil
hp: 15
hit_dice: 2d8 + 6
ac: 8
speed: 20 ft.
stats:
  - 13
  - 6
  - 16
  - 3
  - 6
  - 5
damage_immunities: poison
damage_resistances: ""
damage_vulnerabilities: ""
condition_immunities: exhaustion, poisoned
saves:
  - wisdom: "0"
skillsaves: []
senses: darkvision 60 ft., passive Perception 8
languages: understands Common plus one other language but can't speak
cr: 1/4
traits:
  - name: Undead Fortitude
    desc: If damage reduces the zombie to 0 {@variantrule Hit Points|XPHB}, it makes a Constitution saving throw (5 plus the damage taken) unless the damage is Radiant or from a {@variantrule Critical Hit|XPHB}. On a successful save, the zombie drops to 1 {@variantrule Hit Points|XPHB|Hit Point} instead.
actions:
  - name: Slam
    desc: "{@atkr m} +3, reach 5 ft. 5 (1d8 + 1) Bludgeoning damage."
bonus_actions: []
reactions: []
legendary_actions: []
mythic_actions: []
spells: []
spellsNotes: ""

```
```statblock
creature: Skeleton
```