---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Cradle of the Storm Scion
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/27
  - Monster/Typ/Elementar
  - Quelle/5e/bgg
aliases:
  - Cradle of the Storm Scion
---
# [Cradle of the Storm Scion](3-Mechanics\CLI\bestiary\elemental/cradle-of-the-storm-scion-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 170*  

A scion of Stronmaus often slumbers high in the sky or deep in the ocean, where the tumult caused by the scion's restless sleep has little effect on the world. If it drifts too near the ground or the ocean surface, it causes mighty storms or fierce maelstroms. A scion's slumber is filled with dreams ranging from inspiring visions of Annam's return to melancholy prophecies of inevitable decline, from joyful glimpses of an idyllic past to horrific nightmares of torment and devastation.

A cradle of the storm scion stirs into action not only when the scion is threatened but also if the scion's sleep is troubled by nightmares. When roused, the cradle takes on a vaguely giant-shaped form consisting of air, water, and ice whirling in fury.

If the cradle is destroyed, the scion of Stronmaus inside it awakens. Among the mightiest creatures of all giantkind, the scion stands 80 feet tall. It often finds some relief in waking and being freed from its troubling dreams, so it doesn't necessarily lash out in violence when emerging from its cradle. But it's not particularly interested in Humanoids or other little creatures—either in conversing with them or in protecting them from harm it might cause.

If the scion is threatened, it unleashes elemental might like few other forces in the multiverse can muster: blades of lightning, boulder-sized hailstones, and a storm of churning elements.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Cradle of the Storm Scion (BGG)"
"size": "Gargantuan"
"type": "elemental"
"alignment": "typically  Chaotic Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "682"
"hit_dice": "35d20 + 315"
"modifier": !!int "2"
"stats":
  - !!int "30"
  - !!int "14"
  - !!int "29"
  - !!int "16"
  - !!int "23"
  - !!int "18"
"speed": "40 ft., fly 60 ft. (hover), swim 60 ft."
"damage_resistances": "cold; fire; thunder; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "lightning, poison"
"condition_immunities": "[exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone), [restrained](/3-Mechanics/CLI/conditions.md#Restrained),\
  \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned)"
"senses": "passive Perception 16"
"languages": "Giant, Primordial"
"cr": "27"
"traits":
  - "desc": "The cradle is a container for the [scion of Stronmaus](/3-Mechanics/CLI/bestiary/giant/scion-of-stronmaus-bgg.md).\
      \ When the cradle drops to 0 hit points, its body bursts into light. The scion\
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
  - "desc": "The cradle makes three Slam or Spit Hailstone attacks in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 20 ft., one target. *Hit:* 36\
      \ (4d12 + 10) bludgeoning damage plus 19 (3d12) lightning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +18 to hit, range 120 ft., one target. *Hit:*\
      \ 32 (4d10 + 10) bludgeoning damage plus 14 (4d6) cold damage, and the target\
      \ must succeed on a DC 26 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Spit Hailstone"
  - "desc": "The cradle hurls multiple magical lightning bolts at up to two creatures\
      \ it can see within 500 feet of itself. Each target must make a DC 22 Dexterity\
      \ saving throw. On a failed save, the target takes 71 (11d12) lightning damage\
      \ and has the [stunned](/3-Mechanics/CLI/conditions.md#Stunned) condition until\
      \ the end of its next turn. On a successful save, the target takes half as much\
      \ damage only."
    "name": "Lightning Barrage (Recharge 5-6)"
"reactions":
  - "desc": "Immediately after taking damage, the cradle cracks with thunder and then\
      \ magically teleports up to 60 feet to an unoccupied space it can see. Each\
      \ creature within 10 feet of the space the cradle left must make a DC 22 Constitution\
      \ saving throw, taking 14 (4d6) thunder damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Booming Step"
"regional_effects":
  - "desc": "The region surrounding a scion of Stronmaus is altered by the giant's\
      \ magic, creating one or more of the following effects:\n\n- **Elemental Portals.**\
      \ Two-way portals to the Elemental Plane of Air (if the scion is in the sky)\
      \ or the Elemental Plane of Water (if the scion is in the ocean) form within\
      \ 1 mile of the cradle or scion, allowing elemental creatures into the world.\
      \  \n- **Empowered Storm Giants.** Storm giants within 1,000 feet of the scion\
      \ gain a +8 bonus to attack and damage rolls.  \n- **Extreme Weather.** The\
      \ weather within 1 mile of the scion dramatically shifts day to day, ranging\
      \ from pleasantly sunny to brutal hailstorms.  \n\nIf the scion dies, these\
      \ effects end immediately."
    "name": ""
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/elemental/token/cradle-of-the-storm-scion-bgg.webp"
```
^statblock