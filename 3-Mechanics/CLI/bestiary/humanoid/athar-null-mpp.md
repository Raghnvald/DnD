---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Athar Null"
---
# [Athar Null](3-Mechanics/CLI/bestiary/humanoid/athar-null-mpp.md)
*Source: Morte's Planar Parade p. 53*  

The Athar deny the legitimacy of gods, believing the so-called deities are merely powerful spellcasters. To combat false gods, Athar nulls train to negate the powers of those with magic. Nulls work in the shadows, serving as assassins and spies for the Athar.

```statblock
"name": "Athar Null (MPP)"
"size": "Small or Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "14"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"senses": "passive Perception 15"
"languages": "Common plus two more languages"
"cr": "5"
"traits":
  - "desc": "If the null is subjected to an effect that allows it to make a saving\
      \ throw to take half as much damage, it instead takes no damage if it succeeds\
      \ on the saving throw, and half as much damage if it fails."
    "name": "Avoidance"
"actions":
  - "desc": "The null makes two Force Dagger attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage plus 13 (3d8) force\
      \ damage. *Hit or Miss:* The dagger magically returns to the null's hand immediately\
      \ after a ranged attack."
    "name": "Force Dagger"
"bonus_actions":
  - "desc": "The null takes the [Dash](3-Mechanics/CLI/rules/actions.md#Dash), [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage),\
      \ or Use an Object action."
    "name": "Defier's Whim"
"reactions":
  - "desc": "The null utters a magical word of cancellation to interrupt a creature\
      \ it can see that is casting a spell. If the spell is 3rd level or lower, it\
      \ fails and has no effect. If the spell is 4th level or higher, the null makes\
      \ an Intelligence check (DC 10 + the spell's level). On a successful check,\
      \ the spell fails and has no effect."
    "name": "Nullify Spell (3/Day)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/athar-null-mpp.webp"
```
^statblock