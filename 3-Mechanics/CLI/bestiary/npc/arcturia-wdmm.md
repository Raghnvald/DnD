---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Arcturia"
---
# [Arcturia](3-Mechanics/CLI/bestiary/npc/arcturia-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 296*  

Unable to abide normalcy and consistency, Arcturia fixates on transforming herself, her surroundings, and other creatures. Her moods are ever-changing as well.

```statblock
"name": "Arcturia (WDMM)"
"size": "Medium"
"type": "undead"
"alignment": "Any Evil alignment"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "20"
  - !!int "14"
  - !!int "16"
"speed": "30 ft., fly 60 ft. (hover)"
"saves":
  - "constitution": !!int "10"
  - "intelligence": !!int "12"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+19"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+12"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold, lightning, necrotic"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 19"
"languages": "Common plus up to five other languages"
"cr": "21"
"traits":
  - "desc": "Arcturia is an 18th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 20, +12 to hit with spell attacks). Arcturia can cast [alter\
      \ self](3-Mechanics/CLI/spells/alter-self-xphb.md) at will and has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md), [ray\
      \ of frost](3-Mechanics/CLI/spells/ray-of-frost-xphb.md)\n\n**1st level (4 slots):**\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [magic missile](3-Mechanics/CLI/spells/magic-missile-xphb.md),\
      \ [shield](3-Mechanics/CLI/spells/shield-xphb.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\
      \n**2nd level (3 slots):** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [enlarge/reduce](3-Mechanics/CLI/spells/enlarge-reduce-xphb.md), [Melf's acid\
      \ arrow](3-Mechanics/CLI/spells/melfs-acid-arrow-xphb.md), [mirror image](3-Mechanics/CLI/spells/mirror-image-xphb.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell-xphb.md),\
      \ [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [fireball](3-Mechanics/CLI/spells/fireball-xphb.md),\
      \ [slow](3-Mechanics/CLI/spells/slow-xphb.md)\n\n**4th level (3 slots):** [blight](3-Mechanics/CLI/spells/blight-xphb.md),\
      \ [polymorph](3-Mechanics/CLI/spells/polymorph-xphb.md)\n\n**5th level (3 slots):**\
      \ [animate objects](3-Mechanics/CLI/spells/animate-objects-xphb.md), [telekinesis](3-Mechanics/CLI/spells/telekinesis-xphb.md)\n\
      \n**6th level (1 slots):** [disintegrate](3-Mechanics/CLI/spells/disintegrate-xphb.md),\
      \ [flesh to stone](3-Mechanics/CLI/spells/flesh-to-stone-xphb.md)\n\n**7th level\
      \ (1 slots):** [reverse gravity](3-Mechanics/CLI/spells/reverse-gravity-xphb.md),\
      \ [teleport](3-Mechanics/CLI/spells/teleport-xphb.md)\n\n**8th level (1 slots):**\
      \ [feeblemind](3-Mechanics/CLI/spells/befuddlement-xphb.md), [maze](3-Mechanics/CLI/spells/maze-xphb.md)\n\
      \n**9th level (1 slots):** [true polymorph](3-Mechanics/CLI/spells/true-polymorph-xphb.md)"
    "name": "Spellcasting"
  - "desc": "If Arcturia fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If it has a phylactery, a destroyed lich gains a new body in 1d10 days,\
      \ regaining all its hit points and becoming active again. The new body appears\
      \ within 5 feet of the phylactery."
    "name": "Rejuvenation"
  - "desc": "Arcturia has advantage on saving throws against any effect that turns\
      \ undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "*Melee Spell Attack:* +12 to hit, reach 5 ft., one creature. *Hit:*\
      \ 10 (3d6) cold damage. The target must succeed on a DC 18 Constitution saving\
      \ throw or be [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed) for\
      \ 1 minute. The target can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Paralyzing Touch"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Arcturia can expend a use to take one of the following actions. Arcturia\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Arcturia casts a cantrip."
    "name": "Cantrip"
  - "desc": "Arcturia uses its Paralyzing Touch."
    "name": "Paralyzing Touch (Costs 2 Actions)"
  - "desc": "Arcturia fixes its gaze on one creature it can see within 10 feet of\
      \ it. The target must succeed on a DC 18 Wisdom saving throw against this magic\
      \ or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) for\
      \ 1 minute. The [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success. If a target's saving throw is successful\
      \ or the effect ends for it, the target is immune to Arcturia's gaze for the\
      \ next 24 hours."
    "name": "Frightening Gaze (Costs 2 Actions)"
  - "desc": "Each non-undead creature within 20 feet of Arcturia must make a DC 18\
      \ Constitution saving throw against this magic, taking 21 (6d6) necrotic damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Disrupt Life (Costs 3 Actions)"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/arcturia-wdmm.webp"
```
^statblock