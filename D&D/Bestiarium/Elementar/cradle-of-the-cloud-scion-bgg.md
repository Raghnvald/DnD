---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/26
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- Cradle of the Cloud Scion
---
# [Cradle of the Cloud Scion](3-Mechanics\CLI\bestiary\elemental/cradle-of-the-cloud-scion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 166*  

A slumbering scion of Memnor appears as a dense, slowly drifting tower of clouds that never dissipates. Often, this cloud lingers over a remote valley, creating a constantly overcast sky. Sapient creatures who live beneath this cloud often display superstitious and duplicitous behavior, almost unconsciously leaving gifts for "rain spirits" while playing mischievous pranks on each other.

When roused, a cradle of the cloud scion manifests as a titanic air elemental made of fierce winds and wisps of cloud. It wields air and thunder to knock enemies from the sky.

If the cradle is destroyed, the scion of Memnor emerges from the dissipating cloud, often laughing as if it just heard a great joke. Incredibly tall and lanky, the scion towers 75 feet tall and wields a morningstar made from magically dense clouds.

It tends to regard other creatures as toys rather than serious threats, and it uses its illusion magic to manipulate creatures into fighting each other. If seriously threatened, it wields thunder and wind to demolish its enemies.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Cradle of the Cloud Scion (BGG)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "624"
"hit_dice": "32d20 + 288"
"modifier": !!int "5"
"stats":
  - !!int "29"
  - !!int "21"
  - !!int "28"
  - !!int "14"
  - !!int "22"
  - !!int "19"
"speed": "0 ft., fly 90 ft. (hover)"
"saves":
  - "intelligence": !!int "10"
  - "charisma": !!int "12"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison, thunder"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "passive Perception 16"
"languages": "Giant, Primordial"
"cr": "26"
"traits":
  - "desc": "The cradle is a container for the [scion of Memnor](/3-Mechanics/CLI/bestiary/giant/scion-of-memnor-bgg.md).\
      \ When the cradle drops to 0 hit points, its body dissipates into cloud wisps.\
      \ The scion instantly appears in the space the cradle occupied and uses the\
      \ cradle's initiative count."
    "name": "Awakening of the Scion"
  - "desc": "The cradle doesn't provoke opportunity attacks when it flies out of an\
      \ enemy's reach."
    "name": "Flyby"
  - "desc": "If the cradle fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "The cradle has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The cradle deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The cradle makes three Slam or Wind Javelin attacks in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 20 ft., one target. *Hit:* 31\
      \ (4d10 + 9) bludgeoning damage plus 19 (3d12) thunder damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +17 to hit, range 120 ft., one target. *Hit:*\
      \ 27 (4d8 + 9) bludgeoning damage plus 10 (3d6) thunder damage, and the target\
      \ must succeed on a DC 25 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Wind Javelin"
  - "desc": "The cradle conjures a vortex of wind at a point it can see within 90\
      \ feet of itself. The wind vortex is a 30-foot-radius, 100-foot-high cylinder\
      \ centered on that point. Each creature other than the cradle in that area must\
      \ make a DC 25 Dexterity saving throw. On a failed save, a creature takes 71\
      \ (11d12) bludgeoning damage and has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition within the vortex. On a successful save, a creature takes half as\
      \ much damage and is pushed to the nearest unoccupied space outside the cylinder.\
      \ The vortex lasts until the start of the cradle's next turn. A creature with\
      \ the [restrained](/3-Mechanics/CLI/conditions.md#Restrained) condition falls\
      \ [prone](/3-Mechanics/CLI/conditions.md#Prone) when the vortex ends.\n\nA creature\
      \ with the [restrained](/3-Mechanics/CLI/conditions.md#Restrained) condition\
      \ can use its action to try to escape the vortex. The creature makes a DC 19\
      \ Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) or Dexterity\
      \ ([Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)) check. On a successful\
      \ check, the creature escapes and moves 3d6 × 10 feet away from the vortex in\
      \ a random direction."
    "name": "Vortex (Recharge 5-6)"
"reactions":
  - "desc": "Immediately after taking damage, the cradle unleashes a thunderclap in\
      \ a 30-foot-radius sphere centered on itself. All other creatures in that area\
      \ must succeed on a DC 25 Constitution saving throw or take 18 (4d8) thunder\
      \ damage and have the [deafened](/3-Mechanics/CLI/conditions.md#Deafened) condition\
      \ for 1 minute."
    "name": "Thunderclap"
"regional_effects":
  - "desc": "The region surrounding a scion of Memnor is altered by the giant's magic,\
      \ creating one or more of the following effects:\n\n- **Compulsory Offering.**\
      \ The first time a sapient creature comes within 6 miles of the scion, the creature\
      \ must succeed on a DC 15 Wisdom saving throw or feel an overwhelming compulsion\
      \ to leave an offering worth at least 5 gp stashed in an out-of-the-way place.\
      \ Cloud giants within 6 miles of the cradle or scion immediately sense the location\
      \ of this gift. A creature can be affected only once by this compulsion.  \n\
      - **Empowered Cloud Giants.** Cloud giants within 1,000 feet of the scion gain\
      \ a +8 bonus to attack and damage rolls.  \n- **Mischievous Whispers.** Whispers\
      \ can be heard on the wind within 1 mile of the scion. The words are indistinct,\
      \ but a creature with an Intelligence score of 5 or higher interprets them as\
      \ instructions for a prank they can play on others.  \n\nIf the scion dies,\
      \ these effects end immediately."
    "name": ""
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/cradle-of-the-cloud-scion-bgg.webp"
```
^statblock