---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Merrow Shallowpriest
Status: WIP
linter-yaml-title-alias: Merrow Shallowpriest
tags:
  - Monster/Größe/Groß
  - Monster/HG/4
  - Monster/Typ/Monstrosität
  - Quelle/5e/egw
aliases:
  - Merrow Shallowpriest
---
# [Merrow Shallowpriest](3-Mechanics\CLI\bestiary\monstrosity/merrow-shallowpriest-egw.md)
*Source: Explorer's Guide to Wildemount p. 294*  

Some of the many merrow that dwell in the watery shadows of the Menagerie Coast learn to harness the magical aspects of the elements. Often working as guides leading merrow hunting parties, some of these shallowpriests rise to become powerful leaders, inspiring their clans to terrorize coastal communities and passing ships.

Rumors speak of underground waterways and lakes carved into the rock beneath Wildemount, where shallowpriests hold court over huge subterranean communities of merrow. These evil creatures are thought to seek the means of flooding the surface world, allowing them to steal away who and what they will to the dark waters below.

While most shallowpriests do not bind themselves in the service of a specific deity, some are drawn to the worship of entities that reign over regions of the Elemental Plane of Water, hoping to find means of expanding their dominion into the seas of Exandria. These merrow often spearhead the construction of intricate shrines and temples along the bottom of the ocean, preparing a sacred space for planar doorways to their master's realm to be opened and maintained.

```statblock
"name": "Merrow Shallowpriest (EGW)"
"size": "Large"
"type": "monstrosity"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "75"
"hit_dice": "10d10 + 20"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "11"
  - !!int "16"
  - !!int "9"
"speed": "10 ft., swim 40 ft."
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": "Abyssal, Aquan"
"cr": "4"
"traits":
  - "desc": "The merrow is a 6th-level spellcaster. Its spellcasting ability is Wisdom\
      \ (spell save DC 13, +5 to hit with spell attacks). The merrow has the following\
      \ druid spells prepared:\n\n**Cantrips (at will):** [druidcraft](/3-Mechanics/CLI/spells/druidcraft-xphb.md),\
      \ [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md), [shocking\
      \ grasp](/3-Mechanics/CLI/spells/shocking-grasp-xphb.md)\n\n**1st level (4 slots):**\
      \ [cure wounds](/3-Mechanics/CLI/spells/cure-wounds-xphb.md), [fog cloud](/3-Mechanics/CLI/spells/fog-cloud-xphb.md),\
      \ [thunderwave](/3-Mechanics/CLI/spells/thunderwave-xphb.md)\n\n**2nd level\
      \ (3 slots):** [hold person](/3-Mechanics/CLI/spells/hold-person-xphb.md), [mirror\
      \ image](/3-Mechanics/CLI/spells/mirror-image-xphb.md), [misty step](/3-Mechanics/CLI/spells/misty-step-xphb.md)\n\
      \n**3rd level (3 slots):** [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [lightning bolt](/3-Mechanics/CLI/spells/lightning-bolt-xphb.md) (see \"Actions\"\
      \ below), [sleet storm](/3-Mechanics/CLI/spells/sleet-storm-xphb.md)"
    "name": "Spellcasting"
  - "desc": "The merrow can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 11 (2d6 + 4) piercing damage. If the target is a Medium\
      \ or smaller creature, the merrow can pull it 10 feet closer."
    "name": "Harpoon"
  - "desc": "The merrow unleashes a stroke of lightning in a line 100 feet long and\
      \ 5 feet wide. Each creature in the line must make a DC 13 Dexterity saving\
      \ throw, taking 28 (8d6) lightning damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Lightning Bolt (3rd-Level Spell; Requires a Spell Slot)"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/merrow-shallowpriest-egw.webp"
```
^statblock