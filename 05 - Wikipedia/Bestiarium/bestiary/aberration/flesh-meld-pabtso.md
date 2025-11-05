---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/cr/7
  - Monster/Größe/Riesig
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Flesh Meld
Größe: Riesig
Typ: Aberration
Habitat:
  - /
HG: 7
---
# [Flesh Meld](3-Mechanics\CLI\bestiary\aberration/flesh-meld-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 207*  

Squelching and quivering with insatiable hunger, a flesh meld is a hulking amalgamation of teeth, blood, and body parts. Sinuous appendages of gore, each ending in a gnashing mouth, bite at prey before yanking the piteous creatures into the flesh meld's core. The stench of death surrounds a flesh meld.

When a creature is consumed by a flesh meld, the creature's mind is merged into the flesh meld's consciousness. More resilient minds may fight against this assimilation, but inevitably, the mind succumbs to the discordant chorus of thoughts to kill and consume.

```statblock
"name": "Flesh Meld (PaBTSO)"
"size": "Huge"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "12"
"hp": !!int "95"
"hit_dice": "10d12 + 30"
"modifier": !!int "2"
"stats":
  - !!int "21"
  - !!int "14"
  - !!int "17"
  - !!int "7"
  - !!int "13"
  - !!int "5"
"speed": "30 ft., climb 30 ft."
"saves":
  - "strength": !!int "8"
  - "dexterity": !!int "5"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (can't see beyond\
  \ this radius), passive Perception 11"
"languages": "understands all but can't speak"
"cr": "7"
"traits":
  - "desc": "The flesh meld can move through a space as narrow as 1 inch without squeezing."
    "name": "Amorphous"
  - "desc": "At the start of each of the flesh meld's turns, each creature within\
      \ 5 feet of it must succeed on a DC 15 Constitution saving throw or take 3 (1d6)\
      \ necrotic damage and have the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ condition until the start of the flesh meld's next turn."
    "name": "Aura of Death"
  - "desc": "The flesh meld has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The flesh meld can climb difficult surfaces, including ceilings, without\
      \ needing to make an ability check."
    "name": "Spider Climb"
"actions":
  - "desc": "The flesh meld makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 30 ft., one target. *Hit:* 16\
      \ (2d10 + 5) piercing damage, and if the target is a Large or smaller creature,\
      \ it has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape\
      \ DC 15) and is pulled up to 15 feet toward the flesh meld."
    "name": "Bite"
"bonus_actions":
  - "desc": "The flesh meld targets one Large or smaller creature within 5 feet of\
      \ itself that it's grappling. The target must succeed on a DC 15 Dexterity saving\
      \ throw or be swallowed by the flesh meld. The flesh meld can have one creature\
      \ swallowed at a time.\n\nA swallowed creature no longer has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ condition. While swallowed, it has the [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ and [restrained](/3-Mechanics/CLI/conditions.md#Restrained) conditions, has\
      \ total cover against attacks and other effects outside the flesh meld, and\
      \ takes 10 (3d6) necrotic damage at the start of each of the flesh meld's turns.\
      \ If this damage reduces a swallowed creature to 0 hit points, the creature\
      \ dies, and the flesh meld consumes its body.\n\nIf the flesh meld takes 30\
      \ damage or more on a single turn from the swallowed creature, the flesh meld\
      \ must succeed on a DC 15 Constitution saving throw at the end of that turn\
      \ or regurgitate the creature, which falls with the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition in a space within 5 feet of the flesh meld. If the flesh meld dies,\
      \ the swallowed creature is no longer [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 10 feet of movement, exiting\
      \ with the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Consume Creature"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/flesh-meld-pabtso.webp"
```
^statblock