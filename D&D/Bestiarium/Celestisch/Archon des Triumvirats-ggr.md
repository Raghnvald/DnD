---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/14
- Monster/Größe/Mittelgroß
- Monster/Typ/Himmlische
statblock: inline
statblock-link: "#^statblock"
aliases:
- Archon of the Triumvirate
---
# [Archon of the Triumvirate](3-Mechanics\CLI\bestiary\celestial/archon-of-the-triumvirate-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 192*  

Archons are enigmatic, supernatural embodiments of the harshest aspects of law and order. They espouse a rigid sense of justice and deal ruthless punishment to those who break the law. This nature often aligns them with the Azorius Senate, and they are commonly seen circling above the Azorius guildhall astride their winged felidar mounts, soaring alongside griffon-mounted hussars.

An archon appears as an armored humanoid figure, nearly always mounted. Its face is usually shadowed beneath a large hood; those who have seen beneath the hood describe a face of celestial beauty with a stern expression and blank white eyes.

## Eternal Riders

The bond between an archon and its winged felidar mount is so close that the two are sometimes considered a single being, acting with a single mind. If an archon is ever thrown from its saddle, it can magically return to its place astride its mount in an instant.

## Immortal Nature

An archon doesn't require food, drink, or sleep.

```statblock
"name": "Archon of the Triumvirate (GGR)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Neutral"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "15"
  - !!int "19"
  - !!int "15"
  - !!int "21"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "10"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "Insight"
    "desc": "+10"
  - "name": "Perception"
    "desc": "+10"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "charmed, exhaustion, frightened"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "all"
"cr": "14"
"traits":
  - "desc": "The archon's innate spellcasting ability is Wisdom (spell save DC 18,\
      \ +10 to hit with spell attacks). The archon can innately cast the following\
      \ spells, requiring no material components:\n\n**At will:** calm emotions, command,\
      \ compelled duel"
    "name": "Innate Spellcasting"
  - "desc": "As a bonus action, the archon can target a creature it can see within\
      \ 120 feet of it and determine which laws that creature has broken in the last\
      \ 24 hours."
    "name": "Eye of the Law"
  - "desc": "If the archon isn't mounted, it can use a bonus action to magically teleport\
      \ onto the creature serving as its mount, provided the archon and its mount\
      \ are on the same plane of existence. When it teleports, the archon appears\
      \ astride the mount along with any equipment it is wearing or carrying. While\
      \ mounted and not incapacitated, the archon can't be surprised, and both it\
      \ and its mount gain advantage on Dexterity saving throws. If the archon is\
      \ reduced to 0 hit points while riding its mount, the mount is reduced to 0\
      \ hit points as well."
    "name": "Mount"
"actions":
  - "desc": "The archon makes two Hammer of Justice attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) bludgeoning damage plus 18 (4d8) force damage. If the target is\
      \ a creature, it must succeed on a DC 18 Strength saving throw or be knocked\
      \ prone."
    "name": "Hammer of Justice"
  - "desc": "Each creature of the archon's choice that the archon can see within 120\
      \ feet of it must succeed on a DC 18 Wisdom saving throw, or else the target\
      \ drops any weapons it is holding, ends its concentration on any spells or other\
      \ effects, and becomes charmed by the archon for 1 minute. The charmed creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success. If a creature's saving throw is successful or the\
      \ effect ends for it, the creature is immune to the archon's Pacifying Presence\
      \ for the next 24 hours."
    "name": "Pacifying Presence"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the archon of the triumvirate can expend a use to take one of the following\
  \ actions. The archon of the triumvirate regains all expended uses at the start\
  \ of each of its turns."
"legendary_actions":
  - "desc": "If the archon isn't mounted, it magically teleports to its steed and\
      \ mounts it as long as the archon and its steed are on the same plane of existence."
    "name": "Rejoin Mount"
  - "desc": "The archon makes a Hammer of Justice attack, and then its mount can use\
      \ its reaction to make a melee weapon attack."
    "name": "Smite (Costs 2 Actions)"
  - "desc": "The archon targets a creature it can see within 60 feet of it. The target\
      \ must succeed on a DC 18 Charisma saving throw or be magically teleported to\
      \ a harmless demiplane until the end of the archon's next turn, whereupon the\
      \ target reappears in the space it left or the nearest unoccupied space if that\
      \ space is occupied."
    "name": "Detention (Costs 3 Actions)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/celestial/token/archon-of-the-triumvirate-ggr.webp"
```
^statblock