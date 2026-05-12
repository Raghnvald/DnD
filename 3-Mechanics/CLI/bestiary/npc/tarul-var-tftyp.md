---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tarul Var"
---
# [Tarul Var](3-Mechanics/CLI/bestiary/npc/tarul-var-tftyp.md)
*Source: Tales from the Yawning Portal p. 244*  

After failing in an earlier task for the Red Wizards, the lich Tarul Var is sequestered within the Doomvault (Dead in Thay), where he tries to avoid the attention of Szass Tam. Interlopers who discover his quarters are set upon by the lich and his dread warrior guards, but if Var is brought to the brink of death, he might bargain for a chance to escape the dungeon.

## Undead Nature

A lich doesn't require air, food, drink, or sleep.

```statblock
"name": "Tarul Var (TftYP)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "19"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+9"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+9"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "cold; lightning; necrotic; bludgeoning, piercing, slashing\
  \ from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 17"
"languages": "Abyssal, Common, Infernal, Primordial, Thayan"
"cr": "13"
"traits":
  - "desc": "Var is a 12th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 17, +9 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n*Conjuration spell of 1st level or higher\n\n**Cantrips\
      \ (at will):** [fire bolt](3-Mechanics/CLI/spells/fire-bolt-xphb.md), [mage\
      \ hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [minor illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md), [ray\
      \ of frost](3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n**1st level (4 slots):**\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md),\
      \ [shield](3-Mechanics/CLI/spells/shield-xphb.md), [unseen servant](3-Mechanics/CLI/spells/unseen-servant-xphb.md)*\n\
      \n**2nd level (3 slots):** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [flaming sphere](3-Mechanics/CLI/spells/flaming-sphere-xphb.md)*, [mirror\
      \ image](3-Mechanics/CLI/spells/mirror-image-xphb.md), [scorching ray](3-Mechanics/CLI/spells/scorching-ray-xphb.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md),\
      \ [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [fireball](3-Mechanics/CLI/spells/fireball-xphb.md)\n\
      \n**4th level (3 slots):** [dimension door](3-Mechanics/CLI/spells/dimension-door-xphb.md)*,\
      \ [Evard's black tentacles](3-Mechanics/CLI/spells/evards-black-tentacles-xphb.md)*\n\
      \n**5th level (3 slots):** [cloudkill](3-Mechanics/CLI/spells/cloudkill-xphb.md)*,\
      \ [scrying](3-Mechanics/CLI/spells/scrying-xphb.md)\n\n**6th level (1 slots):**\
      \ [circle of death](3-Mechanics/CLI/spells/circle-of-death-xphb.md)"
    "name": "Spellcasting"
  - "desc": "While Var is [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a conjuration spell, his [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ can't be broken as a result of taking damage."
    "name": "Focused Conjuration"
  - "desc": "If Var fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If Var is destroyed but his phylactery remains intact, Var gains a new\
      \ body in 1d10 days, regaining all his hit points and becoming active again.\
      \ The new body appears within 5 feet of the phylactery."
    "name": "Rejuvenation"
  - "desc": "Var has advantage on saving throws against any effect that turns undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "*Melee Spell Attack:* +9 to hit, reach 5 ft., one creature. *Hit:*\
      \ 10 (3d6) cold damage. The target must succeed on a DC 17 Constitution saving\
      \ throw or be [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed) for\
      \ 1 minute. The target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Paralyzing Touch"
  - "desc": "Var teleports up to 30 feet to an unoccupied space he can see. Alternatively,\
      \ he can choose a space within range that is occupied by a Small or Medium creature.\
      \ If that creature is willing, both creatures teleport, swapping places. Var\
      \ can use this feature again only after he finishes a long rest or casts a conjuration\
      \ spell of 1st level or higher."
    "name": "Benign Transposition"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Tarul can expend a use to take one of the following actions. Tarul regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Var casts a cantrip."
    "name": "Cantrip"
  - "desc": "Var uses Paralyzing Touch."
    "name": "Paralyzing Touch (Costs 2 Actions)"
  - "desc": "Var fixes his gaze on one creature he can see within 10 feet of him.\
      \ The target must succeed on a DC 17 Wisdom saving throw against this magic\
      \ or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) for\
      \ 1 minute. The [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success. If a target's saving throw is successful\
      \ or the effect ends for it, the target is immune to Var's gaze for the next\
      \ 24 hours."
    "name": "Frightening Gaze (Costs 2 Actions)"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/npc/token/tarul-var-tftyp.webp"
```
^statblock