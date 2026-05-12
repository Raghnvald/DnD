---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wtthc
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Demodragon"
---
# [Demodragon](3-Mechanics/CLI/bestiary/fiend/demodragon-wtthc.md)
*Source: Stranger Things: Welcome to the Hellfire Club*  

Once the prized pet of Demogorgon, Prince of Demons, the demodragon now resides in the Nine Hells, where it serves as the gatekeeper of the Hellfire Games' final challenge.

Raised by vile magic from the corpse of a beheaded black dragon, the demodragon is the picture of its creator: an abomination with three writhing tails, monstrous wings, and two hideous heads. Initially, each bulbous head appears featureless—a disturbing, preternatural bud yet to bloom. When threatened, however, each unfurls to reveal a flower-like arrangement of glistening flesh and teeth around two crushing jaws.

Though the head of the dragon from which the demodragon spawned is long gone, its breath remains. Without warning, the demodragon can unleash a deluge of bone-melting acid on any who dare challenge it.

```statblock
"name": "Demodragon (WttHC)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Unaligned"
"ac": !!int "16"
"hp": !!int "102"
"hit_dice": "12d12 + 24"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "10"
  - !!int "15"
  - !!int "8"
  - !!int "12"
  - !!int "10"
"speed": "40 ft., fly 60 ft."
"saves":
  - "constitution": !!int "5"
  - "wisdom": !!int "4"
"damage_resistances": "acid, cold, lightning"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[Blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 120 ft., passive\
  \ Perception 11"
"languages": ""
"cr": "5"
"traits":
  - "desc": "Sources of light in a 120-foot [Emanation](3-Mechanics/CLI/rules/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the demodragon flicker wildly. Nonmagical sources of [Bright\
      \ Light](3-Mechanics/CLI/rules/variant-rules/bright-light-xphb.md) in that area\
      \ instead shed [Dim Light](3-Mechanics/CLI/rules/variant-rules/dim-light-xphb.md)."
    "name": "Baleful Presence"
  - "desc": "The demodragon regains 10 [Hit Points](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)\
      \ at the start of each of its turns if it has at least 1 [Hit Point](3-Mechanics/CLI/rules/variant-rules/hit-points-xphb.md)"
    "name": "Regeneration"
"actions":
  - "desc": "The demodragon makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 10 ft.  *Hit:* 11 (2d6 + 4) Piercing\
      \ damage plus 4 (1d8) Acid damage."
    "name": "Bite"
  - "desc": "*Dexterity Saving Throw:* DC 13, each creature in a 30-foot-long, 5-foot-wide\
      \ [Line](3-Mechanics/CLI/rules/variant-rules/line-area-of-effect-xphb.md). *Failure:*\
      \ 22 (4d10) Acid damage. *Success:* Half damage."
    "name": "Acid Breath (Recharge 5-6)"
"source":
  - "WttHC"
"image": "3-Mechanics/CLI/bestiary/fiend/token/demodragon-wtthc.webp"
```
^statblock