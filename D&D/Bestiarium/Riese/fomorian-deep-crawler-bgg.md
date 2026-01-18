---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/10
  - Monster/Größe/Riesig
  - Monster/Typ/Riese
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Fomorian Deep Crawler
---
# [Fomorian Deep Crawler](3-Mechanics\CLI\bestiary\giant/fomorian-deep-crawler-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 142*  

Deep crawlers are fomorians whose bodies are adapted to crawling through the tunnels of the Underdark, perhaps in imitation or in honor of Karontor, "the king that crawls." Their limbs are long and sinuous, and their grip is strong enough for them to climb walls and ceilings.

## Fomorians

Descended from Annam's son Karontor, fomorians once occupied a place in the giants' ordning between hill and stone giants. In ancient times, they were scholars of magic known for their keen intellect—but also for their inflated egos and sense of entitlement. Karontor exploited these qualities, tempting them with promises of higher standing in the ordning, and incited his descendants to launch an assault on the Feywild. When the assault failed, the fomorians were banished to the Underdark and their god was consigned to a subterranean prison. Subjected to the strange magic of the Underdark, the fomorians' bodies and souls twisted until they became the fomorians of today.

```statblock
"name": "Fomorian Deep Crawler (BGG)"
"size": "Huge"
"type": "giant"
"alignment": "Any alignment"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "184"
"hit_dice": "16d12 + 80"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "20"
  - !!int "9"
  - !!int "17"
  - !!int "6"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 17"
"languages": "Giant, Undercommon"
"cr": "10"
"traits":
  - "desc": "The fomorian can enter a space large enough for a Large creature without\
      \ squeezing."
    "name": "Contortionist"
  - "desc": "While the fomorian has the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition, crawling does not cost it extra movement. In addition, the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition does not grant advantage on attack rolls against the fomorian."
    "name": "Crawling Stance"
  - "desc": "The fomorian can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The fomorian makes two Slam attacks and uses Crawling Hex if it is available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:* 22\
      \ (3d10 + 6) bludgeoning damage."
    "name": "Slam"
  - "desc": "The fomorian targets one creature it can see within 60 feet of itself.\
      \ The target must succeed on a DC 15 Wisdom saving throw or take 31 (7d8) psychic\
      \ damage, have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition,\
      \ and become cursed for 1 hour. While cursed this way, the target can't stand\
      \ up and end the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition on\
      \ itself."
    "name": "Crawling Hex (Recharge 4-6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/fomorian-deep-crawler-bgg.webp"
```
^statblock