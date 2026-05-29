---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Fazrian
linter-yaml-title-alias: Fazrian
tags:
  - Monster/Größe/Groß
  - Monster/HG/16
  - Monster/Typ/Himmlische
  - Quelle/5e/wdmm
aliases:
  - Fazrian
---
# [Fazrian](3-Mechanics\CLI\bestiary\npc/fazrian-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 275*  

Once an exemplar of courage and good judgment, Fazrian now seeks to destroy any creature it believes is undeserving of continued existence. Fazrian's views are a mockery of what they once were. Every creature is guilty of "deformity" in the planetar's eyes. Unless someone can swiftly prove their innocence, Fazrian sentences that individual to an immediate death.

```statblock
"name": "Fazrian (WDMM)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "200"
"hit_dice": "16d10 + 112"
"modifier": !!int "5"
"stats":
  - !!int "24"
  - !!int "20"
  - !!int "24"
  - !!int "19"
  - !!int "22"
  - !!int "25"
"speed": "40 ft., fly 120 ft."
"saves":
  - "constitution": !!int "12"
  - "wisdom": !!int "11"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "Perception"
    "desc": "+11"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "charmed, exhaustion, frightened"
"senses": "truesight 120 ft., passive Perception 21"
"languages": "all, telepathy 120 ft."
"cr": "16"
"traits":
  - "desc": "Fazrian's spellcasting ability is Charisma (spell save DC 20). Fazrian\
      \ can innately cast the following spells, requiring no material components:\n\
      \n**At will:** detect evil and good, invisibility (self only)\n\n**3/day each:**\
      \ blade barrier, dispel evil and good, flame strike, raise dead\n\n**1/day each:**\
      \ commune, control weather, insect plague"
    "name": "Innate Spellcasting"
  - "desc": "Fazrian's weapon attacks are magical. When Fazrian hits with any weapon,\
      \ the weapon deals an extra 5d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "Fazrian knows if it hears a lie."
    "name": "Divine Awareness"
  - "desc": "Fazrian has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Fazrian makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 21\
      \ (4d6 + 7) slashing damage plus 22 (5d8) radiant damage."
    "name": "Greatsword"
"lair_actions":
  - "desc": "Unless he is incapacitated, Fazrian can take one of the following lair\
      \ actions on initiative count 20 (losing initiative ties) while on the Terminus\
      \ Level:\n\n- Blood flows from Fazrian's eyes until initiative count 20 on the\
      \ next round. No creature within 120 feet of the planetar can regain hit points\
      \ until the effect ends.  \n- Fazrian's eyes become smoldering black voids until\
      \ initiative count 20 on the next round. All other creatures within 120 feet\
      \ of the planetar have disadvantage on saving throws until the effect ends.\
      \  \n- Blinding magical light springs from Fazrian's eyes until initiative count\
      \ 20 on the next round. If a creature starts its turn within 120 feet of the\
      \ planetar and the two of them can see each other, Fazrian can force the creature\
      \ to make a DC 20 Constitution saving throw. On a failed save, the creature\
      \ is blinded. The blindness lasts until the creature receives a lesser restoration\
      \ spell or similar magic.  "
    "name": ""
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/fazrian-wdmm.webp"
```
^statblock