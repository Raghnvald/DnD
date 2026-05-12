---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/1
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Razorvine Blight"
---
# [Razorvine Blight](3-Mechanics/CLI/bestiary/plant/razorvine-blight-mpp.md)
*Source: Morte's Planar Parade p. 42*  

Travelers of Sigil and the Lower Planes take care to avoid razorvine, a creeping plant named for its prickly stems and cutting leaves. While razorvine is normally a mere environmental nuisance or deterrent, razorvine that absorbs the blood of a vampiric passerby can awaken into a terror known as a razorvine blight.

Razorvine blights lay ambushes on well-traveled paths by standing still to appear as ordinary razorvine. When unassuming travelers pass by the seemingly inanimate plant, the blight strikes, revealing its twisted, humanlike form and lashing out with razor-sharp vines to feed its bloodlust.

While razorvine blights are usually dangerous, in Sigil they sometimes mimic the behaviors of the city's other inhabitants—for better or worse. At least one blight, known as Patch, spreads copies of itself across the city, creating a spy network of copies with mysterious goals.

```statblock
"name": "Razorvine Blight (MPP)"
"size": "Medium"
"type": "plant"
"alignment": "typically  Neutral Evil"
"ac": !!int "12"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "13"
  - !!int "5"
  - !!int "10"
  - !!int "3"
"speed": "30 ft., climb 30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft. (can't\
  \ see beyond this radius), passive Perception 10"
"languages": "understands Common but can't speak"
"cr": "1"
"traits":
  - "desc": "If the blight is motionless at the start of combat, it has advantage\
      \ on its initiative roll. If a creature hasn't observed the blight move or act,\
      \ that creature must succeed on a DC 18 Intelligence ([Investigation](3-Mechanics/CLI/rules/skills.md#Investigation))\
      \ check to discern that the blight is animate."
    "name": "False Appearance"
  - "desc": "The blight can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The blight makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit (with advantage if the target is missing\
      \ any of its hit points), reach 10 ft., one target. *Hit:* 5 (1d6 + 2) slashing\
      \ damage."
    "name": "Claw"
  - "desc": "Snaking vines erupt from the blight. Each creature within 10 feet of\
      \ it must make a DC 12 Dexterity saving throw, taking 9 (2d8) slashing damage\
      \ on failed save, or half as much damage on a successful one. If at least one\
      \ of the creatures that failed this save isn't a Construct or an Undead, the\
      \ blight regains 9 hit points."
    "name": "Life-Draining Vines (Recharge 6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/plant/token/razorvine-blight-mpp.webp"
```
^statblock