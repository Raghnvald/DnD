---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/cm
- new/monster/cr/1-2
- new/monster/size/small
- new/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kiddywidget
---
# [Kiddywidget](3-Mechanics\CLI\bestiary\construct/kiddywidget-cm.md)
*Source: Candlekeep Mysteries p. 136*  

A skitterwidget that gives birth to a kiddywidget can't procreate for `dice:3d6|noform|noparens|avg` (`3d6`) days afterward. Still, given that skitterwidgets are constructs with no natural life span, there is no telling how many kiddywidgets a pair of skitterwidgets can produce.

```statblock
"name": "Kiddywidget (CM)"
"size": "Small"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "15"
"hit_dice": "2d6 + 8"
"modifier": !!int "2"
"stats":
  - !!int "6"
  - !!int "14"
  - !!int "18"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "lightning, poison"
"condition_immunities": "blinded, deafened, exhaustion, paralyzed, petrified, poisoned"
"senses": "darkvision 60, passive Perception 10"
"languages": "Skitterwidget"
"cr": "1/2"
"traits":
  - "desc": "The kiddywidget doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The kiddywidget makes two attacks: one with its bite and one with its\
      \ tail."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage. If the target is a creature, it is grappled by the kiddywidget\
      \ (escape DC 8)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4 (1d4\
      \ + 2) piercing damage plus 2 (1d4) lightning damage."
    "name": "Tail"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/construct/token/kiddywidget-cm.webp"
```
^statblock