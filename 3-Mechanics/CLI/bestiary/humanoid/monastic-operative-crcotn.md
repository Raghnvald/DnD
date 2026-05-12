---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/small-or-medium
- ttrpg-cli/monster/type/humanoid/monk
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Monastic Operative"
---
# [Monastic Operative](3-Mechanics/CLI/bestiary/humanoid/monastic-operative-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 202*  

Operatives are agents of organizations that engage in espionage. The best among them are often considered for filling vacancies in higher positions.

## Monastics of the Cobalt Soul

Scholars, priests, and ascetics who have been drawn to the cause of truth and knowledge spend their lives in support of the Library of the Cobalt Soul, united by the teachings of Ioun the Knowing Mentor. The Cobalt Soul is guided by a central belief that true strength comes from understanding the world around you. Beyond its efforts in knowledge-seeking, each branch of the Cobalt Soul strives to expose lies, unveil propaganda, and fight corruption in whatever society their chapter, referred to as an archive, calls home.

The Library of the Cobalt Soul is headquartered in Rexxentrum, the capital of the Dwendalian Empire on the continent of Wildemount. The organization has archives across Exandria. The Ank'Hareli branch of the Cobalt Soul is based in the Temple of the Mentor. Like many of the archives, the Temple of the Mentor is both a vast library and a shrine to Ioun. This Marquesian archive is led by High Curator Jamil A'alithiya.

```statblock
"name": "Monastic Operative (CRCotN)"
"size": "Small or Medium"
"type": "humanoid"
"subtype": "monk"
"alignment": "Any alignment"
"ac": !!int "17"
"ac_class": "Unarmored Defense"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "4"
"stats":
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "17"
  - !!int "11"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+7"
  - "name": "Insight"
    "desc": "+6"
  - "name": "Investigation"
    "desc": "+8"
  - "name": "Stealth"
    "desc": "+7"
"senses": "passive Perception 13"
"languages": "Common plus two other languages"
"cr": "5"
"traits":
  - "desc": "While the operative is wearing no armor and wielding no shield, its AC\
      \ includes its Wisdom modifier."
    "name": "Unarmored Defense"
"actions":
  - "desc": "The operative makes three Unarmed Strike attacks, three Cobalt Dart attacks,\
      \ or a combination thereof."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d10 + 4) bludgeoning damage."
    "name": "Unarmed Strike"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 20/60 ft., one target. *Hit:*\
      \ 6 (1d4 + 4) piercing damage plus 3 (1d6) force damage."
    "name": "Cobalt Dart"
"reactions":
  - "desc": "When a creature within 5 feet of the operative hits or misses the operative\
      \ with a melee attack, the operative makes one Unarmed Strike attack against\
      \ the attacker."
    "name": "Retaliating Strike"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/monastic-operative-crcotn.webp"
```
^statblock