---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cradle of the Hill Scion
---
# [Cradle of the Hill Scion](3-Mechanics\CLI\bestiary\elemental/cradle-of-the-hill-scion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 164*  

A slumbering scion of Grolantor is often mistaken for a hill, and sometimes people erect standing stones, a village, or a city on a scion's back, unaware of the mighty power beneath them. Such settlements can thrive for centuries, as the scion's magic causes crops to flourish and livestock to thrive in the surrounding region. An ancient tree towers from the crest of the hill.

When roused, a cradle of the hill scion rises as a mass of dirt, stone, and roots with two massive arms. The cradle uses tree roots and waves of dirt to entangle and entomb foes.

If the cradle is destroyed, the scion of Grolantor inside it awakens. Standing 50 feet tall, the scion devours everything within reach to satiate its hunger. Its powerful lungs can suck food straight into its gullet. The scion uses a great tree to bat foes far into the distance.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Cradle of the Hill Scion (BGG)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "typically  Chaotic Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "402"
"hit_dice": "23d20 + 161"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "24"
  - !!int "9"
  - !!int "16"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "10"
  - "charisma": !!int "7"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "passive Perception 13"
"languages": "Giant, Primordial"
"cr": "22"
"traits":
  - "desc": "The cradle is a container for the [scion of Grolantor](/3-Mechanics/CLI/bestiary/giant/scion-of-grolantor-bgg.md).\
      \ When the cradle drops to 0 hit points, its body crumbles to dirt and moss.\
      \ The scion instantly appears in the space the cradle occupied and uses the\
      \ cradle's initiative count."
    "name": "Awakening of the Scion"
  - "desc": "If the cradle fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "The cradle has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The cradle deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The cradle makes three Slam or Spit Rock attacks in any combination and\
      \ one Grasping Root attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 20 ft., one target. *Hit:* 33\
      \ (4d12 + 7) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +14 to hit, range 120 ft., one target. *Hit:*\
      \ 25 (4d8 + 7) bludgeoning damage, and the target must succeed on a DC 22 Strength\
      \ saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Spit Rock"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 30 ft., one creature not [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by the cradle. *Hit:* the target has the [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ condition (escape DC 17). Until the grapple ends, the target takes 29 (4d10\
      \ + 7) bludgeoning damage at the start of each of its turns. The root has AC\
      \ 19 and can be severed by dealing 15 or more slashing damage to it on one attack.\
      \ Cutting the root doesn't hurt the cradle but ends the grapple."
    "name": "Grasping Root"
  - "desc": "The cradle magically creates a wave of dirt that extends from a point\
      \ on the ground within 120 feet of itself. The wave is up to 30 feet long, up\
      \ to 30 feet tall, and up to 30 feet wide. Each creature in the wave must make\
      \ a DC 22 Strength saving throw. On a failed save, a creature takes 58 (9d12)\
      \ bludgeoning damage, has the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition, and is buried under dirt. On a successful save, a creature takes\
      \ half as much damage only.\n\nA buried creature has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition, has total cover, and can't breathe. As an action, a creature buried\
      \ in this way, or another creature within 5 feet of it that isn't buried, can\
      \ make a DC 17 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics))\
      \ check. On a successful check, the buried creature no longer has the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained) conditions."
    "name": "Rolling Hills (Recharge 6)"
"regional_effects":
  - "desc": "The region surrounding a scion of Grolantor is altered by the giant's\
      \ magic, creating one or more of the following effects:\n\n- **Abundant Food.**\
      \ Crops and domestic animals grow and reproduce quickly within 6 miles of the\
      \ scion.  \n- **Empowered Hill Giants.** Hill giants within 1,000 feet of the\
      \ scion gain a +7 bonus to attack and damage rolls.  \n- **Farming Weather.**\
      \ The weather within 6 miles of the scion is always ideal for farming: sunny\
      \ and warm with occasional showers.  \n\nIf the scion dies, these effects end\
      \ immediately."
    "name": ""
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/cradle-of-the-hill-scion-bgg.webp"
```
^statblock