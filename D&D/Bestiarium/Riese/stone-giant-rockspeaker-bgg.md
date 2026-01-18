---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/16
  - Monster/Größe/Riesig
  - Monster/Typ/giant/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Stone Giant Rockspeaker
---
# [Stone Giant Rockspeaker](3-Mechanics\CLI\bestiary\giant/stone-giant-rockspeaker-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 180*  

Stone giants practice rune magic more than other giants do, perhaps because of these giants' interest in and aptitude for carving stone. Stone giants who combine this magic with prodigious artistic skill are called rockspeakers. Within their communities, they act as leaders and oracles.

Rockspeakers incorporate crystals and stones into their clothing and embed them in their skin. By invoking the power of their stone runes, these giants can turn these crystals into scintillating works of art. In combat, rockspeakers can use this same magic to cause their crystals to emit brilliantly colored, intense beams of light than can sear flesh and inhibit enemies.

```statblock
"name": "Stone Giant Rockspeaker (BGG)"
"size": "Huge"
"type": "giant"
"subtype": "wizard"
"alignment": "Any alignment"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "276"
"hit_dice": "24d12 + 120"
"modifier": !!int "2"
"stats":
  - !!int "23"
  - !!int "15"
  - !!int "20"
  - !!int "19"
  - !!int "14"
  - !!int "10"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "10"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+16"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 17"
"languages": "Common, Giant, Terran"
"cr": "16"
"traits":
  - "desc": "If the giant fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The giant has a stone rune inscribed on a mineral object in its possession.\
      \ While holding or wearing the object bearing the rune, the giant can use its\
      \ Prismatic Rays action.\n\nThe object bearing the rune has AC 18; 30 hit points;\
      \ and immunity to necrotic, poison, and psychic damage. The object regains all\
      \ its hit points at the end of every turn, but it turns to dust if reduced to\
      \ 0 hit points or when the giant dies. If the rune is destroyed, the giant can\
      \ inscribe a stone rune on an object in its possession when it finishes a short\
      \ or long rest."
    "name": "Stone Rune"
"actions":
  - "desc": "The giant makes three Prism Staff attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:* 16\
      \ (3d6 + 6) bludgeoning damage plus 13 (3d8) radiant damage."
    "name": "Prism Staff"
  - "desc": "The giant throws a geode at a point within 60 feet of itself, and the\
      \ geode explodes in a dazzling flash. Each creature in a 20-foot-radius sphere\
      \ centered on that point must make a DC 17 Dexterity saving throw. On a failed\
      \ save, a creature takes 13 (3d8) piercing damage plus 13 (3d8) radiant damage\
      \ and has the [blinded](/3-Mechanics/CLI/conditions.md#Blinded) condition until\
      \ the end of its next turn. On a successful save, a creature takes half as much\
      \ damage only. After the giant throws the geode, roll a d6; on a roll of 4 or\
      \ lower, the giant has no more geodes to throw."
    "name": "Exploding Geode"
  - "desc": "The giant's stone rune emits beams of light that form a 60-foot cone.\
      \ Each creature in that area must make a DC 17 Dexterity saving throw. For each\
      \ creature in that area, roll a d6 to determine what ray affects it:"
    "name": "Prismatic Rays (Requires Stone Rune)"
  - "desc": "On a failed save, the creature takes 35 (10d6) radiant damage and has\
      \ the [blinded](/3-Mechanics/CLI/conditions.md#Blinded) condition until the\
      \ end of the giant's next turn. On a successful save, the creature takes half\
      \ as much damage only."
    "name": "1-2: Blazing Red"
  - "desc": "On a failed save, the creature takes 35 (10d6) necrotic damage and has\
      \ the [frightened](/3-Mechanics/CLI/conditions.md#Frightened) condition until\
      \ the end of the giant's next turn. On a successful save, the creature takes\
      \ half as much damage only."
    "name": "3-4: Dreadful Blue"
  - "desc": "On a failed save, the creature takes 35 (10d6) force damage and has the\
      \ [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated) condition until\
      \ the end of the giant's next turn. On a successful save, the creature takes\
      \ half as much damage only."
    "name": "5-6: Sapping Green"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/stone-giant-rockspeaker-bgg.webp"
```
^statblock