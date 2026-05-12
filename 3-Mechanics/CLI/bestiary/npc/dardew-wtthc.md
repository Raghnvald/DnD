---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dardew"
---
# [Dardew](3-Mechanics/CLI/bestiary/npc/dardew-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Dardew the Banished is a devilishly charming showman with fiery ambition. He knows how to delight an audience, even if it means making a few infernal pacts on the sly for a truly juicy spectacle.

Dardew is a cambion, a former mortal corrupted by an otherworldly power. His red skin and leathery wings betray his fiendish nature, and his boisterous but smooth voice commands attention. When that fails him, he accentuates his words with audacious riffs on his wicked lute.

```statblock
"name": "Dardew (WttHC)"
"size": "Medium"
"type": "fiend"
"alignment": "Chaotic Neutral"
"ac": !!int "19"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "16"
"speed": "30 ft., fly 60 ft."
"saves":
  - "intelligence": !!int "5"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+9"
"damage_resistances": "cold, fire, lightning, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 14"
"languages": "Abyssal, Common, Infernal"
"cr": "5"
"actions":
  - "desc": "Dardew makes two attacks, using Fiery Claw or Power Chord in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft.  *Hit:* 8 (1d8 + 4) Slashing\
      \ damage plus 7 (2d6) Fire damage."
    "name": "Fiery Claw"
  - "desc": "*Constitution Saving Throw:* DC 14, one creature Dardew can see within\
      \ 120 ft. *Failure:* 13 (3d6 + 3) Thunder damage."
    "name": "Power Chord"
"bonus_actions":
  - "desc": "*Charisma Saving Throw:* DC 14, one creature Dardew can see within 60\
      \ feet. *Failure:* The creature has the [Charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition until the start of Dardew's next turn."
    "name": "Silver Tongue"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/npc/token/dardew-wtthc.webp"
```
^statblock