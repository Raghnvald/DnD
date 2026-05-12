---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thessalar"
---
# [Thessalar](3-Mechanics/CLI/bestiary/npc/thessalar-imr.md)
*Source: Infernal Machine Rebuild p. 57*  

Thessalar was a master alchemist and creator of monsters, whose own blood was said to possess dire magical properties.

He is vainglorious, egotistical, and utterly ruthless in furthering his research. His career began as a priest in the service of Moloch, where he rose through the ranks before eventually taking over the temple as a working laboratory. Most of his experiments have involved the pursuit of new forms of life, resulting in such creatures as the thessalhydra and the owlbear. In recent years, he has also researched the prolonging of life—namely his own. Thessalar hopes that by becoming a lich, his research and experiments can continue indefinitely.

Over time, Thessalar has subjected himself to so many of his own experiments that his blood has taken on alchemical and magical properties. He regularly uses it as the basis for many of the reagents used throughout his labs.

```statblock
"name": "Thessalar (IMR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "104"
"hit_dice": "19d8 + 19"
"modifier": !!int "1"
"stats":
  - !!int "10"
  - !!int "12"
  - !!int "13"
  - !!int "19"
  - !!int "16"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "5"
  - "intelligence": !!int "8"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+7"
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+7"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 13"
"languages": "Common, Draconic, Elvish, Primordial"
"cr": "12"
"traits":
  - "desc": "Thessalar is an 18th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 16, +8 to hit with spell attacks). He has the following artificer\
      \ spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light.md),\
      \ [mending](3-Mechanics/CLI/spells/mending.md), [message](3-Mechanics/CLI/spells/message.md),\
      \ [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp.md)\n\n**1st level\
      \ (4 slots):** [alarm](3-Mechanics/CLI/spells/alarm.md), [cure wounds](3-Mechanics/CLI/spells/cure-wounds.md),\
      \ [identify](3-Mechanics/CLI/spells/identify.md), [ray of sickness](3-Mechanics/CLI/spells/ray-of-sickness.md)\n\
      \n**2nd level (3 slots):** [invisibility](3-Mechanics/CLI/spells/invisibility.md),\
      \ [Melf's acid arrow](3-Mechanics/CLI/spells/melfs-acid-arrow.md), [web](3-Mechanics/CLI/spells/web.md)\n\
      \n**3rd level (3 slots):** [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md),\
      \ [haste](3-Mechanics/CLI/spells/haste.md), [stinking cloud](3-Mechanics/CLI/spells/stinking-cloud.md)\n\
      \n**4th level (3 slots):** [blight](3-Mechanics/CLI/spells/blight.md), [Mordenkainen's\
      \ faithful hound](3-Mechanics/CLI/spells/mordenkainens-faithful-hound.md), [Otiluke's\
      \ resilient sphere](3-Mechanics/CLI/spells/otilukes-resilient-sphere.md)\n\n\
      **5th level (1 slots):** [cloudkill](3-Mechanics/CLI/spells/cloudkill.md)"
    "name": "Spellcasting"
  - "desc": "Thessalar wields a +1 dagger coated with [thessaltoxin poison](3-Mechanics/CLI/items/thessaltoxin-imr.md)\
      \ (see appendix C)."
    "name": "Special Equipment"
  - "desc": "Thessalar is accompanied by his [Thessalar's homunculus](3-Mechanics/CLI/bestiary/npc/thessalars-homunculus-imr.md).\
      \ If the [mending](3-Mechanics/CLI/spells/mending.md) spell is cast on it, the\
      \ homunculus regains 2d6 hit points."
    "name": "Alchemical Homunculus"
  - "desc": "Any magic item that restores hit points and can be applied to a piercing\
      \ or slashing weapon (a potion, an ointment, and so forth) causes a hit with\
      \ that weapon to deal extra damage to Thessalar equal to the amount the item\
      \ would normally heal."
    "name": "Healing Toxicity"
  - "desc": "Thessalar can cast [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md)\
      \ if he has access to [alchemical supplies](3-Mechanics/CLI/items/alchemists-supplies.md)."
    "name": "Greater Restoration (1/Day)"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 3 (1d4 + 1) piercing damage, and the target must\
      \ succeed on a DC 15 Constitution saving throw. On a failed save, the target\
      \ is affected as if by the [polymorph](3-Mechanics/CLI/spells/polymorph.md)\
      \ spell, transforming into a random beast or a creature it has seen within the\
      \ last 24 hours (as chosen by the DM). This effect lasts until the target finishes\
      \ a long rest."
    "name": "Dagger"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/npc/token/thessalar-imr.webp"
```
^statblock