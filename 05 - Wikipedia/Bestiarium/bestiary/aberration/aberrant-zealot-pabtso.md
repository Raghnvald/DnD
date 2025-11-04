---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/cr/8
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Aberrant Zealot
Typ: Aberration
Größe: Mittelgroß
HG: 8
status: WIP
Habitat:
  - /
---
# [Aberrant Zealot](3-Mechanics\CLI\bestiary\aberration/aberrant-zealot-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 203*  

Aberrant zealots are cultists who have reached out to the powers of the Far Realm—only for something to reach back. Steeped in strange energy, aberrant zealots borrow their vicious might from the monstrous entities that inhabit that fell plane.

```statblock
"name": "Aberrant Zealot (PaBTSO)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "[studded leather armor](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "93"
"hit_dice": "17d8 + 17"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "12"
  - !!int "13"
  - !!int "8"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "7"
  - "charisma": !!int "7"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"damage_resistances": "psychic"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [grappled](/3-Mechanics/CLI/conditions.md#Grappled),\
  \ [restrained](/3-Mechanics/CLI/conditions.md#Restrained)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., [truesight](/3-Mechanics/CLI/senses.md#Truesight)\
  \ 10 ft., passive Perception 15"
"languages": "Common, Deep Speech"
"cr": "8"
"traits":
  - "desc": "The zealot exudes the chaos of the Far Realm. Any non-Aberration creature\
      \ that starts its turn within 5 feet of the zealot must succeed on a DC 15 Wisdom\
      \ saving throw or take 7 (2d6) psychic damage."
    "name": "Aberrant Form"
  - "desc": "The zealot, along with any equipment it is wearing or carrying, is unnaturally\
      \ flexible. The zealot can move through any space as narrow as 1 inch without\
      \ squeezing."
    "name": "Weirdly Pliable"
"actions":
  - "desc": "The zealot makes one Psychic Rend attack and two Shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +7 to hit, reach 15 ft. or range 120\
      \ ft., one target. *Hit:* 14 (3d6 + 4) psychic damage, and the target must succeed\
      \ on a DC 15 Wisdom saving throw or have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition until the start of the zealot's next turn."
    "name": "Psychic Rend"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 15 ft., one target. *Hit:* 7\
      \ (1d6 + 4) piercing damage plus 7 (2d6) psychic damage."
    "name": "Shortsword"
  - "desc": "The zealot casts one of the following spells, requiring no components\
      \ and using Charisma as the spellcasting ability (spell save DC 15):\n\n**At\
      \ will:** [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [minor illusion](/3-Mechanics/CLI/spells/minor-illusion-xphb.md)\n\n**1/day\
      \ each:** [arcane gate](/3-Mechanics/CLI/spells/arcane-gate-xphb.md), [hunger\
      \ of Hadar](/3-Mechanics/CLI/spells/hunger-of-hadar-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "The zealot teleports, along with any equipment it is wearing or carrying,\
      \ to an unoccupied space it can see within 120 feet of itself, leaving a churning\
      \ void in the space it left. Immediately after it teleports, each creature within\
      \ 30 feet of the void other than the zealot must make a DC 15 Strength saving\
      \ throw. On a failed save, a creature takes 18 (4d8) force damage and is pulled\
      \ to the unoccupied space closest to the void. On a successful save, the creature\
      \ takes half as much damage only. The void then disappears."
    "name": "Void Warp (Recharge 5-6)"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/aberrant-zealot-pabtso.webp"
```
^statblock