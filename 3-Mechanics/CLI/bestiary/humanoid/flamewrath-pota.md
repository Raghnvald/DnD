---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Flamewrath"
---
# [Flamewrath](3-Mechanics/CLI/bestiary/humanoid/flamewrath-pota.md)
*Source: Princes of the Apocalypse p. 201*  

A flamewrath is a spellcaster that has earned the favor of Imix, the Prince of Elemental Fire, through a series of painful rites. A flamewrath's skin is burned and scarred. Inured to pain, the flamewrath revels in battle, using an array of fire spells to incinerate enemies who would try to douse the power of elemental fire. Melee combatants who draw too close face fires that can dance across the flamewrath's skin and burn attackers.

```statblock
"name": "Flamewrath (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "16"
  - !!int "11"
  - !!int "10"
  - !!int "16"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+3"
"damage_immunities": "fire"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 10"
"languages": "Common, Ignan"
"cr": "6"
"traits":
  - "desc": "The flamewrath is a 7th-level spellcaster. Its spellcasting ability is\
      \ Charisma (spell save DC 14, +6 to hit with spell attacks). It knows the\
      \ following sorcerer spells:\n\n**Cantrips (at will):** control flames, [fire\
      \ bolt](3-Mechanics/CLI/spells/fire-bolt.md), [friends](3-Mechanics/CLI/spells/friends.md),\
      \ [light](3-Mechanics/CLI/spells/light.md), [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md)\n\
      \n**1st level (4 slots):** [burning hands](3-Mechanics/CLI/spells/burning-hands.md),\
      \ [color spray](3-Mechanics/CLI/spells/color-spray.md), [mage armor](3-Mechanics/CLI/spells/mage-armor.md)\n\
      \n**2nd level (3 slots):** [scorching ray](3-Mechanics/CLI/spells/scorching-ray.md),\
      \ [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\n**3rd level (3 slots):**\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md), [hypnotic pattern](3-Mechanics/CLI/spells/hypnotic-pattern.md)\n\
      \n**4th level (1 slots):** [fire shield](3-Mechanics/CLI/spells/fire-shield.md)\
      \ (see Wreathed in Flame)"
    "name": "Spellcasting"
  - "desc": "For the flamewrath, the warm version of the [fire shield](3-Mechanics/CLI/spells/fire-shield.md)\
      \ spell has a duration of \"until dispelled.\" The fire shield burns for 10\
      \ minutes after the flamewrath dies, consuming its body."
    "name": "Wreathed in Flame"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/flamewrath-pota.webp"
```
^statblock