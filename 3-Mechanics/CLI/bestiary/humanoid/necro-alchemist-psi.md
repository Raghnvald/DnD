---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Necro-Alchemist"
---
# [Necro-Alchemist](3-Mechanics/CLI/bestiary/humanoid/necro-alchemist-psi.md)
*Source: Plane Shift: Innistrad p. 20*  

Some bizarre and eccentric scientists use geists—the spirits of the dead—as an energy source to conduct strange experiments on living creatures and fuel crazed technological inventions. Necro-alchemists sometimes call themselves geistmages, but different practitioners identify themselves in different ways. What all have in common, however, is their use of elaborate contraptions to capture, bind, and draw the energy from geists.

This technology is often employed to power sprawling laboratories. But some necro-alchemists have managed to bind geists to smaller containers, including tubelike canisters that are strapped to the back and attached to weapons that hurl lightning. At their best, necro-alchemists use their technological advances to fight the crazed angels. However, even the most true-hearted geistmages have been known to capture the spirits of fallen allies to recharge a geist-lightning weapon that has run out of fuel.

Necro-alchemists are best described using the [mage](3-Mechanics/CLI/bestiary/humanoid/mage.md) statistics in the Monster Manual, with the assumption that their spellcasting is facilitated by the use of geist-powered devices.

```statblock
"name": "Necro-Alchemist (PSI)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "40"
"hit_dice": "9d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+6"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "6"
"traits":
  - "desc": "The Necro-Alchemist is a 9th-level spellcaster. Its spellcasting ability\
      \ is Intelligence (spell save DC 14, +6 to hit with spell attacks). The Necro-Alchemist\
      \ has the following wizard spells prepared:\n\n**Cantrips (at will):** [fire\
      \ bolt](3-Mechanics/CLI/spells/fire-bolt.md), [light](3-Mechanics/CLI/spells/light.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1st level (4 slots):** [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor.md), [magic missile](3-Mechanics/CLI/spells/magic-missile.md),\
      \ [shield](3-Mechanics/CLI/spells/shield.md)\n\n**2nd level (3 slots):** [misty\
      \ step](3-Mechanics/CLI/spells/misty-step.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell.md),\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md), [fly](3-Mechanics/CLI/spells/fly.md)\n\
      \n**4th level (3 slots):** [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility.md),\
      \ [ice storm](3-Mechanics/CLI/spells/ice-storm.md)\n\n**5th level (1 slots):**\
      \ [cone of cold](3-Mechanics/CLI/spells/cone-of-cold.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/necro-alchemist-psi.webp"
```
^statblock