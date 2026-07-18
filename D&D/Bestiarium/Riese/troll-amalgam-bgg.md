---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Troll Amalgam
Status: WIP
linter-yaml-title-alias: Troll Amalgam
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/17
  - Monster/Typ/Riese
  - Quelle/5e/bgg
aliases:
  - Troll Amalgam
---
# [Troll Amalgam](3-Mechanics\CLI\bestiary\giant/troll-amalgam-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 186*  

A troll amalgam forms when multiple trolls fuse together during regeneration. This sometimes occurs when many trolls are slain in a single battle, when troll parts are thrown into charnel pits or mass graves, or through twisted rituals of wicked spellcasters. Sometimes troll worshipers of Vaprak hear a call to gather in the Underdark and perform a gruesome rite that fuses them into an amalgam that is regarded as an avatar of their fearsome god.

A troll amalgam is a misshapen mass of rubbery flesh, claws, and faces. If a creature tries to attack it from beyond its reach or to escape through a small tunnel, the troll amalgam tears off a piece of its own body and hurls it at the creature. These body parts eventually regenerate into full trolls, and sometimes they regather and combine into a new troll amalgam.

## Trolls

The dwarven tale titled *The Saga of Gnarldan Steelshield* claims the god Vaprak the Destroyer came into being when Annam was injured and his blood spilled on the ground. The saga further claims that trolls were born similarly when Vaprak's blood was spilled. Whatever the truth of their origin, trolls embody life's steadfast determination to grow and thrive despite all obstacles.

Trolls' rapid healing makes them subject to bizarre mutations, particularly when they regenerate in unusual environments or heal from extraordinary magical wounds. Troll amalgams and troll mutates are two examples of such strangely mutated forms.

> [!quote] A quote from Bigby  
> 
> I'll just keep reminding myself that the gods delight in the variety of their creations, new wonders are revealed every day, and the multiverse is much larger than I can imagine. And that's a good thing!

> [!quote] A quote from Diancastra  
> 
> Excellent. But these trolls are loathsome.

```statblock
"name": "Troll Amalgam (BGG)"
"size": "Gargantuan"
"type": "giant"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "217"
"hit_dice": "14d20 + 70"
"modifier": !!int "2"
"stats":
  - !!int "25"
  - !!int "14"
  - !!int "21"
  - !!int "9"
  - !!int "16"
  - !!int "5"
"speed": "60 ft., climb 60 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 19"
"languages": "Giant, Undercommon"
"cr": "17"
"traits":
  - "desc": "If the amalgam fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The amalgam has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The amalgam regains 15 hit points at the start of its turn. If the amalgam\
      \ takes acid or fire damage, it regains only 5 hit points at the start of its\
      \ next turn. The amalgam dies only if it takes 20 or more acid or fire damage\
      \ while it has 0 hit points."
    "name": "Regeneration"
"actions":
  - "desc": "The amalgam makes three Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:* 25\
      \ (4d8 + 7) slashing damage."
    "name": "Rend"
"bonus_actions":
  - "desc": "*Ranged Weapon Attack:* +13 to hit, range 60/240 ft., one target. *Hit:*\
      \ 11 (1d8 + 7) bludgeoning damage. If the limb hits a Medium or smaller creature,\
      \ that creature has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ condition (escape DC 17). The limb has the statistics of a troll amalgam,\
      \ except for the following: it is Medium, it has 45 hit points, its speed is\
      \ 30 ft., it doesn't have a challenge rating or Legendary Resistance, and the\
      \ only action it can take is the Attack action, which it can use only to grapple.\n\
      \nUntil this grapple ends, the target has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition and takes 25 (4d8 + 7) slashing damage at the start of each of its\
      \ turns. If the limb is not destroyed within 24 hours of being flung, roll a\
      \ d12; on a roll of 12, the limb regenerates into a troll (see the Monster Manual).\
      \ Otherwise, the limb withers away."
    "name": "Fling Limb (3/Day)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/troll-amalgam-bgg.webp"
```
^statblock