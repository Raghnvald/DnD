---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gremlin"
---
# [Gremlin](3-Mechanics/CLI/bestiary/beast/gremlin-psk.md)
*Source: Plane Shift: Kaladesh p. 26*  

Gremlins are tenacious scavengers with an insatiable appetite for aether. They are drawn to places with abundant supplies of aether, including laboratories and workshops, where they can destroy months of careful work in a matter of hours. A small infestation of gremlins can easily end an inventor's career—and in sufficient numbers, these creatures could obliterate the aether infrastructure of a city like Ghirapur. Although the Consulate has extensive programs to prevent and control gremlin infestations, it often seems as though the city of wonders is just one gremlin away from a large-scale blackout and complete shutdown.

Gremlins are small, hairless creatures with six legs and long snouts. Each leg is tipped with hard, dense claws that are perfect for slicing and shredding through rock and wood in natural environments—as well as metal and machinery in more urban areas. Gremlins can also use their claws to climb, to widen holes and tunnels, and to pull themselves through cramped spaces.

```statblock
"name": "Gremlin (PSK)"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "13"
  - !!int "13"
  - !!int "3"
  - !!int "13"
  - !!int "6"
"speed": "40 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "1/2"
"traits":
  - "desc": "The gremlin can pinpoint, by scent, the location of refined or unrefined\
      \ aether within 30 feet of it."
    "name": "Aether Scent"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d8 + 1) slashing damage."
    "name": "Claws"
  - "desc": "The gremlin drains aether from an aether-powered device it can see within\
      \ 5 feet of it. If the object isn't being worn or carried, the touch automatically\
      \ drains aether. If the object is being worn or carried by a creature, the creature\
      \ must succeed on a DC 11 Dexterity saving throw to keep it out of the gremlin's\
      \ reach.\n\nIf the aether-powered device grants any bonus (to attack rolls,\
      \ damage rolls, Armor Class, and so on), that bonus is reduced by 1. If the\
      \ device has charges, it loses 1 charge. Otherwise, it stops functioning for\
      \ 1 round. Left unhindered, a gremlin can completely destroy an aether-powered\
      \ device."
    "name": "Siphon"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/beast/token/gremlin-psk.webp"
```
^statblock