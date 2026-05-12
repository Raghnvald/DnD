---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv3mc
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Blaze"
---
# [Blaze](3-Mechanics/CLI/bestiary/elemental/blaze-mcv3mc.md)
*Source: Monstrous Compendium Volume 3: Minecraft Creatures p. 3*  

Blazes are elemental beings that congregate at Nether fortresses. They float a short distance above the ground, and each one is orbited by three sets of glowing rods. When a blaze is destroyed, it sometimes leaves one of these rods behind. Blaze rods are a source of great energy that, when carefully crushed into powder, can be used to brew potions and craft other magic items.

A blaze attacks by launching three fireballs from its fiery core. This fire ignites creatures and flammable objects. If necessary, a blaze levitates into the air to better see and more easily target its enemies.

```statblock
"name": "Blaze (MCV3MC)"
"size": "Medium"
"type": "elemental"
"alignment": "typically  Neutral Evil"
"ac": !!int "13"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "17"
  - !!int "16"
  - !!int "6"
  - !!int "10"
  - !!int "7"
"speed": "20 ft., fly 20 ft. (vertical movement only; hover)"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "fire"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned),\
  \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "When the blaze drops to 0 hit points, it disappears in a cloud of smoke\
      \ and has a 50 percent chance of leaving behind a glowing rod worth 100 gp.\
      \ The rod sheds dim light in a 5-foot radius. As an action, a creature can try\
      \ to snap the rod, doing so with a successful DC 14 Strength check. The snapped\
      \ rod releases its fiery energy in a 5-foot-radius sphere centered on itself.\
      \ Each creature in that area must make a DC 14 Dexterity saving throw, taking\
      \ 6 (1d12) fire damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Blaze Rod"
  - "desc": "Any creature that starts its turn within 5 feet of the blaze takes 3\
      \ (1d6) fire damage."
    "name": "Heat Aura"
  - "desc": "The blaze sheds bright light in a 20-foot radius and dim light for an\
      \ additional 20 feet."
    "name": "Illumination"
  - "desc": "The blaze takes 1 cold damage for every 5 feet it moves in water, for\
      \ every gallon of water splashed on it, or whenever it starts its turn in the\
      \ rain."
    "name": "Water Susceptibility"
"actions":
  - "desc": "The blaze makes three Fiery Doom attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +6 to hit; reach 5 ft. or ranged 60\
      \ ft., one target. *Hit:* 8 (1d10 + 3) fire damage, and the target catches\
      \ fire if it's a creature or a flammable object. Until a creature takes an action\
      \ to extinguish the fire, the burning target takes 3 (1d6) fire damage at\
      \ the end of each of its turns."
    "name": "Fiery Doom"
"source":
  - "MCV3MC"
"image": "3-Mechanics/CLI/bestiary/elemental/token/blaze-mcv3mc.webp"
```
^statblock