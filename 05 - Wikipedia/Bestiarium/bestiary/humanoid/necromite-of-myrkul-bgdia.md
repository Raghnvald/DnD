---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/HG/1-2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Necromite of Myrkul
---
# [Necromite of Myrkul](3-Mechanics\CLI\bestiary\humanoid/necromite-of-myrkul-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 234*  

Those who follow Myrkul are either wizards or those who seek to master the necromantic arts.

## Delvers into Lore

Cultists of Myrkul study rituals that allow them to force the souls of the dead into service, compelling them to answer questions and share forgotten lore. They seek out arcane secrets in ancient ruins, and attempt to steal spellbooks and other tomes from wizards outside of the cult.

## Cult Ranks

A follower of Myrkul wields a flail that has a skull replacing the normal flail's striking head. Necromites are initiates who have not yet mastered arcane magic and rely on their flails in battle. Skull lashers are spellcasters who use magic to augment their combat abilities. The Masters of Souls delve deep into Myrkul's secrets, allowing them to animate the dead and perform other grave magic.

```statblock
"name": "Necromite of Myrkul (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "13"
"hit_dice": "2d8 + 4"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "13"
  - !!int "15"
  - !!int "16"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Religion](/3-Mechanics/CLI/skills.md#Religion)"
    "desc": "+5"
"senses": "passive Perception 10"
"languages": "Abyssal, Common, Infernal"
"cr": "1/2"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 4 (1d8)\
      \ bludgeoning damage."
    "name": "Skull Flail"
  - "desc": "*Ranged Spell Attack:* +5 to hit, range 90 ft., one target. *Hit:* 8\
      \ (2d4 + 3) necrotic damage."
    "name": "Claws of the Grave"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/necromite-of-myrkul-bgdia.webp"
```
^statblock