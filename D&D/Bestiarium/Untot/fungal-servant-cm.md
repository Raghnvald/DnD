---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Fungal Servant
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/15
  - Monster/Typ/Untote
  - Quelle/5e/cm
aliases:
  - Fungal Servant
linter-yaml-title-alias: Fungal Servant
---
# [Fungal Servant](3-Mechanics\CLI\bestiary\undead/fungal-servant-cm.md)
*Source: Candlekeep Mysteries p. 217*  

```statblock
"name": "Fungal Servant (CM)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "97"
"hit_dice": "13d8 + 39"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "17"
  - !!int "11"
  - !!int "18"
  - !!int "16"
"speed": "20 ft."
"saves":
  - "constitution": !!int "8"
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "History"
    "desc": "+5"
  - "name": "Religion"
    "desc": "+5"
"damage_vulnerabilities": "fire"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "The languages it knew in life"
"cr": "15"
"traits":
  - "desc": "The fungal servant is a 10th-level spellcaster. Its spellcasting ability\
      \ is Wisdom (spell save DC 17, +9 to hit with spell attacks). The fungal servant\
      \ has the following cleric spells prepared:\n\n**Cantrips (at will):** sacred\
      \ flame, thaumaturgy\n\n**1st level (4 slots):** command, guiding bolt, shield\
      \ of faith\n\n**2nd level (3 slots):** hold person, silence, spiritual weapon\n\
      \n**3rd level (3 slots):** animate dead, dispel magic\n\n**4th level (3 slots):**\
      \ divination, guardian of faith\n\n**5th level (2 slots):** contagion, insect\
      \ plague\n\n**6th level (1 slots):** harm"
    "name": "Spellcasting"
  - "desc": "The fungal servant has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
  - "desc": "A destroyed fungal servant gains a new body in 24 hours if its heart\
      \ is intact, regaining all its hit points and becoming active again. The new\
      \ body appears within 5 feet of the fungal servant's heart."
    "name": "Rejuvenation"
"actions":
  - "desc": "The fungal servant can use its Dreadful Glare and makes one attack with\
      \ its rotting fist."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (3d6 + 4) bludgeoning damage plus 21 (6d6) necrotic damage. If the target\
      \ is a creature, it must succeed on a DC 16 Constitution saving throw or be\
      \ cursed with mummy rot. The cursed target can't regain hit points, and its\
      \ hit point maximum decreases by 10 (3d6) for every 24 hours that elapse. If\
      \ the curse reduces the target's hit point maximum to 0, the target dies, and\
      \ its body turns to spores. The curse lasts until removed by the remove curse\
      \ spell or other magic."
    "name": "Rotting Fist"
  - "desc": "The fungal servant targets one creature it can see within 60 feet of\
      \ it. If the target can see the fungal servant, it must succeed on a DC 16 Wisdom\
      \ saving throw against this magic or become frightened until the end of the\
      \ fungal servant's next turn. If the target fails the saving throw by 5 or more,\
      \ it is also paralyzed for the same duration. A target that succeeds on the\
      \ saving throw is immune to the Dreadful Glare of all fungal servants for the\
      \ next 24 hours."
    "name": "Dreadful Glare"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the fungal servant can expend a use to take one of the following actions.\
  \ The fungal servant regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The fungal servant makes one attack with its rotting fist or uses its\
      \ Dreadful Glare."
    "name": "Attack"
  - "desc": "Blinding spores swirls magically around the fungal servant. Each creature\
      \ within 5 feet of the fungal servant must succeed on a DC 16 Constitution saving\
      \ throw or be blinded until the end of the creature's next turn."
    "name": "Blinding Spores"
  - "desc": "The fungal servant utters a blasphemous word. Each non-undead creature\
      \ within 10 feet of the fungal servant that can hear the magical utterance must\
      \ succeed on a DC 16 Constitution saving throw or be stunned until the end of\
      \ the fungal servant's next turn."
    "name": "Blasphemous Word (Costs 2 Actions)"
  - "desc": "The fungal servant magically unleashes negative energy. Creatures within\
      \ 60 feet of the fungal servant, including ones behind barriers and around corners,\
      \ can't regain hit points until the end of the fungal servant's next turn."
    "name": "Channel Negative Energy (Costs 2 Actions)"
  - "desc": "The fungal servant magically transforms into a whirlwind of spores, moves\
      \ up to 60 feet, and reverts to its normal form. While in whirlwind form, the\
      \ fungal servant is immune to all damage, and it can't be grappled, petrified,\
      \ knocked prone, restrained, or stunned. Equipment worn or carried by the fungal\
      \ servant remain in its possession."
    "name": "Whirlwind of Spores (Costs 2 Actions)"
"source":
  - "CM"
"image": "/3-Mechanics/CLI/bestiary/undead/token/fungal-servant-cm.webp"
```
^statblock