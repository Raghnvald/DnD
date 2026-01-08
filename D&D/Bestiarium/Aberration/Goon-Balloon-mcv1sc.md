---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/mcv1sc
- Monster/HG/1-8
- Monster/Größe/Mittelgroß
- Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- Goon Balloon
---
# [Goon Balloon](3-Mechanics\CLI\bestiary\aberration/goon-balloon-mcv1sc.md)
*Source: Monstrous Compendium Volume 1: Spelljammer Creatures p. 9*  

> [!quote] A quote from Final log entry of Arquebus Graves, giff first mate of the wasp ship Lightning Bolt  
> 
> We found several of the creatures in an astral diamond mine at the edge of Greyspace. The miners wanted us to eliminate them. Our warlock, who was fluent in Deep Speech, managed to convince the bulbous creatures to relocate peacefully. They insisted we take them to a small, misshapen moon that doesn't appear on our charts. A horrible fear grips me. What if they're leading us into a trap?

A goon balloon looks like a 5-foot-diameter beach ball with clawed feet. Unblinking eyes on the outer surface of its spherical air sac enable the creature to see in all directions at once. These eyes can produce kaleidoscopic light that tears at the minds of the goon balloon's foes.

A goon balloon speaks by pumping air through a hidden orifice on its underside. When the goon balloon dies, the air in its sac transforms into a noxious gas that bursts from the corpse, potentially poisoning other creatures nearby.

Although they can seem playful and harmless, goon balloons are quite mean-spirited. They like to observe the suffering of other creatures and orchestrate that suffering, given half a chance.

```statblock
"name": "Goon Balloon (MCV1SC)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "10"
"hp": !!int "6"
"hit_dice": "1d8 + 2"
"modifier": !!int "0"
"stats":
  - !!int "10"
  - !!int "11"
  - !!int "14"
  - !!int "11"
  - !!int "14"
  - !!int "4"
"speed": "20 ft., climb 20 ft."
"saves":
  - "constitution": !!int "4"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
"damage_vulnerabilities": "piercing"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Deep Speech"
"cr": "1/8"
"traits":
  - "desc": "The goon balloon bursts when it drops to 0 hit points, releasing noxious\
      \ gas in a 10-foot-radius sphere centered on itself. Creatures in that area\
      \ must succeed on a DC 12 Constitution saving throw or be poisoned for 1 minute.\
      \ A poisoned creature can repeat the saving throw at the end of each of its\
      \ turns, ending the effect on itself on a success."
    "name": "Burst"
  - "desc": "The goon balloon doesn't require air, food, or drink."
    "name": "Unusual Nature"
"actions":
  - "desc": "The goon balloon makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 3 (1d6)\
      \ slashing damage."
    "name": "Claw"
  - "desc": "Magical, kaleidoscopic light emanates from one of the goon balloon's\
      \ eyes as the goon balloon targets one creature it can see within 30 feet of\
      \ itself. The target must make a DC 12 Wisdom saving throw, taking 6 (1d12)\
      \ psychic damage on a failed save, or half as much damage on a successful one."
    "name": "Scintillating Eye"
"bonus_actions":
  - "desc": "The goon balloon moves up to 20 feet vertically in one direction without\
      \ provoking opportunity attacks. If it ends this movement suspended in the air,\
      \ it hovers in place. It can't be knocked prone while airborne."
    "name": "Float"
"source":
  - "MCV1SC"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/goon-balloon-mcv1sc.webp"
```
^statblock