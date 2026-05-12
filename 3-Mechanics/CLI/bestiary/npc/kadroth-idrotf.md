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
- "Kadroth"
---
# [Kadroth](3-Mechanics/CLI/bestiary/npc/kadroth-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 42*  

From this usurped office, he coordinates all cult activities in Ten-Towns. It's a role he carved out for himself by asserting that he's tight with Levistus. He rules the roost by sheer force of personality, though it chafes him that Hethyl Arkorran has more respect and influence within the cult. Kadroth doesn't involve Avarice in cult affairs because he fears her spellcasting ability and her connection to the Arcane Brotherhood. She could take over the cult anytime she wanted, and Kadroth doesn't want to give her any reason to do so.

For all his political machinations, Kadroth is a visionary who has so far made the cult stronger through his actions and decisions. He spends hours behind his desk, staring into the burning fireplace and drawing inspiration from its crackling flames. The slightest disturbance upsets him.

Kadroth appreciates the wisdom of maintaining the illusion that Speaker Crannoc Siever is still in charge, if only to keep Caer-Dineval's townsfolk from becoming restless. Thus, when necessary, Kadroth has the town speaker brought to his office to sign official documents.

```statblock
"name": "Kadroth (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Lawful Evil"
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
"damage_resistances": "fire"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 11"
"languages": "any one language (usually Common), Infernal"
"cr": "2"
"traits":
  - "desc": "Kadroth is a 4th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 11, +3 to hit with spell attacks). Kadroth has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (4 slots):** [command](3-Mechanics/CLI/spells/command.md), [inflict\
      \ wounds](3-Mechanics/CLI/spells/inflict-wounds.md), [shield of faith](3-Mechanics/CLI/spells/shield-of-faith.md)\n\
      \n**2nd level (3 slots):** [hold person](3-Mechanics/CLI/spells/hold-person.md),\
      \ [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon.md)"
    "name": "Spellcasting"
  - "desc": "Kadroth has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Dark Devotion"
"actions":
  - "desc": "Kadroth makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one creature. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/npc/token/kadroth-idrotf.webp"
```
^statblock