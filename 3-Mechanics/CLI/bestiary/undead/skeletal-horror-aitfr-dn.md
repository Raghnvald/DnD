---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-dn
- ttrpg-cli/monster/cr/6
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Skeletal Horror"
---
# [Skeletal Horror](3-Mechanics/CLI/bestiary/undead/skeletal-horror-aitfr-dn.md)
*Source: Adventures in the Forgotten Realms: Deepest Night p. 13*  

This horrid mass of bones clambers along on a dozen hands and feet without maintaining any consistent shape. One moment it moves like a centipede, the next it rears back to claw like a bear. The only consistent feature is a weird absence: no matter how many skulls make up its mass, this strange horror always seems to be headless.

The skeletal horrors in Kyrilla's lair are made from the bones of yuan-ti supplicants and cultists who came to learn her powers or, later, to steal them. She spared none of these intruders' lives, and in death their remains do her bidding.

```statblock
"name": "Skeletal Horror (AitFR-DN)"
"size": "Large"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "150"
"hit_dice": "20d10 + 40"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "15"
  - !!int "6"
  - !!int "10"
  - !!int "5"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+3"
"damage_vulnerabilities": "bludgeoning"
"damage_immunities": "poison"
"condition_immunities": "exhaustion, poisoned"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": ""
"cr": "6"
"actions":
  - "desc": "The horror makes two attacks with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 19\
      \ (3d10 + 3) slashing damage."
    "name": "Claw"
  - "desc": "The horror crashes into foes like a wave before quickly reforming. Each\
      \ creature within 10 feet of the horror must make a DC 15 Dexterity saving throw,\
      \ taking 18 (4d8) bludgeoning damage on a failed save, or half as much damage\
      \ on a successful one. A creature that fails this saving throw is also knocked\
      \ prone."
    "name": "Wave of Bones (Recharge 5-6)"
"source":
  - "AitFR-DN"
"image": "3-Mechanics/CLI/bestiary/undead/token/skeletal-horror-aitfr-dn.webp"
```
^statblock