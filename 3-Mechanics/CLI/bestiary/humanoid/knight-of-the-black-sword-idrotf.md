---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Knight of the Black Sword"
---
# [Knight of the Black Sword](3-Mechanics/CLI/bestiary/humanoid/knight-of-the-black-sword-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 259*  

Fanatics are often part of a cult's leadership, using their charisma and dogma to influence and prey on those of weak will. Most are interested in personal power above all else.

```statblock
"name": "Knight of the Black Sword (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "13"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor.md)"
"hp": !!int "33"
"hit_dice": "6d8 + 6"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "12"
  - !!int "10"
  - !!int "13"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 11"
"languages": "Common, Infernal"
"cr": "2"
"traits":
  - "desc": "The fanatic is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 11, +3 to hit with spell attacks). The fanatic has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (4 slots):** [command](3-Mechanics/CLI/spells/command.md), [inflict\
      \ wounds](3-Mechanics/CLI/spells/inflict-wounds.md), [shield of faith](3-Mechanics/CLI/spells/shield-of-faith.md)\n\
      \n**2nd level (3 slots):** [hold person](3-Mechanics/CLI/spells/hold-person.md),\
      \ [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon.md)"
    "name": "Spellcasting"
  - "desc": "The fanatic has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dark Devotion"
  - "desc": "When the cultist dies, its corpse freezes for 9 days, during which time\
      \ it can't be thawed, harmed by fire, animated, or raised from the dead."
    "name": "Icy Doom"
"actions":
  - "desc": "The fanatic makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/knight-of-the-black-sword-idrotf.webp"
```
^statblock