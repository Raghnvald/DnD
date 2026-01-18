---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/egw
  - Monster/HG/17
  - Monster/Größe/Gigantisch
  - Monster/Typ/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Frost Worm
---
# [Frost Worm](3-Mechanics\CLI\bestiary\monstrosity/frost-worm-egw.md)
*Source: Explorer's Guide to Wildemount p. 289*  

Frost worms burrow through the snow, dirt, ice, and rock of Wildemount's Biting North. These enormous monstrosities eagerly consume any living creature they can wrap their jaws around.

A frost worm spends most of its time beneath the frozen ground, conserving energy while it waits for prey to pass overhead. Smart travelers can identify a frost worm's hunting grounds by looking for recently iced-over tunnels. When the worm senses vibrations above, it bursts forth through dirt, ice, and snow. Those who escape its initial assault must still contend with the worm's haunting trill—a hypnotizing call that stops creatures in their tracks to make them easy prey.

```statblock
"name": "Frost Worm (EGW)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "264"
"hit_dice": "16d20 + 96"
"modifier": !!int "-1"
"stats":
  - !!int "28"
  - !!int "8"
  - !!int "22"
  - !!int "1"
  - !!int "5"
  - !!int "5"
"speed": "40 ft., burrow 30 ft."
"saves":
  - "constitution": !!int "12"
  - "wisdom": !!int "3"
"damage_vulnerabilities": "fire"
"damage_immunities": "cold"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., tremorsense\
  \ 60 ft., passive Perception 7"
"languages": ""
"cr": "17"
"traits":
  - "desc": "A creature that touches the worm or hits it with a melee attack while\
      \ within 5 feet of it takes 10 (3d6) cold damage."
    "name": "Freezing Body"
  - "desc": "When the worm dies, it explodes in a burst of frigid energy. Each creature\
      \ within 60 feet of it must make a DC 20 Dexterity saving throw, taking 28 (8d6)\
      \ cold damage on a failed save, or half as much damage on a successful one.\
      \ Creatures inside the worm when it dies automatically fail this saving throw."
    "name": "Death Burst"
  - "desc": "The worm can burrow through solid rock at half its burrowing speed and\
      \ leaves a 10-foot-diameter tunnel in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The worm makes two bite attacks, or uses its Trill and makes a bite attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:* 22\
      \ (3d8 + 9) piercing damage plus 10 (3d6) cold damage. If the target is a Large\
      \ or smaller creature, it must succeed on a DC 20 Dexterity saving throw or\
      \ be swallowed by the worm. A swallowed creature is [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained), has total cover\
      \ against attacks and other effects outside the worm, and takes 10 (3d6) acid\
      \ damage and 10 (3d6) cold damage at the start of each of the worm's turns.\n\
      \nIf the worm takes 30 damage or more on a single turn from a creature inside\
      \ it, the worm must succeed on a DC 20 Constitution saving throw at the end\
      \ of that turn or regurgitate all swallowed creatures, which fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ in a space within 10 feet of the worm."
    "name": "Bite"
  - "desc": "The frost worm emits a haunting cry. Each creature within 60 feet of\
      \ the worm that can hear it must succeed on a DC 20 Wisdom saving throw or be\
      \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned) for 1 minute. A creature\
      \ can repeat the saving throw each time it takes damage and at the end of each\
      \ of its turns, ending the effect on itself on a success. Once a creature successfully\
      \ saves against this effect, or if this effect ends for it, that creature is\
      \ immune to the Trill of all frost worms for the next 24 hours. Frost worms\
      \ are immune to this effect."
    "name": "Trill"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/frost-worm-egw.webp"
```
^statblock