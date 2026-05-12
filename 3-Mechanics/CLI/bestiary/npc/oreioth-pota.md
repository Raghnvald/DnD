---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Oreioth"
---
# [Oreioth](3-Mechanics/CLI/bestiary/npc/oreioth-pota.md)
*Source: Princes of the Apocalypse p. 212*  

A lean, black-bearded young noble from Baldur's Gate, Oreioth is more at home among the dead than the living. He was cruel almost from the time he could talk, catching small creatures and killing them in hideously inventive ways to savor the power of life and death. He grew to be an embarrassment to his well-off family, who paid a tutor to channel his undeniable intelligence and curiosity into more positive outlets. They didn't know they had apprenticed the young Oreioth to a necromancer in need of an assistant for his researches.

When Oreioth's master decided he had no more use for his apprentice, he sent Oreioth off to make his own way in the world. Oreioth worked his way northward, robbing graves and using his magic to intimidate or rob anyone weaker than him. Driven out of one decent town after another, he finally sought refuge in an old outlaw's lair he discovered near Lance Rock. There he commenced his newest round of experiments, avoiding all other living souls.

What few social graces Oreioth once possessed are fading rapidly. He has become a megalomaniac, styling himself the Lord of Lance Rock and surrounding himself with zombies and skeletons compelled to heed his every whim. Oreioth barely recognizes his own name anymore, and he harbors dreams of founding a kingdom of undead servitors with himself on the throne.

```statblock
"name": "Oreioth (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "14 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "1"
"stats":
  - !!int "8"
  - !!int "13"
  - !!int "14"
  - !!int "16"
  - !!int "9"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "1"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Investigation](3-Mechanics/CLI/rules/skills.md#Investigation)"
    "desc": "+5"
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+1"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "passive Perception 9"
"languages": "Abyssal, Common"
"cr": "2"
"traits":
  - "desc": "Oreioth is a 6th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 13, +5 to hit with spell attacks). He has the following wizard\
      \ spells prepared:\n\n**Cantrips (at will):** [chill touch](3-Mechanics/CLI/spells/chill-touch.md),\
      \ [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md),\
      \ [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp.md)\n\n**1st level\
      \ (4 slots):** [false life](3-Mechanics/CLI/spells/false-life.md), [mage armor](3-Mechanics/CLI/spells/mage-armor.md),\
      \ [magic missile](3-Mechanics/CLI/spells/magic-missile.md), [ray of sickness](3-Mechanics/CLI/spells/ray-of-sickness.md)\n\
      \n**2nd level (3 slots):** [crown of madness](3-Mechanics/CLI/spells/crown-of-madness.md),\
      \ [misty step](3-Mechanics/CLI/spells/misty-step.md)\n\n**3rd level (3 slots):**\
      \ [animate dead](3-Mechanics/CLI/spells/animate-dead.md), [vampiric touch](3-Mechanics/CLI/spells/vampiric-touch.md)"
    "name": "Spellcasting"
  - "desc": "Once per turn when Oreioth kills one or more creatures with a spell of\
      \ 1st level or higher, he regains hit points equal to twice the spell's level."
    "name": "Grim Harvest"
  - "desc": "When a living Medium or Small humanoid within 30 feet of Oreioth dies,\
      \ he can use an action on his next turn to cast [animate dead](3-Mechanics/CLI/spells/animate-dead.md)\
      \ on that humanoid's corpse, instead of using the spell's normal casting time."
    "name": "Swift Animation (Recharges after a Long Rest)"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3\
      \ (1d4 + 1) piercing damage."
    "name": "Dagger"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/oreioth-pota.webp"
```
^statblock