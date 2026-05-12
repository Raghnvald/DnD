---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lothar"
---
# [Lothar](3-Mechanics/CLI/bestiary/npc/lothar-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 80*  

Lothar is an Uthgardt barbarian and priest of the Raven Queen. He was born to the Uthgardt tribe of the Black Raven. His mother left him to be raised by her Uthgardt husband when Lothar was still young. Lothar was struck with wanderlust an early age, both because of a desire to see the world and a chance to escape the superstition of his people. Lothar can sense paths that are [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible) to mortal senses. He can walk into a forest glade and emerge in the Feywild or track a stag through the snow to appear on the glacial fields of Elysium.

Eventually the wanderings of his youth took him into the Shadowfell. Unlike most, Lothar felt an affinity for the dread realm and had no desire to leave. In the years he spent there, he met his lifelong friend Borivik as well as coming into the service of the Raven Queen.

Unlike most faithful, Lothar's devotion to the Raven Queen was not something that came willingly. Lothar was infected with lycanthropy when he stayed with a family of wereravens disguised as simple merchants. Initially he searched for a cure to the supernatural affliction, but soon began to hear the whisperings of the Raven Queen. At first, she only spoke to him in his dreams, but her voice became more insistent as time went on. It was not long before her voice would encroach upon his thoughts day and night. Lothar realized that he could swear fealty to the enigmatic ruler of the Shadowfell or he could descend into madness. He chose the former.

Much like most who follow the Raven Queen, Lothar rarely understands her motivations or goals. It is his duty to find those he has seen in the visions that she sends him.

## Lothar as a Contact

Lothar is the primary contact for the Raven Circle at low levels. Lothar can take companions with him when he walks the paths between worlds. He will only take members of the Raven Circle on each unique journey once and he waits for one week before returning to Faerûn.

**Journeys with Lothar**

| Journey | Required Level |
|---------|----------------|
| Barovia | 1 |
| Suldanessellar | 1 |
| Other domain of dread | 3 |
| Shadowfell—Evernight | 3 |
| Feywild | 5 |
| Elysium | 5 |
| Beastlands | 7 |
| The Outlands | 7 |
^journeys-with-lothar

```statblock
"name": "Lothar (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Neutral"
"ac": !!int "13"
"hp": !!int "210"
"hit_dice": "28d8 + 84"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "10"
  - !!int "10"
"speed": "30 ft., fly 50 ft. in raven and hybrid forms"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+8"
"damage_immunities": "bludgeoning, piercing, slashing damage from nonmagical weapons\
  \ that aren't silvered"
"gear":
  - "[greataxe](3-Mechanics/CLI/items/greataxe.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Common, Orc"
"cr": "9"
"traits":
  - "desc": "Lothar can mimic simple sounds he has heard, such as a person whispering,\
      \ a baby crying, or an animal chittering. A creature that hears the sounds can\
      \ tell they are imitations with a successful DC 15 Wisdom ([Insight](3-Mechanics/CLI/rules/skills.md#Insight))\
      \ check."
    "name": "Mimicry"
"actions":
  - "desc": "Lothar makes three Greataxe attacks."
    "name": "Multiattack (Humanoid or Hybrid Form Only)"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d12 + 4) slashing damage, 14 (1d12 + 8) while in a rage."
    "name": "Greataxe (Humanoid or Hybrid Form Only)"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 1\
      \ piercing damage in raven form, or 6 (1d4 + 4) piercing damage in hybrid\
      \ form. If the target is Humanoid, it must succeed on a DC 15 Constitution saving\
      \ throw or be cursed with wereraven lycanthropy."
    "name": "Beak (Raven or Hybrid Form Only)"
  - "desc": "Lothar can use his action to polymorph into a raven-humanoid hybrid,\
      \ or into a Small raven, or back into his true form, which is Humanoid. His\
      \ statistics, other than his size, are the same in each form. Any equipment\
      \ he is wearing or carrying isn't transformed. Lothar reverts to his true form\
      \ if he dies."
    "name": "Change Shape"
  - "desc": "Lothar casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 12, +4 to\
      \ hit with spell attacks):\n\n**At will:** [blade ward](3-Mechanics/CLI/spells/blade-ward.md),\
      \ [eldritch blast](3-Mechanics/CLI/spells/eldritch-blast.md), [message](3-Mechanics/CLI/spells/message.md)\n\
      \n**1/day each:** [bane](3-Mechanics/CLI/spells/bane.md), [charm person](3-Mechanics/CLI/spells/charm-person.md),\
      \ [daylight](3-Mechanics/CLI/spells/daylight.md), [faerie fire](3-Mechanics/CLI/spells/faerie-fire.md),\
      \ [fear](3-Mechanics/CLI/spells/fear.md), [misty step](3-Mechanics/CLI/spells/misty-step.md),\
      \ [plane shift](3-Mechanics/CLI/spells/plane-shift.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Lothar rages for 1 minute. During his rage he has advantage on Strength\
      \ checks and Strength saving throws. He gains a +4 bonus to damage while he\
      \ is in a rage. He has resistance to bludgeoning, piercing, and slashing damage\
      \ while in a rage. Lothar can't cast spells while in a rage."
    "name": "Rage"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/lothar-mabjov.webp"
```
^statblock