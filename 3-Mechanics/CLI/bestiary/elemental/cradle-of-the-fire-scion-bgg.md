---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cradle of the Fire Scion"
---
# [Cradle of the Fire Scion](3-Mechanics/CLI/bestiary/elemental/cradle-of-the-fire-scion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 172*  

A scion of Surtur slumbering at the peak of a volcano causes an unending plume of smoke to rise, sometimes lit from below by fiery bursts of lava. As the scion dreams of battle—perhaps a battle to rouse Annam from seclusion by uniting the giants or a war to conquer all in Surtur's name—the volcano rumbles and spews molten rage.

If intruders disturb its resting place, the fire scion's cradle rises as a bipedal juggernaut of molten rock. Sometimes miners risk their lives to find rich veins of ore in a scion's volcano, or misguided fire cultists offer sacrifices meant to appease or awaken the volcano, and the awakened cradle defies all their expectations. Like a living volcano, the cradle hurls balls of magma at intruders, exhales fiery gases, and causes molten stone to erupt from the ground around it.

If the cradle is destroyed, the scion of Surtur inside it awakens. Standing 60 feet tall, the scion's form is shrouded in a continual cloud of billowing ash and smoke. The awakened scion forms a blade of lava in its mighty hand and schemes to resume its ancient campaigns of conquest, preferably at the head of a fire giant army.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Cradle of the Fire Scion (BGG)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "typically  Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "555"
"hit_dice": "30d20 + 240"
"modifier": !!int "1"
"stats":
  - !!int "28"
  - !!int "12"
  - !!int "27"
  - !!int "12"
  - !!int "20"
  - !!int "17"
"speed": "40 ft."
"damage_resistances": "cold; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "fire, poison"
"condition_immunities": "exhaustion, petrified, poisoned"
"senses": "darkvision 120 ft., passive Perception 15"
"languages": "Giant, Primordial"
"cr": "25"
"traits":
  - "desc": "The cradle is a container for the [scion of Surtur](3-Mechanics/CLI/bestiary/giant/scion-of-surtur-bgg.md).\
      \ When the cradle drops to 0 hit points, its body hardens and crumbles to ash.\
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
  - "desc": "The cradle makes three Slam or Hurl Lava attacks in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 20 ft., one target. *Hit:*\
      \ 31 (4d10 + 9) bludgeoning damage plus 14 (4d6) fire damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +17 to hit, range 120 ft., one target. *Hit:*\
      \ 27 (4d8 + 9) fire damage. If the target is a creature or a flammable object,\
      \ it ignites. Until a creature within 5 feet of the fire takes an action to\
      \ douse the fire, the target takes 10 (3d6) fire damage at the start of each\
      \ of its turns."
    "name": "Hurl Lava"
  - "desc": "The cradle exhales flames and volcanic gases in a 90-foot cone. Each\
      \ creature in that area must make a DC 24 Dexterity saving throw. On a failed\
      \ save, a creature takes 55 (10d10) fire damage and has the poisoned condition\
      \ for 1 minute. On a successful save, a creature takes half as much damage only.\n\
      \nA creature poisoned in this way can make a DC 24 Constitution saving throw\
      \ at the end of each of its turns, ending the effect on itself on a success."
    "name": "Erupting Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "The cradle causes lava to erupt from a point on the ground it can see\
      \ within 120 feet of itself. Each creature in a 20-foot-radius, 50-foot-high\
      \ cylinder centered on that point must succeed on a DC 21 Dexterity saving throw\
      \ or take 14 (4d6) fire damage."
    "name": "Lava Geyser"
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
"image": "3-Mechanics/CLI/bestiary/elemental/token/cradle-of-the-fire-scion-bgg.webp"
```
^statblock