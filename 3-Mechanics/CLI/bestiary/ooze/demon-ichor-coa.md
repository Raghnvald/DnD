---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/ooze
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Demon Ichor"
---
# [Demon Ichor](3-Mechanics/CLI/bestiary/ooze/demon-ichor-coa.md)
*Source: Chains of Asmodeus p. 78*  

```statblock
"name": "Demon Ichor (CoA)"
"size": "Large"
"type": "ooze"
"alignment": "Unaligned"
"ac": !!int "7"
"hp": !!int "120"
"hit_dice": "10d10 + 30"
"modifier": !!int "-3"
"stats":
  - !!int "16"
  - !!int "5"
  - !!int "16"
  - !!int "1"
  - !!int "6"
  - !!int "1"
"speed": "20 ft., climb 20 ft."
"damage_immunities": "acid, cold, fire, lightning, slashing"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, prone"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 8"
"languages": ""
"cr": "4"
"traits":
  - "desc": "The ichor can move through a space as narrow as 1 inch wide without squeezing."
    "name": "Amorphous"
  - "desc": "A creature that touches the ichor or hits it with a melee attack while\
      \ within 5 feet of it takes 4 (1d8) acid damage. Any nonmagical weapon made\
      \ of metal or wood that hits the ichor corrodes. After dealing damage, the weapon\
      \ takes a permanent and cumulative −1 penalty to damage rolls. If its penalty\
      \ drops to −5, the weapon is destroyed. Nonmagical ammunition made of metal\
      \ or wood that hits the ichor is destroyed after dealing damage. The ichor can\
      \ eat through 2-inch-thick, nonmagical wood or metal in 1 round."
    "name": "Corrosive Form"
  - "desc": "The ichor can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage plus 18 (4d8) acid damage. In addition, nonmagical\
      \ armor worn by the target is partly dissolved and takes a permanent and cumulative\
      \ −1 penalty to the AC it offers. The armor is destroyed if the penalty reduces\
      \ its AC to 10."
    "name": "Pseudopod"
"reactions":
  - "desc": "When a ichor that is Medium or larger is subjected to lightning or slashing\
      \ damage, it splits into two new ichors if it has at least 10 hit points. Each\
      \ new ichor has hit points equal to half the original ichor's, rounded down.\
      \ New ichors are one size smaller than the original ichor."
    "name": "Split"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/ooze/token/demon-ichor-coa.webp"
```
^statblock