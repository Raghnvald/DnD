---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Altisaur
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/13
  - Monster/Typ/Monstrosität/dinosaur
  - Quelle/5e/bgg
aliases:
  - Altisaur
---
# [Altisaur](3-Mechanics\CLI\bestiary\monstrosity/altisaur-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 129*  

The altisaur is a titanic sauropod often likened to a walking mountain, with craggy spines, patterns of elemental energy that glow in its hide like streams of lava, and eight massive legs the size of ancient trees. It creates gullies where its tail drags along the ground. Clouds often seem to gather around its head, which can reach as high as 150 feet off the ground.

## Dinosaurs

When Annam's children first began to populate the worlds of the Material Plane, the All-Father created behemoth dinosaurs to live alongside them as companions. The primeval magic used to create the dinosaurs still thrums through their being and manifests in colorful, scar-like lines on their towering bodies. Some of these ancient dinosaurs persist in timeless jungles, hidden enclaves, and other lands untouched by the rest of the world.

```statblock
"name": "Altisaur (BGG)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "dinosaur"
"alignment": "Unaligned"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "198"
"hit_dice": "12d20 + 72"
"modifier": !!int "-2"
"stats":
  - !!int "28"
  - !!int "6"
  - !!int "23"
  - !!int "3"
  - !!int "12"
  - !!int "7"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
"senses": "passive Perception 21"
"languages": ""
"cr": "13"
"traits":
  - "desc": "The altisaur has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The altisaur makes one Stomp attack and one Tail attack. The altisaur\
      \ can't make both attacks against the same target."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:* 33\
      \ (7d6 + 9) bludgeoning damage. If the target is a Huge or smaller creature,\
      \ it must succeed on a DC 22 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Stomp"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 20 ft., one target. *Hit:* 45\
      \ (8d8 + 9) bludgeoning damage, and the target is pushed up to 20 feet horizontally\
      \ from the altisaur."
    "name": "Tail"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/altisaur-bgg.webp"
```
^statblock