---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/HG/1
- Monster/Größe/Mittelgroß
- Monster/Typ/Humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Thought Spy
---
# [Thought Spy](3-Mechanics\CLI\bestiary\humanoid/thought-spy-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 233*  

Thought spies form the backbone of House Dimir's covert operations. They are trained in stealth and infiltration, tactics that they supplement with rigorously developed mental abilities. To ensure that no secrets slip through Dimir's fingers, they infiltrate rival guilds. In addition to traditional means of gathering intelligence, thought spies use their magic to spy on the thoughts of their targets.

```statblock
"name": "Thought Spy (GGR)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "leather armor"
"hp": !!int "27"
"hit_dice": "6d8"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "10"
  - !!int "16"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "Deception"
    "desc": "+6"
  - "name": "Insight"
    "desc": "+3"
  - "name": "Investigation"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Sleight of Hand"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+4"
"senses": "darkvision 30 ft., passive Perception 13"
"languages": "Common plus any one language"
"cr": "1"
"traits":
  - "desc": "The thought spy's innate spellcasting ability is Intelligence (spell\
      \ save DC 13). The thought spy can innately cast the following spells, requiring\
      \ no components:\n\n**At will:** charm person, disguise self, [encode thoughts](/3-Mechanics/CLI/spells/encode-thoughts-ggr.md)\
      \ (see chapter 2)\n\n**1/day each:** blur, detect thoughts, gaseous form"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "On each of its turns, the thought spy can use a bonus action to take\
      \ the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
"actions":
  - "desc": "The thought spy makes two melee attacks, or it makes three ranged attacks\
      \ with its daggers."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6 (1d8\
      \ + 2) piercing damage."
    "name": "Rapier"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/thought-spy-ggr.webp"
```
^statblock