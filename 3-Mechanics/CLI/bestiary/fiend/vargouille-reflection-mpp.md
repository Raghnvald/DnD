---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vargouille Reflection"
---
# [Vargouille Reflection](3-Mechanics/CLI/bestiary/fiend/vargouille-reflection-mpp.md)
*Source: Morte's Planar Parade p. 52*  

Vargouilles are flying Fiends that resemble disembodied Humanoid heads with wings. While most vargouilles roam the planes to curse Humanoids and create more vargouilles, a variant known as the vargouille reflection resides in Undersigil. When a vargouille reflection spots a Humanoid target, it takes on that creature's visage, terrifying that creature by appearing as its own disembodied head.

```statblock
"name": "Vargouille Reflection (MPP)"
"size": "Tiny"
"type": "fiend"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d4 + 10"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "15"
  - !!int "14"
  - !!int "6"
  - !!int "10"
  - !!int "2"
"speed": "5 ft., fly 40 ft."
"damage_resistances": "cold, fire, lightning, psychic"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "understands Abyssal, Infernal, and any languages it knew before becoming\
  \ a vargouille, but it can't speak"
"cr": "1"
"traits":
  - "desc": "The vargouille has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) piercing damage plus 10 (3d6) psychic damage."
    "name": "Bite"
  - "desc": "The vargouille targets one Humanoid within 5 feet of itself that has\
      \ the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated) condition.\
      \ The target must succeed on a DC 12 Charisma saving throw or become cursed.\
      \ The cursed target's Charisma decreases by 1 after each hour, as its head takes\
      \ on fiendish aspects, and its Charisma can't increase. The curse doesn't advance\
      \ while the target is in sunlight or the area of a [daylight](3-Mechanics/CLI/spells/daylight.md)\
      \ spell. When the cursed target's Charisma becomes 2, the target dies, and its\
      \ head tears from its body and becomes a new vargouille reflection. Casting\
      \ remove curse, greater restoration, or a similar spell on the target before\
      \ the transformation is complete ends the curse and restores the target's Charisma."
    "name": "Abyssal Curse"
  - "desc": "The vargouille's head mimics that of a Humanoid the vargouille can see\
      \ within 120 feet of itself. The target must succeed on a DC 12 Wisdom saving\
      \ throw or take 10 (3d6) psychic damage and have the [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ condition for 1 hour or until the vargouille loses [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). If the target's saving throw is successful or if the effect ends\
      \ on it, the target is immune to the Horrific Reflection of all vargouille reflections\
      \ for 1 hour."
    "name": "Horrific Reflection (Recharge 5-6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/fiend/token/vargouille-reflection-mpp.webp"
```
^statblock