---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv4ec
  - Monster/HG/6
  - Monster/Größe/Groß
  - Monster/Typ/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Witchstalker
---
# [Witchstalker](3-Mechanics\CLI\bestiary\monstrosity/witchstalker-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Twice the size of their ordinary kin, witchstalkers are giant wolves drawn to sources of magic by their supernatural sense of smell. As a result, the moors and forests of Dunbarrow make for good hunting grounds. The greater the source of magic, the more witchstalkers are drawn to the area. To their dismay, witches have drawn as many as a dozen witchstalkers.

Witchstalkers resemble monstrous wolves with enormous jaws and ridged spines. By feeding on spellcasters and other sources of magic, witchstalkers developed their own magical abilities, including a supernatural howl and the ability to teleport next to unsuspecting prey.

```statblock
"name": "Witchstalker (MCV4EC)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "13"
"hp": !!int "82"
"hit_dice": "11d10 + 22"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "15"
  - !!int "8"
  - !!int "12"
  - !!int "6"
"speed": "60 ft."
"saves":
  - "strength": !!int "7"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+6"
"senses": "truesight 60 ft., passive Perception 17"
"languages": "understands Common but can't speak"
"cr": "6"
"traits":
  - "desc": "The witchstalker has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The witchstalker can sense the presence and location of magic within\
      \ 120 feet of itself. It also has advantage on attack rolls against creatures\
      \ that have cast a spell since the end of the witchstalker's last turn."
    "name": "Smell Magic"
"actions":
  - "desc": "The witchstalker makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (3d6 + 4) piercing damage. If the target is a Large or smaller creature, it\
      \ must succeed on a DC 15 Strength saving throw or have the prone condition."
    "name": "Bite"
  - "desc": "The witchstalker unleashes a terrible howl, and each creature within\
      \ 30 feet of it that isn't a Monstrosity must make a DC 13 Wisdom saving throw.\
      \ On a failed save, a creature takes 24 (7d6) psychic damage and has disadvantage\
      \ on Constitution saving throws to maintain concentration on spells until the\
      \ end of its next turn. On a successful save, a creature takes half as much\
      \ damage only."
    "name": "Mind-Wracking Howl (Recharge 5-6)"
"reactions":
  - "desc": "Immediately after a creature within 120 feet of the witchstalker casts\
      \ a spell, the witchstalker magically teleports to an unoccupied space within\
      \ 5 feet of the creature and can make one Bite attack against the creature."
    "name": "Spell Stalk"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/witchstalker-mcv4ec.webp"
```
^statblock