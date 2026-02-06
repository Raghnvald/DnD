---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/17
  - Monster/Größe/Riesig
  - Monster/Typ/Riese/cleric
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Frost Giant Ice Shaper
---
# [Frost Giant Ice Shaper](3-Mechanics\CLI\bestiary\giant/frost-giant-ice-shaper-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 145*  

Frost giants who master rune magic are known as ice shapers, and their sheer power typically contributes to a meteoric rise in the giants' ordning. Many of them end up as jarls, leading their communities, or as advisers to jarls—often the true power behind the throne. They are usually devoted to Thrym.

True to their name, these ice shapers manipulate the raw elemental energy of air and water to wield ice in both offense and defense. They summon ice elementals in the shape of wolves, cloak themselves in icy armor, and just as quickly turn that armor into a hail of deadly ice shards.

```statblock
"name": "Frost Giant Ice Shaper (BGG)"
"size": "Huge"
"type": "giant"
"subtype": "cleric"
"alignment": "Any alignment"
"ac": !!int "16"
"ac_class": "[chain mail](/3-Mechanics/CLI/items/chain-mail-xphb.md)"
"hp": !!int "310"
"hit_dice": "27d12 + 135"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "11"
  - !!int "19"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "strength": !!int "12"
  - "constitution": !!int "11"
  - "wisdom": !!int "10"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Athletics](/3-Mechanics/CLI/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
"damage_immunities": "cold"
"senses": "passive Perception 20"
"languages": "Common, Giant"
"cr": "17"
"traits":
  - "desc": "The giant has a frost rune inscribed on a chunk of ice or some other\
      \ object in its possession. While holding or wearing the object bearing the\
      \ rune, the giant can use its Ice Wolves action and Ice Armor reaction.\n\n\
      The object bearing the rune has AC 16; 40 hit points; and immunity to necrotic,\
      \ poison, and psychic damage. The object regains all its hit points at the end\
      \ of every turn, but it turns to dust if reduced to 0 hit points or when the\
      \ giant dies. If the rune is destroyed, the giant can inscribe a frost rune\
      \ on an object in its possession when it finishes a short or long rest."
    "name": "Frost Rune"
  - "desc": "If the giant fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
"actions":
  - "desc": "The giant makes three attacks using Greataxe, Freezing Ray, or a combination\
      \ of them."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:* 22\
      \ (3d10 + 6) slashing damage plus 9 (2d8) cold damage."
    "name": "Greataxe"
  - "desc": "*Ranged Spell Attack:* +10 to hit, range 120 ft., one target. *Hit:*\
      \ 17 (3d8 + 4) cold damage, and the target must make a DC 18 Constitution saving\
      \ throw. On a failed save, the target has the [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ condition until the end of its next turn. On a successful save, the target's\
      \ speed is reduced by 10 feet until the end of its next turn."
    "name": "Freezing Ray"
  - "desc": "The giant magically summons 1d4 wolves made of ice (use the [winter wolf](/3-Mechanics/CLI/bestiary/monstrosity/winter-wolf-xmm.md)\
      \ stat block in the Monster Manual to represent them, but they are Elementals\
      \ instead of Monstrosities). The wolves appear in unoccupied spaces the giant\
      \ can see within 30 feet of itself. The wolves take their turn immediately after\
      \ the giant on the same initiative count, and they obey the giant's commands.\
      \ The wolves gain a +6 bonus to their attack and damage rolls while they are\
      \ within 30 feet of the giant. The wolves disappear after 1 minute, when the\
      \ giant dies, or when the giant uses this action again."
    "name": "Ice Wolves (Requires Frost Rune)"
"reactions":
  - "desc": "When a creature the giant can see makes an attack roll against it, the\
      \ giant can form a coat of ice around itself, granting it a +6 bonus to its\
      \ AC against that attack. After the attack hits or misses, the ice shatters,\
      \ and each creature within 5 feet of the giant must succeed on a DC 18 Dexterity\
      \ saving throw or take 13 (3d8) cold damage."
    "name": "Ice Armor (Requires Frost Rune)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/frost-giant-ice-shaper-bgg.webp"
```
^statblock