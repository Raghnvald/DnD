---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/mcv2dc
- new/monster/cr/5
- new/monster/size/small
- new/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- Nevermind Gnome Mastermind
---
# [Nevermind Gnome Mastermind](3-Mechanics\CLI\bestiary\humanoid/nevermind-gnome-mastermind-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 11*  

The gnome masterminds of Mount Nevermind temper their creativity with years of experience. While they still create wild inventions on a whim, these masterminds also wield at least one more stable clockwork invention—typically something that affords the mastermind more movement, extends their reach with extra appendages, or both.

## Nevermind Gnomes

Mount Nevermind is a hollow, dormant volcano on the island of Sancrist in Krynn. Within the mountain, a vibrant community of rock gnome tinkerers and other inventors relentlessly study various scientific pursuits to create mechanical marvels.

```statblock
"name": "Nevermind Gnome Mastermind (MCV2DC)"
"size": "Small"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "15"
"ac_class": "leather armor"
"hp": !!int "82"
"hit_dice": "15d6 + 30"
"modifier": !!int "4"
"stats":
  - !!int "9"
  - !!int "18"
  - !!int "14"
  - !!int "20"
  - !!int "11"
  - !!int "15"
"speed": "30 ft., climb 30 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "5"
  - "intelligence": !!int "8"
"skillsaves":
  - "name": "Arcana"
    "desc": "+8"
  - "name": "Investigation"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common, Gnomish"
"cr": "5"
"traits":
  - "desc": "The mastermind has advantage on initiative rolls."
    "name": "Always Thinking Ahead"
  - "desc": "The mastermind can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check. This trait doesn't function\
      \ if the mastermind is grappling creatures in both of its clockwork claws."
    "name": "Spider Climb"
"actions":
  - "desc": "The mastermind makes two Clockwork Claw attacks. The mastermind can replace\
      \ one of these attacks with Generate Gadget if it's available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 20 ft., one target. *Hit:* 11\
      \ (2d6 + 4) piercing damage, and if the target is a Medium or smaller creature,\
      \ the target is grappled (escape DC 15). Until this grapple ends, the target\
      \ takes 10 (3d6) piercing damage at the start of each of the mastermind's turns.\
      \ The mastermind has two claws, each of which can grapple only one target."
    "name": "Clockwork Claw"
  - "desc": "The mastermind quickly assembles a clockwork gadget, producing one of\
      \ the following effects (the mastermind's choice):"
    "name": "Generate Gadget (Recharge 5-6)"
  - "desc": "Parts of this gadget look like gnashing metal teeth. This gadget hurtles\
      \ toward a creature the mastermind can see within 60 feet of itself. The creature\
      \ must succeed on a DC 16 Dexterity saving throw or take 31 (7d8) piercing damage\
      \ and be incapacitated until the start of the mastermind's next turn."
    "name": "Chattergrab"
  - "desc": "The mastermind launches this gadget to a point the mastermind can see\
      \ within 30 feet of itself, where the gadget unleashes a cloud of mind-warping\
      \ gases in a 10-foot-radius sphere. Each creature within the sphere must succeed\
      \ on a DC 16 Wisdom saving throw or take 11 (2d10) psychic damage and be frightened\
      \ of the mastermind until the start of the mastermind's next turn."
    "name": "Phasmoball"
  - "desc": "This gadget emits a screeching wave of sound in a 30-foot cone originating\
      \ from the mastermind. Each creature in that area must make a DC 16 Constitution\
      \ saving throw, taking 21 (6d6) thunder damage on a failed save or half as much\
      \ damage on a successful one."
    "name": "Thunderscream"
"source":
  - "MCV2DC"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/nevermind-gnome-mastermind-mcv2dc.webp"
```
^statblock