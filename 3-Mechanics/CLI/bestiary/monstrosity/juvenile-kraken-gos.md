---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/gos
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Juvenile Kraken"
---
# [Juvenile Kraken](3-Mechanics/CLI/bestiary/monstrosity/juvenile-kraken-gos.md)
*Source: Ghosts of Saltmarsh p. 238*  

Hidden in a deep, dark underwater pit near the Styes, this creature bears the mark of the dark god Tharizdun's madness. Becoming more independent every day, it dreams of freeing itself from its aboleth tenders and wreaking its own foul will upon the seas.

```statblock
"name": "Juvenile Kraken (GoS)"
"size": "Huge"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"modifier": !!int "0"
"stats":
  - !!int "24"
  - !!int "11"
  - !!int "20"
  - !!int "19"
  - !!int "15"
  - !!int "17"
"speed": "20 ft., swim 50 ft."
"saves":
  - "strength": !!int "12"
  - "dexterity": !!int "5"
  - "constitution": !!int "10"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning"
"condition_immunities": "frightened, paralyzed"
"senses": "truesight 120 ft., passive Perception 12"
"languages": "Abyssal, Celestial, Infernal, Primordial, telepathy 60 ft. but can't\
  \ speak"
"cr": "14"
"traits":
  - "desc": "The kraken can breathe air and water."
    "name": "Amphibious"
  - "desc": "The kraken ignores difficult terrain, and magical effects can't reduce\
      \ its speed or cause it to be restrained. It can spend 5 feet of movement to\
      \ escape from nonmagical restraints or being grappled."
    "name": "Freedom of Movement"
"actions":
  - "desc": "The kraken makes two tentacle attacks, each of which it can replace with\
      \ a use of Fling."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 20 (3d8 + 7) piercing damage. If the target is a Medium or smaller creature\
      \ grappled by the kraken, that creature is swallowed and the grapple ends. While\
      \ swallowed, the creature is blinded and restrained, it has total cover against\
      \ attacks and other effects outside the kraken, and it takes 21 (6d6) acid\
      \ damage at the start of each of the kraken's turns. One Medium or two smaller\
      \ creatures can be swallowed at the same time.\n\nIf the kraken takes 35 damage\
      \ or more on a single turn from a creature inside it, the kraken must succeed\
      \ on a DC 23 Constitution saving throw at the end of that turn or regurgitate\
      \ all swallowed creatures, which fall prone in spaces within 10 feet of the\
      \ kraken. If the kraken dies, a swallowed creature is no longer restrained by\
      \ it and can escape from the corpse using 10 feet of movement, exiting prone."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 20 ft., one target. *Hit:*\
      \ 17 (3d6 + 7) bludgeoning damage, and the target is grappled (escape DC 20).\
      \ Until the grapple ends, the target is restrained. The kraken has ten tentacles,\
      \ each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Medium or smaller object held or creature grappled by the kraken\
      \ is thrown up to 40 feet in a random direction and knocked prone. If a thrown\
      \ target strikes a solid surface, the target takes 3 (1d6) bludgeoning damage\
      \ for every 10 feet it was thrown. If the target is thrown at another creature,\
      \ that creature must succeed on a DC 13 Dexterity saving throw or take the same\
      \ damage and be knocked prone."
    "name": "Fling"
  - "desc": "The kraken magically create a bolt of lightning, which can strike a target\
      \ the kraken can see within 90 feet of it. The target must make a DC 18 Dexterity\
      \ saving throw, taking 22 (4d10) lightning damage on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Lightning Strike"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the juvenile kraken can expend a use to take one of the following actions.\
  \ The juvenile kraken regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The kraken makes one tentacle attack."
    "name": "Tentacle Attack (Costs 2 Actions)"
  - "desc": "The kraken uses Fling."
    "name": "Fling"
  - "desc": "While underwater, the kraken expels an ink cloud in a 40-foot radius.\
      \ The cloud spreads around corners, and that area is heavily obscured to creatures\
      \ other than the kraken. Each creature other than the kraken that ends its turn\
      \ there must succeed on a DC 18 Constitution saving throw, taking 11 (2d10)\
      \ poison damage on a failed save or half as much damage on a successful one.\
      \ A strong current disperses the cloud, which otherwise disappears at the end\
      \ of the kraken's next turn."
    "name": "Ink Cloud (Costs 3 Actions)"
"source":
  - "GoS"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/juvenile-kraken-gos.webp"
```
^statblock