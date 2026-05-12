---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mtf
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/environment/coastal
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/tortle
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tortle"
---
# [Tortle](3-Mechanics/CLI/bestiary/humanoid/tortle-mtf.md)
*Source: Mordenkainen's Tome of Foes p. 242, The Tortle Package p. 23*  

## Tortles

Tortles are omnivorous, turtle-like humanoids with shells that cover most of their bodies. Tortles have a saying: "We wear our homes on our backs." Consequently, tortles feel little need to stay put for long.

An adult tortle stands about 6 feet tall and weighs between 450 and 500 pounds. Males and females are nearly identical in size and appearance.

## Temporary Towns

A tortle settlement is primarily used as a kind of moot, where tortles can socialize with one another and trade with strangers. Tortles don't regard these settlements as places worth defending with their lives, and they abandon a settlement when it no longer serves their needs.

## A Life of Wandering

Most tortles like to see how other creatures live and discover new customs. The urge to procreate doesn't kick in until the end of a tortle's life, and a tortle can spend decades away from its native land without feeling homesick.

```statblock
"name": "Tortle (MTF)"
"size": "Medium"
"type": "humanoid"
"subtype": "tortle"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "12"
  - !!int "11"
  - !!int "13"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+3"
"gear":
  - "[light crossbow](3-Mechanics/CLI/items/light-crossbow-xphb.md)"
  - "[quarterstaff](3-Mechanics/CLI/items/quarterstaff-xphb.md)"
"senses": "passive Perception 11"
"languages": "Aquan, Common"
"cr": "1/4"
"traits":
  - "desc": "The tortle can hold its breath for 1 hour."
    "name": "Hold Breath"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) slashing damage."
    "name": "Claws"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage, or 6 (1d8 + 2) bludgeoning damage if used\
      \ with two hands."
    "name": "Quarterstaff"
  - "desc": "*Ranged Weapon Attack:* +2 to hit, range 80/320 ft., one target. *Hit:*\
      \ 4 (1d8) piercing damage."
    "name": "Light Crossbow"
  - "desc": "The tortle withdraws into its shell. Until it emerges, it gains a +4\
      \ bonus to AC and has advantage on Strength and Constitution saving throws.\
      \ While in its shell, the tortle is [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
      \ its speed is 0 and can't increase, it has disadvantage on Dexterity saving\
      \ throws, it can't take reactions, and the only action it can take is a bonus\
      \ action to emerge."
    "name": "Shell Defense"
"source":
  - "MTF"
  - "TTP"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/tortle-mtf.webp"
```
^statblock

## Environment

coastal