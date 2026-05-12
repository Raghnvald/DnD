---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Anacreda"
---
# [Anacreda](3-Mechanics/CLI/bestiary/npc/anacreda-coa.md)
*Source: Chains of Asmodeus p. 146*  

```statblock
"name": "Anacreda (CoA)"
"size": "Large"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "253"
"hit_dice": "22d10 + 132"
"modifier": !!int "3"
"stats":
  - !!int "25"
  - !!int "16"
  - !!int "22"
  - !!int "15"
  - !!int "16"
  - !!int "19"
"speed": "40 ft., fly 40 ft."
"saves":
  - "constitution": !!int "12"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "Deception"
    "desc": "+10"
  - "name": "Perception"
    "desc": "+9"
"damage_immunities": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"senses": "darkvision 120 ft., truesight 10 ft., passive Perception 19"
"languages": "Common, Giant, Infernal, Sylvan"
"cr": "17"
"actions":
  - "desc": "Anacreda makes two Claw attacks. She can replace one of the attacks with\
      \ a Crushing Hug attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one target. *Hit:*\
      \ 16 (2d8 + 7) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one target. *Hit:*\
      \ 51 (8d10 + 7) bludgeoning damage, and if the target is a Large or smaller\
      \ creature, Anacreda grabs it with both arms. The target has the grappled condition\
      \ (escape DC 18). Until the grapple ends, the target takes 73 (12d10 + 7)\
      \ necrotic damage at the start of each of Anacreda's turns. Anacreda can't make\
      \ attacks while grappling a creature in this way."
    "name": "Crushing Hug"
  - "desc": "Anacreda causes a 50-foot-long, 5-foot-wide row of bones to pierce the\
      \ earth at a point within 120 feet of her. She chooses the direction of the\
      \ line. The bones rise 10 feet into the air and form a solid wall. A 5-foot\
      \ section of bone has an AC of 20 and 10 hit points."
    "name": "Spinewall"
  - "desc": "Anacreda shrieks loud enough to shatter stone and bone alike. Each creature\
      \ within a 50-foot-radius sphere centered on Anacreda must make a DC 18 Constitution\
      \ saving throw. A creature takes 55 (10d10) thunder damage on a failed save,\
      \ or half as much damage on a successful one. Unworked stone, exposed bone,\
      \ and similar materials in the radius are shattered and turned into difficult\
      \ terrain."
    "name": "Shattering Shriek (1/Day)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/anacreda-coa.webp"
```
^statblock