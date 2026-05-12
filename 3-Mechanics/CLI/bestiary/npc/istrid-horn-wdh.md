---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/dwarf
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Istrid Horn"
---
# [Istrid Horn](3-Mechanics/CLI/bestiary/npc/istrid-horn-wdh.md)
*Source: Waterdeep: Dragon Heist p. 199*  

Istrid is regarded as the Black Network's Master of Trade and Coin in Waterdeep. The shield dwarf operates an illegal lending operation out of a heavily guarded warehouse in the Dock Ward, offering loans to those in need of coin. Her interest rates are comparable to those of her competitors (including noble families of bankers such as the Cassalanters and the Irlingstars), but the penalties for not paying back Istrid's loans are severe.

Istrid worships Vergadain, the dwarven god of wealth and luck. She likes having others indebted to her, and she employs thugs and enforcers to collect on her loans. If those resources prove inadequate, Istrid can call on her old adventuring companions for assistance.

## The Doom Raiders

The Doom Raiders were five unscrupulous adventurers who liked to plunder lich lairs (called "dooms" by some). They gave up adventuring to join the Black Network and came to Waterdeep three years ago with plans to establish a Zhentarim foothold in the city. In that time, they have forged alliances with various nobles and guilds and run afoul of others, all the while fending off Harper spies.

```statblock
"name": "Istrid Horn (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "dwarf"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor-xphb.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "0"
"stats":
  - !!int "12"
  - !!int "10"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "13"
"speed": "25 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+3"
"damage_resistances": "poison"
"gear":
  - "[maul](3-Mechanics/CLI/items/maul-xphb.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common, Dwarvish"
"cr": "8"
"traits":
  - "desc": "Istrid is a 9th-level spellcaster. Her spellcasting ability is Wisdom\
      \ (spell save DC 14, +6 to hit with spell attacks) She has the following cleric\
      \ spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [mending](3-Mechanics/CLI/spells/mending-xphb.md), [sacred flame](3-Mechanics/CLI/spells/sacred-flame-xphb.md),\
      \ [spare the dying](3-Mechanics/CLI/spells/spare-the-dying-xphb.md)\n\n**1st\
      \ level (4 slots):** [divine favor](3-Mechanics/CLI/spells/divine-favor-xphb.md),\
      \ [guiding bolt](3-Mechanics/CLI/spells/guiding-bolt-xphb.md), [healing word](3-Mechanics/CLI/spells/healing-word-xphb.md),\
      \ [shield of faith](3-Mechanics/CLI/spells/shield-of-faith-xphb.md)\n\n**2nd\
      \ level (3 slots):** [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration-xphb.md),\
      \ [magic weapon](3-Mechanics/CLI/spells/magic-weapon-xphb.md), [hold person](3-Mechanics/CLI/spells/hold-person-xphb.md),\
      \ [silence](3-Mechanics/CLI/spells/silence-xphb.md), [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon-xphb.md)\n\
      \n**3rd level (3 slots):** [beacon of hope](3-Mechanics/CLI/spells/beacon-of-hope-xphb.md),\
      \ [crusader's mantle](3-Mechanics/CLI/spells/crusaders-mantle-xphb.md), [dispel\
      \ magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [revivify](3-Mechanics/CLI/spells/revivify-xphb.md),\
      \ [spirit guardians](3-Mechanics/CLI/spells/spirit-guardians-xphb.md), [water\
      \ walk](3-Mechanics/CLI/spells/water-walk-xphb.md)\n\n**4th level (3 slots):**\
      \ [banishment](3-Mechanics/CLI/spells/banishment-xphb.md), [freedom of movement](3-Mechanics/CLI/spells/freedom-of-movement-xphb.md),\
      \ [guardian of faith](3-Mechanics/CLI/spells/guardian-of-faith-xphb.md), [stoneskin](3-Mechanics/CLI/spells/stoneskin-xphb.md)\n\
      \n**5th level (1 slots):** [flame strike](3-Mechanics/CLI/spells/flame-strike-xphb.md),\
      \ [mass cure wounds](3-Mechanics/CLI/spells/mass-cure-wounds-xphb.md), [hold\
      \ monster](3-Mechanics/CLI/spells/hold-monster-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Istrid has advantage on saving throws against being [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)."
    "name": "Dwarven Resilience"
"actions":
  - "desc": "Istrid makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (2d6 + 1) bludgeoning damage."
    "name": "Maul"
  - "desc": "Istrid magically pinpoints precious metals and stones, such as coins\
      \ and gems, within 60 feet of her."
    "name": "Treasure Sense (3/Day)"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/istrid-horn-wdh.webp"
```
^statblock