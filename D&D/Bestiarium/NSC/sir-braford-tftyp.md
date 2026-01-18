---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/tftyp
  - Monster/HG/1-2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sir Braford
---
# [Sir Braford](3-Mechanics\CLI\bestiary\npc/sir-braford-tftyp.md)
*Source: Tales from the Yawning Portal p. 243*  

While traveling in the vicinity of the Sunless Citadel, Sir Braford and his companions were captured by goblins. The young paladin of Pelor has been corrupted by the sinister Gulthias Tree and now swings his magic sword, [Shatterspike](/3-Mechanics/CLI/items/shatterspike-tftyp.md), on behalf of a different sort of "deity."

```statblock
"name": "Sir Braford (TftYP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "chain mail, shield"
"hp": !!int "19"
"hit_dice": "3d8 + 6"
"modifier": !!int "-1"
"stats":
  - !!int "16"
  - !!int "9"
  - !!int "14"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "Athletics"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+3"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "Sir Braford's AC can't be lower than 16."
    "name": "Barkskin"
  - "desc": "Sir Braford wields [Shatterspike](/3-Mechanics/CLI/items/shatterspike-tftyp.md),\
      \ a magic longsword that grants a +1 bonus to attack and damage rolls made with\
      \ it (included in his attack). See the Shatterspike handout for the item's other\
      \ properties."
    "name": "Special Equipment"
  - "desc": "If the Gulthias Tree dies, Sir Braford dies 24 hours later."
    "name": "Tree Thrall"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with two hands."
    "name": "Longsword"
"reactions":
  - "desc": "When a creature Sir Braford can see attacks a target other than him that\
      \ is within 5 feet of him, he can use a reaction to use his shield to impose\
      \ disadvantage on the attack roll."
    "name": "Protection"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/npc/token/sir-braford-tftyp.webp"
```
^statblock