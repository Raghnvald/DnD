---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Crushing Wave Reaver"
---
# [Crushing Wave Reaver](3-Mechanics/CLI/bestiary/humanoid/crushing-wave-reaver-pota.md)
*Source: Princes of the Apocalypse p. 205*  

The foot soldiers of the Crushing Wave cult are vicious sea reavers. Many of them were pirates before they fell in with the cult, and they remain eager for blood and plunder. Crushing Wave reavers appreciate the value of stealth and surprise, and look for chances to launch sudden attacks from positions of concealment whenever possible. The soldiers of the Crushing Wave cult are highly loyal to the cult priests, but they rarely fight to the death if an avenue of retreat is open to them.

Reavers carry shields made of giant crab shells, and the blades of their swords are lined with shark's teeth.

```statblock
"name": "Crushing Wave Reaver (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "14"
"ac_class": "[shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "13"
  - !!int "10"
  - !!int "11"
  - !!int "8"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"gear":
  - "[javelin](3-Mechanics/CLI/items/javelin.md)"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "1/2"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) slashing damage, or 7 (1d10 + 2) slashing damage if used with\
      \ two hands. Against a target is wearing no armor, the reaver deals an extra\
      \ die of damage with this sword."
    "name": "Sharktoothed Longsword"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 30/120\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage."
    "name": "Javelin"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/crushing-wave-reaver-pota.webp"
```
^statblock