---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/3
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Untote
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Sephek Kaltro
---
# [Sephek Kaltro](3-Mechanics\CLI\bestiary\npc/sephek-kaltro-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 23*  

Sephek Kaltro is a well-built man in his thirties. He has an olive complexion, dark hair pulled back in a ponytail, and no facial or body hair. He is dressed in a stylish vest with matching pants and boots, similar in style to those worn by mariners of the southern Sword Coast, but wears no armor or cold weather clothing and doesn't appear to be armed. His most striking feature is his eyes, which are as blue as a frozen lake.

```statblock
"name": "Sephek Kaltro (IDRotF)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "75"
"hit_dice": "10d8 + 30"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "16"
  - !!int "11"
  - !!int "16"
  - !!int "18"
"speed": "30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+5"
  - "name": "Survival"
    "desc": "+5"
"damage_immunities": "cold"
"condition_immunities": "charmed, frightened"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "Sephek can innately cast misty step up to three times per day, requiring\
      \ no components. His innate spellcasting ability is Charisma.\n"
    "name": "Innate Spellcasting"
  - "desc": "If the temperature around him is 0 degrees Fahrenheit or lower, Sephek\
      \ regains 5 hit points at the start of his turn. If he takes fire damage, this\
      \ trait doesn't function at the start of Sephek's next turn. Sephek dies only\
      \ if he starts his turn with 0 hit points and doesn't regenerate."
    "name": "Cold Regeneration"
"actions":
  - "desc": "Sephek attacks twice with a weapon."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 7 (1d8\
      \ + 3) slashing damage, or 8 (1d10 + 3) slashing damage if Sephek uses the weapon\
      \ with two hands, plus 5 (2d4) cold damage."
    "name": "Ice Longsword"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60 ft., one\
      \ target. *Hit:* 5 (1d4 + 3) piercing damage plus 5 (2d4) cold damage."
    "name": "Ice Dagger"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/npc/token/sephek-kaltro-idrotf.webp"
```
^statblock