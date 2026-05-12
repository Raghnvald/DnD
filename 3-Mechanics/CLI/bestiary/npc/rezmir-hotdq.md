---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hotdq
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/half-black-dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Rezmir"
---
# [Rezmir](3-Mechanics/CLI/bestiary/npc/rezmir-hotdq.md)
*Source: Hoard of the Dragon Queen p. 93, Tyranny of Dragons p. 180*  

```statblock
"name": "Rezmir (HotDQ)"
"size": "Medium"
"type": "humanoid"
"subtype": "half-black dragon"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "15 with the Black Dragon Mask"
"hp": !!int "90"
"hit_dice": "12d8 + 36"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "15"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+9"
"damage_immunities": "acid"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword-xphb.md)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 10 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 11"
"languages": "Common, Draconic, Infernal, Giant, Netherese"
"cr": "7"
"traits":
  - "desc": "Rezmir has the [Black Dragon Mask](3-Mechanics/CLI/items/black-dragon-mask-hotdq.md),\
      \ [Hazirawn](3-Mechanics/CLI/items/hazirawn-hotdq.md), and an [insignia of claws](3-Mechanics/CLI/items/insignia-of-claws-hotdq.md)."
    "name": "Special Equipment"
  - "desc": "Rezmir can breathe air and water."
    "name": "Amphibious"
  - "desc": "Once per turn, Rezmir can deal an extra 10 (3d6) damage when she hits\
      \ with a weapon attack, provided Rezmir has advantage on the attack roll."
    "name": "Dark Advantage"
  - "desc": "While wearing no armor and wearing the Black Dragon Mask, Rezmir adds\
      \ her Charisma bonus to her AC (included)."
    "name": "Draconic Majesty"
  - "desc": "When Rezmir is reduced to 0 hit points, her body disintegrates into a\
      \ pile of ash."
    "name": "Immolation"
  - "desc": "If Rezmir fails a saving throw while wearing the Black Dragon Mask, she\
      \ can choose to succeed instead."
    "name": "Legendary Resistance (1/Day)"
"actions":
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d6 + 6) slashing damage plus 7 (2d6) necrotic damage. If the target\
      \ is a creature, it can't regain hit points for 1 minute. The target can make\
      \ a DC 15 Constitution saving throw at the end of each of its turns, ending\
      \ this effect early on a success."
    "name": "Greatsword (Hazirawn)"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 90 ft., one target. *Hit:*\
      \ 18 (4d8) acid damage."
    "name": "Caustic Bolt"
  - "desc": "Rezmir breathes acid in a 30-foot line that is 5 feet wide. Each creature\
      \ in the line must make a DC 14 Dexterity saving throw, taking 22 (5d8) acid\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Acid Breath (Recharge 5-6)"
"legendary_description": "If she is wearing the Black Dragon Mask, Rezmir can take\
  \ up to two legendary actions between each of her turns, taking the actions all\
  \ at once or spreading them over the round. A legendary action can be taken only\
  \ at the start or end of a turn."
"legendary_actions":
  - "desc": "A 15-foot radius of magical darkness extends from a point Rezmir can\
      \ see within 60 feet of her and spreads around corners. The darkness lasts as\
      \ long as Rezmir maintains [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration),\
      \ up to 1 minute. A creature with darkvision can't see through this darkness,\
      \ and no natural light can illuminate it. If any of the area overlaps with a\
      \ area of light created by a spell of 2nd level or lower, the spell creating\
      \ the light is dispelled."
    "name": "Darkness (Costs 2 Actions)"
  - "desc": "Rezmir makes one melee attack."
    "name": "Melee Attack"
  - "desc": "Rezmir takes the [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Hide"
"source":
  - "HotDQ"
  - "ToD"
"image": "3-Mechanics/CLI/bestiary/npc/token/rezmir-hotdq.webp"
```
^statblock