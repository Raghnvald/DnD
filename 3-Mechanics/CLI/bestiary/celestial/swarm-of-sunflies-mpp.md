---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Swarm of Sunflies"
---
# [Swarm of Sunflies](3-Mechanics/CLI/bestiary/celestial/swarm-of-sunflies-mpp.md)
*Source: Morte's Planar Parade p. 47*  

Sunflies are whimsical, buzzing inhabitants of the Outer Planes. They travel widely and are important indicators of the health of the realms in which they reside; when sunflies struggle, so do the places they inhabit. Sunflies have stingers that they use to inject natural toxins into other creatures. Planar magic can alter a sunfly's toxin so that its effect is different depending on which Outer Plane the sunfly is on.

Many inhabitants of the planes have strong feelings about sunflies, viewing them as loathsome pests or adorable pets. Sunflies in Sigil are often the pets of doting, highly protective owners.

```statblock
"name": "Swarm of Sunflies (MPP)"
"size": "Medium"
"type": "celestial"
"alignment": "typically  Chaotic Good"
"ac": !!int "13"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "3"
"stats":
  - !!int "6"
  - !!int "17"
  - !!int "10"
  - !!int "4"
  - !!int "10"
  - !!int "6"
"speed": "10 ft., fly 40 ft."
"senses": "passive Perception 10"
"languages": "understands Celestial but can't speak"
"cr": "1"
"traits":
  - "desc": "The swarm can occupy another creature's space and vice versa, and the\
      \ swarm can move through any opening large enough for a Tiny dragonfly. The\
      \ swarm can't regain hit points or gain temporary hit points."
    "name": "Swarm"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 0 ft., one creature in the\
      \ swarm's space. *Hit:* 10 (3d4 + 3) piercing damage, or 5 (1d4 + 3) piercing\
      \ damage if the swarm has half of its hit points or fewer. Additionally, if\
      \ the swarm is on an Outer Plane, it injects the target with a toxin, the effect\
      \ of which is determined by the swarm's location:"
    "name": "Stings"
  - "desc": "The target sheds bright light in a 5-foot radius until the end of its\
      \ next turn. During that time, the [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ condition has no effect on it."
    "name": "Upper Plane"
  - "desc": "If the target is [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell or similar effect, it loses its [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)."
    "name": "Neutral Plane"
  - "desc": "The target's speed is reduced by 10 feet until the end of its next turn."
    "name": "Lower Plane"
  - "desc": "The swarm shines its lights in a dazzling display. Each creature within\
      \ 15 feet of the swarm must succeed on a DC 10 Constitution saving throw or\
      \ have the [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned) condition\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success."
    "name": "Dazzling Lights (Recharge 6)"
"bonus_actions":
  - "desc": "The swarm sheds bright light in a 15-foot radius and dim light for an\
      \ additional 15 feet, or it uses a bonus action to extinguish the light."
    "name": "Illumination"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/celestial/token/swarm-of-sunflies-mpp.webp"
```
^statblock