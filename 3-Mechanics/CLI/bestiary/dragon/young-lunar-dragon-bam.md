---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Young Lunar Dragon"
---
# [Young Lunar Dragon](3-Mechanics/CLI/bestiary/dragon/young-lunar-dragon-bam.md)
*Source: Boo's Astral Menagerie p. 35*  

Lunar dragons (also known as moon dragons or phase dragons) are capricious, xenophobic creatures that make their lairs inside desolate moons by burrowing through the rock.

Before laying eggs, a female lunar dragon stocks her lair with food; she won't leave the lair again until the eggs hatch and the offspring are old enough to fend for themselves. Lunar dragon eggs have stony shells that are pale white to light gray in color. Lunar dragons are alabaster white when they hatch and gradually turn darker as they age. Ancient moon dragons are the color of slate.

Lunar dragons enjoy depriving other creatures of treasure more than acquiring the treasure themselves. Often found among the treasures in a lunar dragon's hoard are one or more spelljamming helms (see the *Astral Adventurer's Guide*) taken from vessels that dared to invade the dragon's territory.

A lunar dragon can become incorporeal, but not to the extent that it can pass through other creatures or solid objects. In this semi-incorporeal state, roughly half of the dragon's body has a dark, indistinctly spectral form.

```statblock
"name": "Young Lunar Dragon (BAM)"
"size": "Large"
"type": "dragon"
"alignment": "typically  Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "123"
"hit_dice": "13d10 + 52"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "12"
  - !!int "18"
  - !!int "8"
  - !!int "10"
  - !!int "13"
"speed": "40 ft., burrow 20 ft., fly 80 ft."
"saves":
  - "constitution": !!int "7"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+7"
"damage_immunities": "cold"
"senses": "darkvision 240 ft., passive Perception 16"
"languages": "Draconic"
"cr": "7"
"traits":
  - "desc": "The dragon can burrow through solid rock at half its burrowing speed\
      \ and leaves a 10-foot-diameter tunnel in its wake."
    "name": "Tunneler"
  - "desc": "The dragon doesn't require air."
    "name": "Unusual Nature"
"actions":
  - "desc": "The dragon makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 7 (1d6 + 4) piercing damage plus 3 (1d6) cold damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) slashing damage."
    "name": "Claw"
  - "desc": "The dragon exhales a blast of frost in a 30-foot cone. Each creature\
      \ in the cone must make a DC 15 Constitution saving throw. On a failed save,\
      \ the creature takes 27 (6d8) cold damage, and its speed is halved until the\
      \ end of its next turn. On a successful save, the creature takes half as much\
      \ damage, and its speed isn't reduced."
    "name": "Cold Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "The dragon becomes partially incorporeal for as long as it maintains\
      \ concentration on the effect (as if concentrating on a spell). While partially\
      \ incorporeal, the dragon has resistance to bludgeoning, piercing, and slashing\
      \ damage."
    "name": "Phase (2/Day)"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/dragon/token/young-lunar-dragon-bam.webp"
```
^statblock