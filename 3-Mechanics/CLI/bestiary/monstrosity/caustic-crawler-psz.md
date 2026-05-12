---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Caustic Crawler"
---
# [Caustic Crawler](3-Mechanics/CLI/bestiary/monstrosity/caustic-crawler-psz.md)
*Source: Plane Shift: Zendikar p. 27*  

The black mana that brews and festers in Zendikar's swamps infuses a wide variety of natural animals, creating large, deadly vermin—rats, bats, insects, scorpions, and spiders that spread death and decay with their bites, stings, or caustic saliva. The swamps of Guul Draz are home to many such creatures, from the enormous heartstabber mosquitoes (best represented with [stirge](3-Mechanics/CLI/bestiary/beast/stirge.md) statistics) to giant scorpions large enough to hold a struggling vampire in one claw. The gigantic, ant-like caustic crawlers (similar to [ankhegs](3-Mechanics/CLI/bestiary/monstrosity/ankheg.md)) shape burrows from stone with their acidic saliva, creating strangely smooth walls easily mistaken for ancient construction. Gloomhunter bats the size of griffins have reservoirs of vaporous mana in their heads, causing their bite to tear at the spirit as well as the flesh. These and other creatures can be built from the offerings in "appendix A of the Monster Manual".

```statblock
"name": "Caustic Crawler (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor; 11 while prone"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "11"
  - !!int "13"
  - !!int "1"
  - !!int "13"
  - !!int "6"
"speed": "30 ft., burrow 10 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., tremorsense\
  \ 60 ft., passive Perception 11"
"languages": ""
"cr": "2"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage plus 3 (1d6) acid damage. If the target is a\
      \ Large or smaller creature, it is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 13). Until this grapple ends, the crawler can bite only the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ creature and has advantage on attack rolls to do so."
    "name": "Bite"
  - "desc": "The crawler spits acid in a line that is 30 feet long and 5 feet wide,\
      \ provided that it has no creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled).\
      \ Each creature in that line must make a DC 13 Dexterity saving throw, taking\
      \ 10 (3d6) acid damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Acid Spray (Recharge 6)"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/caustic-crawler-psz.webp"
```
^statblock