---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Reduced-Threat Gray Ooze"
---
# [Reduced-Threat Gray Ooze](3-Mechanics/CLI/bestiary/ooze/reduced-threat-gray-ooze-tftyp.md)
*Source: Tales from the Yawning Portal p. 113*  

```statblock
"name": "Reduced-Threat Gray Ooze (TftYP)"
"size": "Medium"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "11"
"hit_dice": "3d8 + 9"
"modifier": !!int "-2"
"stats":
  - !!int "12"
  - !!int "6"
  - !!int "16"
  - !!int "1"
  - !!int "6"
  - !!int "2"
"speed": "10 ft., climb 10 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+0"
"damage_resistances": "acid, cold, fire"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 8"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "A reduced-threat monster takes a −2 penalty on attack rolls (included\
      \ in the stat block), ability checks (included in the stat block for skill proficiencies),\
      \ saving throws (included in the stat block for saving throw proficiencies),\
      \ and saving throw DCs (included in the stat block)."
    "name": "Reduced Threat"
  - "desc": "The ooze can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "Any nonmagical weapon made of metal that hits the ooze corrodes. After\
      \ dealing damage, the weapon takes a permanent and cumulative −1 penalty to\
      \ damage rolls. If its penalty drops to −5, the weapon is destroyed. Nonmagical\
      \ ammunition made of metal that hits the ooze is destroyed after dealing damage.\n\
      \nThe ooze can eat through 2-inch-thick, nonmagical metal in 1 round."
    "name": "Corrode Metal"
  - "desc": "While the ooze remains motionless, it is indistinguishable from an oily\
      \ pool or wet rock."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +1 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d6 + 1) bludgeoning damage plus 7 (2d6) acid damage, and if the target\
      \ is wearing nonmagical metal armor, its armor is partly corroded and takes\
      \ a permanent and cumulative −1 penalty to the AC it offers. The armor is destroyed\
      \ if the penalty reduces its AC to 10."
    "name": "Pseudopod"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/ooze/token/reduced-threat-gray-ooze-tftyp.webp"
```
^statblock