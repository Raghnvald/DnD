---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Malformed Kraken
Status: WIP
linter-yaml-title-alias: Malformed Kraken
tags:
  - Monster/Größe/Riesig
  - Monster/HG/10
  - Monster/Typ/Monstrosität
  - Quelle/5e/tftyp
aliases:
  - Malformed Kraken
---
# [Malformed Kraken](3-Mechanics\CLI\bestiary\monstrosity/malformed-kraken-tftyp.md)
*Source: Tales from the Yawning Portal p. 239*  

The Doomvault (Dead in Thay) contains a number of denizens that don't have all the traits or abilities of normal creatures of their kind. By far the most powerful of these "inferior" creatures is a malformed kraken that is kept in a saltwater pool and is not as large or as durable as a true kraken

```statblock
"name": "Malformed Kraken (TftYP)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "11"
  - !!int "20"
  - !!int "11"
  - !!int "15"
  - !!int "15"
"speed": "20 ft., swim 40 ft."
"saves":
  - "strength": !!int "11"
  - "constitution": !!int "9"
  - "intelligence": !!int "4"
  - "wisdom": !!int "6"
  - "charisma": !!int "6"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning"
"condition_immunities": "frightened, paralyzed"
"senses": "truesight 60 ft., passive Perception 12"
"languages": "understands Common but can't speak, telepathy 60 ft."
"cr": "10"
"traits":
  - "desc": "The kraken can breathe air and water."
    "name": "Amphibious"
  - "desc": "The kraken deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The kraken makes three tentacle attacks. One of them can be replaced\
      \ with a bite attack, and any of them can be replaced with Fling."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (2d8 + 7) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 20 ft., one target. *Hit:* 14\
      \ (2d6 + 7) bludgeoning damage, and the target is grappled (escape DC 16). Until\
      \ this grapple ends, the target is restrained. The kraken has ten tentacles,\
      \ each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Medium or smaller object held or creature grappled by the kraken's\
      \ tentacles is thrown up to 60 feet in a random direction and knocked prone.\
      \ If a thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning\
      \ damage for every 10 feet it was thrown. If the target is thrown at another\
      \ creature, that creature must succeed on a DC 16 Dexterity saving throw or\
      \ take the same damage and be knocked prone."
    "name": "Fling"
  - "desc": "The kraken creates three bolts of lightning, each of which can strike\
      \ a target the kraken can see within 150 feet of it. A target must make a DC\
      \ 16 Dexterity saving throw, taking 16 (3d10) lightning damage on a failed save,\
      \ or half as much damage on a successful one."
    "name": "Lightning Storm"
"source":
  - "TftYP"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/malformed-kraken-tftyp.webp"
```
^statblock