---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Nevermind Gnome Inventor
linter-yaml-title-alias: Nevermind Gnome Inventor
tags:
  - Monster/Größe/Klein
  - Monster/HG/2
  - Monster/Typ/Humanoid
  - Quelle/5e/mcv2dc
aliases:
  - Nevermind Gnome Inventor
---
# [Nevermind Gnome Inventor](3-Mechanics\CLI\bestiary\humanoid/nevermind-gnome-inventor-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 10*  

> [!quote]  
> 
> Who among us hasn't marveled at a majestic bird soaring high above and thought, "I can do better"?
> 
> First, thanks to the work of esteemed elavationist, Rirordinees Thrump, we created lifts to climb the heights of Mount Nevermind. Then, with the gnomeflinger, we brushed the heavens as gracefully as skipping stones. Now, let me present the next stage in automated ascendancy: the cloud clinger!
> 
> Where is it, you ask? You're seated in it! And in just three... two... one...

Brimming with innovative ideas and reckless enthusiasm, the inventors of Mount Nevermind love any chance to showcase their creations. These talented inventors use their cleverness and technological know-how to outwit foes.

## Nevermind Gnomes

Mount Nevermind is a hollow, dormant volcano on the island of Sancrist in Krynn. Within the mountain, a vibrant community of rock gnome tinkerers and other inventors relentlessly study various scientific pursuits to create mechanical marvels.

```statblock
"name": "Nevermind Gnome Inventor (MCV2DC)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "leather armor"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "17"
  - !!int "13"
  - !!int "18"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "6"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "Investigation"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+2"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "Common, Gnomish"
"cr": "2"
"traits":
  - "desc": "The inventor has advantage on initiative rolls."
    "name": "Always Thinking Ahead"
"actions":
  - "desc": "The inventor makes two Flying Fangtrap attacks. It can replace one of\
      \ these attacks with Thunderscream Gadget if it's available."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 60\
      \ ft., one target. *Hit:* 8 (1d10 + 3) piercing damage, and the creature must\
      \ succeed on a DC 14 Dexterity saving throw or have its speed reduced to 0 until\
      \ the start of the inventor's next turn."
    "name": "Flying Fangtrap"
  - "desc": "The inventor produces a gadget that emits a screeching wave of sound\
      \ in a 30-foot cone originating from the inventor. Each creature in that area\
      \ must make a DC 14 Constitution saving throw, taking 10 (3d6) thunder damage\
      \ on a failed save or half as much damage on a successful one."
    "name": "Thunderscream Gadget (Recharge 5-6)"
"reactions":
  - "desc": "If the inventor is damaged by a creature it can see within 15 feet of\
      \ itself, the inventor retaliates by flinging brilliantly explosive powder at\
      \ the creature. The creature must succeed on a DC 14 Dexterity saving throw\
      \ or be blinded until the end of its next turn."
    "name": "Flash Powder"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/nevermind-gnome-inventor-mcv2dc.webp"
```
^statblock