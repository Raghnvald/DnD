---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Equinal Guardinal"
---
# [Equinal Guardinal](3-Mechanics/CLI/bestiary/celestial/equinal-guardinal-mpp.md)
*Source: Morte's Planar Parade p. 33*  

The horselike equinals are among the strongest of the guardinals. Equinals have long faces and crested manes, and their powerful, hocked legs carry them over great distances. These good-natured, boisterous Celestials boast their might in contests of strength and rarely back down from a challenge. Tough and courageous, they use their iron-hard fists to pound evil to a pulp. Equinals can also bellow a mighty shout that stops their foes in their tracks.

## Guardinals

Nomadic and peaceful, guardinals are animalistic Celestials who hail from Elysium. Guardinals resemble Humanoids with bestial traits. In their daily interactions, guardinals embody the beauty, calm, and righteousness of their home plane. Guardinals can be found throughout the Outlands, especially in Ecstasy, the gate-town to Elysium, and in Faunel, the gate-town to the Beastlands.

While guardinals are usually friendly and slow to anger, their supernatural virtue puts them at odds with the evil beings of the Lower Planes. Guardinals abhor wickedness and strike out against injustice and villainy without hesitation, determined to eradicate forces that threaten beauty and peace.

```statblock
"name": "Equinal Guardinal (MPP)"
"size": "Large"
"type": "celestial"
"alignment": "typically  Neutral Good"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "93"
"hit_dice": "11d10 + 33"
"modifier": !!int "3"
"stats":
  - !!int "23"
  - !!int "16"
  - !!int "17"
  - !!int "15"
  - !!int "14"
  - !!int "12"
"speed": "50 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+5"
"damage_resistances": "radiant"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "passive Perception 15"
"languages": "Celestial, Common"
"cr": "6"
"traits":
  - "desc": "If the equinal moves at least 30 feet in a straight line toward a creature\
      \ and ends within 5 feet of it, that creature must succeed on a DC 17 Strength\
      \ saving throw or take 14 (4d6) bludgeoning damage and have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Headfirst Charge"
"actions":
  - "desc": "The equinal makes two Fist attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d6 + 6) bludgeoning damage plus 3 (1d6) radiant damage."
    "name": "Fist"
  - "desc": "*Ranged Weapon Attack:* +9 to hit, range 60/180 ft., one target. *Hit:*\
      \ 22 (3d10 + 6) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 17 Strength saving throw or have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Rock"
  - "desc": "The equinal lets out a booming shout. Each creature within 30 feet of\
      \ the equinal must succeed on a DC 14 Constitution saving throw or have the\
      \ [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) condition until the\
      \ end of the equinal's next turn."
    "name": "Shout (Recharge 6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/equinal-guardinal-mpp.webp"
```
^statblock