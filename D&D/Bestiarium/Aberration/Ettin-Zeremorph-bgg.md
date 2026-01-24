---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/8
  - Monster/Größe/Groß
  - Monster/Typ/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ettin Ceremorph
---
# [Ettin Ceremorph](3-Mechanics\CLI\bestiary\aberration/ettin-ceremorph-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 133*  

Mind flayers, which are described in the *Monster Manual*, are created through ceremorphosis, a process that begins with the implantation of an illithid tadpole in the brain of a Humanoid host. Mind flayers have subjected giants to this process in an effort to create larger, stronger mind flayers, but those experiments all ended in failure: a giant's body is simply too large for a single tadpole to take over. Ettins, however, proved to be perfect subjects. An ettin's two brains provide sufficient food for two tadpoles, and the two tadpoles are able to transform the entirety of the ettin's body, creating an ettin ceremorph. As part of the transformation process, one of the ettin's heads sinks into the body, with that brain focused on controlling the body. The other head focuses on cogitation and psionic power, though its power is not as great as a mind flayer's.

Ettin ceremorphs serve mind flayer colonies, protecting the elder brains that rule the communities and guarding their treasures. They retain no memory of their previous existence as ettins.

```statblock
"name": "Ettin Ceremorph (BGG)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "104"
"hit_dice": "11d10 + 44"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "18"
  - !!int "15"
  - !!int "14"
"speed": "40 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
"damage_resistances": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned), [unconscious](/3-Mechanics/CLI/conditions.md#Unconscious)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 18"
"languages": "Deep Speech, Giant, telepathy 60 ft., Undercommon"
"cr": "8"
"traits":
  - "desc": "The ceremorph has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The ceremorph makes one Slam attack and one Tentacles attack. The ceremorph\
      \ can replace one of the attacks with a Mind Bolt attack, if available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:* 22\
      \ (4d8 + 4) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one creature. *Hit:*\
      \ 15 (2d10 + 4) psychic damage. If the target is Large or smaller, it has the\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape DC 14)\
      \ and must succeed on a DC 15 Intelligence saving throw or have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition until this grapple ends."
    "name": "Tentacles"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ Humanoid [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the ceremorph.\
      \ *Hit:* 55 (10d10) piercing damage. If this damage reduces the target to 0\
      \ hit points, the ceremorph kills the target by extracting and devouring its\
      \ brain."
    "name": "Extract Brain"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 120 ft., one creature. *Hit:*\
      \ 17 (2d12 + 4) psychic damage, and the target must succeed on a DC 15 Intelligence\
      \ saving throw or have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition until the end of its next turn."
    "name": "Mind Bolt (3/Day)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/ettin-ceremorph-bgg.webp"
```
^statblock