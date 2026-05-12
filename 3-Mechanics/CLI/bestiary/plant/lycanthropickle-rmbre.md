---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/rmbre
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lycanthropickle"
---
# [Lycanthropickle](3-Mechanics/CLI/bestiary/plant/lycanthropickle-rmbre.md)
*Source: The Lost Dungeon of Rickedness: Big Rick Energy p. 11*  

> [!note] Curse of Lycanthropickling
> 
> A humanoid creature has a 20 percent chance to be afflicted with the curse of lycanthropickling after being wounded by a lycanthropickle. The curse lasts for 3 days. Each long rest the creature spends in a vat or jar of pickling brine prolongs the curse by 1 day.
> 
> A lycanthropickle can either resist its curse or embrace it. By resisting the curse, a lycanthropickle retains its normal alignment and personality while in humanoid form. It lives its boring life as it always has, burying deep its raging, murderous urges just like the rest of us.
> 
> Some individuals see little point in fighting the curse and accept what they are. They can assume pickle form or hybrid form at will. Most lycanthropickles that embrace their briny natures succumb to bloodlust, becoming evil, opportunistic creatures that prey on the weak.
> 
> In hybrid form, a lycanthropickle has the same statistics as a twig blight with the altered ability noted here.
> 
> In pickle form, a lycanthropickle has no statistics and is indistinguishable from a pickle... because it's a pickle.
^curse-of-lycanthropickling

```statblock
"name": "Lycanthropickle (RMBRE)"
"size": "Small"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "4"
"hit_dice": "1d6 + 1"
"modifier": !!int "1"
"stats":
  - !!int "6"
  - !!int "13"
  - !!int "12"
  - !!int "4"
  - !!int "8"
  - !!int "3"
"speed": "20 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"damage_vulnerabilities": "fire"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (blind\
  \ beyond this radius), passive Perception 9"
"languages": "understands Common but can't speak"
"cr": "1/8"
"traits":
  - "desc": "While the lycanthropickle remains motionless, it is indistinguishable\
      \ from a pickle."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d4 + 1) piercing damage."
    "name": "Claws"
"source":
  - "RMBRE"
"image": "3-Mechanics/CLI/bestiary/plant/token/lycanthropickle-rmbre.webp"
```
^statblock