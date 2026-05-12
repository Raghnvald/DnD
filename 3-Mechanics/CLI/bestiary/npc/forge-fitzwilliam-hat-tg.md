---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hat-tg
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Forge Fitzwilliam"
---
# [Forge Fitzwilliam](3-Mechanics/CLI/bestiary/npc/forge-fitzwilliam-hat-tg.md)
*Source: Honor Among Thieves: Thieves' Gallery*  

Forge Fitzwilliam is a con artist who manipulates others with lies and flattery. The audacious criminal has left a trail of broken promises and false identities along the Sword Coast. He conceals flexible morals and a ready dagger behind his winning smile.

Forge enjoys the finer things in life, particularly when they result from his own cleverness. Decades of heists and cons haven't slaked his thirst—in fact, his ambitions only grow grander with time.

```statblock
"name": "Forge Fitzwilliam (HAT-TG)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "disarming charm"
"hp": !!int "110"
"hit_dice": "20d8 + 20"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "13"
  - !!int "15"
  - !!int "17"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "5"
  - "intelligence": !!int "5"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+5"
  - "name": "Deception"
    "desc": "+11"
  - "name": "Investigation"
    "desc": "+8"
  - "name": "Persuasion"
    "desc": "+11"
  - "name": "Sleight of Hand"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+8"
"gear":
  - "dagger"
  - "heavy crossbow"
"senses": "passive Perception 13"
"languages": "Common, Thieves' cant"
"cr": "8"
"traits":
  - "desc": "While Forge isn't wearing armor, his AC includes his Charisma modifier."
    "name": "Disarming Charm"
  - "desc": "If Forge hits a creature friendly to him with an attack roll, the attack\
      \ is automatically a critical hit."
    "name": "Double-Cross"
  - "desc": "If Forge is subjected to an effect that allows him to make a Dexterity\
      \ saving throw to take only half damage, he takes no damage if he succeeds on\
      \ the saving throw, and only half damage if he fails, provided he isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Evasion"
"actions":
  - "desc": "Forge makes two Dagger attacks, two Heavy Crossbow attacks, or one of\
      \ each."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage plus 24 (7d6) poison\
      \ damage, and the target is [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ until the end of its next turn."
    "name": "Dagger"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 100/400 ft., one target. *Hit:*\
      \ 7 (1d10 + 2) piercing damage plus 24 (7d6) poison damage. *Hit or Miss:*\
      \ If the target is a creature, it has disadvantage on the next attack roll it\
      \ makes before the start of Forge's next turn."
    "name": "Heavy Crossbow"
"bonus_actions":
  - "desc": "Forge takes the Dash, Disengage, or Hide action, or he gives himself\
      \ advantage on the next attack roll he makes before the end of this turn."
    "name": "Cunning"
"reactions":
  - "desc": "Forge halves the damage he takes from an attack that hits him. He must\
      \ be able to see the attacker."
    "name": "Uncanny Dodge"
"source":
  - "HAT-TG"
"image": "3-Mechanics/CLI/bestiary/npc/token/forge-fitzwilliam-hat-tg.webp"
```
^statblock