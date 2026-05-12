---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fey
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dankwood Hag"
---
# [Dankwood Hag](3-Mechanics/CLI/bestiary/fey/dankwood-hag-awm.md)
*Source: Adventure with Muk p. 31*  

Dankwood hags are the worst kind of hags in the world. They are creepy and grumpy with long fingers that end in iron claws. They are known to eat small goblins and other warm-blooded creatures, but Dankwood hags are especially fond of sparkleberry tarts.

Since sparkleberries grow only where dryads have their sacred groves, Dankwood hags don't dare enter lest they anger the dryads and suffer their wrath. Dankwood hags are also very greedy and this can be used against them to lure them into a trap or trick them into eating something they shouldn't.

```statblock
"name": "Dankwood Hag (AWM)"
"size": "Medium"
"type": "fey"
"alignment": "Neutral Evil"
"ac": !!int "17"
"hp": !!int "82"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "16"
  - !!int "13"
  - !!int "14"
  - !!int "14"
"speed": "30 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The hag's spellcasting ability is Charisma (spell save DC 12). It can\
      \ innately cast the following spells:\n\n**At will:** dancing lights, minor\
      \ illusion, vicious mockery"
    "name": "Innate Spellcasting"
  - "desc": "The hag can breathe air and water."
    "name": "Amphibious"
  - "desc": "The hag can mimic animal sounds and humanoid voices. A creature that\
      \ hears the sounds can tell they are imitations with a successful DC 14 Wisdom\
      \ (Insight) check."
    "name": "Mimicry (Green Hag)"
"actions":
  - "desc": "The hag covers herself with a magical illusion that allows her to look\
      \ like another creature of her general size and shape. The illusion ends when\
      \ the hag chooses, or if she dies. A DC 20 Intelligence (Investigation) check\
      \ will expose the hag's disguise."
    "name": "Illusory Appearance"
  - "desc": "The hag magically turns invisible until she attacks or casts a spell,\
      \ or until her concentration ends. While invisible, she leaves no physical evidence\
      \ of her passage, and can only be tracked by magic."
    "name": "Invisible Passage"
  - "desc": "*Melee Weapon Attack:* +6 to hit, one target. *Hit:* 17 (2d8 + 4)\
      \ slashing damage."
    "name": "Claws"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/fey/token/dankwood-hag-awm.webp"
```
^statblock