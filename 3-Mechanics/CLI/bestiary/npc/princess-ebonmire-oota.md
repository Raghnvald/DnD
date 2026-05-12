---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oota
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Princess Ebonmire"
---
# [Princess Ebonmire](3-Mechanics/CLI/bestiary/npc/princess-ebonmire-oota.md)
*Source: Out of the Abyss p. 111*  

```statblock
"name": "Princess Ebonmire (OotA)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "7"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"modifier": !!int "-3"
"stats":
  - !!int "16"
  - !!int "5"
  - !!int "16"
  - !!int "6"
  - !!int "6"
  - !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "acid, cold, lightning, slashing"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [prone](3-Mechanics/CLI/rules/conditions.md#Prone)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 8"
"languages": ""
"cr": "4"
"traits":
  - "desc": "Princess Ebonmire can move through a space as narrow as 1 inch wide without\
      \ squeezing."
    "name": "Amorphous"
  - "desc": "A creature that touches Princess Ebonmire or hits it with a melee attack\
      \ while within 5 feet of it takes 4 (1d8) acid damage. Any nonmagical weapon\
      \ made of metal or wood that hits Princess Ebonmire corrodes. After dealing\
      \ damage, the weapon takes a permanent and cumulative −1 penalty to damage rolls.\
      \ If its penalty drops to −5, the weapon is destroyed. Nonmagical ammunition\
      \ made of metal or wood that hits Princess Ebonmire is destroyed after dealing\
      \ damage. Princess Ebonmire can eat through 2-inch-thick, nonmagical wood or\
      \ metal in 1 round."
    "name": "Corrosive Form"
  - "desc": "Princess Ebonmire can climb difficult surfaces, including upside down\
      \ on ceilings, without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or 30 ft.,\
      \ one target. *Hit:* 6 (1d6 + 3) bludgeoning damage plus 18 (4d8) acid damage.\
      \ In addition, nonmagical armor worn by the target is partly dissolved and takes\
      \ a permanent and cumulative −1 penalty to the AC it offers. The armor is destroyed\
      \ if the penalty reduces its AC to 10."
    "name": "Pseudopod"
"reactions":
  - "desc": "When a pudding that is Medium or larger is subjected to lightning or\
      \ slashing damage, it splits into two new puddings if it has at least 10 hit\
      \ points. Each new pudding has hit points equal to half the original pudding's,\
      \ rounded down. New puddings are one size smaller than the original pudding."
    "name": "Split"
"source":
  - "OotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/princess-ebonmire-oota.webp"
```
^statblock