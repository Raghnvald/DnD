---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/18
  - Monster/Größe/Riesig
  - Monster/Typ/Riese/cleric
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Fire Giant Forgecaller
---
# [Fire Giant Forgecaller](3-Mechanics\CLI\bestiary\giant/fire-giant-forgecaller-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 138*  

A fire giant who masters traditional rune magic can control the heat of a volcanic environment and conjure raw elemental energy of fire and magma. In a fire giant community, these forgecallers oversee both forges and the community's defense, often in Surtur's name. Some forgecallers prefer to live and work in isolation, seeking the hottest fires in volcanoes' hearts or the Elemental Plane of Fire to pursue their own crafts and studies.

A forgecaller is a walking furnace, clad head to toe in plate armor that seems to barely contain intense heat and billowing smoke. They conjure waves of magma and can fly by jetting magical fire from their legs and body.

```statblock
"name": "Fire Giant Forgecaller (BGG)"
"size": "Huge"
"type": "giant"
"subtype": "cleric"
"alignment": "Any alignment"
"ac": !!int "18"
"ac_class": "[plate](/3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "312"
"hit_dice": "25d12 + 150"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "11"
  - !!int "23"
  - !!int "16"
  - !!int "21"
  - !!int "18"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": !!int "6"
  - "intelligence": !!int "9"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+13"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
"damage_immunities": "fire"
"senses": "passive Perception 21"
"languages": "Common, Giant"
"cr": "18"
"traits":
  - "desc": "If the giant fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The giant has a fire rune inscribed on a medallion or some other object\
      \ in its possession. While holding or wearing the object bearing the rune, the\
      \ giant can use its Magma Wave action and Furnace Armor bonus action.\n\nThe\
      \ object bearing the rune has AC 15; 40 hit points; and immunity to necrotic,\
      \ poison, and psychic damage. The object regains all its hit points at the end\
      \ of every turn, but it turns to dust if reduced to 0 hit points or when the\
      \ giant dies. If the rune is destroyed, the giant can inscribe a fire rune on\
      \ an object in its possession when it finishes a short or long rest."
    "name": "Fire Rune"
"actions":
  - "desc": "The giant makes three Forge Hammer attacks or two Heated Rock attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target. *Hit:* 24\
      \ (5d6 + 7) bludgeoning damage. *Hit or Miss:* The giant can cause the hammer\
      \ to emit a burst of heat in a 30-foot-radius sphere centered on the target.\
      \ Metal objects in that area glow red-hot until the start of the giant's next\
      \ turn. Any creature in physical contact with a heated object at the start of\
      \ its turn must make a DC 19 Constitution saving throw. On a failed save, the\
      \ creature takes 10 (3d6) fire damage and has disadvantage on attack rolls until\
      \ the start of its next turn unless it has immunity to fire damage. The hammer\
      \ can emit heat in this way only once per turn."
    "name": "Forge Hammer"
  - "desc": "*Ranged Weapon Attack:* +13 to hit, range 60/240 ft., one target. *Hit:*\
      \ 23 (3d10 + 7) bludgeoning damage plus 19 (3d12) fire damage. If the target\
      \ is a Large or smaller creature, it must succeed on a DC 21 Strength saving\
      \ throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition.\
      \ After the giant throws the rock, roll a d6; on a roll of 3 or lower, the giant\
      \ has no more rocks to throw."
    "name": "Heated Rock"
  - "desc": "The giant emits a wave of magma from its fire rune in a 30-foot cone.\
      \ Each creature in that area must make a DC 19 Dexterity saving throw. On a\
      \ failed save, a creature takes 36 (8d8) fire damage and has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition. As an action, a creature can make a DC 19 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ check, freeing itself or a creature within its reach from the rock on a success.\
      \ The rock restraining each creature has AC 17; 20 hit points; and immunity\
      \ to fire, poison, and psychic damage. On a successful save, a creature takes\
      \ half as much damage only."
    "name": "Magma Wave (Requires Fire Rune)"
"bonus_actions":
  - "desc": "The giant causes smoke and cinders to billow from its armor, filling\
      \ a 30-foot-radius sphere centered on the giant. While the armor is billowing\
      \ smoke, the giant has half cover. The armor stops billowing smoke after 1 minute,\
      \ when the giant dies, when the giant uses a bonus action to end the effect,\
      \ or when the giant's fire rune is destroyed."
    "name": "Furnace Armor (Requires Fire Rune)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/fire-giant-forgecaller-bgg.webp"
```
^statblock