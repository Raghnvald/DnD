---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Arveiaturace"
---
# [Arveiaturace](3-Mechanics/CLI/bestiary/npc/arveiaturace-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 105*  

Known to Ten-Towners as the White Wyrm, Arveiaturace is an ancient white dragon that lairs atop the Reghed Glacier. She remains the most fearsome predator in Icewind Dale, although age has clouded her eyes with cataracts, limiting the range of her vision to 60 feet. Her blindsight, hearing, and sense of smell are undiminished, however. Fortunately for the residents of the dale, she prefers the taste of reindeer, walrus, and polar bear flesh to that of humanoids. The dragon has a healthy respect for humanoids and has never threatened Ten-Towns directly, though it wouldn't take much to provoke her into doing so.

At one time, Arveiaturace served a wizard named Meltharond, whose frozen corpse remains strapped to a saddle on the dragon's back. Arveiaturace has never acknowledged his death and still speaks to his body as if he were alive. He was, while he lived, her only friend and confidant.

```statblock
"name": "Arveiaturace (IDRotF)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "333"
"hit_dice": "18d20 + 144"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "10"
  - !!int "26"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "40 ft., burrow 40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "6"
  - "constitution": !!int "14"
  - "wisdom": !!int "7"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+13"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "cold"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 60 ft., passive Perception 23"
"languages": "Common, Draconic"
"cr": "20"
"traits":
  - "desc": "Arveiaturace can move across and climb icy surfaces without needing to\
      \ make an ability check. Additionally, difficult terrain composed of ice or\
      \ snow doesn't cost it extra movement."
    "name": "Ice Walk"
  - "desc": "If Arveiaturace fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "Arveiaturace can use its Frightful Presence. It then makes three attacks:\
      \ one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 15 ft., one target. *Hit:*\
      \ 19 (2d10 + 8) piercing damage plus 9 (2d8) cold damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 15 (2d6 + 8) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 20 ft., one target. *Hit:*\
      \ 17 (2d8 + 8) bludgeoning damage."
    "name": "Tail"
  - "desc": "Each creature of Arveiaturace's choice that is within 120 feet of Arveiaturace\
      \ and aware of it must succeed on a DC 16 Wisdom saving throw or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to Arveiaturace's\
      \ Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "Arveiaturace exhales an icy blast in a 90-foot cone. Each creature in\
      \ that area must make a DC 22 Constitution saving throw, taking 72 (16d8)\
      \ cold damage on a failed save, or half as much damage on a successful one."
    "name": "Cold Breath (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Arveiaturace can expend a use to take one of the following actions. Arveiaturace\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Arveiaturace makes a Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ check."
    "name": "Detect"
  - "desc": "Arveiaturace makes a tail attack."
    "name": "Tail Attack"
  - "desc": "Arveiaturace beats its wings. Each creature within 15 feet of Arveiaturace\
      \ must succeed on a DC 22 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning\
      \ damage and be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ Arveiaturace can then fly up to half its flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/npc/token/arveiaturace-idrotf.webp"
```
^statblock