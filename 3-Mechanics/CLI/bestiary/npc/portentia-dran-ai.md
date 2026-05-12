---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/ai
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Portentia Dran"
---
# [Portentia Dran](3-Mechanics/CLI/bestiary/npc/portentia-dran-ai.md)
*Source: Acquisitions Incorporated p. 208*  

Now the owner and driving force behind Dran Enterprises-perhaps Acquisitions Incorporated's most notable rival in the adventuring-for-profit-and-power biz—Portentia Dran is more than she appears to be. Quite literally. The person known as Portentia is actually a changeling, who took the place of the real Portentia before her fifth year.

The changeling Portentia can affect a range of dis guises, and has spent long years engaged in a mission of manipulating the members of the Dran family. Years ago, it was Portentia who tricked her sister Auspicia into exploring the depths of the Wandering Crypt. And she would have been successful in arranging for Omin to be claimed by that creature as well if he hadn't fled immediately in search of a weapon to aid his captured sister.

Whether in combat or social encounters, Portentia shifts frequently between different forms and mindsets, only some of which are fully humanoid. She fights to maim, with a cruel combat style that emphasizes surprise and painful instruction. She is willing to affect any appearance or attitude to achieve her goals. But what those goals are-for herself and Dran Enterprises alike-remain a secret known only to her.

```statblock
"name": "Portentia Dran (AI)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "chain shirt"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "16"
  - !!int "13"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "Deception"
    "desc": "+6"
  - "name": "Insight"
    "desc": "+3"
  - "name": "Perception"
    "desc": "+3"
"condition_immunities": "charmed"
"gear":
  - "shortsword"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Elvish"
"cr": "3"
"traits":
  - "desc": "Portentia deals an extra 14 (4d6) damage when she hits a target with\
      \ a weapon attack and has advantage on the attack roll, or when the target is\
      \ within 5 feet of an ally of Portentia that isn't incapacitated and Portentia\
      \ doesn't have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
"actions":
  - "desc": "Portentia makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) slashing damage."
    "name": "Shortsword"
  - "desc": "Portentia magically polymorphs into a humanoid or beast that has a challenge\
      \ rating equal to or less than her own, or back into her true form. Any equipment\
      \ she is wearing or carrying is absorbed or borne by the new form (her choice).\
      \ In a new form, Portentia retains her game statistics and ability to speak,\
      \ but her AC, movement modes, Strength, Dexterity, and special senses are replaced\
      \ by those of the new form, and she gains any statistics and capabilities (except\
      \ class features, legendary actions, and lair actions) that the new form has\
      \ but that she lacks."
    "name": "Change Shape"
"source":
  - "AI"
"image": "3-Mechanics/CLI/bestiary/npc/token/portentia-dran-ai.webp"
```
^statblock