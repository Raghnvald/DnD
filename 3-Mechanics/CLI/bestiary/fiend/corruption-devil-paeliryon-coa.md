---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Corruption Devil (Paeliryon)"
---
# [Corruption Devil (Paeliryon)](3-Mechanics/CLI/bestiary/fiend/corruption-devil-paeliryon-coa.md)
*Source: Chains of Asmodeus p. 239*  

One of the stronger greater devils, the paeliryon focus on corruption and obtaining mortal souls. While they can be found on almost every layer of the Nine Hells, paeliryons are particularly prominent in Dis and Malbolge, where they hold positions of power. Their duties include managing lesser devils, directing and manipulating the soul trade, and infernal politics. They're particularly talented at blackmailing and spying—abilities used both within and without the Nine Hells.

## Imposing Devils

As greater devils, paeliryons are particularly large, often weighing more than 4000 pounds. Like hags, their skin is covered in boils and warts of varying colors, and they have massive bellies and leathery wings. Despite their physical drawbacks, corruption devils are quite formidable in combat. Rather than fight themselves, however, they use followers and lesser devils as fodder.

## Sire of Corruption

Occasionally a paeliryon becomes more powerful than their sisters and takes on the mantle of a sire of corruption. These sires can be counted among the strongest infernals, aside from archdevils, and usually direct their power to other planes of existence. Befitting their name, sires of corruption only seek one goal: to corrupt. To this end, their plans often involve the decay of empires or corruption of religious groups. Sires are few and far between, and a new sire usually rises only once every few centuries. Though they usually operate alone, some sires have served archdevils whose plans involved enough corruption to encourage cooperation.

```statblock
"name": "Corruption Devil (Paeliryon) (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "218"
"hit_dice": "19d10 + 114"
"modifier": !!int "2"
"stats":
  - !!int "21"
  - !!int "14"
  - !!int "22"
  - !!int "19"
  - !!int "15"
  - !!int "14"
"speed": "20 ft., burrow 20 ft., fly 60 ft. (hover)"
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "Deception"
    "desc": "+7"
  - "name": "Insight"
    "desc": "+7"
  - "name": "Intimidation"
    "desc": "+7"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned, stunned"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 12"
"languages": "all, telepathy 120 ft."
"cr": "14"
"traits":
  - "desc": "Magical darkness doesn't impede the paeliryon's darkvision."
    "name": "Devil's Sight"
  - "desc": "The paeliryon scores a critical hit on a roll of 19 or 20."
    "name": "Keen Eyes"
  - "desc": "The paeliryon has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The paeliryon makes three Claw attacks. It can replace one of the attacks\
      \ with Draining Grasp (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 16 (2d10 + 5) slashing damage plus 10 (3d6) fire damage."
    "name": "Claw"
  - "desc": "The paeliryon makes a Claw attack. On a hit, the target's Charisma score\
      \ is reduced by 2 (1d4). This reduction lasts until the target finishes a\
      \ short or long rest. A creature whose Charisma is reduced to 3 or less because\
      \ of this ability, has the stunned condition for 1 minute."
    "name": "Draining Grasp (Recharge 4-6)"
  - "desc": "The paeliryon casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 17):\n\n**At will:** Bestow Curse, Command, Darkness, Hold Monster, Major\
      \ Image\n\n**1/day each:** Antilife Shell, Incendiary Cloud, Scrying, Weird"
    "name": "Spellcasting"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/corruption-devil-paeliryon-coa.webp"
```
^statblock