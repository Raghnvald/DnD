---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shade"
---
# [Shade](3-Mechanics/CLI/bestiary/undead/shade-psz.md)
*Source: Plane Shift: Zendikar p. 28*  

Magic fueled by black mana can alter the natural cycle of life and death. Whether wielded by mortal wizards or demons, or simply an environmental manifestation of black mana's flow through the land, such magic can trap spirits between the realm of the living and the mysterious fate of the dead. These ghostly undead are as destructive and hateful as the magic that calls them into being. Zendikar's shades and wraiths can be represented by the [shadows](3-Mechanics/CLI/bestiary/undead/shadow.md) and [wraiths](3-Mechanics/CLI/bestiary/undead/wraith.md) in the Monster Manual.

Not all spirits are created with black mana, however, and not all are malevolent. The spirits of the dead sometimes linger in the world to protect their kin or communities, or to stand guard over sacred or important sites. These spirits can be dangerous, but they are not usually malicious. Both the kor and the Mul Daya elves remain in communion with the spirits of their dead kindred, entreating them for wisdom and protection. Such spirits are best described as the [ghosts](3-Mechanics/CLI/bestiary/undead/ghost.md) in the Monster Manual.

```statblock
"name": "Shade (PSZ)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "13"
  - !!int "6"
  - !!int "10"
  - !!int "8"
"speed": "40 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_vulnerabilities": "radiant"
"damage_resistances": "acid; cold; fire; lightning; thunder; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The shadow can move through a space as narrow as 1 inch wide without\
      \ squeezing."
    "name": "Amorphous"
  - "desc": "While in dim light or darkness, the shadow can take the [Hide](3-Mechanics/CLI/rules/actions.md#Hide)\
      \ action as a bonus action. Its stealth bonus is also improved to +6."
    "name": "Shadow Stealth"
  - "desc": "While in sunlight, the shadow has disadvantage on attack rolls, ability\
      \ checks, and saving throws."
    "name": "Sunlight Weakness"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one creature. *Hit:*\
      \ 9 (2d6 + 2) necrotic damage, and the target's Strength score is reduced\
      \ by 1d4. The target dies if this reduces its Strength to 0. Otherwise, the\
      \ reduction lasts until the target finishes a short or long rest.\n\nIf a non-evil\
      \ humanoid dies from this attack, a new [shadow](3-Mechanics/CLI/bestiary/undead/shadow.md)\
      \ rises from the corpse 1d4 hours later."
    "name": "Strength Drain"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/undead/token/shade-psz.webp"
```
^statblock