---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/24
  - Monster/Größe/Gigantisch
  - Monster/Typ/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Cradle of the Frost Scion
---
# [Cradle of the Frost Scion](3-Mechanics\CLI\bestiary\elemental/cradle-of-the-frost-scion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 174*  

A slumbering scion of Thrym encased in its cradle is functionally identical to a glacier or iceberg, nestled in an alpine valley or drifting in a polar sea. In its wintry seclusion, the scion dreams of battle and glory.

If it is disturbed, the scion's cradle animates as a bipedal figure formed of ice and snow. It smashes intruders with its icy fists or hurls shards of its own icy substance at them, and it can exhale a blast of frigid air to freeze foes in place.

If the cradle is destroyed, its icy body shatters to reveal the awakened scion of Thrym inside it. Forming a double-bladed axe in its hand, the 70-foot-tall scion rushes at any foe that dares to challenge it. Emulating sagas of Thrym, the scion can achieve a tremendous feat of strength: creating a glacier in the ground and hurling it skyward, along with any creatures standing on it.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Cradle of the Frost Scion (BGG)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "typically  Neutral Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "499"
"hit_dice": "27d20 + 216"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "26"
  - !!int "11"
  - !!int "19"
  - !!int "16"
"speed": "40 ft., swim 40 ft."
"saves":
  - "wisdom": !!int "11"
  - "charisma": !!int "10"
"damage_resistances": "fire; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "cold, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 14"
"languages": "Giant, Primordial"
"cr": "24"
"traits":
  - "desc": "The cradle is a container for the [scion of Thrym](/3-Mechanics/CLI/bestiary/giant/scion-of-thrym-bgg.md).\
      \ When the cradle drops to 0 hit points, its body shatters into shards of ice.\
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
  - "desc": "The cradle makes two Slam or Hurl Icicle attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target. *Hit:* 30\
      \ (4d10 + 8) bludgeoning damage plus 11 (2d10) cold damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +15 to hit, range 120 ft., one target. *Hit:*\
      \ 26 (4d8 + 8) piercing damage plus 9 (2d8) cold damage, and the target must\
      \ succeed on a DC 23 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Hurl Icicle"
  - "desc": "The cradle exhales a blast of frost in a 90-foot cone. Each creature\
      \ in that area must make a DC 23 Constitution saving throw. On a failed save,\
      \ a creature takes 52 (8d12) cold damage, and its speed is reduced to 0 until\
      \ the end of its next turn. On a successful save, a creature takes half as much\
      \ damage only. If this damage would reduce the target to 0 hit points, the target\
      \ drops to 1 hit point instead and has the [petrified](/3-Mechanics/CLI/conditions.md#Petrified)\
      \ condition, turning into a frozen statue.\n\nIf the statue takes bludgeoning\
      \ damage, it shatters, killing the frozen creature. If the statue would take\
      \ fire damage, it instead takes no damage and thaws, ending the petrification."
    "name": "Freezing Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "The cradle magically conjures a cloud of chilling mist that fills a 30-foot-radius\
      \ sphere centered on a point it can see within 90 feet of itself. The mist spreads\
      \ around corners. Each creature in that area must succeed on a DC 19 Constitution\
      \ saving throw or take 28 (8d6) cold damage and be unable to use reactions until\
      \ the start of its next turn. The mist vanishes at the end of the cradle's turn."
    "name": "Chilling Mist"
"regional_effects":
  - "desc": "The region surrounding a scion of Thrym is altered by the giant's magic,\
      \ creating one or more of the following effects:\n\n- **Biting Chill.** Extreme\
      \ cold envelops the land within 6 miles of the scion (see the \"Dungeon Master's\
      \ Guide\" for rules on [extreme cold](/3-Mechanics/CLI/traps-hazards/extreme-cold-xdmg.md)).\
      \ If the climate in the area already features extreme cold, the cold is numbing—\
      creatures in the area without immunity or resistance to cold damage have disadvantage\
      \ on Strength and Dexterity checks.  \n- **Empowered Frost Giants.** Frost giants\
      \ within 1,000 feet of the scion gain a +7 bonus to attack and damage rolls.\
      \  \n- **Thriving Wildlife.** Beasts reproduce rapidly and thrive within 6 miles\
      \ of the scion.  \n\nIf the scion dies, these effects end immediately."
    "name": ""
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/cradle-of-the-frost-scion-bgg.webp"
```
^statblock