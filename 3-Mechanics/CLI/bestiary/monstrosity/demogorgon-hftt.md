---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hftt
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Demogorgon"
---
# [Demogorgon](3-Mechanics/CLI/bestiary/monstrosity/demogorgon-hftt.md)
*Source: Hunt for the Thessalhydra p. 36*  

A predator of the Upside Down, the demogorgon hunts the dimension looking for unfortunate creatures that find their way there. The size and shape of an adult humanoid, the demogorgon's mouth encompasses its face and unfolds like a blossoming flower

```statblock
"name": "Demogorgon (HftT)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "60"
"hit_dice": "8d8 + 24"
"modifier": !!int "1"
"stats":
  - !!int "16"
  - !!int "12"
  - !!int "16"
  - !!int "3"
  - !!int "12"
  - !!int "5"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
  - "name": "Stealth"
    "desc": "+5"
"senses": "blindsight 60 ft., passive Perception 13"
"languages": ""
"cr": "4"
"traits":
  - "desc": "The demogorgon has advantage on Wisdom (Perception) checks that rely\
      \ on smell."
    "name": "Keen Smell"
  - "desc": "The demogorgon has advantage on melee attack rolls against any creature\
      \ that doesn't have all its hit points."
    "name": "Blood Frenzy"
  - "desc": "The demogorgon regains 10 hit points at the start of its turn. If the\
      \ demogorgon takes acid or fire damage, this trait doesn't function at the start\
      \ of the demogorgon's next turn. The demogorgon dies only if it starts its turn\
      \ with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "The demogorgon makes three attacks: one with its bite and two with its\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d8 + 3) slashing damage."
    "name": "Claw"
"source":
  - "HftT"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/demogorgon-hftt.webp"
```
^statblock