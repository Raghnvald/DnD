---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/construct/warforged
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Glaive"
---
# [Glaive](3-Mechanics/CLI/bestiary/npc/glaive-veor.md)
*Source: Vecna: Eve of Ruin p. 81*  

Since the Mournland's earliest days, Glaive has wielded her namesake weapon in service to the Lord of Blades' bloody conquest of the blighted region. Among the blades, Glaive is best known for her talent at self-modification. "Glaive" is etched onto the back of her neck-plate. It is the only name Glaive has ever known, and fellow blades don't dare call her anything else. Mournland adventurers, however, refer to the terrifying commander by another name: Kill Switch.

```statblock
"name": "Glaive (VEoR)"
"size": "Medium"
"type": "construct"
"subtype": "warforged"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"modifier": !!int "3"
"stats":
  - !!int "20"
  - !!int "16"
  - !!int "19"
  - !!int "11"
  - !!int "16"
  - !!int "9"
"speed": "30 ft. (50 ft. with overdrive)"
"saves":
  - "strength": !!int "9"
  - "dexterity": !!int "7"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+7"
"damage_resistances": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "passive Perception 17"
"languages": "Common"
"cr": "11"
"traits":
  - "desc": "When Glaive takes cold damage, her Overdrive immediately recharges."
    "name": "Heatsink"
  - "desc": "Glaive has advantage on attack rolls if at least one ally is within 5\
      \ feet of the creature she's attacking and the ally doesn't have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "Glaive makes two Spiked Glaive attacks and two Serrated Bolt attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:*\
      \ 10 (1d10 + 5) piercing or slashing damage, or 14 (1d10 + 9) piercing or\
      \ slashing damage if Glaive is in overdrive."
    "name": "Spiked Glaive"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 60 ft., one target. *Hit:*\
      \ 13 (3d6 + 3) piercing damage. If Glaive has advantage on the attack roll,\
      \ the serrated bolt lodges in the target, and the target's speed is reduced\
      \ by 10 feet until the serrated bolt is removed. A target's speed can be reduced\
      \ by only one serrated bolt at a time. A creature can use its action to remove\
      \ a serrated bolt lodged in itself or another creature within its reach; when\
      \ the bolt is removed from a creature, that creature takes 5 (2d4) slashing\
      \ damage."
    "name": "Serrated Bolt"
"bonus_actions":
  - "desc": "Glaive enters a state of overdrive that lasts for 1 minute or until she\
      \ has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition. While in overdrive, Glaive gains the following benefits:\n\n- Glaive\
      \ has advantage on Strength checks and Strength saving throws.  \n- When Glaive\
      \ makes a melee weapon attack, she gains a +4 bonus to the damage roll.  \n\
      - Glaive's speed increases to 50 feet.  "
    "name": "Overdrive (Recharges after Finishing a Short or Long Rest)"
"reactions":
  - "desc": "In response to being hit by a weapon attack, Glaive reduces the damage\
      \ by 11 (2d10)."
    "name": "Self-Preservation"
"source":
  - "VEoR"
"image": "3-Mechanics/CLI/bestiary/npc/token/glaive-veor.webp"
```
^statblock