---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/1
  - Monster/Größe/Mittelgroß
  - Monster/Typ/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Hypnos Magen
---
# [Hypnos Magen](3-Mechanics\CLI\bestiary\construct/hypnos-magen-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 301*  

Hypnos magen are telepathic and use their power of suggestion to control others. Their creators use them to force enemies to withdraw or surrender.

A hypnos magen carries no weapons, relying entirely on its psychic abilities to manipulate and harm other creatures.

Magen are magical, humanlike beings created by a wizard spell (see the [create magen](/3-Mechanics/CLI/spells/create-magen-idrotf.md) spell in appendix D) or by other arcane methods.

Though magen look like humanoids with green skin, they are constructs. When one is wounded, its blood is seen to have the color and consistency of mercury. They exist purely through magical means. When one is killed, its body disappears in a burst of harmless fire and a cloud of smoke that quickly dissipates.

```statblock
"name": "Hypnos Magen (IDRotF)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "34"
"hit_dice": "4d8 + 16"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "18"
  - !!int "14"
  - !!int "10"
  - !!int "7"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "passive Perception 10"
"languages": "understands the languages of its creator but can't speak, telepathy\
  \ 30 ft."
"cr": "1"
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
  - "desc": "The magen's eyes glow silver as it targets one creature that it can see\
      \ within 60 feet of it. The target must succeed on a DC 12 Wisdom saving throw\
      \ or take 11 (2d10) psychic damage."
    "name": "Psychic Lash"
  - "desc": "The magen casts the suggestion spell (save DC 12), requiring no material\
      \ components. The target must be a creature that the magen can communicate with\
      \ telepathically. If it succeeds on its saving throw, the target is immune to\
      \ this magen's suggestion spell for the next 24 hours. The magen's spellcasting\
      \ ability is Intelligence."
    "name": "Suggestion"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/construct/token/hypnos-magen-idrotf.webp"
```
^statblock