---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sunfly"
---
# [Sunfly](3-Mechanics/CLI/bestiary/celestial/sunfly-mpp.md)
*Source: Morte's Planar Parade p. 47*  

Sunflies are whimsical, buzzing inhabitants of the Outer Planes. They travel widely and are important indicators of the health of the realms in which they reside; when sunflies struggle, so do the places they inhabit. Sunflies have stingers that they use to inject natural toxins into other creatures. Planar magic can alter a sunfly's toxin so that its effect is different depending on which Outer Plane the sunfly is on.

Many inhabitants of the planes have strong feelings about sunflies, viewing them as loathsome pests or adorable pets. Sunflies in Sigil are often the pets of doting, highly protective owners.

```statblock
"name": "Sunfly (MPP)"
"size": "Tiny"
"type": "celestial"
"alignment": "typically  Chaotic Good"
"ac": !!int "13"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "3"
"stats":
  - !!int "4"
  - !!int "17"
  - !!int "10"
  - !!int "4"
  - !!int "10"
  - !!int "6"
"speed": "10 ft., fly 40 ft."
"senses": "passive Perception 10"
"languages": "understands Celestial but can't speak"
"cr": "0"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 2\
      \ (1d4) piercing damage. Additionally, if the sunfly is on an Outer Plane,\
      \ it injects the target with a toxin, the effect of which is determined by the\
      \ sunfly's location:"
    "name": "Sting"
  - "desc": "The target sheds bright light in a 5-foot radius until the end of its\
      \ next turn."
    "name": "Upper Plane"
  - "desc": "If the target is [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell or similar effect, it makes the Constitution saving throw with\
      \ disadvantage to maintain its [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)."
    "name": "Neutral Plane"
  - "desc": "The target's speed is reduced by 5 feet until the end of its next turn."
    "name": "Lower Plane"
"bonus_actions":
  - "desc": "The sunfly sheds bright light in a 5-foot radius and dim light for an\
      \ additional 5 feet, or it uses a bonus action to extinguish the light."
    "name": "Illumination"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/sunfly-mpp.webp"
```
^statblock