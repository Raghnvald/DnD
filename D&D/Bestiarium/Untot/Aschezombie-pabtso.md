---
prefer-view: edit-source read
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Aschezombie
Kategorie: Untoter
Größe: Mittelgroß
HG: 1/4
Habitat:
  - /
image: token/ash-zombie-pabtso.webp
status: WIP
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-4
  - Monster/Typ/Untote
  - Quelle/5e/pabtso
aliases:
  - Aschezombie
  - Ash Zombie
linter-yaml-title-alias: Aschezombie
---
# Aschezombie
*Source: Phandelver and Below: The Shattered Obelisk p. 52*  

```statblock
"name": "Aschezombie"
"image": "undead/token/ash-zombie-pabtso.webp"
"source": "PaBTSO"
"size": "Mittelgroß"
"type": "Untoter"
"alignment": "Neutral Böse"
"ac": !!int "8"
"hp": !!int "22"
"hit_dice": "3d8 + 9"
"modifier": !!int "-2"
"stats":
  - !!int "13"
  - !!int "6"
  - !!int "16"
  - !!int "3"
  - !!int "6"
  - !!int "5"
"speed": "20 ft."
"saves":
  - "Weisheit": !!int "0"
"damage_immunities": "Gift"
"condition_immunities": "[Vergiftet](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[Dunkelsicht](senses.md#Darkvision) 60 ft., passive Wahrnehmung 8"
"languages": "understands all languages it spoke in life but can't speak"
"cr": "1/4"
"traits":
  - "desc": "If damage reduces the zombie to 0 hit points, it must make a Constitution\
      \ saving throw with a DC of 5 + the damage taken, unless the damage is radiant\
      \ or from a critical hit. On a success, the zombie drops to 1 hit point instead."
    "name": "Undead Fortitude"
  - "desc": "When the zombie dies, it leaves a cloud of ash that lasts for 5 minutes\
      \ but does not obscure vision."
    "name": "Ash Cloud"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 4 (1d6\
      \ + 1) bludgeoning damage."
    "name": "Slam"

```
^statblock