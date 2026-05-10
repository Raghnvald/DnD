---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/environment/underdark
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hangry Otyugh"
---
# [Hangry Otyugh](3-Mechanics/CLI/bestiary/aberration/hangry-otyugh-awm.md)
*Source: Adventure with Muk p. 33*  

Otyughs are really stinky and ugly monsters that dine on offal, garbage, and dung. They are generally grumpy and aggressive. Most people don't like otyughs at all.

This otyugh can be dealt with in a few ways:

- You can get it to dance by playing music and dancing. Who knew that otyughs liked to dance? It will follow you anywhere now.  
- If you feed an otyugh a magical pie made with the nectar of a fairy fob lily, mixed with spit nettles, and gobnobs, it will be your best friend. (But it will still be stinky.)  
- Otyughs are scared of vampires. If you dress up as one, you might be able to scare it away. You better do a good job of scaring it!  

```statblock
"name": "Hangry Otyugh (AWM)"
"size": "Large"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "14"
"hp": !!int "114"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "19"
  - !!int "6"
  - !!int "13"
  - !!int "6"
"speed": "30 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The otyugh can magically transmit simple messages and images to any creature\
      \ within 120 feet of it that can understand a language. This form of telepathy\
      \ doesn't allow the receiving creature to telepathically respond."
    "name": "Limited Telepathy"
"actions":
  - "desc": "The otyugh makes three attacks:"
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d8 + 3) piercing damage. Target must make a DC 15 Constitution save, or\
      \ take 6 (1d10) poison damage until cured."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 10 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) bludgeoning damage. Target must make a DC 19 Constitution save,\
      \ or take 42 (12d6) poison damage."
    "name": "Tentacle"
  - "desc": "Target must make a DC 14 Constitution save, or be grappled."
    "name": "Slam!"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/aberration/token/hangry-otyugh-awm.webp"
```
^statblock

## Environment

underdark