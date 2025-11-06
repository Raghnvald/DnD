---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/HG/6
  - Monster/Größe/Groß
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Otyugh Mutate
---
# [Otyugh Mutate](3-Mechanics\CLI\bestiary\aberration/otyugh-mutate-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 213*  

Rising from piles of carrion and filth exposed to Far Realm energy, an otyugh mutate grows chitinous, jet-black plating over its limbs. The plates contrast sharply with the translucent, almost ghostly, appearance of its flesh, which provides a grotesque window into the virulent refuse the otyugh recently consumed.

## Mutates

A creature exposed to the strange energy of the Far Realm risks developing mutations. Such a creature undergoes a metamorphosis as the powers of the Far Realm rewrite the fundamentals of the creature's existence.

Any creature can become a mutate and transform to exhibit physical characteristics associated with the Far Realm. Some creatures become mutates after prolonged exposure to Far Realm energy or magic drawn from that strange plane. Others deliberately change themselves, seeking to embrace the fell powers they worship. Creatures that become mutates often inexplicably change back to their previous forms once the Far Realm influence abates.

Forcing a transformation on creatures inexplicably fails, though evil forces—such as the mind flayer empire of old—have conducted much research on the topic. For centuries, mind flayers have tried to create armies of mutates to sweep through the Underdark. However, their efforts always proved fruitless, and eventually the mind flayers gave up their schemes.

Several common types of mutates exist. The individuals with stat blocks presented in this section are found in the preceding adventure, although other mutates exist. Some creatures are more prone to becoming Far Realm mutates, such as the cloaker and otyugh.

Mutates often gain psionic abilities, grow wings, become covered in otherworldly slime, or exhibit other unsettling traits. Specific mutated creatures are further described in appendix A.

```statblock
"name": "Otyugh Mutate (PaBTSO)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Neutral"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "76"
"hit_dice": "8d10 + 32"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "18"
  - !!int "10"
  - !!int "15"
  - !!int "6"
"speed": "30 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "7"
"damage_immunities": "poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 12"
"languages": "Otyugh, telepathy 120 ft."
"cr": "6"
"traits":
  - "desc": "Noxious gas from the mutate's digestion of previous meals spews from\
      \ its mouth. At the start of the mutate's turn, each creature within 5 feet\
      \ of it must succeed on a DC 15 Constitution saving throw or take 3 (1d6) poison\
      \ damage."
    "name": "Virulent Breath"
"actions":
  - "desc": "The mutate makes two Bite or Tentacle attacks. It can replace one of\
      \ these attacks with Chitin Slam."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) piercing damage. If the target is a creature, it must succeed on\
      \ a DC 15 Constitution saving throw or have the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ condition. Every 24 hours that elapse, the target must repeat the saving throw,\
      \ reducing its hit point maximum by 5 (1d10) on a failure. On a successful save,\
      \ the target is no longer [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned).\
      \ The target dies if its hit point maximum is reduced to 0. This reduction to\
      \ the target's hit point maximum lasts until it no longer has the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ condition."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage, and if the target is a Medium or smaller creature,\
      \ it has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape\
      \ DC 15) and the [restrained](/3-Mechanics/CLI/conditions.md#Restrained) condition\
      \ until this grapple ends. The mutate has two tentacles that can grapple one\
      \ target each."
    "name": "Tentacle"
  - "desc": "The mutate targets one creature it is grappling, slamming the creature\
      \ against its chitinous plating. The creature must succeed on a DC 15 Constitution\
      \ saving throw or take 16 (3d10) bludgeoning damage and have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition until the end of the mutate's next turn."
    "name": "Chitin Slam"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/otyugh-mutate-pabtso.webp"
```
^statblock