---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- Monster/cr/26
- Monster/Größe/Gigantisch
- Monster/Typ/Drache
statblock: inline
statblock-link: "#^statblock"
aliases:
- Niv-Mizzet
---
# [Niv-Mizzet](3-Mechanics\CLI\bestiary\npc/niv-mizzet-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 241*  

Possessed of arrogance and vanity that matches his vast intellect and tremendous power, Niv-Mizzet is the ancient dragon who founded and continues to control the Izzet League. From his private laboratory at the top of the Izzet guildhall, Niv-Mizzet directs the research and experiments of his countless underlings. He coordinates a tremendous number of apparently unrelated projects, working toward some mysterious end.

There can be little doubt that this ancient dragon is one of the most intelligent beings on Ravnica and one of the world's most powerful spellcasters. He is just as acquisitive as any dragon, but his treasure is scientific and magical knowledge. His ambition is a looming threat in the minds of all the other guildmasters, but confronting him directly is almost unthinkable thanks to the combination of his awesome magical power and the sheer physical threat of a fire-breathing, sword-toothed dragon.

```statblock
"name": "Niv-Mizzet (GGR)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Neutral"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "370"
"hit_dice": "19d20 + 171"
"modifier": !!int "2"
"stats":
  - !!int "29"
  - !!int "14"
  - !!int "29"
  - !!int "30"
  - !!int "17"
  - !!int "25"
"speed": "40 ft., climb 30 ft., fly 80 ft."
"saves":
  - "constitution": !!int "17"
  - "intelligence": !!int "18"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "Arcana"
    "desc": "+18"
  - "name": "Insight"
    "desc": "+11"
  - "name": "Perception"
    "desc": "+11"
"damage_resistances": "cold, psychic, thunder"
"damage_immunities": "fire, lightning"
"condition_immunities": "charmed"
"senses": "blindsight 60 ft., darkvision 120 ft., passive Perception 21"
"languages": "Common, Draconic"
"cr": "26"
"traits":
  - "desc": "Niv-Mizzet is a 20th-level Izzet spellcaster. His spellcasting ability\
      \ is Intelligence (spell save DC 26, +18 to hit with spell attacks). He has\
      \ the following wizard spells prepared:\n\n**Cantrips (at will):** fire bolt,\
      \ light, prestidigitation, ray of frost, shocking grasp\n\n**1st level (4 slots):**\
      \ detect magic, magic missile, shield, thunderwave, unseen servant\n\n**2nd\
      \ level (3 slots):** blur, enlarge/reduce, flaming sphere, hold person, scorching\
      \ ray\n\n**3rd level (3 slots):** counterspell, fireball, lightning bolt, slow\n\
      \n**4th level (3 slots):** confusion, dimension door, fabricate\n\n**5th level\
      \ (2 slots):** conjure elemental, polymorph, wall of fire, wall of force\n\n\
      **6th level (1 slots):** chain lightning, disintegrate, true seeing\n\n**7th\
      \ level (1 slots):** project image, reverse gravity, teleport\n\n**8th level\
      \ (1 slots):** control weather, maze, power word stun\n\n**9th level (1 slots):**\
      \ prismatic wall"
    "name": "Spellcasting"
  - "desc": "If Niv-Mizzet fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Niv-Mizzet can maintain concentration on two different spells at the\
      \ same time. In addition, he has advantage on saving throws to maintain concentration\
      \ on spells."
    "name": "Locus of the Firemind"
  - "desc": "Niv-Mizzet has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "When Niv-Mizzet casts a spell that deals damage, he can change the spell's\
      \ damage to cold, fire, force, lightning, or thunder."
    "name": "Master Chemister"
"actions":
  - "desc": "Niv-Mizzet makes three attacks: one with his bite and two with his claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 15 ft., one target. *Hit:* 18\
      \ (2d8 + 9) piercing damage plus 14 (4d6) fire damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:* 14\
      \ (2d4 + 9) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 20 ft., one target. *Hit:* 16\
      \ (2d6 + 9) bludgeoning damage."
    "name": "Tail"
  - "desc": "Niv-Mizzet exhales fire in a 90-foot cone. Each creature in that area\
      \ must make a DC 25 Dexterity saving throw, taking 91 (26d6) fire damage on\
      \ a failed save, or half as much damage on a successful one."
    "name": "Fire Breath (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Niv-Mizzet can expend a use to take one of the following actions. Niv-Mizzet\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Niv-Mizzet casts one of his cantrips."
    "name": "Cantrip"
  - "desc": "Niv-Mizzet makes a tail attack."
    "name": "Tail Attack"
  - "desc": "Niv-Mizzet beats his wings. Each creature within 15 feet of him must\
      \ succeed on a DC 25 Dexterity saving throw or take 14 (2d4 + 9) bludgeoning\
      \ damage and be knocked prone. Niv-Mizzet can then fly up to half his flying\
      \ speed."
    "name": "Wing Attack (Costs 2 Actions)"
  - "desc": "Niv-Mizzet regains a spell slot of 3rd level or lower."
    "name": "Dracogenius (Costs 3 Actions)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/niv-mizzet-ggr.webp"
```
^statblock