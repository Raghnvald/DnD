---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/26
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/giant/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- Scion of Memnor
---
# [Scion of Memnor](3-Mechanics\CLI\bestiary\giant/scion-of-memnor-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 167*  

A slumbering scion of Memnor appears as a dense, slowly drifting tower of clouds that never dissipates. Often, this cloud lingers over a remote valley, creating a constantly overcast sky. Sapient creatures who live beneath this cloud often display superstitious and duplicitous behavior, almost unconsciously leaving gifts for "rain spirits" while playing mischievous pranks on each other.

When roused, a cradle of the cloud scion manifests as a titanic air elemental made of fierce winds and wisps of cloud. It wields air and thunder to knock enemies from the sky.

If the cradle is destroyed, the scion of Memnor emerges from the dissipating cloud, often laughing as if it just heard a great joke. Incredibly tall and lanky, the scion towers 75 feet tall and wields a morningstar made from magically dense clouds.

It tends to regard other creatures as toys rather than serious threats, and it uses its illusion magic to manipulate creatures into fighting each other. If seriously threatened, it wields thunder and wind to demolish its enemies.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Scion of Memnor (BGG)"
"size": "Gargantuan"
"type": "giant"
"subtype": "titan"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "656"
"hit_dice": "32d20 + 320"
"modifier": !!int "4"
"stats":
  - !!int "30"
  - !!int "18"
  - !!int "30"
  - !!int "24"
  - !!int "22"
  - !!int "26"
"speed": "60 ft., fly 80 ft. (hover)"
"saves":
  - "dexterity": !!int "12"
  - "charisma": !!int "16"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+14"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "thunder"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [petrified](/3-Mechanics/CLI/conditions.md#Petrified)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 24"
"languages": "Giant, Primordial"
"cr": "26"
"traits":
  - "desc": "The scion doesn't provoke opportunity attacks when it flies out of an\
      \ enemy's reach."
    "name": "Flyby"
  - "desc": "If the scion fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (6/Day)"
  - "desc": "The scion has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The scion deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The scion makes one attack using Cloud Morningstar or Wind Javelin, as\
      \ well as two Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 30 ft., one target. *Hit:* 32\
      \ (4d10 + 10) force damage plus 22 (4d10) thunder damage."
    "name": "Cloud Morningstar"
  - "desc": "*Ranged Weapon Attack:* +18 to hit, range 120/480 ft., one target. *Hit:*\
      \ 42 (5d12 + 10) thunder damage, and the target must succeed on a DC 26 Strength\
      \ saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Wind Javelin"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 20 ft., one target. *Hit:* 28\
      \ (4d8 + 10) force damage."
    "name": "Slam"
  - "desc": "The scion magically creates a vortex of wind in a 60-foot-radius sphere\
      \ centered on a point it can see within 120 feet of itself. Each creature in\
      \ the sphere must succeed on a DC 24 Strength saving throw or be pulled straight\
      \ toward the sphere's center, ending in an unoccupied space as close as possible\
      \ to the center. Then a burst of thunder erupts in a 30-foot-radius sphere centered\
      \ on the same point. Each creature in that area takes 52 (8d12) thunder damage\
      \ and must succeed on a DC 24 Constitution saving throw or have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition until the end of its next turn."
    "name": "Thunderous Vortex (Recharge 5-6)"
"bonus_actions":
  - "desc": "The scion conjures a magical cloud that fills a 30-foot-radius sphere\
      \ centered on a point it can see within 90 feet of itself. Each creature in\
      \ that area must make a DC 24 Wisdom saving throw. On a failed save, a creature\
      \ has the [charmed](/3-Mechanics/CLI/conditions.md#Charmed) condition until\
      \ the end of its next turn. While it has the [charmed](/3-Mechanics/CLI/conditions.md#Charmed)\
      \ condition, the creature must use its action to make a melee attack against\
      \ a creature other than itself of the scion's choice. If no creature is within\
      \ its reach, the affected creature makes a ranged attack against a creature\
      \ of the scion's choice, throwing its weapon if necessary. On a successful save,\
      \ a creature is immune to the scion's Fog of [Deception](/3-Mechanics/CLI/skills.md#Deception)\
      \ for the next 24 hours."
    "name": "Fog of Deception"
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
"image": "/3-Mechanics/CLI/bestiary/giant/token/scion-of-memnor-bgg.webp"
```
^statblock