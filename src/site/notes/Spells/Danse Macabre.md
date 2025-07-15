---
{"dg-publish":true,"permalink":"/spells/danse-macabre/"}
---

**Level:** 5th-level
**Casting Time:** 1 action
**Range:** 60 feet
**Components:** V, S
**Duration:** 1 hour
**School:** [[Spells/Schools of Magic/Necromancy\|Necromancy]]

Threads of dark power leap from your fingers to pierce up to five Small or Medium corpses you can see within range. Each corpse immediately stands up and becomes undead. You decide whether it is a zombie or a skeleton (the statistics for zombie and skeletons are in the Monster Manual), and it gains a bonus to its attack and damage rolls equal to your spellcasting ability modifier.
You can use a bonus action to mentally command the creatures you make with this spell, issuing the same command to all of them. To receive the command, a creature must be within 60 feet of you. You decide what action the creatures will take and where they will move during their next turn, or you can issue a general command, such as to guard a chamber or passageway against your foes. If you issue no commands, the creatures do nothing except defend themselves against hostile creatures. Once given an order, the creatures continue to follow it until their task is complete.
The creatures are under your control until the spell ends, after which they become inanimate once more.
**_At Higher Levels_**
When you cast this spell using a spell slot of 6th level or higher, you animate up to two additional corpses for each slot level above 5th.


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