---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Cradle of the Stone Scion
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/23
  - Monster/Typ/Elementar
  - Quelle/5e/bgg
aliases:
  - Cradle of the Stone Scion
---
# [Cradle of the Stone Scion](3-Mechanics\CLI\bestiary\elemental/cradle-of-the-stone-scion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 168*  

A scion of Skoraeus typically slumbers deep in the heart of a towering mountain, almost becoming one with the earth. While the scion dreams, the mountain's minerals are transformed into fine carving stones and brilliant gems.

If a miner tunnels too close to the heart of the mountain, the cradle awakens as a bipedal mass of stone and crystals. It brings the weight of the mountain down on the intruder's head and unleashes an earsplitting roar that can collapse mine tunnels.

If the cradle is destroyed, the scion of Skoraeus inside it awakens. At nearly 70 feet tall, it towers over most other creatures and wields a mass of crystal as a club. Once awakened, the scion continues to pursue the art that ornamented its dreams, seeking to mold and shape stone into beautiful elegance. If it needs more raw materials, the scion can transform a living creature in its palm into stone.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Cradle of the Stone Scion (BGG)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "typically  Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "455"
"hit_dice": "26d20 + 182"
"modifier": !!int "2"
"stats":
  - !!int "26"
  - !!int "15"
  - !!int "24"
  - !!int "11"
  - !!int "18"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "wisdom": !!int "11"
  - "charisma": !!int "7"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "tremorsense 120 ft., passive Perception 14"
"languages": "Giant, Primordial"
"cr": "23"
"traits":
  - "desc": "The cradle is a container for the [scion of Skoraeus](/3-Mechanics/CLI/bestiary/giant/scion-of-skoraeus-bgg.md).\
      \ When the cradle drops to 0 hit points, its body crumbles to dust. The scion\
      \ instantly appears in the space the cradle occupied and uses the cradle's initiative\
      \ count."
    "name": "Awakening of the Scion"
  - "desc": "If the cradle fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
  - "desc": "The cradle has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The cradle deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The cradle makes two Slam or Spit Rock attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target. *Hit:* 30\
      \ (4d10 + 8) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +15 to hit, range 120 ft., one target. *Hit:*\
      \ 24 (3d10 + 8) bludgeoning damage, and the target must succeed on a DC 23 Strength\
      \ saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Spit Rock"
  - "desc": "The cradle lets out a painfully load roar. Each creature within 60 feet\
      \ of the cradle must make a DC 23 Constitution saving throw. On a failed save,\
      \ a creature takes 33 (6d10) thunder damage and has the [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition until the end of its next turn."
    "name": "Shattering Roar (Recharge 5-6)"
"bonus_actions":
  - "desc": "The cradle causes the crystals on its body to flare with light. Each\
      \ creature within 30 feet of the cradle must succeed on a DC 22 Constitution\
      \ saving throw or take 21 (6d6) radiant damage and have the [blinded](/3-Mechanics/CLI/conditions.md#Blinded)\
      \ condition until the end of the cradle's next turn."
    "name": "Crystal Flare"
  - "desc": "The cradle causes the ground in a 20-foot square within 90 feet of itself\
      \ to sprout crystal spikes until the start of its next turn. The area becomes\
      \ difficult terrain for the duration. A creature takes 10 (3d6) piercing damage\
      \ for each 5 feet it moves on this terrain."
    "name": "Stone Spikes"
"regional_effects":
  - "desc": "The region surrounding a scion of Skoraeus is altered by the giant's\
      \ magic, creating one or more of the following effects:\n\n- **Abundant Stone\
      \ and Minerals.** Smooth stones and gems grow within 6 miles of the scion. \
      \ \n- **Edible Moss.** Carpets of golden moss that stone giants find tasty grow\
      \ on cavern walls within 6 miles of the scion.  \n- **Empowered Stone Giants.**\
      \ Stone giants within 1,000 feet of the scion gain a +7 bonus to attack and\
      \ damage rolls.  \n\nIf the scion dies, the Empowered Stone Giants effect ends\
      \ immediately. The other effects cease to produce new moss and minerals, and\
      \ existing moss dies within 1d10 days."
    "name": ""
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/cradle-of-the-stone-scion-bgg.webp"
```
^statblock