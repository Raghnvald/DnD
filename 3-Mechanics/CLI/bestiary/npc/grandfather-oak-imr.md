---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Grandfather Oak"
---
# [Grandfather Oak](3-Mechanics/CLI/bestiary/npc/grandfather-oak-imr.md)
*Source: Infernal Machine Rebuild p. 5*  

```statblock
"name": "Grandfather Oak (IMR)"
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
"speed": "30 ft."
"damage_vulnerabilities": "fire"
"damage_resistances": "bludgeoning, piercing"
"senses": "passive Perception 13"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "9"
"traits":
  - "desc": "While Grandfather Oak remains motionless, it is indistinguishable from\
      \ a normal tree."
    "name": "False Appearance"
  - "desc": "Grandfather Oak deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "Grandfather Oak makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 16 (3d6 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 60/180 ft., one target. *Hit:*\
      \ 28 (4d10 + 6) bludgeoning damage."
    "name": "Rock"
  - "desc": "Grandfather Oak magically animates one or two trees it can see within\
      \ 60 feet of it. These trees have the same statistics as a [treant](3-Mechanics/CLI/bestiary/plant/treant.md),\
      \ except they have Intelligence and Charisma scores of 1, they can't speak,\
      \ and they have only the Slam action option. An animated tree acts as an ally\
      \ of Grandfather Oak. The tree remains animate for 1 day or until it dies; until\
      \ Grandfather Oak dies or is more than 120 feet from the tree; or until Grandfather\
      \ Oak takes a bonus action to turn it back into an inanimate tree. The tree\
      \ then takes root if possible."
    "name": "Animate Trees (1/Day)"
  - "desc": "Grandfather Oak ejects spores at one creature it can see within 5 feet\
      \ of it. The target must succeed on a DC 17 Constitution saving throw or be\
      \ [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) for 1 minute. The target\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success."
    "name": "Pacifying Spores (3/Day)"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/grandfather-oak-imr.webp"
```
^statblock