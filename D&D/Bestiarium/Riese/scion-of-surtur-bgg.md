---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/25
  - Monster/Größe/Gigantisch
  - Monster/Typ/Riese/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Scion of Surtur
---
# [Scion of Surtur](3-Mechanics\CLI\bestiary\giant/scion-of-surtur-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 173*  

A scion of Surtur slumbering at the peak of a volcano causes an unending plume of smoke to rise, sometimes lit from below by fiery bursts of lava. As the scion dreams of battle—perhaps a battle to rouse Annam from seclusion by uniting the giants or a war to conquer all in Surtur's name—the volcano rumbles and spews molten rage.

If intruders disturb its resting place, the fire scion's cradle rises as a bipedal juggernaut of molten rock. Sometimes miners risk their lives to find rich veins of ore in a scion's volcano, or misguided fire cultists offer sacrifices meant to appease or awaken the volcano, and the awakened cradle defies all their expectations. Like a living volcano, the cradle hurls balls of magma at intruders, exhales fiery gases, and causes molten stone to erupt from the ground around it.

If the cradle is destroyed, the scion of Surtur inside it awakens. Standing 60 feet tall, the scion's form is shrouded in a continual cloud of billowing ash and smoke. The awakened scion forms a blade of lava in its mighty hand and schemes to resume its ancient campaigns of conquest, preferably at the head of a fire giant army.

> [!quote] A quote from Bigby  
> 
> When a volcanic eruption makes me concerned, not just for the fate of settlements and wildlife nearby, but that there might be a much more personal sort of violence heading my way, I begin to question my life choices.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Scion of Surtur (BGG)"
"size": "Gargantuan"
"type": "giant"
"subtype": "titan"
"alignment": "typically  Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "546"
"hit_dice": "28d20 + 252"
"modifier": !!int "3"
"stats":
  - !!int "30"
  - !!int "17"
  - !!int "28"
  - !!int "21"
  - !!int "24"
  - !!int "20"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "11"
  - "charisma": !!int "13"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+18"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+15"
"damage_resistances": "cold; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "fire"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 25"
"languages": "Giant, Primordial"
"cr": "25"
"traits":
  - "desc": "If the scion fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (6/Day)"
  - "desc": "The scion has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The scion deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The scion makes one attack using Lava Blade or Lava Ball, as well as\
      \ two Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 30 ft., one target. *Hit:* 32\
      \ (4d10 + 10) slashing damage plus 18 (4d8) fire damage."
    "name": "Lava Blade"
  - "desc": "*Ranged Weapon Attack:* +18 to hit, range 120/480 ft., one target. *Hit:*\
      \ 29 (3d12 + 10) bludgeoning damage plus 10 (3d6) fire damage, and the target\
      \ must succeed on a DC 26 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Lava Ball"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 20 ft., one target. *Hit:* 28\
      \ (4d8 + 10) force damage."
    "name": "Slam"
  - "desc": "The scion emits a wave of lava from its blade, hands, or mouth in a 90-foot\
      \ cone. Each creature in that area must make a DC 25 Dexterity saving throw.\
      \ On a failed save, a creature takes 60 (11d10) fire damage and has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition from being embedded in hardening rock. A creature can make a DC\
      \ 25 Strength ([Athletics](/3-Mechanics/CLI/skills.md#Athletics)) check as an\
      \ action, freeing itself or a creature within reach from the rock on a success.\
      \ The rock has AC 17 and 40 hit points, and it is immune to fire, poison, and\
      \ psychic damage. On a successful save, a creature takes half as much damage\
      \ only."
    "name": "Lava Wave (Recharge 5-6)"
"bonus_actions":
  - "desc": "The scion moves up to its speed and then sends a shock wave through the\
      \ ground in a 60-foot-radius circle centered on itself. Each creature on the\
      \ ground in that area that is [concentrating](/3-Mechanics/CLI/conditions.md#Concentration)\
      \ must succeed on a DC 26 Constitution saving throw or lose [concentration](/3-Mechanics/CLI/conditions.md#Concentration)."
    "name": "Earth-Shaking Movement"
  - "desc": "The scion causes smoke and white-hot embers to billow from its skin,\
      \ filling a 30-foot-radius sphere centered on itself that moves with it. While\
      \ the scion's skin billows smoke, ranged attacks against the scion are made\
      \ with disadvantage. A creature that moves into the smoke for the first time\
      \ on a turn or starts its turn there must succeed on a DC 25 Constitution saving\
      \ throw or take 14 (4d6) fire damage. The scion's skin stops billowing smoke\
      \ after 1 minute, when the scion dies, or when the scion uses this bonus action\
      \ to stop the smoke."
    "name": "Incendiary Smoke"
"regional_effects":
  - "desc": "The region surrounding a scion of Surtur is altered by the giant's magic,\
      \ creating one or more of the following effects:\n\n- **Abundant Ore.** Veins\
      \ of precious metals and ore are more common within 6 miles of the scion.  \n\
      - **Desertification.** Precipitation is almost nonexistent within 6 miles of\
      \ the scion, parching the land and withering most plant life.  \n- **Empowered\
      \ Fire Giants.** Fire giants within 1,000 feet of the scion gain a +8 bonus\
      \ to attack and damage rolls.  \n\nIf the scion dies, existing ore remains,\
      \ but new veins of ore stop forming. The other effects end immediately."
    "name": ""
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/scion-of-surtur-bgg.webp"
```
^statblock