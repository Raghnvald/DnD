---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/halfling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vellin Farstride"
---
# [Vellin Farstride](3-Mechanics/CLI/bestiary/npc/vellin-farstride-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 62*  

> [!quote] A quote from MINSC  
> 
> COURAGE, FRIENDSHIP, AND the sound of steel on steel! These are the stuff of all great adventures. The fight for justice is hard, sweaty work, but when the times get tough, the tough get hamsters!

Vellin Farstride has earned his last name with a travelogue that would be the envy of any would-be explorer. Vellin specializes in hunting fiendish enemies and other extra planar threats. Vellin is almost always accompanied by his faithful wolf, Akela, and often rides the beast into battle.

Originally from the world of Oerth, Vellin arrived in Faerûn several years ago. Between those two worlds Vellin traveled the Astral Sea, hunted demons in the Blood War, dealt with hags in the Gray Waste and assassinated Infernal Dukes on Avernus. Vellin quickly fell in love with the vast and beautiful wilds of Faerûn and decided that it would be his home. In order to protect his new home, Vellin wanted to band together with formidable allies that could protect it from outer planar threats. He discovered that the Harpers had values that were closest to his own.

Vellin is adept at diplomacy and deception, out of necessity from having to deal with Fiendish powers. Though not physically intimidating, his quiet intensity and well-earned confidence can be very convincing. He prefers simple and direct language, even when dealing with nobles and royalty, but can employ eloquence and flattery when the need arises.

## Vellin as a Contact

Vellin is the primary contact for members of the Harpers at low levels. Vellin is an expert at obtaining mounts on short notice for those who need to get somewhere quickly. Each member of your group gets access to the type of mount requested. If any of the mounts die while under your control (or a member of your group), you can never use that type of mount again. Otherwise, you can use the mount as long as needed.

**Mounts via Vellin**

| Mount | Required Level | Terrain |
|-------|----------------|---------|
| Riding horses | 1 | Land |
| Camels | 1 | Desert |
| Dolphins | 3 | Water |
| Hippogriffons | 3 | Air |
| Giant striders | 7 | Fire |
| Polar bears | 7 | Cold |
^mounts-via-vellin

```statblock
"name": "Vellin Farstride (MaBJoV)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Neutral Good"
"ac": !!int "20"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md), +1\
  \ shield"
"hp": !!int "195"
"hit_dice": "30d6 + 90"
"modifier": !!int "5"
"stats":
  - !!int "11"
  - !!int "20"
  - !!int "16"
  - !!int "11"
  - !!int "14"
  - !!int "11"
"speed": "25 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+8"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+13"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+10"
"gear":
  - "[silvered shortsword](3-Mechanics/CLI/items/silvered-weapon.md)"
"senses": "passive Perception 20"
"languages": "Abyssal, Common, Halfling, Infernal, telepathy 30 ft."
"cr": "9"
"traits":
  - "desc": "Vellin is accompanied by Akela ([wolf](3-Mechanics/CLI/bestiary/beast/wolf.md)\
      \ with 18 hit points). Vellin can mount or dismount Akela using 5 feet of movement.\
      \ While mounted, Vellin can order Akela to [Dash](3-Mechanics/CLI/rules/actions.md#Dash),\
      \ [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage), and [Dodge](3-Mechanics/CLI/rules/actions.md#Dodge).\
      \ In addition, Vellin has an [owl](3-Mechanics/CLI/bestiary/beast/owl.md) companion\
      \ with 3 hit points. On Vellin's turn, the owl can perform a flyby on a creature\
      \ of Vellin's choice. The next attack that Vellin makes against that creature\
      \ has advantage."
    "name": "Animal Companions"
  - "desc": "Vellin has advantage on saving throws against being [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Brave"
  - "desc": "When Vellin hits a Fiend with a weapon attack he deals an additional\
      \ 7 (2d6) radiant damage."
    "name": "Fiend Slayer"
  - "desc": "Vellin has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing or sight."
    "name": "Keen Hearing and Sight"
  - "desc": "Vellin wields a +1 shortsword (silvered) and a +1 shield."
    "name": "Special Equipment"
"actions":
  - "desc": "Vellin makes three Silvered Shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 9 (1d6 + 6) piercing damage."
    "name": "Silvered Shortsword"
"bonus_actions":
  - "desc": "Vellin can take the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Nimble Escape"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/vellin-farstride-mabjov.webp"
```
^statblock