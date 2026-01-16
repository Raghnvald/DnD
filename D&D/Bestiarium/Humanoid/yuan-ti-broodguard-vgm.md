---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/vgm
- new/monster/cr/2
- new/monster/environment/desert
- new/monster/environment/forest
- new/monster/environment/underdark
- new/monster/size/medium
- new/monster/type/humanoid/yuan-ti
statblock: inline
statblock-link: "#^statblock"
aliases:
- Yuan-ti Broodguard
---
# [Yuan-ti Broodguard](3-Mechanics\CLI\bestiary\humanoid/yuan-ti-broodguard-vgm.md)
*Source: Volo's Guide to Monsters p. 203, Tomb of Annihilation*  

Yuan-ti malisons who become priestly devotees of a particular god-be it Sseth, Dendar the Night Serpent, or Merrshaulk-often rise through the ranks to become spiritual leaders among the serpent folk. These priests perform sacrificial rites to appease their vile gods.

## Yuan-ti Broodguard

Broodguards are humanoids transformed by yuan-ti into simple-minded, scaly creatures that do their masters' bidding. The transformation process warps not only a subject's body but also its mind, making it instinctively obey any yuan-ti and filling it with a seething rage that rises at the sight of non-reptilian creatures.

Although broodguards have low intelligence, they are able to perform simple yet important tasks in the community, such as guarding eggs or patrolling for intruders. The yuan-ti refer to broodguards as "histachii," which means "egg-watchers."

### Human No More

Most broodguards are made from human prisoners forced to consume a magical brew that renders them helpless and unable to fight off the inevitable. A human transformed into a broodguard loses all semblance of who it once was, and even its human origin is barely discernible. A broodguard is hairless and emaciated, with yellow-green, scaly skin. It has beady, bloodshot eyes and a forked tongue, and smells faintly of rotting meat. Broodguards can speak but rarely do so, preferring to use snake-like hisses and guttural noises.

> [!note] Making a Broodguard
> 
> Yuan-ti create broodguards from captured humanoids. Each subject is fed a special potion that immediately renders it incapacitated and transforms it into a broodguard over the next `dice:1d6+6|noform|noparens|avg` (`1d6 + 6`) days. A subject forced to imbibe the brew can make a DC 15 Constitution saving throw; on a success, it takes `dice:4d6|noform|noparens|avg|text(14)` (`4d6`) poison damage and isn't otherwise affected.
> 
> A spell such as lesser restoration or remove curse can end the transformation process at any time before it runs its course. After the process is complete, only a wish spell can reverse the effect.
^making-a-broodguard

```statblock
"name": "Yuan-ti Broodguard (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "yuan-ti"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "14"
  - !!int "6"
  - !!int "11"
  - !!int "4"
"speed": "30 ft."
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "4"
  - "wisdom": !!int "2"
"skillsaves":
  - "name": "Perception"
    "desc": "+2"
"damage_immunities": "poison"
"condition_immunities": "poisoned"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Abyssal, Common, Draconic"
"cr": "2"
"traits":
  - "desc": "The broodguard has advantage on saving throws against being charmed,\
      \ and magic can't paralyze it."
    "name": "Mental Resistance"
  - "desc": "At the start of its turn, the broodguard can gain advantage on all melee\
      \ weapon attack rolls it makes during that turn, but attack rolls against it\
      \ have advantage until the start of its next turn."
    "name": "Reckless"
"actions":
  - "desc": "The broodguard makes three attacks: one with its bite and two with its\
      \ claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5 (1d6\
      \ + 2) slashing damage."
    "name": "Claws"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/yuan-ti-broodguard-vgm.webp"
```
^statblock

## Environment

underdark, forest, desert