---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Neo-Otyugh"
---
# [Neo-Otyugh](3-Mechanics/CLI/bestiary/aberration/neo-otyugh-imr.md)
*Source: Infernal Machine Rebuild p. 75*  

A neo-otyugh is a stronger, more intelligent version of an otyugh—a grotesque aberration sporting three legs, snake-like tentacles, and a perpetually ravenous maw. Like an otyugh, a neo-otyugh buries itself under mounds of offal and carrion to ambush prey. Their improved intellect and innate spellcasting makes them especially effective against humanoid targets, as they use their powers of control to split off a straggler from a party, then attack.

```statblock
"name": "Neo-Otyugh (IMR)"
"size": "Huge"
"type": "aberration"
"alignment": "Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "150"
"hit_dice": "12d12 + 72"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "11"
  - !!int "22"
  - !!int "12"
  - !!int "13"
  - !!int "6"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 11"
"languages": "Otyugh"
"cr": "7"
"traits":
  - "desc": "The neo-otyugh's innate spellcasting ability is Intelligence (spell save\
      \ DC 12). It can innately cast the following spells, requiring no components:\n\
      \n**At will:** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md)\n\
      \n**1/day each:** [command](3-Mechanics/CLI/spells/command.md), [hold person](3-Mechanics/CLI/spells/hold-person.md)"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The otyugh can magically transmit simple messages and images to any creature\
      \ within 120 feet of it that can understand a language. This form of telepathy\
      \ doesn't allow the receiving creature to telepathically respond."
    "name": "Limited Telepathy"
"actions":
  - "desc": "The neo-otyugh makes three attacks: one with its bite and two with its\
      \ tentacles."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 16 (2d10 + 5) piercing damage. If the target is a creature, it must succeed\
      \ on a DC 17 Constitution saving throw against disease or become [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ until the disease is cured. Every 24 hours that elapse, the target must repeat\
      \ the saving throw, reducing its hit point maximum by 5 (1d10) on a failure.\
      \ The disease is cured on a success. The target dies if the disease reduces\
      \ its hit point maximum to 0. This reduction to the target's hit point maximum\
      \ lasts until the disease is cured."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 15 ft., one target. *Hit:*\
      \ 10 (1d10 + 5) bludgeoning damage. If the target is Large or smaller, it\
      \ is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC 16)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) until the\
      \ grapple ends. The neo-otyugh has two tentacles, each of which can grapple\
      \ one target."
    "name": "Tentacle"
  - "desc": "The neo-otyugh slams creatures [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by it into each other or a solid surface. Each creature must succeed on a\
      \ DC 16 Constitution saving throw or take 15 (3d6 + 5) bludgeoning damage\
      \ and be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) until the end\
      \ of the neo-otyugh's next turn. On a successful save, the target takes half\
      \ the bludgeoning damage and isn't [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)."
    "name": "Tentacle Slam"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/aberration/token/neo-otyugh-imr.webp"
```
^statblock