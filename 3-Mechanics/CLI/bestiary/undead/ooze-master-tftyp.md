---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ooze Master"
---
# [Ooze Master](3-Mechanics/CLI/bestiary/undead/ooze-master-tftyp.md)
*Source: Tales from the Yawning Portal p. 241*  

```statblock
"name": "Ooze Master (TftYP)"
"size": "Huge"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "9"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "-5"
"stats":
  - !!int "16"
  - !!int "1"
  - !!int "20"
  - !!int "17"
  - !!int "10"
  - !!int "16"
"speed": "30 ft., climb 30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+7"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
"damage_resistances": "lightning; necrotic; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "acid, cold, poison"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 120 ft., passive\
  \ Perception 10"
"languages": "Common, Primordial, Thayan"
"cr": "10"
"traits":
  - "desc": "The Ooze Master is a 9th-level spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 15, +7 to hit with spell attacks). It has\
      \ the following wizard spells prepared:\n\n**Cantrips (at will):** [acid splash](3-Mechanics/CLI/spells/acid-splash-xphb.md),\
      \ [friends](3-Mechanics/CLI/spells/friends-xphb.md), [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [poison spray](3-Mechanics/CLI/spells/poison-spray-xphb.md)\n\n**1st level\
      \ (4 slots):** [charm person](3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md),\
      \ [ray of sickness](3-Mechanics/CLI/spells/ray-of-sickness-xphb.md)\n\n**2nd\
      \ level (3 slots):** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [Melf's acid arrow](3-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md), [suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md)\n\
      \n**3rd level (3 slots):** [fear](3-Mechanics/CLI/spells/fear-xphb.md), [slow](3-Mechanics/CLI/spells/slow-xphb.md),\
      \ [stinking cloud](3-Mechanics/CLI/spells/stinking-cloud-xphb.md)\n\n**4th level\
      \ (3 slots):** [confusion](3-Mechanics/CLI/spells/confusion-xphb.md), [Evard's\
      \ black tentacles](3-Mechanics/CLI/spells/evards-black-tentacles-xphb.md)\n\n\
      **5th level (1 slots):** [cloudkill](3-Mechanics/CLI/spells/cloudkill-xphb.md)"
    "name": "Spellcasting"
  - "desc": "A creature that touches the Ooze Master or hits it with a melee attack\
      \ while within 5 feet of it takes 9 (2d8) acid damage. Any nonmagical weapon\
      \ that hits the Ooze Master corrodes. After dealing damage, the weapon takes\
      \ a permanent and cumulative −1 penalty to damage rolls. If its penalty drops\
      \ to −5, the weapon is destroyed. Nonmagical ammunition that hits the Ooze Master\
      \ is destroyed after dealing damage.\n\nThe Ooze Master can eat through 2-inch-thick,\
      \ nonmagical wood or metal in 1 round."
    "name": "Corrosive Form"
  - "desc": "When the Ooze Master casts a spell with a casting time of 1 action, it\
      \ can make one pseudopod attack as a bonus action."
    "name": "Instinctive Attack"
  - "desc": "The Ooze Master can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (3d6 + 3) bludgeoning damage plus 10 (3d6) acid damage."
    "name": "Pseudopod"
"reactions":
  - "desc": "If a creature the Ooze Master can see makes an attack roll against it\
      \ while within 30 feet of it, the Ooze Master can use a reaction to divert the\
      \ attack if another creature is within the attack's range. The attacker must\
      \ make a DC 15 Wisdom saving throw. On a failed save, the attacker targets the\
      \ creature that is closest to it, not including itself or the Ooze Master. If\
      \ multiple creatures are closest, the attacker chooses which one to target.\
      \ On a successful save, the attacker is immune to this Instinctive Charm for\
      \ 24 hours. Creatures that can't be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ are immune to this effect."
    "name": "Instinctive Charm"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/undead/token/ooze-master-tftyp.webp"
```
^statblock