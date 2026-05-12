---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgdia
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/tortle
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Krull"
---
# [Krull](3-Mechanics/CLI/bestiary/npc/krull-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 110*  

```statblock
"name": "Krull (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "tortle"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "2"
"stats":
  - !!int "20"
  - !!int "14"
  - !!int "15"
  - !!int "12"
  - !!int "20"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "8"
  - "charisma": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+4"
  - "name": "Medicine"
    "desc": "+8"
  - "name": "Nature"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+8"
"gear":
  - "[+1 maul](3-Mechanics/CLI/items/1-weapon.md)"
"senses": "passive Perception 15"
"languages": "Aquan, Common, Draconic"
"cr": "6"
"traits":
  - "desc": "Krull is a 14th-level spellcaster. His spellcasting ability is Wisdom\
      \ (spell save DC 16, +8 to hit with spell attacks). He has the following cleric\
      \ spells prepared:\n\n**Cantrips (at will):** chill touch, mending, resistance,\
      \ sacred flame, spare the dying, thaumaturgy\n\n**1st level (4 slots):** cure\
      \ wounds, detect evil and good, false life, inflict wounds, ray of sickness\n\
      \n**2nd level (3 slots):** blindness/deafness, gentle repose, hold person, ray\
      \ of enfeeblement, spiritual weapon\n\n**3rd level (3 slots):** animate dead,\
      \ magic circle, speak with dead, spirit guardians, vampiric touch\n\n**4th level\
      \ (3 slots):** banishment, blight, death ward, divination, locate creature\n\
      \n**5th level (2 slots):** antilife shell, cloudkill, contagion, greater restoration\n\
      \n**6th level (1 slots):** create undead, true seeing\n\n**7th level (1 slots):**\
      \ divine word, regenerate"
    "name": "Spellcasting"
  - "desc": "Krull can hold his breath for 1 hour."
    "name": "Hold Breath"
  - "desc": "Necrotic damage dealt by Krull's spells ignores resistance to necrotic\
      \ damage."
    "name": "Inescapable Destruction"
"actions":
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d4 + 5) piercing damage."
    "name": "Claws"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d6 + 6) bludgeoning damage plus 9 (2d8) necrotic damage."
    "name": "+1 Maul"
  - "desc": "Krull withdraws into his shell. Until he emerges as a bonus action, he\
      \ has a +4 bonus to AC and has advantage on Strength and Constitution saving\
      \ throws. While in his shell, Krull is prone, his speed is 0 and can't increase,\
      \ he has disadvantage on Dexterity saving throws, he can't take reactions, and\
      \ the only action he can take is to emerge from his shell."
    "name": "Shell Defense"
"source":
  - "BGDIA"
"image": "3-Mechanics/CLI/bestiary/npc/token/krull-bgdia.webp"
```
^statblock