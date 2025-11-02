---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - monster/cr/5
  - monster/size/medium
  - monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Nine-Fingers Keene
---
# [Nine-Fingers Keene](3-Mechanics\CLI\bestiary\npc/nine-fingers-keene-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 170*  

The current leader of the Guild, Nine-Fingers Keene, disdains flashy garb and illusion magic. She appears to the world as she is: an unassuming woman of middling age and build. Her forgettable looks have proven her greatest asset as a thief, as her victims have trouble recognizing her even when they meet her again face-to-face. Keene's leadership over the years earned her a reputation of thoughtful pragmatism. When necessary, she seeks revenge for offenses against the Guild—provided doing so is profitable. Her methods are vicious when necessary, and she is as feared as she is respected.

Keene has become increasingly intolerant of the populous tide turning against her organization. While the occasional rabble-rouser has always impeded criminal business, the rise of organized crews and vigilantes is interfering with Guild operations. After a carefully coordinated attack on a patriar's estate fell to pieces when a vigilante clumsily alerted the estate guards, Keene declared open season on do-gooders of all stripes.

```statblock
"name": "Nine-Fingers Keene (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "[leather armor](/3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "14"
  - !!int "13"
  - !!int "17"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "intelligence": !!int "4"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+10"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+5"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+10"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+10"
"senses": "passive Perception 16"
"languages": "Common, Thieves' cant"
"cr": "5"
"traits":
  - "desc": "On each of her turns in combat, Nine-Fingers can use a bonus action to\
      \ take the Dash, Disengage, or Hide action."
    "name": "Cunning Action"
  - "desc": "Nine-Fingers adds double her proficiency bonus to the damage she deals\
      \ on ranged attacks made with daggers (already factored into her attacks)."
    "name": "Dagger Thrower"
"actions":
  - "desc": "Nine-Fingers attacks three times with her daggers."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d4 + 4) piercing damage, plus 6 piercing damage\
      \ if it's a ranged attack."
    "name": "Dagger"
"reactions":
  - "desc": "Nine-Fingers halves the damage that she takes from an attack that hits\
      \ her. She must be able to see the attacker."
    "name": "Uncanny Dodge"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/nine-fingers-keene-bgdia.webp"
```
^statblock