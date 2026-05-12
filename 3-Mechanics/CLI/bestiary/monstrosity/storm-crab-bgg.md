---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Storm Crab"
---
# [Storm Crab](3-Mechanics/CLI/bestiary/monstrosity/storm-crab-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 181*  

Storm crabs are colossal crustaceans with four monstrous claws and a poisonous stinger. Equally adept underwater or on shore, they can exhale a jet of pressurized water to crush foes.

Giants on some worlds claim Stronmaus or one of his children created storm crabs in the early years of an ancient empire. Just as behirs were created to fight dragons on land and rocs to challenge dragons' mastery of the sky, storm crabs were meant to battle dragon turtles, bronze dragons, and other aquatic foes. On many worlds, these creatures fiercely guard the underwater strongholds of storm giants, as well as the ruined keeps giants have abandoned.

> [!quote] A quote from Bigby  
> 
> Given all the weird things that swim in the deep ocean, who am I to complain about a colossal crab with a poison stinger that can knock you away with a high-speed jet of water?


```statblock
"name": "Storm Crab (BGG)"
"size": "Gargantuan"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "155"
"hit_dice": "10d20 + 50"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "5"
  - !!int "14"
  - !!int "9"
"speed": "40 ft., swim 60 ft."
"saves":
  - "strength": !!int "10"
  - "constitution": !!int "9"
"skillsaves":
  - "name": "Perception"
    "desc": "+6"
"damage_resistances": "cold, fire, lightning"
"senses": "blindsight 60 ft., passive Perception 16"
"languages": "understands Giant but can't speak"
"cr": "11"
"traits":
  - "desc": "The crab can breathe air and water."
    "name": "Amphibious"
"actions":
  - "desc": "The crab makes two Claw attacks and one Stinger attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 15 ft., one target. *Hit:*\
      \ 19 (3d8 + 6) bludgeoning damage. If the target is a Huge or smaller creature,\
      \ it has the grappled condition (escape DC 16). The crab has four claws, each\
      \ of which can grapple one target."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one creature. *Hit:*\
      \ 22 (3d10 + 6) piercing damage, and the target must succeed on a DC 17 Constitution\
      \ saving throw or have the poisoned and paralyzed conditions for 1 minute. The\
      \ affected creature can repeat the saving throw at the end of each of its turns,\
      \ ending both the poisoned and paralyzed conditions on itself on a success."
    "name": "Stinger"
  - "desc": "The crab exhales water in a 150-foot line that is 10 feet wide. Each\
      \ creature in that area must make a DC 17 Dexterity saving throw. On a failed\
      \ save, a creature takes 27 (6d8) bludgeoning damage, is pushed up to 30 feet\
      \ from the crab, and has the prone condition. On a successful save, a creature\
      \ takes half as much damage only."
    "name": "Water Jet (Recharge 5-6)"
"source":
  - "BGG"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/storm-crab-bgg.webp"
```
^statblock