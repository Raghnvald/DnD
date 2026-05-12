---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Nafas"
---
# [Nafas](3-Mechanics/CLI/bestiary/npc/nafas-qftis.md)
*Source: Quests from the Infinite Staircase p. 210*  

Nafas is the breath of the multiverse, an ancient djinni born from the planar winds that blow through the myriad doors of the Infinite Staircase. He's a timeless force of untold power, a genie made noble by the planes themselves. A cloud of twinkling stardust follows Nafas wherever he goes, as evidence of his cosmic might.

No bottle, vase, ring, or lamp can contain Nafas. The genie is bound to the Infinite Staircase itself, anchored to the extradimensional realm that created him. From the steps of the staircase, Nafas hears the wishes of creatures across the multiverse but cannot act on them. Moved by their stories but barred by circumstance, Nafas relies on adventurers—whom he considers the living manifestations of a wish granted—to respond to these calls.

To friendly adventurers and weary travelers along the staircase, Nafas is a benevolent host, welcoming his guests with feasts, musical performances, and charming tales over tea. However, those who abuse the djinni's hospitality or seek to bind him to their service with Iron Flasks or other magic provoke his tempestuous ire.

When Nafas is provoked, the scope of his retribution is limited only by his imagination. Though the genie typically reserves the Wish spell for creatures he deems worthy of its gifts, he isn't above leveraging that power against formidable threats, rewriting reality to forcibly tilt the scales in his favor.

The multiverse dictates that there must always be a noble djinni to preside over the Infinite Staircase. If slain, Nafas re-forms within days, coalescing from cosmic air. The only way to truly destroy Nafas is to take his place.

> [!note] Nafas as a Patron
> 
> In addition to linking the adventures in this book, you can use Nafas as a group patron (detailed in Tasha's Cauldron of Everything). In this role, Nafas sends adventurers to distant worlds to fulfill the wishes of creatures beyond his reach. Adventurers who return to Nafas successful receive gifts as rewards. As a noble genie, Nafas can also act as a warlock's otherworldly patron, imparting a fraction of his power in exchange for the warlock's loyal service.
^nafas-as-a-patron

## Nafas's Lair

Nafas lairs in the Censer of Dreams, an aeolian palace within the Infinite Staircase where winds and wishes converge (see chapter 1 of Quests from the Infinite Staircase). Windcatchers rise above its spacious chambers and softly glowing domes, and melodious chimes dance in the shutterless windows of its vaulted halls. Held aloft by genie magic and the staircases that branch from it, the palace is a pit stop for planar travelers and a haven for friendly creatures.

```statblock
"name": "Nafas (QftIS)"
"size": "Large"
"type": "elemental"
"alignment": "Chaotic Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "350"
"hit_dice": "28d10 + 196"
"modifier": !!int "4"
"stats":
  - !!int "23"
  - !!int "18"
  - !!int "24"
  - !!int "15"
  - !!int "18"
  - !!int "23"
"speed": "30 ft., fly 90 ft. (hover)"
"saves":
  - "dexterity": !!int "11"
  - "wisdom": !!int "11"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Performance](3-Mechanics/CLI/rules/skills.md#Performance)"
    "desc": "+13"
"damage_resistances": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "lightning, thunder"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 21"
"languages": "Auran, Common"
"cr": "23"
"traits":
  - "desc": "Nafas can't leave the Infinite Staircase or be trapped within a container\
      \ (such as an Iron Flask). Attempts to transport Nafas to another plane are\
      \ wasted."
    "name": "Dimensionally Bound"
  - "desc": "When Nafas drops to 0 hit points, his body disintegrates into a whirl\
      \ of multiversal dust that surrounds one creature responsible for his demise.\
      \ That creature then hears Nafas's last wish: for the creature to take his place.\n\
      \nIf the creature accepts, it is transformed into a noble djinni. The creature's\
      \ game statistics are replaced by those of Nafas (including this trait), though\
      \ it retains its name, alignment, and personality. The creature also inherits\
      \ Nafas's palace and all it contains.\n\nIf the creature refuses, Nafas gains\
      \ a new body in 1d10 days, regaining all his hit points and appearing in a\
      \ random safe location on the Infinite Staircase."
    "name": "Last Wish"
  - "desc": "If Nafas fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "Nafas has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Nafas doesn't suffer any of the penalties that normally follow casting\
      \ the [Wish](3-Mechanics/CLI/spells/wish.md) spell to produce an effect other\
      \ than duplicating another spell."
    "name": "Noble Genie"
"actions":
  - "desc": "Nafas makes three Storm Shamshir attacks and uses Create Vortex."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) slashing damage plus 14 (4d6) lightning or thunder damage\
      \ (Nafas's choice)."
    "name": "Storm Shamshir"
  - "desc": "A 10-foot-radius, 60-foot-tall cylinder of swirling cosmic dust forms\
      \ on a point Nafas can see within 120 feet of him. The vortex lasts as long\
      \ as Nafas maintains [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). When the vortex appears, each creature other than Nafas in the\
      \ vortex's area must make a DC 22 Strength saving throw. On a failed save, a\
      \ creature takes 36 (8d8) force damage and has the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ condition. On a successful save, a creature takes half as much damage only\
      \ and moves to the nearest unoccupied space outside the vortex.\n\nOn subsequent\
      \ turns, Nafas can use this action to move the vortex up to 60 feet. When the\
      \ vortex enters a creature's space for the first time on a turn, the creature\
      \ must make the same saving throw as when the vortex first appeared. Creatures\
      \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) by the vortex\
      \ move with it.\n\nA creature [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by the vortex, or another creature that can reach it, can use its action to\
      \ make a DC 22 Strength check. On a successful check, the [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ creature is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ and moves to the nearest unoccupied space outside the vortex."
    "name": "Create Vortex"
  - "desc": "Nafas casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 21):\n\n**At\
      \ will:** [Detect Evil and Good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic.md), [Thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**3/day each:** [Create Food and Water](3-Mechanics/CLI/spells/create-food-and-water.md)\
      \ (the food is always tasty), [Dispel Magic](3-Mechanics/CLI/spells/dispel-magic.md),\
      \ [Invisibility](3-Mechanics/CLI/spells/invisibility.md), [Legend Lore](3-Mechanics/CLI/spells/legend-lore.md)\
      \ (as an action), [Tongues](3-Mechanics/CLI/spells/tongues.md), [Wind Walk](3-Mechanics/CLI/spells/wind-walk.md)\
      \ (as an action)\n\n**1/day each:** [Gaseous Form](3-Mechanics/CLI/spells/gaseous-form.md),\
      \ [Major Image](3-Mechanics/CLI/spells/major-image.md), [Teleport](3-Mechanics/CLI/spells/teleport.md),\
      \ [Wish](3-Mechanics/CLI/spells/wish.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Immediately after a creature Nafas can see ends its turn, Nafas exhales\
      \ forceful winds in a 30-foot cone. Large or smaller creatures in that area\
      \ must succeed on a DC 22 Strength saving throw or be pushed up to 15 feet away\
      \ from him."
    "name": "Blowback"
  - "desc": "In response to being hit by an attack roll, Nafas moves up to half his\
      \ flying speed without provoking opportunity attacks."
    "name": "Zephyr Step"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Nafas can take one of\
      \ the following lair actions; he can't take the same lair action two rounds\
      \ in a row:\n\n- **Downdraft.** Nafas targets one creature he can see within\
      \ 120 feet of himself. A downward current of air surrounds the target, reducing\
      \ its flying speed (if any) to 0 feet until the end of its next turn, and the\
      \ target must succeed on a DC 21 Strength saving throw or have the prone condition.\
      \  \n- **Lightning Strike.** A bolt of lightning strikes a point Nafas can see\
      \ within 120 feet of him. Each creature within 10 feet of that point must succeed\
      \ on a DC 21 Dexterity saving throw or take 16 (3d10) lightning damage.  \n\
      - **Stardust.** Nafas creates a 20-foot-radius sphere of multiversal dust centered\
      \ on a point anywhere in his lair. The sphere spreads around corners, and its\
      \ area is heavily obscured. The dust lasts until Nafas disperses it (no action\
      \ required) or uses this lair action again, and it can't be dispersed by wind.\
      \  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Nafas's lair is warped by his magic, creating one\
      \ or more of the following effects:\n\n- **Mirages.** Sapient creatures within\
      \ 3 miles of the lair frequently see illusions of their hearts' desires, be\
      \ they fame, fortune, or long-departed comrades. These mirages don't hold up\
      \ to physical inspection and vanish after a brief interaction.  \n- **Safe Descents.**\
      \ Within 3 miles of the lair, winds buoy creatures that fall, ushering them\
      \ safely to the nearest staircase. Such creatures descend at a rate of 60 feet\
      \ per round and take no damage from falling. Aberrations, Fiends, Undead, and\
      \ creatures that fall due to Nafas's or his allies' actions don't gain this\
      \ benefit, instead falling as normal.  \n- **Wishful Winds.** The wishes of\
      \ creatures across the multiverse, including those within the Infinite Staircase,\
      \ can be heard within 3 miles of the lair as fleeting voices carried on gentle\
      \ breezes.  \n\nIf Nafas is destroyed, all these effects end immediately, resuming\
      \ when he either gains a new body or is replaced by the creature that slays\
      \ him (see the Last Wish trait in Nafas's stat block)."
    "name": ""
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/nafas-qftis.webp"
```
^statblock