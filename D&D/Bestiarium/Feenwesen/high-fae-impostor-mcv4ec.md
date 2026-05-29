---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: High Fae Impostor
linter-yaml-title-alias: High Fae Impostor
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/11
  - Monster/Typ/Fee
  - Quelle/5e/mcv4ec
aliases:
  - High Fae Impostor
---
# [High Fae Impostor](3-Mechanics\CLI\bestiary\fey/high-fae-impostor-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

High fae impostors are sly and mischievous manipulators who delight in disguising themselves with magic to vex other creatures. Their reasons for deception vary, ranging from harmless pranks to malicious infiltration. When a high fae impostor takes on the identity of another creature, the impostor magically gains access to a small portion of that creature's mind—any information that the creature might share with a casual acquaintance. Though not comprehensive, this information helps high fae impostors impersonate their targets effectively.

> [!quote]  
> 
> Though unable to tell outright lies, the high fae of Eldraine have many other means of deception at their disposal.

## High Fae

Ageless and inhuman, high fae are the oldest creatures in Eldraine, embodying the natural splendor and danger of the wilderness. High fae have no regard for mortal values of honor and law, but they nonetheless operate under inviolable rules of their own: gifts must always be repaid, promises must be honored, and outright lies must never be spoken (though misdirection and riddles are always welcome). To amuse themselves over the long centuries of their lives, high fae frequently engage in deceptions and other complex games of wits against one another.

Most high fae remain secluded deep within the wilds of Eldraine. They draw power from motes of light found throughout the wilds, and they use their innate illusory magic to power and embellish their various weapons.

The high fae are ruled by Talion, the Kindly Lord. Talion is as strange, ancient, and fickle as the wilds of Eldraine, and the Kindly Lord demands fealty and respect from followers. Despite having an austere demeanor, the Kindly Lord is also known for following mysterious whims, journeying to the farthest reaches of Eldraine out of an insatiable curiosity.

```statblock
"name": "High Fae Impostor (MCV4EC)"
"size": "Medium"
"type": "fey"
"alignment": "Any alignment"
"ac": !!int "15"
"hp": !!int "149"
"hit_dice": "23d8 + 46"
"modifier": !!int "5"
"stats":
  - !!int "13"
  - !!int "21"
  - !!int "15"
  - !!int "18"
  - !!int "16"
  - !!int "23"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Deception"
    "desc": "+14"
  - "name": "Performance"
    "desc": "+10"
  - "name": "Stealth"
    "desc": "+13"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Sylvan"
"cr": "11"
"traits":
  - "desc": "The high fae has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The high fae makes two Fae Blade attacks and uses Vexing Prank once."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 18\
      \ (3d8 + 5) force damage."
    "name": "Fae Blade"
  - "desc": "The high fae targets one creature it can see within 60 feet of itself\
      \ with a magical trick. The target must make a DC 18 Wisdom saving throw. On\
      \ a failed save, the target takes 21 (6d6) psychic damage and has the frightened\
      \ condition until the start of the high fae's next turn. On a successful save,\
      \ the target takes half as much damage only."
    "name": "Vexing Prank"
  - "desc": "The high fae casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 18):\n\
      \n**At will:** friends, minor illusion\n\n**1/day each:** enthrall, Nystul's\
      \ magic aura"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The high fae magically transforms into a duplicate of a Small or Medium\
      \ creature it can see. While transformed, the high fae retains its game statistics\
      \ (other than its size) but gains access to enough general information about\
      \ the imitated creature, such as background and personality, to reasonably pass\
      \ itself off as the creature. This transformation ends if the high fae is reduced\
      \ to 0 hit points, uses this bonus action again, or uses a bonus action to revert\
      \ to its true form."
    "name": "Loot Likeness"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fey/token/high-fae-impostor-mcv4ec.webp"
```
^statblock