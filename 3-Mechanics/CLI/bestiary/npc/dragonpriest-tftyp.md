---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dragonpriest"
---
# [Dragonpriest](3-Mechanics/CLI/bestiary/npc/dragonpriest-tftyp.md)
*Source: Tales from the Yawning Portal p. 16*  

```statblock
"name": "Dragonpriest (TftYP)"
"size": "Large"
"type": "giant"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "30"
"hit_dice": "8d10 + 40"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "13"
  - !!int "20"
  - !!int "7"
  - !!int "9"
  - !!int "7"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": "Elvish, Draconic"
"cr": "5"
"traits":
  - "desc": "The dragonpriest has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The dragonpriest regains 5 hit points at the start of its turn. If the\
      \ dragonpriest takes acid or fire damage, this trait doesn't function at the\
      \ start of the dragonpriest's next turn. The dragonpriest dies only if it starts\
      \ its turn with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage."
    "name": "Claw"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/npc/token/dragonpriest-tftyp.webp"
```
^statblock