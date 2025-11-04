---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/mcv1sc
- Monster/cr/1-8
- Monster/Größe/Mittelgroß
- Monster/Typ/Pflanze
statblock: inline
statblock-link: "#^statblock"
aliases:
- Gadabout
---
# [Gadabout](3-Mechanics\CLI\bestiary\plant/gadabout-mcv1sc.md)
*Source: Monstrous Compendium Volume 1: Spelljammer Creatures p. 8*  

Gadabouts are gentle, winged creatures that can be used as personal conveyances for short-distance travel across the airless void of Wildspace. A gadabout wraps its branches around a Humanoid creature, spreads its butterfly wings, and allows its wearer to fly through space in a continuously refreshed air envelope. The gadabout's leaves even provide a nourishing syrup that its wearer can consume in the absence of other food and water. One Humanoid can survive on these leaves for up to sixty days.

Gadabouts require sunlight and water to survive. A healthy specimen can live for 25 years. Although its preferred mode of travel is flight, a gadabout can creep slowly along the ground as well.

Elves are the only Humanoids to date who know how to grow gadabouts. Since gadabouts don't generate seeds, each one is a valuable commodity. Mercane and dohwar merchants who come into possession of a healthy gadabout might sell it for 2,500 gp or more.

```statblock
"name": "Gadabout (MCV1SC)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "11"
"ac_class": "natural armor"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "0"
"stats":
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "1"
  - !!int "6"
  - !!int "1"
"speed": "10 ft., fly 60 ft. (hover)"
"damage_vulnerabilities": "fire"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, paralyzed,\
  \ petrified"
"senses": "blindsight 10 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "1/8"
"traits":
  - "desc": "If it has at least 1 hit point, the gadabout can generate an air envelope\
      \ around itself when in a vacuum. This air envelope can sustain the gadabout\
      \ and one other creature in its space indefinitely."
    "name": "Air Envelope"
  - "desc": "The gadabout doesn't require food or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The gadabout makes two Branch attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4\
      \ + 1) slashing damage."
    "name": "Branch"
  - "desc": "The gadabout enters the space of a willing Medium or Small creature within\
      \ 5 feet of itself and gently wraps its branches around the target. The target\
      \ is grappled (escape DC 0). Any attempt by the target to escape the grapple\
      \ causes the gadabout to use its reaction to move into the nearest unoccupied\
      \ space. While grappled by the gadabout, the target determines where the gadabout\
      \ moves on the gadabout's turns and accompanies the gadabout wherever it goes."
    "name": "Wrap"
"source":
  - "MCV1SC"
"image": "/3-Mechanics/CLI/bestiary/plant/token/gadabout-mcv1sc.webp"
```
^statblock