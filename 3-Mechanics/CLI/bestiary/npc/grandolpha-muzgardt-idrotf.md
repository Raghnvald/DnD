---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/idrotf
- new/monster/cr/2
- new/monster/size/medium
- new/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- Grandolpha Muzgardt
---
# [Grandolpha Muzgardt](3-Mechanics\CLI\bestiary\npc/grandolpha-muzgardt-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 176*  

Grandolpha Muzgardt, the grand dame of the Muzgardt duergar clan, has recently arrived at the fortress after being invited here by Xardorok. The Muzgardts are based in Gracklstugh, a duergar city in the Underdark. They mass-produce and distribute a filthy duergar ale made from mushrooms. Xardorok has been eager to take a fourth wife and has had his eye on Grandolpha Muzgardt for many years. He asked Grandolpha to his fortress to give her a gift—a pseudodragon made of chardalyn (a pseudo-pseudodragon, if you will)—and make her an offer she can't refuse. Once he conquers Icewind Dale, he wants the Muzgardts to control the ale trade throughout his sunless surface kingdom.

Grandolpha, for her part, is too canny and jaded to fall for Xardorok's blunt attempt at seduction. She has begun plotting with disenfranchised advisors and warriors in his ranks to overthrow him when the moment is right. Ironically, despite his paranoia, Xardorok is too blinded by his admiration for Grandolpha to foresee her treachery.

Before entering combat, Grandolpha casts stoneskin on herself. Once her guards come to her rescue, she withdraws from combat and uses her faerie fire spell to make enemies easier for her guards to hit. The chardalyn pseudodragon defends Grandolpha to the death.

```statblock
"name": "Grandolpha Muzgardt (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "9"
"hp": !!int "59"
"hit_dice": "7d8 + 28"
"modifier": !!int "-1"
"stats":
  - !!int "14"
  - !!int "9"
  - !!int "18"
  - !!int "13"
  - !!int "17"
  - !!int "16"
"speed": "25 ft."
"damage_resistances": "poison"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Common, Dwarvish, Undercommon"
"cr": "2"
"traits":
  - "desc": "Grandolpha's innate spellcasting ability is Wisdom (spell save DC 13).\
      \ She can innately cast the following spells, requiring no material components:\n\
      \n**At will:** druidcraft, mending, poison spray (see \"Actions\" below)\n\n\
      **3/day each:** detect magic, enlarge/reduce (self only), faerie fire, invisibility\
      \ (self only), polymorph, stoneskin (self only)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "Grandolpha has advantage on saving throws against poison, spells, and\
      \ illusions, as well as to resist being charmed or paralyzed."
    "name": "Duergar Resilience"
  - "desc": "While in sunlight, Grandolpha has disadvantage on attack rolls, as well\
      \ as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Grandolpha extends her hand toward a creature she can see within 10 feet\
      \ of her and projects a puff of noxious gas from her palm. The creature must\
      \ succeed on a DC 13 Constitution saving throw or take 13 (2d12) poison damage."
    "name": "Poison Spray (Cantrip)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/grandolpha-muzgardt-idrotf.webp"
```
^statblock