---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/mcv1sc
- monster/cr/16
- monster/size/gargantuan
- monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- Nightmare Beast
---
# [Nightmare Beast](3-Mechanics\CLI\bestiary\monstrosity/nightmare-beast-mcv1sc.md)
*Source: Monstrous Compendium Volume 1: Spelljammer Creatures p. 10*  

Nightmare beasts are enormous quadrupeds that stand 20 feet tall, or 40 feet tall when rearing on their hind legs.

A nightmare beast's legs end in claws, enabling it to climb well despite its size. Its skin is thick and tough, and its teeth are long and sharp. A pair of long, curved tusks jut from the sides of the beast's mouth, and its large red eyes glow in the dark. The creature smashes through structures and fortifications with ease, and it doesn't hesitate to rend foes with its claws and gore them with its tusks, but its most devastating attack is its magical ability to disintegrate foes with its terrible gaze.

Powerful spellcasters create nightmare beasts to serve as living siege engines. A single beast can lay waste to entire cities and armies.

```statblock
"name": "Nightmare Beast (MCV1SC)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "typically  Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "232"
"hit_dice": "15d20 + 75"
"modifier": !!int "0"
"stats":
  - !!int "26"
  - !!int "10"
  - !!int "21"
  - !!int "9"
  - !!int "12"
  - !!int "15"
"speed": "30 ft., climb 30 ft."
"senses": "darkvision 120 ft., passive Perception 11"
"languages": "understands the languages of its creator but can't speak"
"cr": "16"
"traits":
  - "desc": "If the beast fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "The beast deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The beast makes two Claw attacks and one Tusk attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:* 14\
      \ (1d12 + 8) slashing damage, and if the target is a creature, it must succeed\
      \ on a DC 21 Strength saving throw or be knocked prone."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 15 ft., one target. *Hit:* 17\
      \ (2d8 + 8) slashing damage."
    "name": "Tusk"
  - "desc": "The beast targets one creature it can see within 60 feet of itself. The\
      \ target must make a DC 18 Constitution saving throw, taking 70 (10d6 + 40)\
      \ force damage on a failed save, or half as much damage on a successful one.\
      \ If this magical effect reduces the target to 0 hit points, the target is disintegrated\
      \ and leaves nothing behind, except a pile of ashes plus whatever equipment\
      \ it was wearing or carrying."
    "name": "Disintegration Gaze (Recharge 5-6)"
"bonus_actions":
  - "desc": "The beast magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 120 feet to an unoccupied space it can see."
    "name": "Teleport (2/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the nightmare beast can expend a use to take one of the following actions.\
  \ The nightmare beast regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The beast makes one Tusk attack."
    "name": "Tusk Attack"
  - "desc": "The beast moves up to its speed without provoking opportunity attacks,\
      \ then makes two Tusk attacks."
    "name": "Charge (Costs 2 Actions)"
  - "desc": "The beast howls as it exhales a cloud of magical fear gas in a 120-foot\
      \ cone. Any creature in that area must succeed on a DC 18 Wisdom saving throw\
      \ or be frightened of the beast for 1 minute. A creature can repeat the saving\
      \ throw at the end of each of its turns, ending the effect on itself on a success."
    "name": "Frightful Howl (Costs 2 Actions)"
"source":
  - "MCV1SC"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/nightmare-beast-mcv1sc.webp"
```
^statblock