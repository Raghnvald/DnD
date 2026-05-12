---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/halfling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Wiggan Nettlebee"
---
# [Wiggan Nettlebee](3-Mechanics/CLI/bestiary/npc/wiggan-nettlebee-pota.md)
*Source: Princes of the Apocalypse p. 212*  

Wiggan Nettlebee is the patriarch of the Nettlebee clan, a wealthy family of halflings that raise livestock and farm their land. He presents the outward appearance of a modest rancher, and he forbids extravagance on his farm. Thinking he had found a cult dedicated to the dominating nature and utilizing its darker aspects, Wiggan joined the Cult of the Black Earth. He still doesn't know the full extent of the cult's plans.

Wiggan dislikes and distrusts outsiders. He believes they are all evildoers who would steal from him if they could. He sees the earth cult as a powerful and necessary ally toward securing his finances and sustaining his position. A greedy miser, Wiggan becomes visibly upset at the thought of parting with even a few spare coins from his hoard.

```statblock
"name": "Wiggan Nettlebee (PotA)"
"size": "Small"
"type": "humanoid"
"subtype": "halfling"
"alignment": "Neutral Evil"
"ac": !!int "11"
"ac_class": "16 with [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "36"
"hit_dice": "8d6 + 8"
"modifier": !!int "1"
"stats":
  - !!int "8"
  - !!int "12"
  - !!int "12"
  - !!int "14"
  - !!int "15"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+4"
"senses": "passive Perception 12"
"languages": "Common, Halfling"
"cr": "2"
"traits":
  - "desc": "Wiggan is a 4th-level spellcaster. His spellcasting ability is Wisdom\
      \ (spell save DC 12, +4 to hit with spell attacks). He has the following cleric\
      \ spells prepared:\n\n**Cantrips (at will):** [guidance](3-Mechanics/CLI/spells/guidance.md),\
      \ [light](3-Mechanics/CLI/spells/light.md), [mending](3-Mechanics/CLI/spells/mending.md),\
      \ [shillelagh](3-Mechanics/CLI/spells/shillelagh.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1st level (4 slots):** [animal friendship](3-Mechanics/CLI/spells/animal-friendship.md),\
      \ [cure wounds](3-Mechanics/CLI/spells/cure-wounds.md), [healing word](3-Mechanics/CLI/spells/healing-word.md),\
      \ [inflict wounds](3-Mechanics/CLI/spells/inflict-wounds.md), [speak with animals](3-Mechanics/CLI/spells/speak-with-animals.md)\n\
      \n**2nd level (3 slots):** [barkskin](3-Mechanics/CLI/spells/barkskin.md), [spike\
      \ growth](3-Mechanics/CLI/spells/spike-growth.md), [spiritual weapon](3-Mechanics/CLI/spells/spiritual-weapon.md)"
    "name": "Spellcasting"
  - "desc": "Wiggan has advantage on saving throws against being [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Brave Devotion"
"actions":
  - "desc": "Wiggan makes two attacks with his wooden cane."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +0 to hit (+4 to hit with shillelagh), reach\
      \ 5 ft., one target. *Hit:* 1 (1d4 - 1) bludgeoning damage, or 6 (1d8 + 2)\
      \ bludgeoning damage with shillelagh."
    "name": "Wooden Cane"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/wiggan-nettlebee-pota.webp"
```
^statblock