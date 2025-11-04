---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/11
  - Monster/Größe/Riesig
  - Monster/Typ/Monstrosität
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Necrotic Centipede
---
# [Necrotic Centipede](3-Mechanics\CLI\bestiary\monstrosity/necrotic-centipede-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 119*  

```statblock
"name": "Necrotic Centipede (BGDIA)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"modifier": !!int "1"
"stats":
  - !!int "24"
  - !!int "13"
  - !!int "21"
  - !!int "4"
  - !!int "10"
  - !!int "5"
"speed": "30 ft., burrow 20 ft."
"damage_immunities": "necrotic, fire"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., tremorsense\
  \ 60 ft., passive Perception 10"
"languages": ""
"cr": "11"
"traits":
  - "desc": "A creature that touches the centipede or hits it with a melee attack\
      \ while within 5 feet of it takes 10 (3d6) necrotic damage."
    "name": "Necrotic Body"
"actions":
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 40\
      \ (6d10 + 7) piercing damage plus 10 (3d6) necrotic damage. If the target is\
      \ a creature, it is [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape\
      \ DC 17). Until this grapple ends, the target is [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
      \ and the centipede can't bite another target."
    "name": "Bite"
  - "desc": "The centipede makes one bite attack against a Medium or smaller creature\
      \ it is grappling. If the attack hits, that creature takes the bite's damage\
      \ and is swallowed, and the grapple ends. While swallowed, the creature is [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the centipede, and it takes\
      \ 21 (6d6) acid damage at the start of each of the centipede's turns.\n\nIf\
      \ the centipede takes 30 damage or more on a single turn from a creature inside\
      \ it, the centipede must succeed on a DC 15 Constitution saving throw at the\
      \ end of that turn or regurgitate all swallowed creatures, which fall [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ in a space within 10 feet of the centipede. If the centipede dies, a swallowed\
      \ creature is no longer [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 15 feet of movement, exiting [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Swallow"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/necrotic-centipede-bgdia.webp"
```
^statblock