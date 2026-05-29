---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Kobold Scale Sorcerer
linter-yaml-title-alias: Kobold Scale Sorcerer
tags:
  - Monster/Größe/Klein
  - Monster/Habitat/Berg
  - Monster/Habitat/Hügel
  - Monster/Habitat/Stadt
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wald
  - Monster/HG/1
  - Monster/Typ/Humanoid/kobold
  - Quelle/5e/vgm
aliases:
  - Kobold Scale Sorcerer
---
# [Kobold Scale Sorcerer](3-Mechanics\CLI\bestiary\humanoid/kobold-scale-sorcerer-vgm.md)
*Source: Volo's Guide to Monsters p. 167, Tomb of Annihilation*  

A kobold scale sorcerer has an innate talent for arcane magic, making it a highly valuable member of the tribe for several reasons. Because the kobolds' deity remains imprisoned, most tribes lack individuals that can use divine magic, and so the scale sorcerers fill the roles of advisor and historian. In times of peace, they use their spells to fortify and enhance the warren and aid the rest of the tribe. When the tribe is threatened, a scale sorcerer lashes out with fire and poison against enemies, saving a bit of magic for itself in case it needs to flee or take advantage of a captor.

## Duty-Bound to a Dragon

In a kobold tribe associated with a dragon, typically one that resides in or near the dragon's lair, the scale sorcerer also serves as diplomat and mouthpiece-anticipating the dragon's needs, issuing commands to other kobolds on the dragon's behalf, and reporting information back to the dragon. The sorcerer is just as awed by and respectful of dragons as common kobolds are, but it knows that its duty requires it not to fawn over its master at all times. It also understands that its frequent proximity to the dragon means it would probably be the first to die if its master became angry or displeased, and so it frantically maintains a balance between adoration and terror in its behavior toward the dragon.

```statblock
"name": "Kobold Scale Sorcerer (VGM)"
"size": "Small"
"type": "humanoid"
"subtype": "kobold"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "5d6 + 10"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "15"
  - !!int "14"
  - !!int "10"
  - !!int "9"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "Arcana"
    "desc": "+2"
  - "name": "Medicine"
    "desc": "+1"
"senses": "darkvision 60 ft., passive Perception 9"
"languages": "Common, Draconic"
"cr": "1"
"traits":
  - "desc": "The kobold is a 3rd-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 12, +4 to hit with spell attacks). It has the following sorcerer\
      \ spells prepared:\n\n**Cantrips (at will):** fire bolt, mage hand, mending,\
      \ poison spray\n\n**1st level (4 slots):** charm person, chromatic orb, expeditious\
      \ retreat\n\n**2nd level (2 slots):** scorching ray"
    "name": "Spellcasting"
  - "desc": "The kobold has 3 sorcery points. It regains all its spent sorcery points\
      \ when it finishes a long rest. It can spend its sorcery points on the following\
      \ options:\n\nHeightened Spell: When it casts a spell that forces a creature\
      \ to a saving throw to resist the spell's effects, the kobold can spend 3 sorcery\
      \ points to give one target of the spell disadvantage on its first saving throw\
      \ against the spell.\n\nSubtle Spell: When the kobold casts a spell, it can\
      \ spend 1 sorcery point to cast the spell without any somatic or verbal components."
    "name": "Sorcery Points"
  - "desc": "The kobold has advantage on an attack roll against a creature it at least\
      \ one of the kobold's allies is within 5 feet of the creature and the ally isn't\
      \ incapacitated."
    "name": "Pack Tactics"
  - "desc": "While in sunlight, the kobold has disadvantage on attack rolls, as well\
      \ as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "VGM"
  - "ToA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/kobold-scale-sorcerer-vgm.webp"
```
^statblock

## Environment

underdark, mountain, forest, hill, urban