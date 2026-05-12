---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Fire Kraken"
---
# [Fire Kraken](3-Mechanics/CLI/bestiary/elemental/fire-kraken-coa.md)
*Source: Chains of Asmodeus p. 120*  

```statblock
"name": "Fire Kraken (CoA)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "Chaotic Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "402"
"hit_dice": "23d20 + 161"
"modifier": !!int "0"
"stats":
  - !!int "27"
  - !!int "11"
  - !!int "24"
  - !!int "10"
  - !!int "20"
  - !!int "15"
"speed": "30 ft., swim 60 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "14"
"skillsaves":
  - "name": "Athletics"
    "desc": "+15"
  - "name": "Nature"
    "desc": "+7"
  - "name": "Survival"
    "desc": "+12"
"damage_immunities": "fire; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "frightened, paralyzed"
"senses": "blindsight 120 ft., passive Perception 15"
"languages": "understands Abyssal, Celestial, Infernal, and Primordial but can't speak,\
  \ telepathy 120 ft."
"cr": "21"
"traits":
  - "desc": "The kraken ignores difficult terrain, and magical effects can't reduce\
      \ its speed or cause it to be restrained. It can spend 5 feet of movement to\
      \ escape from nonmagical restraints or grapples."
    "name": "Freedom of Movement"
  - "desc": "If the kraken fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The kraken deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The kraken makes two attacks using its Tentacle, Fling, or a combination\
      \ of the two."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:*\
      \ 18 (3d6 + 8) piercing damage and 7 (2d6) fire damage. If the target is\
      \ a Large or smaller creature grappled by the kraken, the creature is swallowed\
      \ and the grapple ends. While swallowed, a creature has the blinded and restrained\
      \ conditions, has total cover against attacks and other effects outside the\
      \ kraken, and takes 42 (12d6) fire damage at the start of the kraken's turns.\
      \ If the kraken takes 50 damage or more on a single turn from a creature inside\
      \ it, it must succeed on a DC 23 Constitution saving throw or regurgitate all\
      \ swallowed creatures, which fall into a space within 10 feet of the kraken\
      \ and now have the prone condition. If the kraken dies, a swallowed creature\
      \ is no longer restrained by it and can escape from the corpse using 15 feet\
      \ of movement, exiting with the prone condition."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target. *Hit:*\
      \ 13 (2d4 + 8) fire damage. If the target is a Huge or smaller creature, it\
      \ has the grappled condition (escape DC 16). While grappled, the target also\
      \ has the restrained condition. Any target that starts its turn grappled by\
      \ the kraken takes 5 (2d4) fire damage. The kraken has five tentacles, each\
      \ of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Large or smaller object or creature grappled by the kraken is thrown\
      \ up to 60 feet in a random direction, and now has the prone condition. If a\
      \ thrown target strikes a solid surface, the target takes 3 (1d6) bludgeoning\
      \ damage for every 10 feet it was thrown. If the target is thrown at a creature,\
      \ that creature must succeed on a DC 16 Dexterity saving throw or take the same\
      \ damage and be knocked down with the prone condition."
    "name": "Fling"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the fire kraken can expend a use to take one of the following actions. The\
  \ fire kraken regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The kraken makes a Fling attack."
    "name": "Appendage"
  - "desc": "The kraken exhales fire in a 60-foot cone. Each creature in that area\
      \ must make a DC 20 Dexterity saving throw, taking 36 (8d8) fire damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/elemental/token/fire-kraken-coa.webp"
```
^statblock