---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Fensir Devourer"
---
# [Fensir Devourer](3-Mechanics/CLI/bestiary/celestial/fensir-devourer-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 135*  

Some fensirs undergo a transformation after living in Ysgard for at least a thousand years. They grow rapidly to a height of 25 feet, fueled by an insatiable hunger. These fensir devourers use their great size and strength to overwhelm foes. They can also issue a baleful curse in their final moments.

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
"name": "Fensir Devourer (BGG)"
"size": "Huge"
"type": "celestial"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "138"
"hit_dice": "12d12 + 60"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "21"
  - !!int "10"
  - !!int "14"
  - !!int "11"
"speed": "40 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+8"
  - "name": "Survival"
    "desc": "+8"
"senses": "darkvision 60 ft., passive Perception 18"
"languages": "Common, Giant"
"cr": "8"
"traits":
  - "desc": "When the fensir starts its turn with 0 hit points and doesn't regenerate,\
      \ it releases a curse on those around it. Each creature within 30 feet of the\
      \ fensir when it dies must succeed on a DC 13 Charisma saving throw or be cursed\
      \ for the next 24 hours.\n\nWhile cursed in this way, an affected creature gains\
      \ no benefit from finishing a short or long rest. At the end of every hour,\
      \ the creature must succeed on a DC 13 Charisma saving throw or take 11 (2d10)\
      \ psychic damage."
    "name": "Death Curse"
  - "desc": "The fensir regains 10 hit points at the start of its turn if it isn't\
      \ in sunlight. If the fensir takes acid or fire damage, this trait doesn't function\
      \ at the start of the fensir's next turn. The fensir dies only if it starts\
      \ its turn with 0 hit points and doesn't regenerate."
    "name": "Regeneration"
  - "desc": "When the fensir starts its turn in sunlight, it must succeed on a DC\
      \ 15 Constitution saving throw or have the petrified condition until the fensir\
      \ is no longer in sunlight."
    "name": "Sunlight Hypersensitivity"
"actions":
  - "desc": "The fensir makes two attacks, using Rend, Boulder, or a combination of\
      \ them."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 21 (3d10 + 5) slashing damage."
    "name": "Rend"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 60/240 ft., one target. *Hit:*\
      \ 18 (2d12 + 5) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it must succeed on a DC 16 Strength saving throw or have the prone condition.\
      \ After the fensir throws the boulder, roll a d6; on a roll of 4 or lower,\
      \ the fensir has no more boulders to throw."
    "name": "Boulder"
"source":
  - "BGG"
"image": "3-Mechanics/CLI/bestiary/celestial/token/fensir-devourer-bgg.webp"
```
^statblock