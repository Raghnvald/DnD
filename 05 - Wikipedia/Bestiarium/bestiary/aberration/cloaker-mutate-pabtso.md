---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/cr/10
  - Monster/Größe/Groß
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Cloaker Mutate
Größe: Groß
HG: 10
Typ: Aberration
---
# [Cloaker Mutate](3-Mechanics\CLI\bestiary\aberration/cloaker-mutate-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 212*  

The malign energy of the Far Realm causes a cloaker to merge with the rotted corpse of its last meal, resulting in a hideous puppeteering Aberration. The cloaker mutate shrouds its actions in a miasma of phantasmic duplicates. It uses the corpse melded to its underside to absorb damage and to strike at prey.

## Mutates

A creature exposed to the strange energy of the Far Realm risks developing mutations. Such a creature undergoes a metamorphosis as the powers of the Far Realm rewrite the fundamentals of the creature's existence.

Any creature can become a mutate and transform to exhibit physical characteristics associated with the Far Realm. Some creatures become mutates after prolonged exposure to Far Realm energy or magic drawn from that strange plane. Others deliberately change themselves, seeking to embrace the fell powers they worship. Creatures that become mutates often inexplicably change back to their previous forms once the Far Realm influence abates.

Forcing a transformation on creatures inexplicably fails, though evil forces—such as the mind flayer empire of old—have conducted much research on the topic. For centuries, mind flayers have tried to create armies of mutates to sweep through the Underdark. However, their efforts always proved fruitless, and eventually the mind flayers gave up their schemes.

Several common types of mutates exist. The individuals with stat blocks presented in this section are found in the preceding adventure, although other mutates exist. Some creatures are more prone to becoming Far Realm mutates, such as the cloaker and otyugh.

Mutates often gain psionic abilities, grow wings, become covered in otherworldly slime, or exhibit other unsettling traits. Specific mutated creatures are further described in appendix A.

```statblock
"name": "Cloaker Mutate (PaBTSO)"
"size": "Large"
"type": "aberration"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "143"
"hit_dice": "22d10 + 22"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "15"
  - !!int "12"
  - !!int "18"
  - !!int "13"
  - !!int "11"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "necrotic, poison, psychic"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 11"
"languages": "Deep Speech, telepathy 60 ft., Undercommon"
"cr": "10"
"traits":
  - "desc": "If the mutate is subjected to an effect that allows it to make a saving\
      \ throw to take only half damage, it instead takes no damage if it succeeds\
      \ on the saving throw, and only half damage if it fails."
    "name": "Avoidance"
  - "desc": "While in bright light, the mutate has disadvantage on attack rolls."
    "name": "Light Sensitivity"
"actions":
  - "desc": "The mutate makes one Corpse Swipe attack and two Tail attacks, or it\
      \ makes four Tail attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 20\
      \ (3d10 + 4) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 16 Constitution saving throw or have the [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ condition for 1 minute. While [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ in this way, a creature can't regain hit points."
    "name": "Corpse Swipe"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 13\
      \ (2d8 + 4) slashing damage."
    "name": "Tail"
"bonus_actions":
  - "desc": "The mutate magically projects up to four illusory copies of itself. These\
      \ duplicates make it difficult to ascertain the mutate's true location and last\
      \ until the end of the mutate's next turn. While the copies exist, attack rolls\
      \ against the mutate are made with disadvantage."
    "name": "Phantasmal Duplicates"
  - "desc": "The mutate lets out a moan charged with psychic energy. Each creature\
      \ within 60 feet of the mutate that isn't an Aberration must succeed on a DC\
      \ 16 Wisdom saving throw or take 17 (5d6) psychic damage and have the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition until the end of the mutate's next turn."
    "name": "Psychic Moan (Recharge 6)"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/cloaker-mutate-pabtso.webp"
```
^statblock