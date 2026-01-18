---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/vgm
  - Monster/HG/1-2
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Swarm of Rot Grubs
---
# [Swarm of Rot Grubs](3-Mechanics\CLI\bestiary\beast/swarm-of-rot-grubs-vgm.md)
*Source: Volo's Guide to Monsters p. 208, Ghosts of Saltmarsh*  

Rot grubs are finger-sized maggots that eat living or dead flesh, although they can survive on plant matter. They infest corpses and piles of decaying matter and attack living creatures that disturb them. After burrowing into the flesh of a living creature, a rot grub instinctively chews its way toward the heart in order to kill its host.

Rot grubs pose a threat both singly and as a swarm. See the accompanying stat block for the mechanics of a swarm of rot grubs. A single rot grub has no stat block. Any creature that comes into contact with it must make a DC 10 Dexterity saving throw. On a failed save, the rot grub burrows into the creature's flesh and deals `dice:1d6|noform|noparens|avg|text(3)` (`1d6`) piercing damage at the start of each of the host creature's turns. Applying fire to the wound before the end of the host creature's next turn deals 1 fire damage to the host and kills the infesting rot grub. After this time, the rot grub is too far under the host creature's skin to be burned. If a creature infested by one or more rot grubs ends its turn with 0 hit points, it dies as the grubs burrow into its heart and kill it. Any effect that cures disease kills all rot grubs infesting the target. Burning a body kills any rot grubs infesting it.

```statblock
"name": "Swarm of Rot Grubs (VGM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "-2"
"stats":
  - !!int "2"
  - !!int "7"
  - !!int "10"
  - !!int "1"
  - !!int "2"
  - !!int "1"
"speed": "5 ft., climb 5 ft."
"damage_resistances": "piercing, slashing"
"condition_immunities": "charmed, frightened, grappled, paralyzed, petrified, prone,\
  \ restrained"
"senses": "blindsight 10 ft., passive Perception 6"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny maggot. The swarm\
      \ can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Weapon Attack:* +0 to hit, reach 0 ft., one creature in the swarm's\
      \ space. *Hit:* The target is infested by 1d4 rot grubs. At the start of each\
      \ of the target's turns, the target takes 1d6 piercing damage per rot grub infesting\
      \ it. Applying fire to the bite wound before the end of the target's next turn\
      \ deals 1 fire damage to the target and kills these rot grubs. After this time,\
      \ these rot grubs are too far under the skin to be burned. If a target infested\
      \ by rot grubs ends its turn with 0 hit points, it dies as the rot grubs burrow\
      \ into its heart and kill it. Any effect that cures disease kills all rot grubs\
      \ infesting the target."
    "name": "Bites"
"source":
  - "VGM"
  - "GoS"
"image": "/3-Mechanics/CLI/bestiary/beast/token/swarm-of-rot-grubs-vgm.webp"
```
^statblock

## Environment

underdark, swamp