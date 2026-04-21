---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Scion of Thrym
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/24
  - Monster/Typ/Riese/titan
  - Quelle/5e/bgg
aliases:
  - Scion of Thrym
---
# [Scion of Thrym](3-Mechanics\CLI\bestiary\giant/scion-of-thrym-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 175*  

A slumbering scion of Thrym encased in its cradle is functionally identical to a glacier or iceberg, nestled in an alpine valley or drifting in a polar sea. In its wintry seclusion, the scion dreams of battle and glory.

If it is disturbed, the scion's cradle animates as a bipedal figure formed of ice and snow. It smashes intruders with its icy fists or hurls shards of its own icy substance at them, and it can exhale a blast of frigid air to freeze foes in place.

If the cradle is destroyed, its icy body shatters to reveal the awakened scion of Thrym inside it. Forming a double-bladed axe in its hand, the 70-foot-tall scion rushes at any foe that dares to challenge it. Emulating sagas of Thrym, the scion can achieve a tremendous feat of strength: creating a glacier in the ground and hurling it skyward, along with any creatures standing on it.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Scion of Thrym (BGG)"
"size": "Gargantuan"
"type": "giant"
"subtype": "titan"
"alignment": "typically  Neutral Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "499"
"hit_dice": "27d20 + 216"
"modifier": !!int "3"
"stats":
  - !!int "30"
  - !!int "16"
  - !!int "27"
  - !!int "17"
  - !!int "20"
  - !!int "21"
"speed": "60 ft."
"saves":
  - "wisdom": !!int "12"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+17"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+12"
"damage_resistances": "fire; lightning; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "cold"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 22"
"languages": "Giant, Primordial"
"cr": "24"
"traits":
  - "desc": "If the scion fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (6/Day)"
  - "desc": "The scion has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The scion deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The scion makes one Ice Axe and two Slam attacks, or it makes two Glacier\
      \ Throw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 30 ft., one target. *Hit:* 36\
      \ (4d12 + 10) force damage plus 18 (4d8) cold damage."
    "name": "Ice Axe"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 20 ft., one target. *Hit:* 32\
      \ (4d10 + 10) force damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +17 to hit, range 120/480 ft., one target. *Hit:*\
      \ 36 (4d12 + 10) bludgeoning damage plus 14 (4d6) cold damage, and the target\
      \ must succeed on a DC 25 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Glacier Throw"
  - "desc": "The scion digs its hands into the ground at a point it can see within\
      \ 30 feet of itself and launches a magically conjured mass of ice into the air.\
      \ Each creature other than the scion in a 30-foot-radius, 100-foot-high cylinder\
      \ centered on that point must make a DC 25 Dexterity saving throw. On a failed\
      \ save, a creature takes 36 (8d8) bludgeoning damage plus 19 (3d12) cold damage\
      \ and is pushed vertically to the top of the cylinder, at which point the creature\
      \ falls. On a successful save, a creature takes half as much damage and is pushed\
      \ to the nearest unoccupied space outside the cylinder with no additional effects.\n\
      \nAt the start of the scion's next turn, a mass of ice plummets to the ground\
      \ on a point the scion can see within 60 feet of the point the scion dug its\
      \ hands into. Each creature in a 30-foot-radius, 100-foot-high cylinder centered\
      \ on that point must succeed on a DC 25 Dexterity saving throw or take 18 (4d8)\
      \ bludgeoning damage plus 18 (4d8) cold damage."
    "name": "Glacial Upheaval (Recharge 5-6)"
"bonus_actions":
  - "desc": "The scion moves up to its speed and sends a shock wave through the ground\
      \ in a 60-foot-radius circle centered on itself. Each creature on the ground\
      \ in that area that is [concentrating](/3-Mechanics/CLI/conditions.md#Concentration)\
      \ must succeed on a DC 25 Constitution saving throw or lose [concentration](/3-Mechanics/CLI/conditions.md#Concentration)."
    "name": "Earth-Shaking Movement"
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
"image": "/3-Mechanics/CLI/bestiary/giant/token/scion-of-thrym-bgg.webp"
```
^statblock