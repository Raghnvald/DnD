---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/vgm
- new/monster/cr/9
- new/monster/environment/urban
- new/monster/size/medium
- new/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- Evoker
---
# [Evoker](3-Mechanics\CLI\bestiary\humanoid/evoker-vgm.md)
*Source: Volo's Guide to Monsters p. 214, Tales from the Yawning Portal, Dragon of Icespire Peak, Storm Lord's Wrath, Eberron: Rising from the Last War*  

Evokers are specialist wizards who harness magical energy and elemental forces to destroy. Many tend to be hotheaded and aggressive. Others are cold and reserved, unleashing their power at just the right moment to exploit an opponent's weakness.

```statblock
"name": "Evoker (VGM)"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with mage armor"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "12"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "7"
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "Arcana"
    "desc": "+7"
  - "name": "History"
    "desc": "+7"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "9"
"traits":
  - "desc": "The evoker is a 12th-level spellcaster. Its spellcasting ability is Intelligence\
      \ (spell save DC 15, +7 to hit with spell attacks). The evoker has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** fire bolt*, light*, prestidigitation,\
      \ ray of frost*\n\n**1st level (4 slots):** burning hands*, mage armor, magic\
      \ missile*\n\n**2nd level (3 slots):** mirror image, misty step, shatter*\n\n\
      **3rd level (3 slots):** counterspell, fireball*, lightning bolt*\n\n**4th level\
      \ (3 slots):** ice storm*, stoneskin\n\n**5th level (2 slots):** Bigby's hand*,\
      \ cone of cold*\n\n**6th level (1 slots):** chain lightning*, wall of ice*\n\
      \n*Evocation spell"
    "name": "Spellcasting"
  - "desc": "When the evoker casts an evocation spell that forces other creatures\
      \ it can see to make a saving throw, it can choose a number of them equal to\
      \ 1 + the spell's level. These creatures automatically succeed on their saving\
      \ throws against the spell. If a successful save means a chosen creature would\
      \ take half damage from the spell, it instead takes no damage from it."
    "name": "Sculpt Spells"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 2 (1d6\
      \ - 1) bludgeoning damage, or 3 (1d8 - 1) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
"source":
  - "VGM"
  - "TftYP"
  - "DIP"
  - "SLW"
  - "ERLW"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/evoker-vgm.webp"
```
^statblock

## Environment

urban