---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-thp
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/shapeshifter
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Usagt"
---
# [Usagt](3-Mechanics/CLI/bestiary/aberration/usagt-aitfr-thp.md)
*Source: Adventures in the Forgotten Realms: The Hidden Page p. 14*  

These peculiar creatures originate on a tranquil, lawful plane where they lead gentle, languid existences. They enjoy the experiences of life—in memory and in practice—but have curiously few ambitions. Their natural lifespan is centuries long, and they give little thought to the passage of time.

Some scholars of the planes believe usagt are not organisms in any traditional sense but a kind of intelligent being made of notions and psychic matter.

## Curiously Shy

An usagt's true form is amorphous and invisible. They change shape based on the thoughts and memories they observe in other creatures' memories. Each usagt thus has a peculiar sense of itself and its peers, based on what shapes it can take in what order, rather than any visual cues of its own.

## Cunning Observers

The favorite pastime of most usagt is putting on little improvised plays with others of its kind, changing shapes throughout. Usagt observe other creatures and detect their thoughts to broaden the catalog of characters they can portray.

## Strange Nature

Usagt do not reproduce. An usagt requires no food, drink, or sleep, but enjoys them when it can. It does require air.

```statblock
"name": "Usagt (AitFR-THP)"
"size": "Medium"
"type": "aberration"
"subtype": "shapeshifter"
"alignment": "Lawful Neutral"
"ac": !!int "12"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "16"
  - !!int "15"
  - !!int "20"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "8"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "History"
    "desc": "+5"
  - "name": "Insight"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+8"
  - "name": "Performance"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+5"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 100 ft., passive Perception 18"
"languages": "all, telepathy 30 ft."
"cr": "5"
"traits":
  - "desc": "The usagt's innate spellcasting ability is Charisma (spell save DC 15).\
      \ It can cast the following spells, requiring no spell components:\n\n**At will:**\
      \ banishment, detect thoughts, disguise self"
    "name": "Innate Spellcasting"
  - "desc": "The usagt's true form is invisible."
    "name": "Invisibility"
  - "desc": "The usagt can use its action to polymorph into a Small, Medium, or Large\
      \ humanoid it has seen in person or telepathically, or back into its true form.\
      \ Its statistics, other than its size, are the same in each form. While polymorphed,\
      \ the usagt is not invisible. Its new form appears to wear clothes, carry equipment,\
      \ and even wield weapons, but these are all parts of the usagt itself; they\
      \ vanish if dropped or removed from the creature. It can't activate, use, wield,\
      \ or otherwise benefit from any of its apparent equipment. It reverts to its\
      \ true form if it dies."
    "name": "Shapechanger"
"actions":
  - "desc": "The usagt makes two attacks with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (2d4 + 2) slashing damage plus 11 (2d6 + 4) psychic damage."
    "name": "Claws"
  - "desc": "The usagt targets one creature it can see within 30 feet of it. The target\
      \ must contest its Charisma (Deception) check against the usagt's Wisdom (Insight)\
      \ check.\n\nThe target has advantage on the roll if it is immune to being charmed.\
      \ A target can choose to fail this check.\n\nIf the usagt wins, it magically\
      \ learns the identity of a creature from the target's past, someone the target\
      \ wishes it could speak to again or with whom the target has left something\
      \ unsaid. If somehow no such creature exists in the target's past, the usagt\
      \ learns that instead."
    "name": "Personal Insight"
"reactions":
  - "desc": "When the usagt takes damage, it can choose to revert to its default,\
      \ invisible form and move up to 15 feet without provoking opportunity attacks."
    "name": "Invisibility Response (Recharges When the Usagt Uses Its Shapechanger\
      \ Ability)"
"source":
  - "AitFR-THP"
"image": "3-Mechanics/CLI/bestiary/aberration/token/usagt-aitfr-thp.webp"
```
^statblock