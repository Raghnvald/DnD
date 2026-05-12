---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Harpy"
---
# [Harpy](3-Mechanics/CLI/bestiary/monstrosity/harpy-psx.md)
*Source: Plane Shift: Ixalan p. 36*  

Harpies are the mortal servants of demons, and they resemble them in their general features. Their faces are like those of owls, and they have large, feathered wings that suggest their corrupt connection to the Sun Empire—or perhaps their heritage as sirens who were corrupted by the evil of the demons. Utterly nasty in temperament, harpies inhabit many of the islands in both the Stormwreck Sea and the Inner Sea, and dwell on high cliffs on the mainland of Ixalan. Their filthy bodies carry disease that they can spread through their bite.

Use the [harpy](3-Mechanics/CLI/bestiary/monstrosity/harpy.md) statistics in the "Monster Manual" for Ixalan's harpies, but replace the club attack with a bite attack.

## Night Terrors

The legends of the Sun Empire are populated with the enemies of the sun—terrible monsters that threaten to devour its light and undo its work. Unfortunately for the people of Ixalan, these are not just creatures of legend but real monsters with supernatural power, lurking in the darkness of night and the shadows of ancient ruins and crypts.

```statblock
"name": "Harpy (PSX)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "12"
  - !!int "7"
  - !!int "10"
  - !!int "13"
"speed": "20 ft., fly 40 ft."
"gear":
  - "[club](3-Mechanics/CLI/items/club.md)"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "The harpy makes two attacks: one with its claws and one with its bite."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (2d4 + 1) slashing damage."
    "name": "Claws"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d4 + 1) slashing damage. If the target is a creature, it must succeed\
      \ on a DC 11 Constitution saving throw or contract a disease. Until the disease\
      \ is cured, the target can't regain hit points except by magical means, and\
      \ the target's hit point maximum decreases by 3 (1d6) every 24 hours. If the\
      \ target's hit point maximum drops to 0 as a result of this disease, the target\
      \ dies."
    "name": "Bite"
  - "desc": "The harpy sings a magical melody. Every humanoid and giant within 300\
      \ feet of the harpy that can hear the song must succeed on a DC 11 Wisdom saving\
      \ throw or be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) until the\
      \ song ends. The harpy must take a bonus action on its subsequent turns to continue\
      \ singing. It can stop singing at any time. The song ends if the harpy is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated).\n\
      \nWhile [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) by the harpy,\
      \ a target is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and ignores the songs of other harpies. If the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ target is more than 5 feet away from the harpy, the target must move on its\
      \ turn toward the harpy by the most direct route. It doesn't avoid opportunity\
      \ attacks, but before moving into damaging terrain, such as lava or a pit, and\
      \ whenever it takes damage from a source other than the harpy, a target can\
      \ repeat the saving throw. A creature can also repeat the saving throw at the\
      \ end of each of its turns. If a creature's saving throw is successful, the\
      \ effect ends on it.\n\nA target that successfully saves is immune to this harpy's\
      \ song for the next 24 hours."
    "name": "Luring Song"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/harpy-psx.webp"
```
^statblock