---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Gargantua
Kategorie: Aberration
Größe: Gigantisch
HG: 21
Status: WIP
linter-yaml-title-alias: Gargantua
tags:
  - Monster/Größe/Gigantisch
  - Monster/HG/21
  - Monster/Typ/aberration
  - Quelle/5e/bgg
aliases:
  - Gargantua
status: WIP
---
# [Gargantua](3-Mechanics\CLI\bestiary\aberration/gargantua-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 149*  

From time to time—perhaps once a generation, under a particular configuration of stars and planets, or at the whim of some malicious god—a gargantua is born to giant parents. Though the child appears like any other of its kind, the creature's true nature manifests upon reaching adulthood: its complexion turns purplish and horns sprout from its head. The gargantua grows rapidly, eventually towering over other giants at a height of 40 feet or more.

Most gargantuas do not feel at home in giant communities and end up searching for homes large enough to hold their enormous frames. They might find a suitable home in an ancient forest, a deep canyon, or an immense cavern in the Underdark. Some gargantuas seek only peace and solitude, while others lash out fiercely at a world that fears them.

Giants tell a variety of stories to explain the existence of gargantuas. One tale connects their origin to an ancient enclave's pact with an entity from the Far Realm. Another claims that Karontor, "the banished son" of Annam, creates gargantuas in retaliation for his imprisonment. A third blames Annam, claiming the All-Father of the giants is disgusted with his descendants and seeks to destroy them.

```statblock
"name": "Gargantua (BGG)"
"size": "Gargantuan"
"type": "aberration"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "388"
"hit_dice": "21d20 + 168"
"modifier": !!int "0"
"stats":
  - !!int "27"
  - !!int "10"
  - !!int "26"
  - !!int "9"
  - !!int "16"
  - !!int "18"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "7"
  - "intelligence": !!int "6"
  - "wisdom": !!int "10"
"damage_resistances": "force, psychic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 13"
"languages": "Giant"
"cr": "21"
"traits":
  - "desc": "At the start of each of the gargantua's turns, each creature of the gargantua's\
      \ choice within 30 feet of it must make a DC 19 Wisdom saving throw. On a failed\
      \ save, a target sees the gargantua as a manifestation of the target's worst\
      \ fears; it takes 17 (5d6) psychic damage and has the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition until the start of the target's next turn. On a successful save,\
      \ a target is immune to this gargantua's Weird Aura for 24 hours."
    "name": "Weird Aura"
"actions":
  - "desc": "The gargantua makes two Slam or Rock attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target. *Hit:* 27\
      \ (3d12 + 8) bludgeoning damage."
    "name": "Slam"
  - "desc": "*Ranged Weapon Attack:* +15 to hit, range 120/480 ft., one target. *Hit:*\
      \ 24 (3d10 + 8) bludgeoning damage."
    "name": "Rock"
"bonus_actions":
  - "desc": "The gargantua curses one creature it can see within 120 feet of itself.\
      \ The target must succeed on a DC 19 Wisdom saving throw or have the [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ condition until the end of its next turn."
    "name": "Baleful Hex"
  - "desc": "The gargantua teleports, along with any equipment it is wearing or carrying,\
      \ to an unoccupied space that it can see within 120 feet of itself."
    "name": "Teleport"
"reactions":
  - "desc": "Immediately after the gargantua takes damage from a Large or smaller\
      \ creature it can see within 20 feet of itself, it attempts to flick the creature\
      \ away. The target must succeed on a DC 23 Strength saving throw, or the target\
      \ takes 18 (3d6 + 8) bludgeoning damage, is pushed horizontally up to 100 feet\
      \ away from the gargantua, and has the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Flick"
  - "desc": "Immediately after a creature the gargantua can see casts a spell of 5th\
      \ level or lower, the gargantua tries to copy the spell. That creature must\
      \ succeed on a DC 19 Charisma saving throw, or the gargantua immediately casts\
      \ the same spell at the same level (+11 to hit with spell attacks, spell save\
      \ DC 19), requiring no material components and choosing the spell's targets."
    "name": "Spell Mimicry (1/Day)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/gargantua-bgg.webp"
```
^statblock