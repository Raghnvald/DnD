---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Barbatos"
---
# [Barbatos](3-Mechanics/CLI/bestiary/npc/barbatos-imr.md)
*Source: Infernal Machine Rebuild p. 52*  

```statblock
"name": "Barbatos (IMR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "13"
  - !!int "14"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+5"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "poison"
"gear":
  - "[light crossbow](3-Mechanics/CLI/items/light-crossbow.md)"
"senses": "passive Perception 13"
"languages": "Common"
"cr": "6"
"traits":
  - "desc": "Barbatos is a 6th-level spellcaster. His spellcasting ability is Wisdom\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following ranger\
      \ spells prepared:\n\n**1st level (4 slots):** [ensnaring strike](3-Mechanics/CLI/spells/ensnaring-strike.md),\
      \ [hail of thorns](3-Mechanics/CLI/spells/hail-of-thorns.md), [hunter's mark](3-Mechanics/CLI/spells/hunters-mark.md)\n\
      \n**2nd level (2 slots):** [locate animals or plants](3-Mechanics/CLI/spells/locate-animals-or-plants.md)"
    "name": "Spellcasting"
  - "desc": "Any nonmagical weapon made of metal that hits Barbatos corrodes. After\
      \ dealing damage, the weapon takes a permanent and cumulative -1 penalty to\
      \ damage rolls. If its penalty drops to -5, the weapon is destroyed. Nonmagical\
      \ ammunition made of metal that hits Barbatos is destroyed after dealing damage."
    "name": "Rust Monster Cloak"
  - "desc": "Barbatos regains 10 hit points at the start of his turn. If Barbatos\
      \ takes acid or fire damage, this trait doesn't function at the start of Barbatos's\
      \ next turn. Barbatos dies only if he starts his turn with 0 hit points and\
      \ doesn't regenerate."
    "name": "Heart of the Troll"
"actions":
  - "desc": "Barbatos makes two bone shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Bone Shortsword"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 80/320 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) piercing damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ for 1 hour. If the saving throw fails by 5 or more, the target is also [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious).\
      \ The target regains consciousness if it takes damage or if another creature\
      \ takes an action to shake it."
    "name": "Light Crossbow"
  - "desc": "Barbatos corrodes a nonmagical ferrous metal object he can see within\
      \ 5 feet of himself. If the object isn't being worn or carried, the touch destroys\
      \ a 1-foot cube of it. If the object is being worn or carried by a creature,\
      \ the creature can make a DC 12 Dexterity saving throw to avoid Barbatos's touch.\n\
      \nIf the object touched is either metal armor or a metal shield being worn or\
      \ carried, it takes a permanent and cumulative 1 penalty to the AC it offers.\
      \ Armor reduced to an AC of 10 or a shield that drops to a +0 bonus is destroyed.\
      \ If the object touched is a held metal weapon, it rusts as described in Barbatos's\
      \ Rust Monster Cloak trait."
    "name": "Cloak Sweep"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/barbatos-imr.webp"
```
^statblock