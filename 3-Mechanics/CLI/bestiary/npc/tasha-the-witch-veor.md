---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/19
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tasha the Witch"
---
# [Tasha the Witch](3-Mechanics/CLI/bestiary/npc/tasha-the-witch-veor.md)
*Source: Vecna: Eve of Ruin p. 252*  

Tasha's path to greatness began when she was adopted by the arch-hag Baba Yaga, who named her Natasha. Tasha went on to create various spells, including Tasha's Hideous Laughter, and her magic-fueled ambitions brought her into contact with demons and demon lords, which she subjugated and used against her enemies. On the Material Plane, she became known as Iggwilv the Witch Queen and wrote the Demonomicon of Iggwilv, the greatest of all treatises on the Abyss and its demonic inhabitants. In recent years, Tasha sequestered herself in the Feywild, achieving incredible power and slowly turning into a Fey creature. Tasha became Zybilna, archfey of the domain of Prismeer.

## Answering the Summons

When Zybilna received Alustriel Silverhand's summons to combat Vecna, the archfey was sorely needed in Prismeer. As a compromise, and to honor Tasha's friendship with Alustriel, Zybilna sent a version of herself from the past to Alustriel's side. The Tasha who appears in *Vecna: Eve of Ruin* is a powerful wizard, though she is not yet a witch queen or an archfey.

```statblock
"name": "Tasha the Witch (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Chaotic Neutral"
"ac": !!int "19"
"ac_class": "[robe of the archmagi](3-Mechanics/CLI/items/robe-of-the-archmagi-xdmg.md)"
"hp": !!int "210"
"hit_dice": "28d8 + 84"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "17"
  - !!int "23"
  - !!int "12"
  - !!int "22"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "12"
  - "wisdom": !!int "7"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+18"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+12"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+12"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "passive Perception 11"
"languages": "Abyssal, Celestial, Common, Draconic, Elvish, Infernal, Sylvan"
"cr": "19"
"traits":
  - "desc": "If Tasha fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Tasha has advantage on saving throws against spells and other magical\
      \ effects. (This trait is bestowed by her Robe of the Archmagi.)"
    "name": "Magic Resistance"
  - "desc": "Tasha wears a [Robe of the Archmagi](3-Mechanics/CLI/items/robe-of-the-archmagi-xdmg.md)."
    "name": "Special Equipment"
"actions":
  - "desc": "Tasha makes two Caustic Blast attacks and uses Psychic Whip once."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +14 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 21 (6d4 + 6) acid damage."
    "name": "Caustic Blast"
  - "desc": "Tasha psychically lashes out at one creature she can see within 90 feet\
      \ of herself. The target must make a DC 20 Intelligence saving throw. On a failed\
      \ save, the target takes 21 (6d6) psychic damage and has the [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)\
      \ condition until the start of Tasha's next turn. On a successful save, the\
      \ target takes half as much damage only."
    "name": "Psychic Whip"
  - "desc": "Tasha casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 22, +14 to hit with spell attacks):\n\n**At will:**\
      \ [Detect Magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [Disguise Self](3-Mechanics/CLI/spells/disguise-self-xphb.md),\
      \ [Dispel Magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md), [Light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [Mage Hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [Message](3-Mechanics/CLI/spells/message-xphb.md),\
      \ [Prestidigitation](3-Mechanics/CLI/spells/prestidigitation-xphb.md), [Tasha's\
      \ Hideous Laughter](3-Mechanics/CLI/spells/tashas-hideous-laughter-xphb.md)\n\
      \n**2/day:** [Polymorph](3-Mechanics/CLI/spells/polymorph-xphb.md)\n\n**1/day\
      \ each:** [Maze](3-Mechanics/CLI/spells/maze-xphb.md), [Telekinesis](3-Mechanics/CLI/spells/telekinesis-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "For 1 minute, Tasha gains a flying speed of 30 feet, is immune to poison\
      \ damage and the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) condition,\
      \ and has advantage on attack rolls against any creature that doesn't have all\
      \ its hit points. These benefits end early if Tasha has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition or if she uses another bonus action to dismiss them."
    "name": "Abyssal Visage (2/Day)"
"reactions":
  - "desc": "Immediately after Tasha takes damage, she unleashes arcane energy in\
      \ a 10-foot-radius sphere centered on herself. All other creatures in that area\
      \ must make a DC 20 Dexterity saving throw, taking 19 (3d12) lightning damage\
      \ on a failed save or half as much damage on a successful one. Tasha then teleports,\
      \ along with any equipment she is wearing or carrying, to an unoccupied space\
      \ she can see within 60 feet of herself."
    "name": "Arcane Rebuff"
"source":
  - "VEoR"
"image": "3-Mechanics/CLI/bestiary/npc/token/tasha-the-witch-veor.webp"
```
^statblock