---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hat-tg
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Holga Kilgore"
---
# [Holga Kilgore](3-Mechanics/CLI/bestiary/npc/holga-kilgore-hat-tg.md)
*Source: Honor Among Thieves: Thieves' Gallery*  

Holga Kilgore is a member of the Uthgardt Elk Tribe, and her strength and scowl conceal a generous heart. She's a woman of few words who lets her actions (and punches) speak for her. A fearsome combatant when her ire is up, Holga wields anything that comes to hand—from weapons to snacks. Her unwavering loyalty makes her a fierce defender of allies, particularly her best friend, Edgin.

After Holga was exiled from her clan, she wandered unmoored and craving connection. Now that she has forged a new home with Edgin and his band of thieves, she won't lose another family without a fight.

```statblock
"name": "Holga Kilgore (HAT-TG)"
"size": "Medium"
"type": "humanoid"
"alignment": "Chaotic Good"
"ac": !!int "15"
"ac_class": "Unarmored Defense"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "16"
  - !!int "11"
  - !!int "16"
  - !!int "13"
"speed": "40 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "6"
"skillsaves":
  - "name": "Athletics"
    "desc": "+7"
  - "name": "Intimidation"
    "desc": "+4"
  - "name": "Nature"
    "desc": "+3"
  - "name": "Survival"
    "desc": "+6"
"damage_resistances": "lightning (granted by darksteel greataxe)"
"senses": "passive Perception 13"
"languages": "Common, Halfling"
"cr": "5"
"traits":
  - "desc": "At the start of her turn, Holga can gain advantage on melee weapon attack\
      \ rolls during that turn, but attack rolls against her have advantage until\
      \ the start of her next turn."
    "name": "Reckless"
  - "desc": "Holga carries a darksteel greataxe, a magic weapon that grants her resistance\
      \ to lightning damage while she carries it (included above)."
    "name": "Special Equipment"
  - "desc": "While Holga isn't wearing armor, her AC includes her Constitution modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "Holga makes three Darksteel Greataxe or Improvised Weapon attacks, in\
      \ any combination."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d12 + 4) slashing damage."
    "name": "Darksteel Greataxe"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft., or range\
      \ 20/60 ft., one target. *Hit:* 7 (1d6 + 4) bludgeoning damage."
    "name": "Improvised Weapon"
"bonus_actions":
  - "desc": "Holga shoves a creature within 5 feet of herself. That creature must\
      \ succeed on a DC 15 Strength saving throw or be moved 5 feet into an unoccupied\
      \ space of Holga's choice."
    "name": "Wrestle"
"source":
  - "HAT-TG"
"image": "3-Mechanics/CLI/bestiary/npc/token/holga-kilgore-hat-tg.webp"
```
^statblock