---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/awm
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Great Kroom, Purple Worm"
---
# [Great Kroom, Purple Worm](3-Mechanics/CLI/bestiary/npc/great-kroom-purple-worm-awm.md)
*Source: Adventure with Muk p. 33*  

Great Kroom is a purple worm that comes to the Dankwood every twenty years to feed on all kinds of stuff that grows under the forest.

The Great Kroom is a terrifying and dangerous monster that could easily destroy Gob-Town but there are ways to stop it:

- You need to find a tickling stick. This magical stick can be used on a purple worm to tickle it into a docile state. Then it can be led away from the Dankwood.  
- You need to have it eat a rare mushroom called a Punderpuff. This mushroom grows deep in the Dankwood and has a powerful chemical that can put a purple worm to sleep.  

```statblock
"name": "Great Kroom, Purple Worm (AWM)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "247"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "13"
  - !!int "12"
  - !!int "11"
  - !!int "11"
  - !!int "12"
"speed": "50 ft., burrow 30 ft."
"senses": "passive Perception 0"
"languages": ""
"cr": "15"
"traits":
  - "desc": "The worm can burrow through solid rock at half its burrow speed and leaves\
      \ a 10-foot-diameter tunnel in its wake."
    "name": "Tunneler"
"actions":
  - "desc": "The worm makes two attacks:"
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, one target. *Hit:* 22 (3d8) piercing\
      \ damage. Target must make a DC 19 Dexterity save, or be swallowed by the worm!"
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +14 to hit, one creature. *Hit:* 19 (3d6 +\
      \ 9) piercing damage Target must make a DC 19 Constitution save, or take 42\
      \ (12d6) poison damage."
    "name": "Tail Stinger"
"source":
  - "AWM"
"image": "3-Mechanics/CLI/bestiary/npc/token/great-kroom-purple-worm-awm.webp"
```
^statblock