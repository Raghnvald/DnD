---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/1-2
- Monster/Größe/Mittelgroß
- Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Scorchbringer Guard
---
# [Scorchbringer Guard](3-Mechanics\CLI\bestiary\humanoid/scorchbringer-guard-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 243*  

While chemisters focus on inventing new tools, weapons, and other devices for the guild to use, the role of a blastseeker is to put those devices to work. Despite the name, not all such devices produce explosions, but all the most interesting ones (from the Izzet perspective) do.

```statblock
"name": "Scorchbringer Guard (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "breastplate"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "9"
  - !!int "10"
"speed": "30 ft."
"senses": "passive Perception 9"
"languages": "any one language (usually Common)"
"cr": "1/2"
"traits":
  - "desc": "When the guard dies, or if it rolls a 1 when checking whether its Scorchbringer\
      \ action recharges, the tank on its back explodes in a 10-foot radius sphere.\
      \ Each creature in that area must make a DC 12 Dexterity saving throw, taking\
      \ 7 (2d6) fire damage on a failed save, or half as much damage on a successful\
      \ one. The explosion ignites flammable objects that aren't being worn or carried,\
      \ and it destroys the scorchbringer."
    "name": "Explosive Tank"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) bludgeoning damage."
    "name": "Light Hammer"
  - "desc": "The guard's scorchbringer spouts a stream of flame in a line that is\
      \ 30 feet long and 5 feet wide. Each creature in the line must make a DC 12\
      \ Dexterity saving throw, taking 7 (2d6) fire damage on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Scorchbringer (Recharge 4-6)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/scorchbringer-guard-ggr.webp"
```
^statblock