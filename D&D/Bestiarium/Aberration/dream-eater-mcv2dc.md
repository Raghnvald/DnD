---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Dream Eater
Kategorie: Aberration
Größe: Mittelgroß
HG: 7
Status: WIP
linter-yaml-title-alias: Dream Eater
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/7
  - Monster/Typ/aberration
  - Quelle/5e/mcv2dc
aliases:
  - Dream Eater
status: WIP
---
# [Dream Eater](3-Mechanics\CLI\bestiary\aberration/dream-eater-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 3*  

Originating from the dream-warped elven realm of Silvanesti, dream eaters are violent manifestations of nightmares and subconscious terrors. The true appearance of a dream eater is obscured, as the dream eater twists its hazy form into surreal illusions of its foes' greatest fears. However, all dream eaters share one thing: a gaping, always-smiling mouth, which it reveals before engulfing its prey in a phantasmagorical nightmare.

The key to defeating a dream eater lies not in brute force but in the ability to pierce its illusions and wrest others from its terrors. As such, bards and other persuasive adventurers find themselves uniquely poised to confront a hungering dream eater.

```statblock
"name": "Dream Eater (MCV2DC)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "15"
"hp": !!int "77"
"hit_dice": "14d8 + 14"
"modifier": !!int "5"
"stats":
  - !!int "15"
  - !!int "20"
  - !!int "13"
  - !!int "12"
  - !!int "16"
  - !!int "21"
"speed": "0 ft., fly 50 ft. (hover)"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "blinded, charmed, frightened, grappled, paralyzed, petrified,\
  \ restrained"
"senses": "blindsight 120 ft. (blind beyond this radius), passive Perception 13"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "7"
"traits":
  - "desc": "Each creature that starts its turn within 30 feet of the dream eater\
      \ must make a DC 16 Wisdom saving throw. On a failed save, the creature is frightened\
      \ of the dream eater until the start of the creature's next turn. If a creature's\
      \ saving throw is successful, the creature is immune to this dream eater's Ghastly\
      \ Visions trait for the next 24 hours."
    "name": "Ghastly Visions"
  - "desc": "The dream eater can move through other creatures and objects as if they\
      \ were difficult terrain. It takes 5 (1d10) force damage if it ends its turn\
      \ inside an object."
    "name": "Incorporeal Movement"
  - "desc": "The dream eater has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The dream eater makes two Ensnaring Shriek attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +8 to hit, reach 15 ft. or range 60\
      \ ft., one target. *Hit:* 12 (2d6 + 5) psychic damage, and if the target is\
      \ a Medium or smaller creature, the target must succeed on a DC 16 Charisma\
      \ saving throw or be pulled up to 15 feet toward the dream eater."
    "name": "Ensnaring Shriek"
"bonus_actions":
  - "desc": "The dream eater targets one creature within 5 feet of itself. The target\
      \ must succeed on a DC 16 Wisdom saving throw or be engulfed by the dream eater,\
      \ as the dream eater envelops the creature in a miasma of its worst fears.\n\
      \nWhen the dream eater engulfs a target, the dream eater enters its space, and\
      \ the target immediately takes 10 (3d6) psychic damage. An engulfed target is\
      \ restrained and blinded, and it takes an additional 10 (3d6) psychic damage\
      \ at the start of each of the dream eater's turns. When the dream eater moves,\
      \ the engulfed target moves with it.\n\nThe dream eater can have only one target\
      \ engulfed at a time. An engulfed target escapes at the start of its turn by\
      \ making a DC 16 Wisdom saving throw. On a successful save, the target escapes;\
      \ the target is no longer engulfed, and it enters a space of its choice within\
      \ 5 feet of the dream eater. A creature within 15 feet of the dream eater also\
      \ can use its action to attempt to free an engulfed target. Doing so requires\
      \ the creature to use its action to make a DC 16 Charisma (Persuasion) check\
      \ to convince the engulfed target the nightmare isn't real, with the target\
      \ escaping on a success. The creature making the check takes 10 (3d6) psychic\
      \ damage, regardless of the check's success or failure, as its mind brushes\
      \ against the nightmare."
    "name": "Engulfing Nightmare"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/dream-eater-mcv2dc.webp"
```
^statblock