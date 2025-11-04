---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - Monster/cr/9
  - Monster/Größe/Groß
  - Monster/Typ/Drache/young-gem
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Lowarnizel
---
# [Lowarnizel](3-Mechanics\CLI\bestiary\npc/lowarnizel-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 181*  

Lowarnizel is a young amethyst dragon, and his companion is a lawful neutral human mage named Gossa. Both hate the Far Realm and anything tainted by it.

```statblock
"name": "Lowarnizel (PaBTSO)"
"size": "Large"
"type": "dragon"
"subtype": "young gem"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "168"
"hit_dice": "16d10 + 80"
"modifier": !!int "1"
"stats":
  - !!int "21"
  - !!int "12"
  - !!int "21"
  - !!int "18"
  - !!int "15"
  - !!int "19"
"speed": "40 ft., fly 80 ft. (hover), swim 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "9"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+5"
"damage_resistances": "force, psychic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened),\
  \ [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 30 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 120 ft., passive Perception 20"
"languages": "Common, Draconic, telepathy 120 ft."
"cr": "9"
"traits":
  - "desc": "Lowarnizel can breathe both air and water."
    "name": "Amphibious"
"actions":
  - "desc": "Lowarnizel makes one Bite attack and two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 16\
      \ (2d10 + 5) piercing damage plus 4 (1d8) force damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 9 (1d8\
      \ + 5) slashing damage."
    "name": "Claw"
  - "desc": "Lowarnizel creates a shining bead of gravitational force, then releases\
      \ the energy in a 30-foot cone. Each creature in that area must make a DC 17\
      \ Strength saving throw. On a failed save, a creature takes 36 (8d8) force damage,\
      \ and its speed becomes 0 until the start of the dragon's next turn. On a successful\
      \ save, a creature takes half as much damage only."
    "name": "Singularity Breath (Recharge 5-6)"
  - "desc": "Lowarnizel casts one of the following spells, requiring no spell components\
      \ and using Intelligence as the spellcasting ability (spell save DC 16):\n\n\
      **1/day each:** [dispel magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [haste](/3-Mechanics/CLI/spells/haste-xphb.md), [protection from evil and\
      \ good](/3-Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md), [sending](/3-Mechanics/CLI/spells/sending-xphb.md)"
    "name": "Spellcasting (Psionics)"
"bonus_actions":
  - "desc": "Lowarnizel magically transforms into any creature that is Medium or Small,\
      \ while retaining his game statistics (other than his size). This transformation\
      \ ends if the dragon is reduced to 0 hit points or uses a bonus action to end\
      \ it."
    "name": "Change Shape"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/npc/token/lowarnizel-pabtso.webp"
```
^statblock