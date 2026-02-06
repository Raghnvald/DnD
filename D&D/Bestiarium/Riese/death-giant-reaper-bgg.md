---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/12
  - Monster/Größe/Riesig
  - Monster/Typ/Riese
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Death Giant Reaper
---
# [Death Giant Reaper](3-Mechanics\CLI\bestiary\giant/death-giant-reaper-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 126*  

Death giant reapers wield massive scythes and wear armor that resembles the carapaces of giant insects. They wield the magic of shadow, which lets them take on a ghastly appearance and disappear, as well as twist shadow into terrifying bolts of energy that drain the vigor of their victims.

## Death Giants

Long ago, a large band of cloud giants traveled to the Shadowfell in search of a way to preserve their collapsing empire. Desperate to save themselves and their way of life, they collectively made a bet with the Raven Queen, a mysterious god of death and memory who dwells on that plane. Accounts of that bet and its outcome vary: some say the Raven Queen answered every riddle the giants posed until the giants collapsed from exhaustion, while others describe a series of increasingly improbable events favoring the Raven Queen in every wager. What is certain is that the giants severely underestimated the Raven Queen. When they lost their wager, the Shadowfell became their home, and they have grudgingly served the Raven Queen ever since.

Over time, the Shadowfell transformed these giants; their bodies shriveled, and their complexions took on a deep-purple hue. They became the first death giants, and their descendants haunt the Shadowfell to this day, searching both that plane and the Material Plane for souls that might please their divine queen.

> [!quote] A quote from Diancastra  
> 
> Most giants know better than to make regular use of the death rune.

> [!quote] A quote from Bigby  
> 
> "Know better"? Perhaps, but there's no denying that death giants can make excellent use of it.


```statblock
"name": "Death Giant Reaper (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "20"
  - !!int "18"
  - !!int "16"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "constitution": !!int "9"
  - "intelligence": !!int "8"
  - "wisdom": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+8"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "necrotic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 17"
"languages": "Giant"
"cr": "12"
"actions":
  - "desc": "The giant makes two Scythe or Soul Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 15 ft., one target. *Hit:* 21\
      \ (3d8 + 8) slashing damage plus 11 (2d10) necrotic damage."
    "name": "Scythe"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 120 ft., one creature. *Hit:*\
      \ 26 (4d10 + 4) necrotic damage. If the target has the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition, the giant gains temporary hit points equal to the damage dealt."
    "name": "Soul Bolt"
"bonus_actions":
  - "desc": "The giant magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 40 feet to an unoccupied space it can see. Each creature\
      \ within 10 feet of the location the giant left must succeed on a DC 16 Wisdom\
      \ saving throw or have the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition until the end of that creature's next turn."
    "name": "Frightening Teleport (Recharge 4-6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/death-giant-reaper-bgg.webp"
```
^statblock