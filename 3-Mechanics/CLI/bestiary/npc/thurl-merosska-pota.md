---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thurl Merosska"
---
# [Thurl Merosska](3-Mechanics/CLI/bestiary/npc/thurl-merosska-pota.md)
*Source: Princes of the Apocalypse p. 192*  

Thurl Merosska is the leader of the Feathergale Knights. Once a griffon rider of Waterdeep, Thurl retired after a storm nearly claimed his life. Obsessed with his near-death experience, Thurl learned of Yan-C-Bin and swore an oath to serve the elemental prince in exchange for power.

Thurl realized that there were others among the wealthy of Waterdeep who might make worthy servants of Yan-C-Bin. He formed the Feathergale Society to lure likely individuals into the air cult. He indoctrinated his Feathergale knights, one by one, into the cult's beliefs.

When Aerisi Kalinoth arose as the chosen prophet of air, Thurl reluctantly pledged the Feathergale Knights to the cause. He resents Aerisi Kalinoth's rulership of the cult, but tells himself that he can use her and her followers to make the Feathergale Society strong enough to rule Waterdeep as it should be ruled.

```statblock
"name": "Thurl Merosska (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate.md)"
"hp": !!int "71"
"hit_dice": "11d8 + 21"
"modifier": !!int "2"
"stats":
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "11"
  - !!int "10"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+2"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+4"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+4"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
  - "[lance](3-Mechanics/CLI/items/lance.md)"
"senses": "passive Perception 10"
"languages": "Auran, Common"
"cr": "3"
"traits":
  - "desc": "Thurl is a 5th-level spellcaster. His spellcasting ability is Charisma\
      \ (spell save DC 12, +4 to hit with spell attacks). Thurl knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** [friends](3-Mechanics/CLI/spells/friends.md),\
      \ gust, [light](3-Mechanics/CLI/spells/light.md), [message](3-Mechanics/CLI/spells/message.md),\
      \ [ray of frost](3-Mechanics/CLI/spells/ray-of-frost.md)\n\n**1st level (4 slots):**\
      \ [expeditious retreat](3-Mechanics/CLI/spells/expeditious-retreat.md), [feather\
      \ fall](3-Mechanics/CLI/spells/feather-fall.md), [jump](3-Mechanics/CLI/spells/jump.md)\n\
      \n**2nd level (3 slots):** [levitate](3-Mechanics/CLI/spells/levitate.md), [misty\
      \ step](3-Mechanics/CLI/spells/misty-step.md)\n\n**3rd level (2 slots):** [haste](3-Mechanics/CLI/spells/haste.md)"
    "name": "Spellcasting"
"actions":
  - "desc": "Thurl makes two melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (2d6 + 3) slashing damage."
    "name": "Greatsword"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 10 ft., one target. *Hit:*\
      \ 9 (1d12 + 3) piercing damage."
    "name": "Lance"
"reactions":
  - "desc": "Thurl adds 2 to his AC against one melee attack that would hit him. To\
      \ do so, Thurl must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/thurl-merosska-pota.webp"
```
^statblock