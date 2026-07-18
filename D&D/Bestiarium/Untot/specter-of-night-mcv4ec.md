---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Specter of Night
Status: WIP
linter-yaml-title-alias: Specter of Night
tags:
  - Monster/Größe/Riesig
  - Monster/HG/12
  - Monster/Typ/Untote
  - Quelle/5e/mcv4ec
aliases:
  - Specter of Night
---
# [Specter of Night](3-Mechanics\CLI\bestiary\undead/specter-of-night-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Like dark mirrors of Eldraine's archons (see "[Archon of Boundaries](/3-Mechanics/CLI/bestiary/celestial/archon-of-boundaries-mcv4ec.md)"), specters appear as shrouded figures mounted on horrific flying beasts. It is easy to look at a specter and imagine the rider in command of the mount, but the truth is the opposite; the flying horror is an Undead monster that scours the wilds for a knightly corpse. On finding one, the horror binds its essence to the dead body, giving the corpse the semblance of life as a rider. The two function as a single creature, more powerful for their unnatural union.

Humans of Eldraine view specters as heralds of death. Specters are said to utter a keening wail, mournful beyond all other sounds and audible only to those who are about to die.

```statblock
"name": "Specter of Night (MCV4EC)"
"size": "Huge"
"type": "undead"
"alignment": "typically  Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "142"
"hit_dice": "15d12 + 45"
"modifier": !!int "4"
"stats":
  - !!int "22"
  - !!int "18"
  - !!int "17"
  - !!int "12"
  - !!int "13"
  - !!int "12"
"speed": "60 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "8"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Perception"
    "desc": "+5"
"damage_resistances": "necrotic"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, poisoned"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "understands Common but can't speak"
"cr": "12"
"traits":
  - "desc": "If the specter fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The specter has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The specter uses Mournful Keening if available, then makes one Hooves\
      \ attack and one Reaping Scythe attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 16\
      \ (3d6 + 6) bludgeoning damage plus 28 (8d6) necrotic damage. If the target\
      \ is a Medium or smaller creature, it must succeed on a DC 18 Strength saving\
      \ throw or have the prone condition."
    "name": "Hooves"
  - "desc": "The specter utters a keening wail, calling to those close to death. Each\
      \ non-Undead creature within 120 feet of the specter must make a DC 15 Constitution\
      \ saving throw. On a failure, the creature hears the wail and is marked for\
      \ death.\n\nA creature marked for death can't regain hit points, has disadvantage\
      \ on death saving throws, and all attack rolls against it are made with advantage.\
      \ This effect lasts for 1 minute or until the creature is targeted by a remove\
      \ curse spell or similar magic."
    "name": "Mournful Keening (Recharge 6)"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 12\
      \ (1d12 + 6) slashing damage plus 28 (8d6) necrotic damage. If the target is\
      \ a creature, it must succeed on a DC 15 Constitution saving throw or gain a\
      \ level of exhaustion."
    "name": "Reaping Scythe"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/undead/token/specter-of-night-mcv4ec.webp"
```
^statblock