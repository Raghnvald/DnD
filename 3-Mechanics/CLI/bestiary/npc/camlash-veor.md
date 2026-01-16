---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- Camlash
---
# [Camlash](3-Mechanics\CLI\bestiary\npc/camlash-veor.md)
*Source: Vecna: Eve of Ruin p. 181*  

Camlash is a monstrous demon covered in countless tiny, crawling spiders that appear and disappear at random.

Lolth isn't present in Pandesmos; she has given command of her legions to Camlash. The balor general specializes in leading campaigns with troops of loyal driders and mutated arachnids. Adherents of Lolth have joined Camlash's forces, despite the usual animosity between driders and people. All fight together in Lolth's name.

```statblock
"name": "Camlash (VEoR)"
"size": "Huge"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "325"
"hit_dice": "26d12 + 156"
"modifier": !!int "2"
"stats":
  - !!int "26"
  - !!int "15"
  - !!int "22"
  - !!int "20"
  - !!int "16"
  - !!int "22"
"speed": "40 ft., fly 80 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "12"
  - "wisdom": !!int "9"
  - "charisma": !!int "12"
"damage_resistances": "cold; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "truesight 120 ft., passive Perception 13"
"languages": "Abyssal, telepathy 120 ft."
"cr": "19"
"traits":
  - "desc": "Camlash explodes when reduced to 0 hit points, and each creature within\
      \ 30 feet of Camlash must make a DC 21 Dexterity saving throw, taking 70 (20d6)\
      \ fire damage on a failed save or half as much damage on a successful one. The\
      \ explosion ignites flammable objects in that area that aren't being worn or\
      \ carried."
    "name": "Death Throes"
  - "desc": "Camlash has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Camlash is surrounded by tiny biting spiders that magically appear and\
      \ disappear from moment to moment. At the start of each of Camlash's turns,\
      \ each creature within 10 feet of Camlash takes 10 (3d6) poison damage and must\
      \ succeed on a DC 21 Constitution saving throw or have the paralyzed condition\
      \ until the start of Camlash's next turn."
    "name": "Spider Aura"
"actions":
  - "desc": "Camlash makes one Flaming Whip attack and one Lightning Blade attack.\
      \ Camlash can replace one of these attacks with Teleport."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 30 ft., one target. *Hit:* 25\
      \ (5d6 + 8) fire damage, and if the target is a creature, it must succeed on\
      \ a DC 21 Strength saving throw or be pulled up to 25 feet toward Camlash."
    "name": "Flaming Whip"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:* 21\
      \ (3d8 + 8) slashing damage plus 13 (3d8) lightning damage."
    "name": "Lightning Blade"
  - "desc": "Camlash magically teleports, along with any equipment she is wearing\
      \ or carrying, up to 120 feet to an unoccupied space she can see."
    "name": "Teleport"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/camlash-veor.webp"
```
^statblock