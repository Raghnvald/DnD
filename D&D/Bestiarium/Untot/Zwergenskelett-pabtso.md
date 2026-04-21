---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Zwergenskelett
Kategorie: Untoter
Größe: Mittelgroß
HG: 1/2
Habitat:
  - /
status: WIP
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/1-2
  - Monster/Typ/Untote
  - Quelle/5e/pabtso
aliases:
  - Dwarf Skeleton
  - Zwergenskelett
Image: undead/token/dwarf-skeleton-pabtso.webp
linter-yaml-title-alias: Zwergenskelett
---
# Zwergenskelett
*Quellen: Phandelver and Below: The Shattered Obelisk S. 123*  

```statblock
name: Zwergenskelett (PaBTSO)
source: PaBTSO 
image: Untot/token/dwarf-skeleton-pabtso.webp
size: Mittelgroß
type: Untot
alignment: Rechtschaffen Böse
ac: 13
ac_class: <STATBLOCK-MARKDOWN-LINK>Kettenhemd-phb.md|Kettenhemd<STATBLOCK-MARKDOWN-LINK>
hp: 26
hit_dice: 4d8 + 8
modifier: 0
stats:
  - 16
  - 10
  - 15
  - 6
  - 8
  - 5
speed: 7,5 Meter
damage_vulnerabilities: Wuchtschaden
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Exhaustion|exhaustion<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|Vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 Meter, passive Wahrnehmung 9
languages: understands Dwarvish but can't speak
cr: 1/2
traits:
  - desc: The skeleton has advantage on Strength and Dexterity saving throws made against effects that make it have the <STATBLOCK-MARKDOWN-LINK>/3-Mechanics/CLI/conditions.md#Prone|prone<STATBLOCK-MARKDOWN-LINK> condition.
    name: Sure-Footed
actions:
  - desc: "*Nahkampf-Waffenangriff:* +5 zum Treffen, Reichweite 1,5 Meter, ein Ziel. *Treffer:* 7 (1d8 + 3) Hiebschaden, oder 8 (1d10 + 3) Hiebschaden, falls mit beiden Händen geführt."
    name: Streitaxt
```

---

```statblock
"name": "Dwarf Skeleton (PaBTSO)"
"size": "Medium"
"type": "undead"
"alignment": "Lawful Evil"
"ac": !!int "13"
"ac_class": "[chain shirt](/3-Mechanics/CLI/items/chain-shirt-xphb.md)"
"hp": !!int "26"
"hit_dice": "4d8 + 8"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "6"
  - !!int "8"
  - !!int "5"
"speed": "25 ft."
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 9"
"languages": "understands Dwarvish but can't speak"
"cr": "1/2"
"traits":
  - "desc": "The skeleton has advantage on Strength and Dexterity saving throws made\
      \ against effects that make it have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Sure-Footed"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if used with two hands."
    "name": "Battleaxe"
"source":
  - "PaBTSO"
"image": "undead/token/dwarf-skeleton-pabtso.webp"
```
^statblock