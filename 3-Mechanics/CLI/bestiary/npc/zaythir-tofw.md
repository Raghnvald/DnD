---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tofw
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration/gith
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zaythir"
---
# [Zaythir](3-Mechanics/CLI/bestiary/npc/zaythir-tofw.md)
*Source: Turn of Fortune's Wheel p. 32*  

```statblock
"name": "Zaythir (ToFW)"
"size": "Medium"
"type": "aberration"
"subtype": "gith"
"alignment": "Neutral"
"ac": !!int "16"
"ac_class": "psychic defense"
"hp": !!int "123"
"hit_dice": "19d8 + 38"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "17"
  - !!int "15"
  - !!int "15"
  - !!int "17"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "strength": !!int "4"
  - "dexterity": !!int "6"
  - "intelligence": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common, Gith"
"cr": "7"
"traits":
  - "desc": "While Zaythir is wearing no armor and wielding no shield, its AC includes\
      \ its Wisdom modifier."
    "name": "Psychic Defense"
"actions":
  - "desc": "Zaythir makes three Unarmed Strike or Psychic Bolt attacks. It can replace\
      \ any of these attacks with one use of its Pacifying Touch."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) bludgeoning damage plus 10 (3d6) psychic damage."
    "name": "Unarmed Strike"
  - "desc": "*Ranged Spell Attack:* +6 to hit, range 60 ft., one creature. *Hit:*\
      \ 17 (5d6) psychic damage."
    "name": "Psychic Bolt"
  - "desc": "Zaythir touches one creature it can see within 5 feet of itself. The\
      \ target must succeed on a DC 14 Intelligence saving throw, or Zaythir chooses\
      \ an action for that target: Attack, Cast a Spell, or [Dash](3-Mechanics/CLI/rules/actions.md#Dash).\
      \ The affected target can't take that action for 1 minute. At the end of each\
      \ of the target's turns, it can repeat the saving throw, ending the effect on\
      \ itself on a successful save. A target that succeeds on the saving throw becomes\
      \ immune to this githzerai's Pacifying Touch for 24 hours."
    "name": "Pacifying Touch"
  - "desc": "Zaythir casts one of the following spells, requiring no spell components\
      \ and using Wisdom as the spellcasting ability (spell save DC 14):\n\n**At will:**\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand is invisible),\
      \ [see invisibility](3-Mechanics/CLI/spells/see-invisibility-xphb.md)\n\n**1/day\
      \ each:** [plane shift](3-Mechanics/CLI/spells/plane-shift-xphb.md) (self only),\
      \ [telekinesis](3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting (Psionics)"
"source":
  - "ToFW"
"image": "3-Mechanics/CLI/bestiary/npc/token/zaythir-tofw.webp"
```
^statblock