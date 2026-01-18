---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/3
  - Monster/Größe/Mittelgroß
  - Monster/Typ/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Galvan Magen
---
# [Galvan Magen](3-Mechanics\CLI\bestiary\construct/galvan-magen-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 301*  

Galvan magen can fly. They also store static electricity, which they discharge as lightning bolts.

Magen are magical, humanlike beings created by a wizard spell (see the [create magen](/3-Mechanics/CLI/spells/create-magen-idrotf.md) spell in appendix D) or by other arcane methods.

Though magen look like humanoids with green skin, they are constructs. When one is wounded, its blood is seen to have the color and consistency of mercury. They exist purely through magical means. When one is killed, its body disappears in a burst of harmless fire and a cloud of smoke that quickly dissipates.

```statblock
"name": "Galvan Magen (IDRotF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "14"
"hp": !!int "68"
"hit_dice": "8d8 + 32"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "18"
  - !!int "12"
  - !!int "10"
  - !!int "7"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_immunities": "lightning, poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "passive Perception 10"
"languages": "understands the languages of its creator but can't speak"
"cr": "3"
"traits":
  - "desc": "If the magen dies, its body disintegrates in a harmless burst of fire\
      \ and smoke, leaving behind anything it was wearing or carrying."
    "name": "Fiery End"
  - "desc": "The magen has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The magen doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The magen makes two Shocking Touch attacks."
    "name": "Multiattack"
  - "desc": "*Melee Spell Attack:* +6 to hit, reach 5 ft., one target (the magen has\
      \ advantage on the attack roll if the target is wearing armor made of metal).\
      \ *Hit:* 7 (1d6 + 4) lightning damage."
    "name": "Shocking Touch"
  - "desc": "The magen discharges a lightning bolt in a 60-foot line that is 5 feet\
      \ wide. Each creature in that line must make a DC 14 Dexterity saving throw\
      \ (with disadvantage if the creature is wearing armor made of metal), taking\
      \ 22 (4d10) lightning damage on a failed save, or half as much damage on a successful\
      \ one."
    "name": "Static Discharge (Recharge 5-6)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/construct/token/galvan-magen-idrotf.webp"
```
^statblock