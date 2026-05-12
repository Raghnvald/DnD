---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gomazoa"
---
# [Gomazoa](3-Mechanics/CLI/bestiary/monstrosity/gomazoa-psz.md)
*Source: Plane Shift: Zendikar p. 26*  

Zendikar's seas and skies tend to blur together, and creatures typically found in the sea often find their way to the clouds, gliding through the plane's gravitational currents by consuming the mana infused in the wind. The windrider eels hunted by the kor and the cloud mantas sometimes ridden by Emeria-creed merfolk are two examples. The gomazoas found in Murasa and the Makindi Trenches are another.

Gomazoas are similar to aquatic jellyfish, but their bodies are encased in stony growths. A gomazoa drifts motionless among floating rocks or hedrons with its long, sticky tentacles dangling below. When they brush against another creature, those tentacles grab and constrict it, or might slam larger prey against a cliff face. Some species can withdraw their tentacles into their bodies, extending them only to grab their prey. Gomazoas almost never release prey once they've caught it.

A gomazoa might be represented by the [roper](3-Mechanics/CLI/bestiary/monstrosity/roper.md) statistics in the *Monster Manual*, with a flying speed of 10 feet in place of its walking and climbing speeds.

```statblock
"name": "Gomazoa (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "-1"
"stats":
  - !!int "18"
  - !!int "8"
  - !!int "17"
  - !!int "7"
  - !!int "16"
  - !!int "6"
"speed": "fly 10 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 16"
"languages": ""
"cr": "5"
"traits":
  - "desc": "While the gomazoa remains motionless, it is indistinguishable from a\
      \ normal cave formation, such as a stalagmite."
    "name": "False Appearance"
  - "desc": "The gomazoa can have up to six tendrils at a time. Each tendril can be\
      \ attacked (AC 20; 10 hit points; immunity to poison and psychic damage). Destroying\
      \ a tendril deals no damage to the gomazoa, which can extrude a replacement\
      \ tendril on its next turn. A tendril can also be broken if a creature takes\
      \ an action and succeeds on a DC 15 Strength check against it."
    "name": "Grasping Tendrils"
  - "desc": "The gomazoa can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The gomazoa makes four attacks with its tendrils, uses Reel, and makes\
      \ one attack with its bite."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 22\
      \ (4d8 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 50 ft., one creature. *Hit:*\
      \ The target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) (escape\
      \ DC 15). Until the grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ and has disadvantage on Strength checks and Strength saving throws, and the\
      \ gomazoa can't use the same tendril on another target."
    "name": "Tendril"
  - "desc": "The gomazoa pulls each creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by it up to 25 feet straight toward it."
    "name": "Reel"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/gomazoa-psz.webp"
```
^statblock