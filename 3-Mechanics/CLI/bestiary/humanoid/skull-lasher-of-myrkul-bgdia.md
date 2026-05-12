---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgdia
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Skull Lasher of Myrkul"
---
# [Skull Lasher of Myrkul](3-Mechanics/CLI/bestiary/humanoid/skull-lasher-of-myrkul-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 234*  

Those who follow Myrkul are either wizards or those who seek to master the necromantic arts.

## Delvers into Lore

Cultists of Myrkul study rituals that allow them to force the souls of the dead into service, compelling them to answer questions and share forgotten lore. They seek out arcane secrets in ancient ruins, and attempt to steal spellbooks and other tomes from wizards outside of the cult.

## Cult Ranks

A follower of Myrkul wields a flail that has a skull replacing the normal flail's striking head. Necromites are initiates who have not yet mastered arcane magic and rely on their flails in battle. Skull lashers are spellcasters who use magic to augment their combat abilities. The Masters of Souls delve deep into Myrkul's secrets, allowing them to animate the dead and perform other grave magic.

```statblock
"name": "Skull Lasher of Myrkul (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "32"
"hit_dice": "5d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "15"
  - !!int "16"
  - !!int "13"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Arcana"
    "desc": "+5"
  - "name": "Religion"
    "desc": "+5"
"senses": "passive Perception 11"
"languages": "Abyssal, Common, Infernal"
"cr": "1"
"traits":
  - "desc": "The skull lasher is a 3rd-level spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 13, +5 to hit with spell attacks). It has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** mage hand, message, prestidigitation\n\
      \n**1st level (4 slots):** detect magic, protection from evil and good, ray\
      \ of sickness (see \"Actions\" below), shield\n\n**2nd level (2 slots):** darkness,\
      \ misty step"
    "name": "Spellcasting"
"actions":
  - "desc": "The skull lasher makes two attacks with its flail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d8) bludgeoning damage plus 7 (2d6) necrotic damage, and the target\
      \ has disadvantage on all saving throws until the end of the skull lasher's\
      \ next turn."
    "name": "Iron Skull Flail"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 60 ft., one creature. *Hit:*\
      \ 9 (2d8) poison damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be poisoned until the end of the skull lasher's next turn.\
      \ If the skull lasher casts this spell using a spell slot of 2nd level or higher,\
      \ the damage increases by 1d8 for each slot level above 1st."
    "name": "Ray of Sickness (1st-Level Spell; Requires a Spell Slot)"
"source":
  - "BGDIA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/skull-lasher-of-myrkul-bgdia.webp"
```
^statblock