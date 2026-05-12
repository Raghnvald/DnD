---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/24
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Miska the Wolf-Spider"
---
# [Miska the Wolf-Spider](3-Mechanics/CLI/bestiary/npc/miska-the-wolf-spider-veor.md)
*Source: Vecna: Eve of Ruin p. 247*  

Miska the Wolf-Spider is a legendary demon lord and master of battlefield strategy. He has the lower body of a massive armored spider, four arms, and two enormous wolf heads that drip poison. Yet Miska's greatest strength is his cunning mind.

## History

Ages ago, Miska led the hordes of Chaos against the forces of Law at the behest of his patron, the enigmatic Queen of Chaos. It seemed Miska's domination couldn't be stopped.

In desperation, Miska's opponents crafted an artifact to bind him in an extraplanar prison. This rod broke apart after sealing him in Pandemonium, scattering across the planes and becoming known as the Rod of Seven Parts. The rod is the key to releasing Miska from his long imprisonment.

```statblock
"name": "Miska the Wolf-Spider (VEoR)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "399"
"hit_dice": "38d12 + 152"
"modifier": !!int "4"
"stats":
  - !!int "23"
  - !!int "18"
  - !!int "19"
  - !!int "18"
  - !!int "21"
  - !!int "22"
"speed": "40 ft., climb 40 ft."
"saves":
  - "dexterity": !!int "11"
  - "constitution": !!int "11"
  - "wisdom": !!int "12"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+12"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+11"
"damage_resistances": "cold, fire, lightning"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 21"
"languages": "Abyssal, Common, telepathy 120 ft."
"cr": "24"
"traits":
  - "desc": "A creature that hits Miska with a melee weapon attack takes 7 (2d6)\
      \ poison damage."
    "name": "Foul Ichor"
  - "desc": "If Miska fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Miska has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Miska can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "When in contact with a web, Miska knows the exact location of any other\
      \ creature in contact with the same web."
    "name": "Web Sense"
  - "desc": "Miska ignores movement restrictions caused by webbing."
    "name": "Web Walker"
"actions":
  - "desc": "Miska makes one Lupine Bite attack and two Trident of Chaos attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target. *Hit:*\
      \ 17 (2d10 + 6) piercing damage plus 27 (6d8) poison damage. If the target\
      \ is a creature, it must succeed on a DC 21 Constitution saving throw or have\
      \ the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) condition for\
      \ 1 minute. While [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) in\
      \ this way, a creature has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition and can't regain hit points. A [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ creature can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Lupine Bite"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) piercing damage plus 9 (2d8) force damage."
    "name": "Trident of Chaos"
  - "desc": "Miska casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 21):\n\n**At\
      \ will:** [Disguise Self](3-Mechanics/CLI/spells/disguise-self-xphb.md), [Invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [Minor Illusion](3-Mechanics/CLI/spells/minor-illusion-xphb.md),\
      \ [Web](3-Mechanics/CLI/spells/web-xphb.md)\n\n**2/day each:** [Dominate Monster](3-Mechanics/CLI/spells/dominate-monster-xphb.md),\
      \ [Mass Suggestion](3-Mechanics/CLI/spells/mass-suggestion-xphb.md), [Mirror\
      \ Image](3-Mechanics/CLI/spells/mirror-image-xphb.md), [Telekinesis](3-Mechanics/CLI/spells/telekinesis-xphb.md),\
      \ [Teleport](3-Mechanics/CLI/spells/teleport-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Miska magically ends the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ and [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened) conditions\
      \ on himself and on any of his allies within 120 feet of himself."
    "name": "Demand Loyalty"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Miska can expend a use to take one of the following actions. Miska regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Miska utters a bloodthirsty howl at one creature within 120 feet of himself\
      \ that isn't a Fiend. The target must succeed on a DC 20 Wisdom saving throw\
      \ or take 13 (2d12) psychic damage."
    "name": "Howl"
  - "desc": "Miska moves up to his speed without provoking opportunity attacks."
    "name": "Skitter"
  - "desc": "Miska uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
"source":
  - "VEoR"
"image": "3-Mechanics/CLI/bestiary/npc/token/miska-the-wolf-spider-veor.webp"
```
^statblock