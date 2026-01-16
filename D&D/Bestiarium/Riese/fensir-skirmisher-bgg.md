---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- Fensir Skirmisher
---
# [Fensir Skirmisher](3-Mechanics\CLI\bestiary\giant/fensir-skirmisher-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 135*  

Fensir skirmishers boast great skill in battle, honed over centuries of endless conflict on the battlefields of Ysgard. They also wield elemental magic of earth and stone. True to their giant heritage, they can transform even a pinch of mud or gravel into a boulder suitable for hurling, and the thrown stone grows in flight to knock its target flat on impact.

## Fensirs

Long ago, a band of frost giants led trolls in a campaign to win Annam's favor by conquering the outer plane of Ysgard. The campaign's aspirations of conquest quickly failed, but the raiders discovered a key feature of Ysgard: creatures slain on that plane return to life the next dawn. Thus, the giants' incursion became a part of the eternal battle that rages across the plane. The trolls, whose fundamental nature was altered by constant regeneration and rebirth amid the energy of Ysgard, slowly changed into entirely new creatures: fensirs.

Fensirs' troll ancestry is hardly apparent in their appearance. They retain prominent noses and a hint of green in their skin but otherwise resemble relatively small frost or stone giants. They use armor and weapons similar to what other combatants on Ysgard use in the eternal battle.

The transformation that created fensirs left them with an odd quirk to their regenerative powers: their regeneration doesn't function in sunlight, and in fact, sunlight can turn these creatures to stone.

> [!quote] A quote from Bigby  
> 
> Bringing trolls to a place where nothing ever truly dies seems like a transparently bad idea. What were those giants thinking?

> [!quote] A quote from Diancastra  
> 
> And yet, can we fairly say that the existence of fensirs is "transparently bad"? Some might argue they are a significant improvement over trolls. At the very least, the diversity of life in the multiverse increased, and new wonders were revealed. That's only bad if you think a small universe that fits within your narrow understanding is good.


```statblock
"name": "Fensir Skirmisher (BGG)"
"size": "Large"
"type": "giant"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "94"
"hit_dice": "9d10 + 45"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "20"
  - !!int "14"
  - !!int "11"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 16"
"languages": "Common, Giant"
"cr": "6"
"traits":
  - "desc": "The fensir regains 10 hit points at the start of its turn if it isn't\
      \ in sunlight. If the fensir takes acid or fire damage, this trait doesn't function\
      \ at the start of the fensir's next turn. The fensir dies only if it starts\
      \ its turn with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
  - "desc": "When the fensir starts its turn in sunlight, it must succeed on a DC\
      \ 15 Constitution saving throw or have the [petrified](/3-Mechanics/CLI/conditions.md#Petrified)\
      \ condition until the fensir is no longer in sunlight."
    "name": "Sunlight Hypersensitivity"
"actions":
  - "desc": "The fensir makes three Battleaxe attacks or two Magic Stone attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) slashing damage, or 15 (2d10 + 4) slashing damage if used with two\
      \ hands."
    "name": "Battleaxe"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 60 ft., one target. *Hit:* 15\
      \ (2d12 + 2) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 13 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Magic Stone"
  - "desc": "The fensir lobs a magical mass of mud that splashes all creatures in\
      \ a 30-foot-radius sphere centered on a point the fensir can see within 60 feet\
      \ of itself. Each non-fensir creature in that area must succeed on a DC 13 Dexterity\
      \ saving throw or take 13 (3d8) bludgeoning damage and have the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition as the mud begins to turn to stone. An affected creature must repeat\
      \ the saving throw at the end of its next turn. On a successful save, the effect\
      \ ends on the creature. On a failed save, the creature has the [petrified](/3-Mechanics/CLI/conditions.md#Petrified)\
      \ condition for 24 hours."
    "name": "Mud to Stone (Recharge 6)"
  - "desc": "The fensir casts one of the following spells, using Intelligence as the\
      \ spellcasting ability:\n\n**1/day each:** [create or destroy water](/3-Mechanics/CLI/spells/create-or-destroy-water-xphb.md),\
      \ [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [pass without\
      \ trace](/3-Mechanics/CLI/spells/pass-without-trace-xphb.md)"
    "name": "Spellcasting"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/fensir-skirmisher-bgg.webp"
```
^statblock