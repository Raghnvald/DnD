---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Psurlon Leader"
---
# [Psurlon Leader](3-Mechanics/CLI/bestiary/aberration/psurlon-leader-bam.md)
*Source: Boo's Astral Menagerie p. 45*  

One out of every hundred psurlons is a mutant with two heads, one at each end of its body, and a superior intellect. Other psurlons look to the two-headed ones for leadership.

```statblock
"name": "Psurlon Leader (BAM)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "mage armor"
"hp": !!int "127"
"hit_dice": "17d8 + 51"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "20"
  - !!int "11"
  - !!int "7"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
  - "charisma": !!int "1"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
"damage_resistances": "psychic"
"condition_immunities": "blinded, charmed"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 16"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "Magic can't read the psurlon's thoughts or put the psurlon to sleep."
    "name": "Aberrant Mind"
  - "desc": "The psurlon has advantage on saving throws it makes to avoid or end the\
      \ frightened, stunned, or unconscious condition on itself. While one of the\
      \ psurlon's heads is asleep, its other head is awake."
    "name": "Two Heads"
"actions":
  - "desc": "The psurlon makes two Bite attacks and two Claw attacks. It can also\
      \ use Pacify (if available) or Psychic Crush."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:*\
      \ 7 (1d8 + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d4 + 3) slashing damage."
    "name": "Claw"
  - "desc": "The psurlon targets one creature it can see within 120 feet of itself.\
      \ The target must succeed on a DC 16 Wisdom saving throw or fall unconscious\
      \ for 10 minutes. The condition ends if the target takes any damage or if another\
      \ creature uses its action to shake the target awake."
    "name": "Pacify (Recharge 5-6)"
  - "desc": "The psurlon targets one creature it can see within 120 feet of itself.\
      \ The target must make a DC 16 Wisdom saving throw, taking 21 (3d10 + 5) psychic\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Psychic Crush"
  - "desc": "The psurlon casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n\
      **2/day each:** disguise self, mage armor (self only)\n\n**1/day each:** dimension\
      \ door, suggestion"
    "name": "Spellcasting (Psionics)"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/aberration/token/psurlon-leader-bam.webp"
```
^statblock