---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/1-2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Lynx
---
# [Giant Lynx](3-Mechanics\CLI\bestiary\fey/giant-lynx-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 151*  

Though they're often mistaken for mundane cats, giant lynxes are magical creatures with origins in the snowy woodlands of the Feywild. Their coats grow lighter in winter, helping to camouflage them in their favored habitats even when the landscape is draped in snow.

Giant lynxes are crafty hunters, cooperating in small groups to trap prey and occasionally using a magical gift to scout likely hunting locations. They're also smart enough to outwit many of the hunters who seek to trap them for their fur, and they're fond of disabling any trappers' snares they find in their territories.

Frost and cloud giants sometimes befriend giant lynxes and treat them as beloved pets. As long as the lynxes' intelligence and independence are respected, the creatures are happy to share their divination magic with their giant companions.

> [!quote] A quote from Bigby  
> 
> Shortly before encountering the frost giant whose well-placed boulder ended my human existence, Mordenkainen and I saw a giant lynx. It was just staring into space, in that oh-so-feline way. Mordenkainen wanted to talk to it, to find out what it was looking at, but I successfully dissuaded him.

> [!quote] A quote from Diancastra  
> 
> When you see a giant lynx staring into space, you can be quite sure it's looking at something that isn't there. Or at a ghost.


```statblock
"name": "Giant Lynx (BGG)"
"size": "Medium"
"type": "fey"
"alignment": "typically  Neutral"
"ac": !!int "14"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "18"
  - !!int "13"
  - !!int "12"
  - !!int "14"
  - !!int "10"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "cold"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 60 ft., passive Perception\
  \ 16"
"languages": "Giant, Sylvan"
"cr": "1/2"
"traits":
  - "desc": "The lynx can cast [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md),\
      \ requiring no spell components and using Wisdom as the spellcasting ability."
    "name": "Lynx's Sight (1/Day)"
  - "desc": "The lynx has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks made to hide in undergrowth or snowy terrain."
    "name": "Woodland Camouflage"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) slashing damage. If the lynx moved at least 20 feet straight toward the\
      \ target immediately before the hit, the target must succeed on a DC 12 Strength\
      \ saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition.\
      \ If the target has the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition,\
      \ the lynx can make another Claws attack against it as a bonus action."
    "name": "Claws"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/fey/token/giant-lynx-bgg.webp"
```
^statblock