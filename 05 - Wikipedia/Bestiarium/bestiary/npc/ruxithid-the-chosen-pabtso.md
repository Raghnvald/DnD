---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/5
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration/Goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Ruxithid the Chosen
---
# [Ruxithid the Chosen](3-Mechanics\CLI\bestiary\npc/ruxithid-the-chosen-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 99*  

Centuries ago, an abandoned duergar mining outpost called Zorzula's Rest was conquered by mind flayers, and the goblins there were exposed to the illithids' strange powers, leading a subset of the goblins to develop unusual psionic powers. The mind flayers eventually left, but the goblins remained, sequestered from the rest of the world until recently when the mind flayer fanatics called on them. Some of these goblins' descendants possess psionic powers, as evidenced by the goblin psi commanders and goblin psi brawlers (see appendix A for descriptions of both) that make up their ranks. Collectively, the goblins call themselves the Sawplees: a simplification of the word for "goblin" in the illithids' dialect of Deep Speech.

In recent weeks, the Sawplee goblins' leader found a mysterious gemstone. Unknown to Ruxithid the Chosen, a new group of mind flayer fanatics that draw power from the Far Realm planted it for him to find. The gemstone lets Ruxithid telepathically communicate with the mind flayers, who he believes are gods.

```statblock
"name": "Ruxithid the Chosen (PaBTSO)"
"size": "Medium"
"type": "aberration"
"subtype": "goblinoid"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "88"
"hit_dice": "16d8 + 16"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "19"
  - !!int "12"
  - !!int "18"
  - !!int "15"
  - !!int "12"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+10"
"damage_resistances": "psychic"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "Common, Goblin, telepathy 60 ft."
"cr": "5"
"traits":
  - "desc": "When Ruxithid fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "Ruxithid has advantage on saving throws against the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ and [frightened](/3-Mechanics/CLI/conditions.md#Frightened) conditions."
    "name": "Mental Fortitude"
"actions":
  - "desc": "Ruxithid makes two Psi-Charged Scimitar attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage plus 7 (2d6) psychic damage."
    "name": "Psi-Charged Scimitar"
"bonus_actions":
  - "desc": "Ruxithid unleashes a flurry of crystalline psychic tendrils from his\
      \ brain, targeting one creature that he can see within 30 feet of himself. The\
      \ target must succeed on a DC 15 Dexterity saving throw or take 9 (2d8) psychic\
      \ damage and have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned) condition\
      \ until the start of Ruxithid's next turn."
    "name": "Brain Tendrils (Recharge 5-6)"
  - "desc": "Ruxithid commands one allied creature he can see within 60 feet of himself\
      \ to strike. The creature can immediately use its reaction to make one melee\
      \ weapon attack against a target within its reach."
    "name": "Combat Command"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/npc/token/ruxithid-the-chosen-pabtso.webp"
```
^statblock