---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/wdmm
  - Monster/HG/13
  - Monster/Größe/Groß
  - Monster/Typ/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Muiral
---
# [Muiral](3-Mechanics\CLI\bestiary\npc/muiral-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 314*  

Muiral was an accomplished human warrior who long served as Halaster's bodyguard. His descent into madness began when he asked the Mad Mage to tutor him in the wizardly arts. Muiral learned enough magic to transform himself into a half-scorpion monstrosity, becoming known as Muiral the Misshapen. He then retired to the level of Undermountain that would later be called Muiral's Gauntlet, driving out and slaying its original drow denizens. Muiral now spends his days hunting adventurers and other interlopers for fun. Long years alone—and Halaster's influence—have rendered him utterly insane.

```statblock
"name": "Muiral (WDMM)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "23d10 + 69"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "16"
  - !!int "18"
  - !!int "13"
  - !!int "18"
"speed": "50 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+9"
  - "name": "Athletics"
    "desc": "+9"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+5"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Common, Dwarvish, Elvish, Goblin, Undercommon"
"cr": "13"
"traits":
  - "desc": "Muiral is a 13th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 17, +9 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** dancing lights, mage hand, prestidigitation,\
      \ ray of frost, shocking grasp\n\n**1st level (4 slots):** expeditious retreat,\
      \ fog cloud, magic missile, shield\n\n**2nd level (3 slots):** darkness, knock,\
      \ see invisibility, spider climb\n\n**3rd level (3 slots):** animate dead, counterspell,\
      \ lightning bolt\n\n**4th level (3 slots):** greater invisibility, polymorph\n\
      \n**5th level (2 slots):** animate objects, wall of force\n\n**6th level (1\
      \ slots):** create undead, flesh to stone\n\n**7th level (1 slots):** finger\
      \ of death"
    "name": "Spellcasting"
  - "desc": "If Muiral fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "Muiral makes three attacks: two with his longsword and one with his sting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) slashing damage, or 15 (2d10 + 4) slashing damage if used with two\
      \ hands."
    "name": "Longsword"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one creature. *Hit:*\
      \ 9 (1d10 + 4) piercing damage. The target must make a DC 16 Constitution saving\
      \ throw, taking 27 (6d8) poison damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Sting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Muiral can expend a use to take one of the following actions. Muiral regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Muiral casts a cantrip."
    "name": "Cast Cantrip"
  - "desc": "Muiral makes one longsword attack that has a reach of 10 feet."
    "name": "Lunging Attack (Costs 2 Actions)"
  - "desc": "Muiral moves up to his speed without provoking opportunity attacks. Before\
      \ the move, he can make one longsword attack."
    "name": "Retreating Strike (Costs 3 Actions)"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/muiral-wdmm.webp"
```
^statblock