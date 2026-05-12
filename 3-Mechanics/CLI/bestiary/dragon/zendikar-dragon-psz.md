---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zendikar Dragon"
---
# [Zendikar Dragon](3-Mechanics/CLI/bestiary/dragon/zendikar-dragon-psz.md)
*Source: Plane Shift: Zendikar p. 29*  

Dragons are the ultimate representation of the chaos, ferocity, and reckless independence of red mana. They are found across Zendikar in mountainous regions where red mana is plentiful, particularly in Akoum, though never in great numbers.

A dragon is an enormous reptilian monster with thick, tough scales and leathery wings. Sharp spines or thick plates run down its back, and most dragons have large horns. A dragon's body has a vaguely feline shape, with a long neck supporting a large head, and a long, thick tail lashing behind it. Its four legs end in sharp claws that are deadly weapons, and its mouth is full of sharp teeth. Even a young dragon is larger than a powerful warhorse, and the largest are on par with some of the larger Eldrazi (though not as mighty as the towering Eldrazi titans).

The dragons of Zendikar are not particularly intelligent, especially in comparison to the genius dragon Planeswalker Nicol Bolas. They are more aware than the average beast and perhaps slightly smarter than an ogre, but dragons are still driven primarily by their instincts—to hunt for prey and to guard their territories against any intruders. They are hot-tempered and ferocious, typically rending or incinerating anything they perceive as an enemy before even thinking to ask questions.

A dragon's most fearsome aspect is its ability to exhale a blast of fire from its mouth. As it draws breath, a red glow like that of molten metal forms around its mouth, and is sometimes visible in its neck and chest as well. The fire then erupts in a long stream or a broad cone, shaped by the dragon as it chooses. A dragon might strafe the ground with fire as it flies overhead, covering as much ground—and incinerating as many foes—as possible. A grounded dragon turns its head back and forth as it breathes, blanketing its foes in flame or creating a barrier of burning earth to cover its retreat.

The [young red dragon](3-Mechanics/CLI/bestiary/dragon/young-red-dragon.md) in the Monster Manual can represent the dragons of Zendikar, but its Intelligence score is only 8 (−1). This change has no effect on its other statistics.

```statblock
"name": "Zendikar Dragon (PSZ)"
"size": "Large"
"type": "dragon"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "178"
"hit_dice": "17d10 + 85"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "8"
  - !!int "11"
  - !!int "19"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "4"
  - "constitution": !!int "9"
  - "wisdom": !!int "4"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "fire"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 18"
"languages": "Common, Draconic"
"cr": "10"
"actions":
  - "desc": "The dragon makes three attacks: one with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 17 (2d10 + 6) piercing damage plus 3 (1d6) fire damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) slashing damage."
    "name": "Claw"
  - "desc": "The dragon exhales fire in a 30-foot cone. Each creature in that area\
      \ must make a DC 17 Dexterity saving throw, taking 56 (16d6) fire damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/dragon/token/zendikar-dragon-psz.webp"
```
^statblock