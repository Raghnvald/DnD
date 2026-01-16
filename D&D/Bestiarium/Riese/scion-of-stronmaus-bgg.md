---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgg
- ttrpg-cli/monster/cr/27
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/giant/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- Scion of Stronmaus
---
# [Scion of Stronmaus](3-Mechanics\CLI\bestiary\giant/scion-of-stronmaus-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 171*  

A scion of Stronmaus often slumbers high in the sky or deep in the ocean, where the tumult caused by the scion's restless sleep has little effect on the world. If it drifts too near the ground or the ocean surface, it causes mighty storms or fierce maelstroms. A scion's slumber is filled with dreams ranging from inspiring visions of Annam's return to melancholy prophecies of inevitable decline, from joyful glimpses of an idyllic past to horrific nightmares of torment and devastation.

A cradle of the storm scion stirs into action not only when the scion is threatened but also if the scion's sleep is troubled by nightmares. When roused, the cradle takes on a vaguely giant-shaped form consisting of air, water, and ice whirling in fury.

If the cradle is destroyed, the scion of Stronmaus inside it awakens. Among the mightiest creatures of all giantkind, the scion stands 80 feet tall. It often finds some relief in waking and being freed from its troubling dreams, so it doesn't necessarily lash out in violence when emerging from its cradle. But it's not particularly interested in Humanoids or other little creatures—either in conversing with them or in protecting them from harm it might cause.

If the scion is threatened, it unleashes elemental might like few other forces in the multiverse can muster: blades of lightning, boulder-sized hailstones, and a storm of churning elements.

## Scions of Giants' Gods

Giants are descended from the All-Father, Annam, and his children. But scions of giants' gods boast a greater claim: they are Annam's grandchildren, and they occupy a privileged place among giants. On some worlds, these scions ruled the first empires of giants until Annam retreated into seclusion. On other worlds, the scions guard their birthplaces (which are rich in elemental magic) or hold the substance of the world together. (See ""Giants of Myth"" in chapter 3 for additional inspiration.)

Scions of giants' gods are enormously powerful beings who infuse the world around them with primeval magic. In many worlds, they slumber and have become part of the landscape. In this case, each scion is enclosed in stasis inside a powerful Elemental called a cradle. The cradle protects the slumbering scion and follows its subconscious wishes, including driving off intruders. But if the cradle dies, the scion within fully awakens.

```statblock
"name": "Scion of Stronmaus (BGG)"
"size": "Gargantuan"
"type": "giant"
"subtype": "titan"
"alignment": "typically  Chaotic Good"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "656"
"hit_dice": "32d20 + 320"
"modifier": !!int "5"
"stats":
  - !!int "30"
  - !!int "20"
  - !!int "30"
  - !!int "26"
  - !!int "28"
  - !!int "24"
"speed": "60 ft., fly 80 ft. (hover), swim 80 ft."
"saves":
  - "dexterity": !!int "13"
  - "intelligence": !!int "16"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+16"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+16"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+17"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "lightning, thunder"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [petrified](/3-Mechanics/CLI/conditions.md#Petrified), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 27"
"languages": "Giant, Primordial"
"cr": "27"
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
  - "desc": "The scion makes one attack using Lightning Sword or Hailstone, as well\
      \ as two Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 30 ft., one target. *Hit:* 36\
      \ (4d12 + 10) force damage plus 22 (4d10) lightning damage."
    "name": "Lightning Sword"
  - "desc": "*Ranged Weapon Attack:* +18 to hit, range 120/480 ft., one target. *Hit:*\
      \ 32 (4d10 + 10) bludgeoning damage plus 18 (4d8) cold damage, and the target\
      \ must succeed on a DC 26 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Hailstone"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 20 ft., one target. *Hit:* 36\
      \ (4d12 + 10) force damage."
    "name": "Slam"
"bonus_actions":
  - "desc": "The scion conjures a churning storm cloud in a 30-foot-radius, 10-foot-tall\
      \ cylinder centered on a point within 120 feet of itself. The cloud's area is\
      \ heavily obscured. The cloud lasts for 1 minute, until the scion dies, or when\
      \ the scion uses this bonus action again.\n\nWhen the cloud appears, and as\
      \ a bonus action on later turns, the scion can move the cloud up to 30 feet\
      \ and cause one of the following effects in a 30-foot-radius, 120-foot-high\
      \ cylinder directly below it; the scion can't choose the same effect two rounds\
      \ in a row:"
    "name": "Vengeful Storm (Recharge 6)"
  - "desc": "The cloud rains acid. Each creature in the cylinder must succeed on a\
      \ DC 25 Constitution saving throw or be covered in acid for 1 minute or until\
      \ a creature uses its action to remove the acid from itself or another creature.\
      \ A creature covered in the acid takes 26 (4d12) acid damage at the start of\
      \ each of its turns."
    "name": "Acid Rain"
  - "desc": "Shards of ice pelt down, and freezing wind fills the area. Each creature\
      \ in the cylinder must succeed on a DC 25 Dexterity saving throw or take 28\
      \ (8d6) cold damage and be hindered by ice formations for 1 minute or until\
      \ it or another creature within reach of it uses an action to break away the\
      \ ice. A creature hindered by ice has its speed reduced to 0."
    "name": "Freezing Storm"
  - "desc": "Bolts of lightning strike down. Each creature in the cylinder must succeed\
      \ on DC 25 Dexterity saving throw or take 18 (4d8) lightning damage and have\
      \ the [stunned](/3-Mechanics/CLI/conditions.md#Stunned) condition until the\
      \ end of its next turn."
    "name": "Lightning Bolts"
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
"image": "/3-Mechanics/CLI/bestiary/giant/token/scion-of-stronmaus-bgg.webp"
```
^statblock