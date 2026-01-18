---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/1-2
  - Monster/Größe/Klein
  - Monster/Typ/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Gnome Squidling
---
# [Gnome Squidling](3-Mechanics\CLI\bestiary\aberration/gnome-squidling-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 303*  

Mind flayers, which are described in the Monster Manual, are created through ceremorphosis, a process that begins with the implantation of an illithid tadpole in the brain of a humanoid host. After about seven days in its new home, the tadpole transforms its host into a mind flayer. The new creation typically retains no memory of its previous existence.

When the process of turning a gnome into a mind flayer goes horribly awry, the result is a gnome squidling—a deformed mind flayer with weak, spindly limbs and oversized tentacles. It relies on levitation to keep its body aloft and uses its tentacles like legs, to propel it along whatever surface it's floating above. Most mind flayers destroy squidlings on sight, so it's rare to see one or more of these creatures.

Squidlings eat brains for sustenance, just like other mind flayers do, and they don't care where the brains come from.

```statblock
"name": "Gnome Squidling (IDRotF)"
"size": "Small"
"type": "aberration"
"alignment": "Unaligned"
"ac": !!int "8"
"hp": !!int "10"
"hit_dice": "3d6"
"modifier": !!int "-2"
"stats":
  - !!int "4"
  - !!int "7"
  - !!int "10"
  - !!int "4"
  - !!int "10"
  - !!int "3"
"speed": "15 ft."
"senses": "darkvision 60 ft., passive Perception 10"
"languages": "understands Deep Speech and Gnomish but can't speak, telepathy 60 ft."
"cr": "1/2"
"traits":
  - "desc": "The squidling's innate spellcasting ability is Intelligence (spell save\
      \ DC 7). It can innately cast levitate at will, requiring no components.\n"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "The squidling has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +0 to hit, reach 5 ft., one creature. *Hit:* 5\
      \ (2d4) psychic damage. If the target is Medium or smaller, it is grappled (escape\
      \ DC 7) and must succeed on a DC 7 Intelligence saving throw or be stunned until\
      \ this grapple ends."
    "name": "Tentacles"
  - "desc": "*Melee Weapon Attack:* +0 to hit, reach 5 ft., one incapacitated creature\
      \ grappled by the squidling. *Hit:* 27 (5d10) piercing damage. If this damage\
      \ reduces the target to 0 hit points, the squidling kills the target by extracting\
      \ and devouring its brain."
    "name": "Extract Brain"
  - "desc": "The squidling magically emits psychic energy in a 30-foot cone. Each\
      \ creature in that area must succeed on a DC 7 Intelligence saving throw or\
      \ take 2 (1d4) psychic damage and be stunned until the end of its next turn."
    "name": "Mind Tickle (Recharge 5-6)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/gnome-squidling-idrotf.webp"
```
^statblock