---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-thp
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Morwena Veilmist"
---
# [Morwena Veilmist](3-Mechanics/CLI/bestiary/npc/morwena-veilmist-aitfr-thp.md)
*Source: Adventures in the Forgotten Realms: The Hidden Page p. 13*  

Morwena Veilmist was a Red Wizard of Thay, but she was never loyal. She saw the Thayan wizards as a means to acquire power. When she met Tyreus, she thought she saw a new opportunity. She abandoned her old apprentice, Malivar, and joined Tyreus. She hoped she'd found a peer in the pursuit of power. She regrets her choice but remains devoted to her own success and no one else's. The lesson she chose to learn was never to trust anyone.

She is a tall, slender Chondathan woman with a severe hairstyle, kept short for simplicity's sake. She wears her fingernails short but sharp. She is a skilled, even cunning, player of dragonchess.

## Personality

"I read anything I can get my hands on. Most creatures aren't as smart as I am, so I talk down to people when I need them to keep up."

## Ideal

"Power. All things flow from personal power, and although I have little of it right now, I shall find new ways to attain and use power for the only person that matters to me: myself."

## Bond

"I've learned a valuable lesson about trusting people: don't. Other people may be of use to me, but I'm not putting myself in a position to be used again."

## Flaw

"I've let myself be fooled into trusting people, but no one is worth that risk. Only fools tell the whole truth."

```statblock
"name": "Morwena Veilmist (AitFR-THP)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "13"
  - !!int "17"
  - !!int "12"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Arcana"
    "desc": "+6"
  - "name": "History"
    "desc": "+6"
"gear":
  - "quarterstaff"
"senses": "passive Perception 10"
"languages": "any four languages"
"cr": "5"
"traits":
  - "desc": "Morwena is a 10th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 15, +6 to hit with spell attacks). She has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** friends, mage hand, mending,\
      \ message\n\n**1st level (4 slots):** charm person*, mage armor, magic missile\n\
      \n**2nd level (3 slots):** hold person*, invisibility, suggestion*\n\n**3rd\
      \ level (3 slots):** fireball, haste, tongues\n\n**4th level (3 slots):** arcane\
      \ eye, phantasmal killer\n\n**5th level (2 slots):** hold monster*\n\n*Enchantment\
      \ spell of 1st level or higher"
    "name": "Spellcasting"
"actions":
  - "desc": "*Melee Weapon Attack:* +2 to hit, reach 5 ft., one target. *Hit:* 2\
      \ (1d6-1) bludgeoning damage, or 3 (1d8-1) bludgeoning damage if used with two\
      \ hands."
    "name": "Quarterstaff"
"reactions":
  - "desc": "Morwena tries to magically divert an attack made against her, provided\
      \ that the attacker is within 30 feet of her and visible to her. She must decide\
      \ to do so before the attack hits or misses.\n\nThe attacker must make a DC\
      \ 15 Wisdom saving throw. On a failed save, the attacker targets the creature\
      \ closest to it, other than Morwena or itself. If multiple creatures are closest,\
      \ the attacker chooses which one to target."
    "name": "Instinctive Charm (Recharges after Morwena Casts an Enchantment Spell\
      \ of 1st Level or Higher)"
"source":
  - "AitFR-THP"
"image": "3-Mechanics/CLI/bestiary/npc/token/morwena-veilmist-aitfr-thp.webp"
```
^statblock