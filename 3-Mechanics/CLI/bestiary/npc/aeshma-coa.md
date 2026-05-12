---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/tiefling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Aeshma"
---
# [Aeshma](3-Mechanics/CLI/bestiary/npc/aeshma-coa.md)
*Source: Chains of Asmodeus p. 261*  

Aeshma is a tiefling who was born into a rich and affluent family with ties to powerful families within the city of Waterdeep. Aeshma has learned that everything in life comes easy, free, and without consequence. Aeshma is a jack of no trades and master of none, he has ceremoniously failed himself out of magic studies, countless bard colleges, church studies, and military training. Aeshma excels at one thing: convincing and manipulating others to gamble. He doesn't really care for the stakes or the outcome of a bet, rather he gets enjoyment out of the consternation of others. Aeshma is a chronic gambler who always pushes the stakes to their limits.

Aeshma was content to a life pursuing pleasure and with no responsibilities, but his infernal heritage has entangled him with something he could have never expected. He is the soul that the Halruaans call the Unmaker (Aeshma is unaware that he is the Unmaker). Asmodeus has plans for Aeshma and had one of his archdevils, Abigor, kidnap him.

```statblock
"name": "Aeshma (CoA)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Chaotic Neutral"
"ac": !!int "15"
"ac_class": "[bracers of defense](3-Mechanics/CLI/items/bracers-of-defense.md)"
"hp": !!int "45"
"hit_dice": "7d8 + 14"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "Deception"
    "desc": "+7"
  - "name": "Insight"
    "desc": "+4"
  - "name": "Performance"
    "desc": "+7"
  - "name": "Persuasion"
    "desc": "+7"
  - "name": "Sleight of Hand"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+5"
"gear":
  - "hand crossbow"
  - "shortsword"
"senses": "passive Perception 12"
"languages": "Common, Infernal"
"cr": "2"
"actions":
  - "desc": "Aeshma makes two attacks using his Shortsword, Hand Crossbow, or a combination\
      \ of the two."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 30/120 ft., one target. *Hit:*\
      \ 6 (1d6 + 3) piercing damage."
    "name": "Hand Crossbow"
"bonus_actions":
  - "desc": "Aeshma takes the Dash, Disengage, or Hide action."
    "name": "Cunning"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/aeshma-coa.webp"
```
^statblock