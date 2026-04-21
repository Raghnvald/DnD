---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Aerosaur
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/10
  - Monster/Typ/Monstrosität/dinosaur
  - Quelle/5e/bgg
aliases:
  - Aerosaur
---
# [Aerosaur](3-Mechanics\CLI\bestiary\monstrosity/aerosaur-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 128*  

A pterosaur the size of the most ancient dragons, an aerosaur boasts a wingspan of nearly 200 feet. Elemental energy traces patterns like lightning across its scales, giving additional thunderous power to the beating of its enormous wings.

## Dinosaurs

When Annam's children first began to populate the worlds of the Material Plane, the All-Father created behemoth dinosaurs to live alongside them as companions. The primeval magic used to create the dinosaurs still thrums through their being and manifests in colorful, scar-like lines on their towering bodies. Some of these ancient dinosaurs persist in timeless jungles, hidden enclaves, and other lands untouched by the rest of the world.

```statblock
"name": "Aerosaur (BGG)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "155"
"hit_dice": "10d20 + 50"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "10"
  - !!int "21"
  - !!int "3"
  - !!int "10"
  - !!int "5"
"speed": "20 ft., fly 120 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"senses": "passive Perception 14"
"languages": ""
"cr": "10"
"traits":
  - "desc": "The aerosaur has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The aerosaur makes one Bite attack and one Talons attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 27\
      \ (3d12 + 8) piercing damage. If the target is a Huge or smaller creature, it\
      \ has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape\
      \ DC 18). Until this grapple ends, the target has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition, and the aerosaur can't Bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 24\
      \ (3d10 + 8) slashing damage."
    "name": "Talons"
  - "desc": "The aerosaur beats its wings, creating bursts of thunderous force. Each\
      \ creature within 10 feet of the aerosaur must make a DC 20 Strength saving\
      \ throw. On a failed save, a creature takes 38 (7d10) thunder damage, is pushed\
      \ up to 30 feet horizontally from the aerosaur, and has the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition. On a successful save, a creature takes half as much damage and\
      \ is pushed up to 15 feet horizontally from the aerosaur."
    "name": "Wing Gusts (Recharge 5-6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/aerosaur-bgg.webp"
```
^statblock