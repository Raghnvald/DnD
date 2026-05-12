---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shredwing"
---
# [Shredwing](3-Mechanics/CLI/bestiary/fiend/shredwing-coa.md)
*Source: Chains of Asmodeus p. 250*  

Tearing through the skies of the Nine Hells, shredwings aren't only a constant menace to mortal and fiendish travelers, but a reminder of the cruelties of one of Hell's worst overlords. Though Malagard was cast down from the throne of Malbolge and her bloated body shattered, her wickedness remains in the spite and cruelty of her creations.

## Born from Bitterness

At first glance, shredwings appear to be bats or pterodactyls, with a spined body between two great veined wings terminating in a jagged head. They seem to have an ever-open beak, but upon closer scrutiny this shows to be a pair of vicious spikes. Although they seem like horrific flying creatures, the actual truth of their origins makes them even more terrible. Malagard was earthbound and one of the many things she was furiously envious of was the ability of others to fly. One of her pastimes was to tear the wings from Fiends who had displeased her and give them a vile and unnatural life of their own, discarding the mutilated devils and shaping their amputated parts into something new and ghastly. Shredwings are the results of her hobby, now feral and endemic to many parts of the Nine Hells.

## Hideous Appetites

Shredwings are driven by a desire to inflict pain, still possessed by the malice of their original creator. They patrol the skies of the Nine Hells and descend in shrieking flocks on anything weak enough to torment. When they have winged creatures at their mercy, they mob their victim in the air until they can tear away their target's wings. They carry the trophies to their high roosts, where the tattered vanes are transformed into a new shredwing under the caustic ministrations of the 'parents'. For wingless prey, they have other practices. Whilst they harry with claws and beak, they look out for a chance to latch onto the backs of their prey. Driving the spikes of their heads between the shoulders of their victims they enact a terrible merging, becoming a set of wings attached to the creature and carrying them off. They slowly absorb the life-force of their victim, delighting in their pain and fear. Over time they take over their prey's limbs and body, returning to attack any leftover companions, delighting in the distress their puppeteering causes. Most often they leave the head until last, enjoying the screams and pleas of the luckless creature they've usurped.

## Raised to the Whip

There is little bad in the Nine Hells that devils can't make worse. Shredwings are unruly and vicious creatures but determined devils can trap them and break them into a form of domestication. Particularly ingenious hunting Fiends, aided by the souls of evil rangers, have trained packs of shredwings to do their bidding, tracking prey across the hostile plains of the Nine Hells and attacking on command. The creatures remain mutinous at best, and woe betide any handler who shows weakness or lets prey get the better of them.

```statblock
"name": "Shredwing (CoA)"
"size": "Medium"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "170"
"hit_dice": "20d8 + 80"
"modifier": !!int "4"
"stats":
  - !!int "11"
  - !!int "19"
  - !!int "19"
  - !!int "15"
  - !!int "16"
  - !!int "11"
"speed": "0 ft., fly 60 ft. (hover)"
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "8"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+8"
  - "name": "Athletics"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+11"
  - "name": "Survival"
    "desc": "+7"
"damage_resistances": "cold; fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"condition_immunities": "blinded, charmed, poisoned"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": ""
"cr": "12"
"traits":
  - "desc": "After using the Burrow ability, if the shredwing is merged with another\
      \ creature, any damage dealt to the shredwing is split evenly between it and\
      \ the merged creature."
    "name": "Merged"
"actions":
  - "desc": "The shredwing makes three Talon attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage plus 7 (2d6) poison damage."
    "name": "Talon"
  - "desc": "On a hit, the creature takes an additional 32 (5d12) slashing damage\
      \ as the wings merge with it. While merged, the creature moves with the shredwing,\
      \ takes 19 (3d12) necrotic damage at the start of each of its turn, and has\
      \ the grappled condition. The shredwing can unmerge at any time, leaving the\
      \ creature and dropping it if airborne. The only other way to end the merge\
      \ is to kill the shredwing.\n\nIf the merged creature dies while merged, the\
      \ shredwing permanently takes over its body. It gains the merged creature's\
      \ hit dice, natural armor, possessions, and languages. If any of the merged\
      \ creature's statistics are higher than the shredwing, it inherits those statistics\
      \ as well. A creature permanently merged by the shredwing can only be resurrected\
      \ through a Wish spell or similar."
    "name": "Burrow (Recharge 5-6)"
"bonus_actions":
  - "desc": "The shredwing can move up to its speed toward a hostile creature that\
      \ it can see."
    "name": "Aggressive"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/shredwing-coa.webp"
```
^statblock