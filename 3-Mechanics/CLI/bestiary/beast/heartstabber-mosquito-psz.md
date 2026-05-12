---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Heartstabber Mosquito"
---
# [Heartstabber Mosquito](3-Mechanics/CLI/bestiary/beast/heartstabber-mosquito-psz.md)
*Source: Plane Shift: Zendikar p. 27*  

The black mana that brews and festers in Zendikar's swamps infuses a wide variety of natural animals, creating large, deadly vermin—rats, bats, insects, scorpions, and spiders that spread death and decay with their bites, stings, or caustic saliva. The swamps of Guul Draz are home to many such creatures, from the enormous heartstabber mosquitoes (best represented with [stirge](3-Mechanics/CLI/bestiary/beast/stirge.md) statistics) to giant scorpions large enough to hold a struggling vampire in one claw. The gigantic, ant-like caustic crawlers (similar to [ankhegs](3-Mechanics/CLI/bestiary/monstrosity/ankheg.md)) shape burrows from stone with their acidic saliva, creating strangely smooth walls easily mistaken for ancient construction. Gloomhunter bats the size of griffins have reservoirs of vaporous mana in their heads, causing their bite to tear at the spirit as well as the flesh. These and other creatures can be built from the offerings in "appendix A of the Monster Manual".

```statblock
"name": "Heartstabber Mosquito (PSZ)"
"size": "Tiny"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "2"
"hit_dice": "1d4"
"modifier": !!int "3"
"stats":
  - !!int "4"
  - !!int "16"
  - !!int "11"
  - !!int "2"
  - !!int "8"
  - !!int "6"
"speed": "10 ft., fly 40 ft."
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": ""
"cr": "1/8"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one creature. *Hit:*\
      \ 5 (1d4 + 3) piercing damage, and the mosquito attaches to the target. While\
      \ attached, the mosquito doesn't attack. Instead, at the start of each of the\
      \ mosquito's turns, the target loses 5 (1d4 + 3) hit points due to blood loss.\n\
      \nThe mosquito can detach itself by spending 5 feet of its movement. It does\
      \ so after it drains 10 hit points of blood from the target or the target dies.\
      \ A creature, including the target, can use its action to detach the mosquito."
    "name": "Blood Drain"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/beast/token/heartstabber-mosquito-psz.webp"
```
^statblock