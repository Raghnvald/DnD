---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Regisaur
Status: WIP
linter-yaml-title-alias: Regisaur
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/14
  - Monster/Typ/Monstrosität/dinosaur
  - Quelle/5e/bgg
aliases:
  - Regisaur
---
# [Regisaur](3-Mechanics\CLI\bestiary\monstrosity/regisaur-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 130*  

Aptly called "the ruler of dinosaurs," a regisaur is an enormous predator large enough to swallow a giant whole. Fiery veins of elemental energy course through its skin and glow in its eyes and nostrils.

## Dinosaurs

When Annam's children first began to populate the worlds of the Material Plane, the All-Father created behemoth dinosaurs to live alongside them as companions. The primeval magic used to create the dinosaurs still thrums through their being and manifests in colorful, scar-like lines on their towering bodies. Some of these ancient dinosaurs persist in timeless jungles, hidden enclaves, and other lands untouched by the rest of the world.

```statblock
"name": "Regisaur (BGG)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "181"
"hit_dice": "11d20 + 66"
"modifier": !!int "-1"
"stats":
  - !!int "27"
  - !!int "8"
  - !!int "23"
  - !!int "4"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"senses": "passive Perception 11"
"languages": ""
"cr": "14"
"traits":
  - "desc": "The regisaur has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The regisaur makes one Bite attack and one Tail attack. The regisaur\
      \ can't target the same creature with both attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target. *Hit:* 47\
      \ (6d12 + 8) piercing damage, and the target has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ condition (escape DC 18). Until this grapple ends, the target has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition, and the regisaur can't Bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 20 ft., one target. *Hit:* 26\
      \ (4d8 + 8) bludgeoning damage."
    "name": "Tail"
"bonus_actions":
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one Huge or smaller creature\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) by the regisaur. *Hit:*\
      \ The regisaur swallows the target, and the grapple ends. A swallowed creature\
      \ has the [blinded](/3-Mechanics/CLI/conditions.md#Blinded) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ conditions, it has total cover against attacks and other effects outside the\
      \ regisaur, and it takes 7 (2d6) acid damage at the start of each of its turns.\
      \ The regisaur can have up to two creatures swallowed at a time.\n\nIf the regisaur\
      \ takes 25 damage or more on a single turn from a swallowed creature, the regisaur\
      \ must succeed on a DC 16 Constitution saving throw at the end of that turn\
      \ or regurgitate the creature, which falls in a space within 5 feet of the regisaur\
      \ and has the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition; the creature\
      \ no longer has the [blinded](/3-Mechanics/CLI/conditions.md#Blinded) and [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ conditions."
    "name": "Swallow"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/regisaur-bgg.webp"
```
^statblock