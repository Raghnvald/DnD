---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/tftyp
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kelpie"
---
# [Kelpie](3-Mechanics/CLI/bestiary/plant/kelpie-tftyp.md)
*Source: Tales from the Yawning Portal p. 238*  

```statblock
"name": "Kelpie (TftYP)"
"size": "Medium"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "67"
"hit_dice": "9d8 + 27"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "7"
  - !!int "12"
  - !!int "10"
"speed": "10 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "fire, bludgeoning, piercing"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
  \ [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 13"
"languages": "Common, Sylvan"
"cr": "4"
"traits":
  - "desc": "The kelpie can breathe air and water."
    "name": "Amphibious"
  - "desc": "The kelpie can use its action to reshape its body into the form of a\
      \ humanoid or beast that is Small, Medium, or Large. Its statistics are otherwise\
      \ unchanged. The disguise is convincing, unless the kelpie is in bright light\
      \ or the viewer is within 30 feet of it, in which case the seams between the\
      \ seaweed strands are visible. The kelpie returns to its true form if takes\
      \ a bonus action to do so or if it dies."
    "name": "Seaweed Shape"
  - "desc": "While the kelpie remains motionless in its true form, it is indistinguishable\
      \ from normal seaweed."
    "name": "False Appearance"
"actions":
  - "desc": "The kelpie makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one target. *Hit:*\
      \ 11 (2d8 + 2) piercing damage. If the target is a Medium or smaller creature,\
      \ it is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) (escape DC\
      \ 12)."
    "name": "Slam"
  - "desc": "The kelpie chooses one humanoid it can see within 150 feet of it. If\
      \ the target can see the kelpie, the target must succeed on a DC 11 Wisdom saving\
      \ throw or be magically [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ while the kelpie maintains [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration),\
      \ up to 10 minutes (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). The [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) target\
      \ is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated), and\
      \ instead of holding its breath underwater, it tries to breathe normally and\
      \ immediately runs out of breath, unless it can breathe water. If the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ target is more than 5 feet away from the kelpie, the target must move on its\
      \ turn toward the kelpie by the most direct route, trying to get within 5 feet.\
      \ It doesn't avoid opportunity attacks.\n\nBefore moving into damaging terrain,\
      \ such as lava or a pit, and whenever it takes damage from a source other than\
      \ the kelpie or drowning, the target can repeat the saving throw. A [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ target can also repeat the saving throw at the end of each of its turns. If\
      \ the saving throw is successful, the effect ends on it.\n\nA target that successfully\
      \ saves is immune to this kelpie's hypnosis for the next 24 hours."
    "name": "Drowning Hypnosis"
"source":
  - "TftYP"
"image": "3-Mechanics/CLI/bestiary/plant/token/kelpie-tftyp.webp"
```
^statblock