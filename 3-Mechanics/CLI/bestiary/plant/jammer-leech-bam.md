---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bam
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jammer Leech"
---
# [Jammer Leech](3-Mechanics/CLI/bestiary/plant/jammer-leech-bam.md)
*Source: Boo's Astral Menagerie p. 30*  

A jammer leech is a barnacle-like creature that begins life as a space-dwelling spore that attaches to the hull of a spelljamming ship, with the leech inside in larval form. A spore that remains attached to a ship for a few days punctures the hull and begins to develop a hard shell that roughly matches the color of the hull. The shell is affixed to the ship by a glue-like substance secreted by the leech. The shell grows until it's about 1 foot in diameter. The leech inside is reddish-purple in color, with a body resembling that of a snail. It has a single watery eye at one end and a spiked tentacle protruding from just below the eye, which it uses to defend itself.

A mated pair of leeches produces `1d6` spores every month. Some of these spores might join their parents on the hull of the ship, while others float off, waiting to attach themselves to another unwary vessel.

A jammer leech damages the hull of the ship to which it is attached and absorbs magic from the ship's spelljamming helm. It can discharge this magic from time to time as a defensive measure. If the crew of a ship becomes aware of leeches that have become attached, it's customary for them to try to scrape the leeches off the hull rather than attack them with weapons. Killing a leech while it is attached to the ship is dangerous, because the trauma of its death can be felt by the ship's spelljammer, who is weakened and incapacitated by the shock.

```statblock
"name": "Jammer Leech (BAM)"
"size": "Tiny"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "12"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "5d4 + 15"
"modifier": !!int "-5"
"stats":
  - !!int "11"
  - !!int "1"
  - !!int "16"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "10 ft."
"condition_immunities": "charmed, frightened, prone"
"senses": "darkvision 30 ft., passive Perception 10"
"languages": ""
"cr": "1"
"traits":
  - "desc": "If the leech is reduced to 0 hit points while attached to a ship that\
      \ has a spelljamming helm, the creature attuned to that helm must make a DC\
      \ 13 Constitution saving throw. On a failed save, the creature takes 10 (4d4)\
      \ psychic damage and is incapacitated for 1 minute. On a successful save, the\
      \ creature takes half as much damage and is incapacitated until the end of its\
      \ next turn."
    "name": "Spelljammer Overload"
  - "desc": "The leech doesn't require air or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2\
      \ (1d4) piercing damage."
    "name": "Spiked Tentacle"
"bonus_actions":
  - "desc": "The leech attaches itself to a ship's hull in its space, dealing 2 (1d4)\
      \ piercing damage to the ship (ignoring the ship's damage threshold). This damage\
      \ can't be repaired until the leech is scraped off the hull. While the leech\
      \ is attached, its speed is 0, and it can detach itself as a bonus action. As\
      \ an action, a creature within reach of the leech can to try to scrape it off\
      \ the hull, doing so with a successful DC 18 Strength check. On a failed check,\
      \ the action is wasted as the leech remains attached to the hull. Removing the\
      \ leech in this way deals no damage to the leech or the ship."
    "name": "Attach to Hull"
"reactions":
  - "desc": "When it takes damage, the leech can discharge a bolt of magical energy\
      \ from its eye that targets one creature it can see within 30 feet of itself.\
      \ The target must succeed on a DC 13 Dexterity saving throw or take 10 (3d6)\
      \ force damage and be stunned until the end of its next turn."
    "name": "Magical Discharge (1/Day)"
"source":
  - "BAM"
"image": "3-Mechanics/CLI/bestiary/plant/token/jammer-leech-bam.webp"
```
^statblock