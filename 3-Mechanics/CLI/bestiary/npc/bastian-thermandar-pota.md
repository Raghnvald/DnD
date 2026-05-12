---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/fire-genasi
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bastian Thermandar"
---
# [Bastian Thermandar](3-Mechanics/CLI/bestiary/npc/bastian-thermandar-pota.md)
*Source: Princes of the Apocalypse p. 201*  

Like many in the fire cult, Bastian burns with an inner fire, but his fire is ambition, rather than a wish to see the world burn. Bastian is scheming to supplant Vanifer and claim Tinderstrike for himself.

As a practitioner of the arcane arts who learned much of his fire magic from Vanifer herself, Bastian relies on his spells in a fight, and he is a "quick-burning" sort who tries to deliver maximum impact early in the fight. If he knows a fight is coming but can't preemptively strike, Bastian becomes more cautious, casting wall of fire to protect himself before he hurls magic into the fray.

```statblock
"name": "Bastian Thermandar (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "Fire genasi"
"alignment": "Neutral Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "15"
  - !!int "11"
  - !!int "9"
  - !!int "18"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+7"
"damage_resistances": "fire"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": "Common, Ignan"
"cr": "8"
"traits":
  - "desc": "Bastian is a 9th-level spellcaster. His spellcasting ability is Charisma\
      \ (spell save DC 15, +7 to hit with spell attacks). Bastian knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [message](3-Mechanics/CLI/spells/message.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md), [shocking\
      \ grasp](3-Mechanics/CLI/spells/shocking-grasp.md)\n\n**1st level (4 slots):**\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor.md), [magic missile](3-Mechanics/CLI/spells/magic-missile.md),\
      \ [shield](3-Mechanics/CLI/spells/shield.md)\n\n**2nd level (3 slots):** [misty\
      \ step](3-Mechanics/CLI/spells/misty-step.md), [scorching ray](3-Mechanics/CLI/spells/scorching-ray.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell.md),\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md)\n\n**4th level (3 slots):**\
      \ [dimension door](3-Mechanics/CLI/spells/dimension-door.md), [wall of fire](3-Mechanics/CLI/spells/wall-of-fire.md)\n\
      \n**5th level (1 slots):** [hold monster](3-Mechanics/CLI/spells/hold-monster.md)"
    "name": "Spellcasting"
  - "desc": "Bastian's innate spellcasting ability is Constitution (spell save DC\
      \ 13, +5 to hit with spell attacks). He can innately cast the following spells:\n\
      \n**At will:** [produce flame](3-Mechanics/CLI/spells/produce-flame.md)\n\n\
      **1/day:** [burning hands](3-Mechanics/CLI/spells/burning-hands.md)"
    "name": "Innate Spellcasting"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/bastian-thermandar-pota.webp"
```
^statblock