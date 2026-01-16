---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Orinix
---
# [Orinix](3-Mechanics\CLI\bestiary\npc/orinix-veor.md)
*Source: Vecna: Eve of Ruin*  

```statblock
"name": "Orinix (VEoR)"
"size": "Huge"
"type": "dragon"
"alignment": "typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "172"
"hit_dice": "15d12 + 75"
"modifier": !!int "1"
"stats":
  - !!int "23"
  - !!int "12"
  - !!int "20"
  - !!int "10"
  - !!int "13"
  - !!int "15"
"speed": "40 ft., burrow 20 ft., fly 80 ft."
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "Perception"
    "desc": "+11"
  - "name": "Stealth"
    "desc": "+11"
"damage_immunities": "cold"
"senses": "darkvision 240 ft., passive Perception 21"
"languages": "Draconic"
"cr": "13"
"traits":
  - "desc": "If Orinix fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "Orinix can burrow through solid rock at half its burrowing speed and\
      \ leaves a 15-foot-diameter tunnel in its wake."
    "name": "Tunneler"
  - "desc": "Orinix doesn't require air."
    "name": "Unusual Nature"
"actions":
  - "desc": "Orinix makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 13\
      \ (2d6 + 6) piercing damage plus 3 (1d6) cold damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d6 + 6) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 15 ft., one target. *Hit:* 13\
      \ (2d6 + 6) bludgeoning damage."
    "name": "Tail"
  - "desc": "Orinix exhales a blast of frost in a 60-foot cone. Each creature in the\
      \ cone must make a DC 18 Constitution saving throw. On a failed save, the creature\
      \ takes 36 (8d8) cold damage, and its speed is reduced to 0 until the end of\
      \ its next turn. On a successful save, the creature takes half as much damage,\
      \ and its speed isn't reduced."
    "name": "Cold Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "Orinix becomes partially incorporeal for as long as it maintains concentration\
      \ on the effect (as if concentrating on a spell). While partially incorporeal,\
      \ Orinix has resistance to bludgeoning, piercing, and slashing damage."
    "name": "Phase (3/Day)"
"legendary_description": "Legendary Action Uses: 2. Immediately after another creature's\
  \ turn, Orinix can expend a use to take one of the following actions. Orinix regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Orinix makes one Tail attack."
    "name": "Tail Attack"
  - "desc": "Magical ice covers the ground in a 20-foot radius centered on a point\
      \ Orinix can see within 120 feet of itself. The ice, which is difficult terrain\
      \ for all creatures except lunar dragons, lasts for 10 minutes or until Orinix\
      \ uses this legendary action again."
    "name": "Treacherous Ice"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/orinix-veor.webp"
```
^statblock