---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Razerblast"
---
# [Razerblast](3-Mechanics/CLI/bestiary/humanoid/razerblast-pota.md)
*Source: Princes of the Apocalypse p. 201*  

A razerblast seethes with hate for the enemies of the fire cult. The razerblast's elemental overlords have replaced its heart with a flaming orb that detonates if the razerblast dies.

Razerblasts remember little of their life before they the power of elemental fire transformed them. Now they follow the orders of the flamewraths and the cult leaders without question. Razerblasts fight confidently because they know that even if they lose, they go out in a blaze of glory.

```statblock
"name": "Razerblast (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "[splint armor](3-Mechanics/CLI/items/splint-armor.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 75"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "16"
  - !!int "9"
  - !!int "10"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
"damage_immunities": "fire"
"gear":
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "passive Perception 13"
"languages": "Common, Ignan"
"cr": "5"
"traits":
  - "desc": "The razerblast's armor is hot. Any creature grappling the razerblast\
      \ or [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) by it takes 5\
      \ (1d10) fire damage at the end of that creature's turn."
    "name": "Searing Armor"
  - "desc": "When the razerblast drops to 0 hit points, a flaming orb in its chest\
      \ explodes, destroying the razerblast's body and scattering its armor as shrapnel.\
      \ Creatures within 10 feet of the razerblast when it explodes must succeed on\
      \ a DC 12 Dexterity saving throw, taking 21 (6d6) piercing damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Shrapnel Explosion"
"actions":
  - "desc": "The razerblast makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing\
      \ damage if used with two hands to make a melee attack, plus 3 (1d6) fire\
      \ damage."
    "name": "Spear"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/razerblast-pota.webp"
```
^statblock