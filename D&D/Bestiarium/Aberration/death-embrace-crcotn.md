---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Death Embrace
Kategorie: Aberration
Größe: Riesig
HG: 11
Status: WIP
linter-yaml-title-alias: Death Embrace
tags:
  - Quelle/5e/crcotn
  - Monster/HG/11
  - Monster/Größe/Riesig
  - Monster/Typ/Aberration
aliases:
  - Death Embrace
status: WIP
---
# [Death Embrace](3-Mechanics/CLI/bestiary/aberration/death-embrace-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 197*  

Drifting through the dark waters of the Netherdeep, the death embrace is an ominous sight. Beneath its bell hangs a lacy, tendrilous mass that thrums with magic, surrounded by six 60-foot-long, barbed tentacles. The death embrace uses these tentacles to grasp and petrify its prey.

Despite its foreboding name, the death embrace is not an overly aggressive creature. It prefers to bide its time, using creatures it has caught in its tentacles as shields to absorb attacks.

```statblock
"name": "Death Embrace (CRCotN)"
"size": "Huge"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "147"
"hit_dice": "14d12 + 56"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "19"
  - !!int "6"
  - !!int "9"
  - !!int "4"
"speed": "0 ft., swim 20 ft."
"saves":
  - "strength": !!int "10"
  - "wisdom": !!int "3"
"condition_immunities": "exhaustion, paralyzed, petrified, prone"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 9"
"languages": ""
"cr": "11"
"traits":
  - "desc": "Any creature that starts its turn in the death embrace's space must make\
      \ a DC 16 Constitution saving throw. On a failed saving throw, the creature\
      \ is restrained. A creature restrained in this way must repeat the saving throw\
      \ at the end of its next turn, becoming petrified on a failed saving throw or\
      \ ending the effect on a successful one. The petrified condition lasts until\
      \ the effect is ended by a greater restoration spell or similar magic."
    "name": "Petrifying Tendrils"
  - "desc": "At the start of each of its turns, the death embrace can pull each creature\
      \ it is grappling up to 20 feet toward it (no action required)."
    "name": "Reel"
  - "desc": "The death embrace can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "The death embrace makes two Tentacle attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 60 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) piercing damage plus 11 (2d10) psychic damage. If the target\
      \ is Large or smaller, it is also grappled (escape DC 16). The death embrace\
      \ has six tentacles, each of which can grapple one target."
    "name": "Tentacle"
"reactions":
  - "desc": "When the death embrace is hit by an attack, one creature the death embrace\
      \ is grappling (chosen by the death embrace) takes the damage instead."
    "name": "Body Shield"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/aberration/token/death-embrace-crcotn.webp"
```
^statblock