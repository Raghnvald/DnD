---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/22
  - Monster/Größe/Gigantisch
  - Monster/Typ/Riese/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Scion of Grolantor
---
# [Scion of Grolantor](3-Mechanics\CLI\bestiary\giant/scion-of-grolantor-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 165*  

A slumbering scion of Grolantor is often mistaken for a hill, and sometimes people erect standing stones, a village, or a city on a scion's back, unaware of the mighty power beneath them. Such settlements can thrive for centuries, as the scion's magic causes crops to flourish and livestock to thrive in the surrounding region. An ancient tree towers from the crest of the hill.

When roused, a cradle of the hill scion rises as a mass of dirt, stone, and roots with two massive arms. The cradle uses tree roots and waves of dirt to entangle and entomb foes.

If the cradle is destroyed, the scion of Grolantor inside it awakens. Standing 50 feet tall, the scion devours everything within reach to satiate its hunger. Its powerful lungs can suck food straight into its gullet. The scion uses a great tree to bat foes far into the distance.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Scion of Grolantor (BGG)"
"size": "Gargantuan"
"type": "giant"
"subtype": "titan"
"alignment": "typically  Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "402"
"hit_dice": "23d20 + 161"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "25"
  - !!int "15"
  - !!int "21"
  - !!int "18"
"speed": "60 ft."
"saves":
  - "wisdom": !!int "12"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+12"
"damage_resistances": "cold; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "passive Perception 22"
"languages": "Giant, Primordial"
"cr": "22"
"traits":
  - "desc": "If the scion fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (6/Day)"
  - "desc": "The scion has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The scion deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The scion makes one Great Tree Club attack and two Slam attacks, or it\
      \ makes three Boulder attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 30 ft., one target. *Hit:* 30\
      \ (4d10 + 8) bludgeoning damage. If the target is a creature, it must succeed\
      \ on a DC 23 Strength saving throw or be pushed horizontally up to 100 feet\
      \ straight away from the scion and have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Great Tree Club"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target. *Hit:* 26\
      \ (4d8 + 8) force damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +15 to hit, range 120/480 ft., one target. *Hit:*\
      \ 27 (3d12 + 8) bludgeoning damage."
    "name": "Boulder"
  - "desc": "The scion inhales a vortex of air in a 120-foot line that is 15 feet\
      \ wide. Each creature in that area that is Huge or smaller must succeed on a\
      \ DC 23 Strength saving throw or be pulled up to 120 feet straight toward the\
      \ scion and be swallowed. A swallowed creature has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition, has total cover against attacks and other effects outside the scion,\
      \ and takes 24 (7d6) force damage at the start of each of the scion's turns.\n\
      \nThe scion's stomach can hold up to two creatures at a time. If the scion takes\
      \ 60 damage or more on a single turn from a creature inside it, the scion must\
      \ succeed on a DC 17 Constitution saving throw at the end of that turn or regurgitate\
      \ all swallowed creatures, each of which falls in a space within 10 feet of\
      \ the scion and has the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition.\
      \ If the scion dies, any swallowed creature no longer has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition and can escape from the corpse using 15 feet of movement, exiting\
      \ with the [prone](/3-Mechanics/CLI/conditions.md#Prone) condition."
    "name": "Inhale (Recharge 5-6)"
"bonus_actions":
  - "desc": "The scion moves up to its speed and then sends a shock wave through the\
      \ ground in a 60-foot-radius circle centered on itself. Each creature on the\
      \ ground in that area that is [concentrating](/3-Mechanics/CLI/conditions.md#Concentration)\
      \ must succeed on a DC 23 Constitution saving throw or lose [concentration](/3-Mechanics/CLI/conditions.md#Concentration)."
    "name": "Earth-Shaking Movement"
"reactions":
  - "desc": "Immediately after taking damage, if it has at least one creature swallowed,\
      \ the scion deals 10 (3d6) force damage to each swallowed creature and regains\
      \ 10 hit points."
    "name": "Feed"
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
"image": "/3-Mechanics/CLI/bestiary/giant/token/scion-of-grolantor-bgg.webp"
```
^statblock