---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Redbud
image: token/redbud-veor.webp
Image: token/redbuld-veor.webp
status: WIP
linter-yaml-title-alias: Redbud
tags:
  - Monster/Größe/Riesig
  - Monster/HG/9
  - Monster/Typ/Pflanze
  - Quelle/5e/veor
aliases:
  - Redbud
---
# [Redbud](3-Mechanics\CLI\bestiary\npc/redbud-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Redbud (VEoR)"
"size": "Huge"
"type": "plant"
"alignment": "Chaotic Good"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "-1"
"stats":
  - !!int "23"
  - !!int "8"
  - !!int "21"
  - !!int "12"
  - !!int "16"
  - !!int "12"
"speed": "0 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "9"
"traits":
  - "desc": "While Redbud remains motionless, it is indistinguishable from a normal\
      \ tree."
    "name": "False Appearance"
  - "desc": "Redbud deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "Redbud makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (3d6 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 60/180 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage."
    "name": "Rock"
  - "desc": "Redbud magically animates one or two trees it can see within 60 feet\
      \ of it. These trees have the same statistics as a [treant](/3-Mechanics/CLI/bestiary/plant/treant.md),\
      \ except they have Intelligence and Charisma scores of 1, they can't speak,\
      \ and they have only the Slam action option. An animated tree acts as an ally\
      \ of Redbud. The tree remains animate for 1 day or until it dies; until Redbud\
      \ dies or is more than 120 feet from the tree; or until Redbud takes a bonus\
      \ action to turn it back into an inanimate tree. The tree then takes root if\
      \ possible."
    "name": "Animate Trees (1/Day)"
"source":
  - "VEoR"
"image": "nsc/token/redbud-veor.webp"
```
^statblock