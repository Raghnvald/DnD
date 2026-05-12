---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/sdw
- ttrpg-cli/monster/cr/
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Expert"
---
# [Expert](3-Mechanics/CLI/bestiary/humanoid/expert-sdw.md)
*Source: Sleeping Dragon's Wake*  

```statblock
"name": "Expert (SDW)"
"size": "Medium"
"type": "humanoid"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "8"
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+12"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+6"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
  - "name": "[Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+8"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+12"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
  - "[shortbow](3-Mechanics/CLI/items/shortbow-xphb.md)"
  - "[shortsword](3-Mechanics/CLI/items/shortsword-xphb.md)"
"senses": "passive Perception 10"
"languages": "Common, plus one of your choice"
"traits":
  - "desc": "The expert can take the Help action as a bonus action, and the creature\
      \ who receives the help gains a 1d6 bonus to the d20 roll. If that roll\
      \ is an attack roll, the creature can forgo adding the bonus to it, and then\
      \ if the attack hits, the creature can add the bonus to the attack's damage\
      \ roll against one target."
    "name": "Helpful"
  - "desc": "When the expert is not [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and subjected to an effect that allows it to make a Dexterity saving throw\
      \ to take only half damage, it instead takes no damage if it succeeds on the\
      \ saving throw, and only half damage if it failed."
    "name": "Evasion"
  - "desc": "The expert has thieves' tools and a musical instrument."
    "name": "Tools"
"actions":
  - "desc": "The expert can attack twice, instead of once, whenever it takes the attack\
      \ action on its turn."
    "name": "Extra Attack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) piercing damage."
    "name": "Shortsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +8 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d4 + 4) piercing damage."
    "name": "Dagger"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 80/320 ft., one target. *Hit:*\
      \ 7 (1d6 + 4) piercing damage."
    "name": "Shortbow"
"source":
  - "SDW"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/expert-sdw.webp"
```
^statblock