---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Hellenrae"
---
# [Hellenrae](3-Mechanics/CLI/bestiary/npc/hellenrae-pota.md)
*Source: Princes of the Apocalypse p. 198*  

The chief lieutenant of Marlos Urnrayle, Hellenrae lost her sight as a child. A bitter, angry orphan, she was taken in by a monastic order and trained to use her other senses to compensate. However, she took the monks' philosophy of self-denial and emptiness of mind to extremes, seeking to fill herself with the dark power she sensed sleeping in the earth and rock around her.

Hellenrae is a dour, unsmiling woman who habitually wears drab robes and a golden gargoyle mask with no eye holes. She despises weakness in any form. Therefore, she hates just about everybody, and barely tolerates the other Black Earth cultists.

```statblock
"name": "Hellenrae (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "16"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "4"
"stats":
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "10"
  - !!int "15"
  - !!int "13"
"speed": "50 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
"damage_immunities": "poison"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 15"
"languages": "Common, Terran"
"cr": "5"
"traits":
  - "desc": "If Hellenrae is subjected to an effect that allows her to make a Dexterity\
      \ saving throw to take only half damage, she instead takes no damage if she\
      \ succeeds on the saving throw, and only half damage if she fails."
    "name": "Evasion"
  - "desc": "When Hellenrae hits a target with a melee weapon attack, the target must\
      \ succeed on a DC 13 Constitution saving throw or be [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ until the end of Hellenrae's next turn."
    "name": "Stunning Strike (Recharge 5-6)"
  - "desc": "While Hellenrae is wearing no armor and wielding no shield, her AC includes\
      \ her Wisdom modifier."
    "name": "Unarmored Defense"
  - "desc": "While Hellenrae is wearing no armor and wielding no shield, her speed\
      \ increases by 20 feet (included in her speed)."
    "name": "Unarmored Movement"
"actions":
  - "desc": "Hellenrae makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d10 + 4) bludgeoning damage."
    "name": "Unarmed Strike"
"reactions":
  - "desc": "Hellenrae adds 3 to her AC against one melee or ranged weapon attack\
      \ that would hit her. To do so, she must be able to sense the attacker with\
      \ her blindsight. If the attack misses, Hellenrae can make one melee attack\
      \ against the attacker if it is within her reach."
    "name": "Parry and Counter"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/hellenrae-pota.webp"
```
^statblock