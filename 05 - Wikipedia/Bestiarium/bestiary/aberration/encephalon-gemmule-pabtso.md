---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/3
  - Monster/Größe/Winzig
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Encephalon Gemmule
Habitat:
  - /
Typ: Aberration
Größe: Winzig
HG: 3
---
# [Encephalon Gemmule](3-Mechanics\CLI\bestiary\aberration/encephalon-gemmule-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 206*  

Due to the influence of the Far Realm, the eggs within an encephalon cluster no longer hatch into illithid tadpoles. Instead, when one of an encephalon cluster's eggs reaches maturity, it is ejected from the mass as an encephalon gemmule.

When spawned, a gemmule appears as a misshapen, spindly legged, pyramid-shaped nugget of soft, fleshy matter. If left to its own devices, an encephalon gemmule grows into an encephalon cluster in a matter of days, at which point it begins producing its own gemmules.

## Encephalons

When an illithid colony lays its eggs dangerously close to a Far Realm rift, an egg sac has a chance to mutate into what is known as an encephalon cluster—a ravenous, slimy, psionic, brain-shaped mass that spawns horrors called encephalon gemmules.

```statblock
"name": "Encephalon Gemmule (PaBTSO)"
"size": "Tiny"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "54"
"hit_dice": "12d4 + 24"
"modifier": !!int "4"
"stats":
  - !!int "1"
  - !!int "18"
  - !!int "14"
  - !!int "5"
  - !!int "12"
  - !!int "7"
"speed": "40 ft."
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft. (can't see beyond\
  \ this radius), passive Perception 11"
"languages": ""
"cr": "3"
"traits":
  - "desc": "The gemmule matures into an encephalon cluster if not killed within 30\
      \ (4d12 + 4) days of its creation."
    "name": "Encephalon Progeny"
  - "desc": "The gemmule has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 16\
      \ (3d10) psychic damage."
    "name": "Psychic Slam"
"bonus_actions":
  - "desc": "The gemmule targets one creature within 5 feet of itself and forces the\
      \ target to make a DC 14 Dexterity saving throw. On a failed save, the gemmule\
      \ enters the target's space and attaches to the target. While the gemmule is\
      \ attached, the target takes 7 (3d4) piercing damage at the start of each of\
      \ its turns, and the gemmule can't use Leech again until it detaches. It can\
      \ detach itself by spending 5 feet of its movement. As an action, the target\
      \ or a creature within 5 feet of the target can detach the gemmule by succeeding\
      \ on a DC 15 Strength check."
    "name": "Leech"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/encephalon-gemmule-pabtso.webp"
```
^statblock