---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psd
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Homarid"
---
# [Homarid](3-Mechanics/CLI/bestiary/monstrosity/homarid-psd.md)
*Source: Plane Shift: Dominaria p. 15*  

The merfolk of Vodalia have waged bitter war for generations against the cryptic, cold-loving crustacean race of [homarids](3-Mechanics/CLI/bestiary/monstrosity/homarid-psd.md). The surface ocean waters have become too warm for the homarids in recent times, but in the years following the Brothers' War, as a global ice age settled over Dominaria, the homarids swarmed to the surface and nearly unraveled the fabric of the first Vodalian Empire. Even now, these creatures teem in the deep, frigid trenches to the west of the Voda Sea.

## Genocidal Foe

Homarids don't seem to understand any language other than their own—and might have only the barest suspicion that the sounds made by other creatures can communicate meaning at all. In their minds, they are the most advanced species on Dominaria, and all others are effectively animals. In the Homarid Wars that coincided with the start of the ice age, the homarids treated their merfolk enemies like cattle, to be slain and then tossed into spawning beds to provide food for homarid hatchlings. However, later historical revision tried to portray the expansionist homarids as victims of the merfolk Empress Galina's aggression.

## Offshoots

A variety of homarid more suited to warm water, called viscerids, lives in less frigid seas, particularly around Yavimaya.

```statblock
"name": "Homarid (PSD)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "-1"
"stats":
  - !!int "13"
  - !!int "8"
  - !!int "13"
  - !!int "9"
  - !!int "14"
  - !!int "10"
"speed": "20 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Homarid"
"cr": "1"
"traits":
  - "desc": "The homarid can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The homarid makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d8 + 1) slashing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 11). The homarid has two claws, each of which can grapple only\
      \ one target."
    "name": "Claw"
"source":
  - "PSD"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/homarid-psd.webp"
```
^statblock