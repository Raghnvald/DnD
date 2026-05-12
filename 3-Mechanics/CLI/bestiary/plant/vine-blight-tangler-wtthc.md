---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vine Blight Tangler"
---
# [Vine Blight Tangler](3-Mechanics/CLI/bestiary/plant/vine-blight-tangler-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Blights are malicious plants that sprout from deep-rooted evil. Their gnarled forms twist with fearsome features suggestive of human limbs and vicious maws. Blights lurk in ambush amid mundane vegetation and lash out at non-Plant creatures.

Vine blights resemble humans wrapped in vines common to the areas in which they grow, from hairy ivy vines to flowering kudzu. They can cause plants to burst from the ground around themselves and entangle nearby foes.

```statblock
"name": "Vine Blight Tangler (WttHC)"
"size": "Medium"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "19"
"hit_dice": "3d8"
"modifier": !!int "-1"
"stats":
  - !!int "15"
  - !!int "8"
  - !!int "14"
  - !!int "5"
  - !!int "10"
  - !!int "3"
"speed": "20 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+1"
"condition_immunities": "[deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., passive\
  \ Perception 10"
"languages": "Common"
"cr": "1/2"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 10 ft. *Hit:* 1d10 + 2 Bludgeoning\
      \ damage. If the target is a Large or smaller creature, it has the [Grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 12) from one of three vines."
    "name": "Constricting Vine"
  - "desc": "Grasping vines momentarily appear on each enemy in a 10-foot-radius [Sphere](3-Mechanics/CLI/rules/variant-rules/sphere-area-of-effect-xphb.md)\
      \ centered on a point of the blight's choice within 60 feet of it. Each target\
      \ must succeed on a DC 12 Strength saving throw or have the [Restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition until the start of the blight's next turn."
    "name": "Entangling Vines (Recharge 5-6)"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/plant/token/vine-blight-tangler-wtthc.webp"
```
^statblock