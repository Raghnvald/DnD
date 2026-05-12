---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Horrid Plant"
---
# [Horrid Plant](3-Mechanics/CLI/bestiary/plant/horrid-plant-qftis.md)
*Source: Quests from the Infinite Staircase p. 204*  

Horrid plants are a family of carnivorous vegetation found in bogs, damp heaths, jungles, and swamps. Some botanists theorize these plants are an invasive species from a faraway world. When still, horrid plants resemble ordinary (if vibrant) foliage.

## Horrid Plant Varieties

The most infamous varieties of horrid plant are dew drinkers, purple blossoms, and snapper saws.

### Dew Drinker

Dew drinkers resemble large cabbage plants until they unfurl their long, hair-tipped tendrils. Dew drinkers use these tendrils to drain the moisture and life force from their prey.

### Purple Blossom

The purple blossom is a treelike plant with cup-shaped purple flowers. Tubules within the plant's branches connect the flowers to reserves of acidic sap in the plant's trunk. Purple blossoms squirt this sap at prey through the flowers' pistils.

### Snapper Saw

Snapper saws resemble ordinary bushes and bear fragrant white berries during temperate seasons. Between encounters, the plant buries its weapons—wide, razor-sharp outer leaves—in the loose dirt around itself to catch unsuspecting prey off guard.

```statblock
"name": "Horrid Plant (QftIS)"
"size": "Large"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "6"
"hp": !!int "42"
"hit_dice": "5d10 + 15"
"modifier": !!int "-4"
"stats":
  - !!int "18"
  - !!int "3"
  - !!int "17"
  - !!int "1"
  - !!int "10"
  - !!int "1"
"speed": "5 ft."
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (can't\
  \ see beyond this radius), passive Perception 10"
"languages": ""
"cr": "4"
"traits":
  - "desc": "A horrid plant comes in one of three varieties (choose or roll a d6):\
      \ 1-2, dew drinker; 3-4, purple blossom; or 5-6, snapper saw. This form determines\
      \ certain traits in this stat block."
    "name": "Horrid Plant Varieties"
  - "desc": "If the horrid plant is motionless at the start of combat, it has advantage\
      \ on its initiative roll. Moreover, if a creature hasn't observed the horrid\
      \ plant move or act, that creature must succeed on a DC 18 Intelligence ([Nature](3-Mechanics/CLI/rules/skills.md#Nature))\
      \ check to discern that the horrid plant isn't an ordinary plant."
    "name": "False Appearance"
"actions":
  - "desc": "The horrid plant makes two Tendril attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 30 ft., one target. *Hit:*\
      \ 7 (2d6) bludgeoning damage. If the target is a Huge or smaller creature,\
      \ it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
      \ (escape DC 14), and the horrid plant can pull the target up to 25 feet closer\
      \ to itself. Until the grapple ends, the target has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition, and the horrid plant can't use the same tendril on another target.\
      \ The horrid plant has two tendrils."
    "name": "Tendril"
"bonus_actions":
  - "desc": "The horrid plant targets one creature it can see within 15 feet of itself.\
      \ The target must succeed on a DC 14 Dexterity saving throw or take 28 (8d6)\
      \ acid damage and become covered in acidic sap. This sap lasts for 1 minute\
      \ or until a creature uses its action to scrape the sap off itself or another\
      \ creature it can reach. A creature covered in sap takes 14 (4d6) acid damage\
      \ at the start of each of its turns."
    "name": "Sap Squirt (Purple Blossom Only)"
  - "desc": "Creatures within 10 feet of the horrid plant and not behind total cover\
      \ must make a DC 14 Dexterity saving throw, taking 21 (6d6) slashing damage\
      \ on a failed save or half as much damage on a successful one."
    "name": "Spiked Leaves (Snapper Saw Only)"
  - "desc": "One creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the horrid plant must make a DC 13 Constitution saving throw, taking 10\
      \ (3d6) necrotic damage on a failed save or half as much damage on a successful\
      \ one. The target's hit point maximum is reduced by an amount equal to the damage\
      \ taken, and the horrid plant regains hit points equal to that amount. This\
      \ reduction lasts until the target finishes a long rest. The target dies if\
      \ this effect reduces its hit point maximum to 0."
    "name": "Vampiric Tendril (Dew Drinker Only)"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/plant/token/horrid-plant-qftis.webp"
```
^statblock