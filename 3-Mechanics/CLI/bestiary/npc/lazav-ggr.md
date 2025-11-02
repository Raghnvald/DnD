---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- monster/cr/17
- monster/size/medium
- monster/type/monstrosity/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- Lazav
---
# [Lazav](3-Mechanics\CLI\bestiary\npc/lazav-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 232*  

Lazav is uniquely qualified to be the Dimir guildmaster: he is a shapechanger whose mysterious genius is informed by agents from the entire Dimir network. He takes on a tremendous variety of guises as his needs and plans require. He might step out into the Ravnican streets as an elderly widow to eavesdrop at the bazaar, become a vedalken hussar of the Azorius Senate to sidestep a checkpoint, or transform into a Tin Street merchant to deceive a passing noble. His true form might be that of a doppelganger or some other creature; no one has ever seen it.

```statblock
"name": "Lazav (GGR)"
"size": "Medium"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "204"
"hit_dice": "24d8 + 96"
"modifier": !!int "7"
"stats":
  - !!int "16"
  - !!int "24"
  - !!int "18"
  - !!int "22"
  - !!int "20"
  - !!int "22"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "13"
  - "intelligence": !!int "12"
  - "wisdom": !!int "11"
  - "charisma": !!int "12"
"skillsaves":
  - "name": "Deception"
    "desc": "+18"
  - "name": "Insight"
    "desc": "+11"
  - "name": "Perception"
    "desc": "+11"
  - "name": "Stealth"
    "desc": "+19"
"damage_resistances": "necrotic, psychic"
"damage_immunities": "poison"
"condition_immunities": "charmed, frightened, poisoned"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": "Common, Thieves' cant"
"cr": "17"
"traits":
  - "desc": "Lazav's innate spellcasting ability is Intelligence (spell save DC 20).\
      \ He can innately cast the following spells, requiring no material components:\n\
      \n**At will:** detect thoughts, [encode thoughts](/3-Mechanics/CLI/spells/encode-thoughts-ggr.md)\
      \ (see chapter 2), freedom of movement, vicious mockery (4d4 psychic damage)\n\
      \n**3/day each:** blur, confusion, mirror image\n\n**1/day each:** modify memory,\
      \ Rary's telepathic bond"
    "name": "Innate Spellcasting"
  - "desc": "No attack roll has advantage against Lazav unless he is incapacitated."
    "name": "Elusive"
  - "desc": "If Lazav fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Lazav can use a bonus action to polymorph into a Small or Medium humanoid\
      \ he has seen. His statistics, other than his size, are the same in each form.\
      \ Any equipment he is wearing or carrying isn't transformed."
    "name": "Shapechanger Savant"
  - "desc": "Unless Lazav is incapacitated, he is immune to magic that allows other\
      \ creatures to read his thoughts, determine whether he is lying, know his alignment,\
      \ or know his creature type. Creatures can telepathically communicate with Lazav\
      \ only if he allows it."
    "name": "Psychic Defenses"
"actions":
  - "desc": "Lazav makes three shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one target. *Hit:* 10\
      \ (1d6 + 7) piercing damage plus 10 (3d6) psychic damage, and the target has\
      \ disadvantage on the next attack roll it makes before Lazav's next turn."
    "name": "Shortsword"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Lazav can expend a use to take one of the following actions. Lazav regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Lazav makes a weapon attack."
    "name": "Attack"
  - "desc": "Lazav casts one of his innate spells."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "Lazav rapidly takes the form of several nightmarish creatures, lashing\
      \ out at all nearby. Each creature within 10 feet of Lazav must succeed on a\
      \ DC 21 Dexterity saving throw or take 18 (4d8) damage of a type chosen by Lazav:\
      \ acid, cold, fire, lightning, or necrotic."
    "name": "Shifting Nightmare (Costs 3 Actions)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/lazav-ggr.webp"
```
^statblock