---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Slarkrethel
Status: WIP
linter-yaml-title-alias: Slarkrethel
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/25
  - Monster/Typ/Monstrosität/titan
  - Quelle/5e/skt
aliases:
  - Slarkrethel
---
# [Slarkrethel](3-Mechanics\CLI\bestiary\npc/slarkrethel-skt.md)
*Source: Storm King's Thunder p. 224*  

Beneath the waves, the kraken sleeps for untold ages, awaiting some fell sign or calling. Land-born mortals who sail the open sea forget the reasons their ancestors dreaded the ocean, even as the races of the deep ignore strange gaps in their histories when their civilizations nearly vanished after the appearance of the tentacled horror.

## Leviathans of Legend

At the beginning of time, krakens served as fierce warriors of the gods. When the gods' wars ended, the krakens shrugged free of their servitude, never again to be bound by other beings. Whole nations quake in fear when the kraken emerges from its dark demesne, and even in the middle of the deepest oceans, storms rise or abate according to its will. The kraken is a primeval force that obliterates the greatest achievements of civilization as if they were castles in the sand. Its devastating attacks can destroy ocean trade and halt communication between coastal cities.

An ominous darkness presages a kraken's attack, and a cloud of inky poison colors the water around it. Galleons and warships vanish when its tentacles uncoil from the deep, the kraken breaking their masts like kindling before drawing down ships and crew. Not even landlocked surface dwellers are safe from a kraken's wrath. Krakens can breathe air as easily as water, and some crawl up rivers to nest in freshwater lakes, destroying cities and towns along the way. Adventurers tell of these monsters lairing in the ruins of lakeside citadels, their tentacles twined around leaning towers of disintegrating stone.

## Mortal Foes

Some krakens are virtual gods, with cults and minions spread across sea and land. Others are allied with Olhydra, the evil Princess of Elemental Water, and use her cultists to enforce their will on land and sea. A kraken pleased with its worshipers can becalm rough seas and bring a bounteous harvest of fish to the faithful. However, the devious mind of a kraken is ancient beyond reckoning, and is ultimately bent to the ruination of all things.

## A Kraken's Lair

A kraken lives in dark depths, usually a sunken rift or a cavern filled with detritus, treasure, and wrecked ships.

```statblock
"name": "Slarkrethel (SKT)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "472"
"hit_dice": "27d20 + 189"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "11"
  - !!int "25"
  - !!int "22"
  - !!int "18"
  - !!int "20"
"speed": "20 ft., swim 60 ft."
"saves":
  - "strength": !!int "18"
  - "dexterity": !!int "8"
  - "constitution": !!int "15"
  - "intelligence": !!int "14"
  - "wisdom": !!int "12"
"damage_immunities": "lightning; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "frightened, paralyzed"
"senses": "truesight 120 ft., passive Perception 14"
"languages": "understands Abyssal, Celestial, Infernal, and Primordial but can't speak,\
  \ telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "If Slarkrethel fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Slarkrethel can breathe air and water."
    "name": "Amphibious"
  - "desc": "Slarkrethel ignores difficult terrain, and magical effects can't reduce\
      \ its speed or cause it to be restrained. It can spend 5 feet of movement to\
      \ escape from nonmagical restraints or being grappled."
    "name": "Freedom of Movement"
  - "desc": "Slarkrethel deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "Slarkrethel makes three tentacle attacks, each of which it can replace\
      \ with one use of Fling."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 5 ft., one target. *Hit:* 23\
      \ (3d8 + 10) piercing damage. If the target is a Large or smaller creature grappled\
      \ by Slarkrethel, that creature is swallowed, and the grapple ends. While swallowed,\
      \ the creature is blinded and restrained, it has total cover against attacks\
      \ and other effects outside Slarkrethel, and it takes 42 (12d6) acid damage\
      \ at the start of each of Slarkrethel's turns. If Slarkrethel takes 50 damage\
      \ or more on a single turn from a creature inside it, Slarkrethel must succeed\
      \ on a DC 25 Constitution saving throw at the end of that turn or regurgitate\
      \ all swallowed creatures, which fall prone in a space within 10 feet of Slarkrethel.\
      \ If Slarkrethel dies, a swallowed creature is no longer restrained by it and\
      \ can escape from the corpse using 15 feet of movement, exiting prone."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 30 ft., one target. *Hit:* 20\
      \ (3d6 + 10) bludgeoning damage, and the target is grappled (escape DC 18).\
      \ Until this grapple ends, the target is restrained. Slarkrethel has ten tentacles,\
      \ each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Large or smaller object held or creature grappled by Slarkrethel\
      \ is thrown up to 60 feet in a random direction and knocked prone. If a thrown\
      \ target strikes a solid surface, the target takes 3 (1d6) bludgeoning damage\
      \ for every 10 feet it was thrown. If the target is thrown at another creature,\
      \ that creature must succeed on a DC 18 Dexterity saving throw or take the same\
      \ damage and be knocked prone."
    "name": "Fling"
  - "desc": "Slarkrethel magically creates three bolts of lightning, each of which\
      \ can strike a target Slarkrethel can see within 120 feet of it. A target must\
      \ make a DC 23 Dexterity saving throw, taking 22 (4d10) lightning damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Lightning Storm"
  - "desc": "Slarkrethel casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 22):\n\n\
      **At will:** detect magic, detect thoughts, sending\n\n**2/day each:** control\
      \ weather (cast as 1 action), fly, ice storm\n\n**1/day each:** arcane eye,\
      \ chain lightning, feeblemind, foresight, locate creature, mass suggestion,\
      \ nondetection, power word kill, scrying (cast as 1 action), sequester, telekinesis,\
      \ teleport"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Slarkrethel can expend a use to take one of the following actions. Slarkrethel\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Slarkrethel makes one tentacle attack or uses its Fling."
    "name": "Tentacle Attack or Fling"
  - "desc": "Slarkrethel uses Lightning Storm."
    "name": "Lightning Storm (Costs 2 Actions)"
  - "desc": "While underwater, Slarkrethel expels an ink cloud in a 60-foot radius.\
      \ The cloud spreads around corners, and that area is heavily obscured to creatures\
      \ other than Slarkrethel. Each creature other than Slarkrethel that ends its\
      \ turn there must succeed on a DC 23 Constitution saving throw, taking 16 (3d10)\
      \ poison damage on a failed save, or half as much damage on a successful one.\
      \ A strong current disperses the cloud, which otherwise disappears at the end\
      \ of Slarkrethel's next turn."
    "name": "Ink Cloud (Costs 3 Actions)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/npc/token/slarkrethel-skt.webp"
```
^statblock