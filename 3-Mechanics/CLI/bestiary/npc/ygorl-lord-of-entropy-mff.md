---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mff
- ttrpg-cli/monster/cr/23
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ygorl, Lord of Entropy"
---
# [Ygorl, Lord of Entropy](3-Mechanics/CLI/bestiary/npc/ygorl-lord-of-entropy-mff.md)
*Source: Mordenkainen's Fiendish Folio p. 20*  

The enigmatic being known as Ygorl was one of the first slaadi created after Primus unleashed the Spawning Stone upon Limbo. A powerful being suffused with entropic power, Ygorl delights in the act of unmaking and bringing chaos to any ecosystem it visits. Lesser slaadi follow close behind the lord of entropy, delighting and furthering the destruction it brings.

## Cycles of Chaos

As a personification of entropy, Ygorl is cursed to see things as they will become—broken and consumed by the march of eternity. It has no sense of empathy or compassion, driven only to unmake so that the resulting base elements of reality can fuel the multiverse's endless cycles of creation and destruction.

Speaking to Ygorl is a taxing endeavor, as the lord of entropy channels its thoughts as a stream of consciousness that is both disturbing and difficult to follow. Mortal creatures that have attempted to parley with Ygorl are known to have been driven to madness in the process.

## Death and Destruction

Ygorl's most notable possession is an adamantine scythe with the slaad word for death inscribed across the blade, which can reduce living creatures to ash. The lord of entropy also bears a set of obsidian tablets slung about its waist, upon which it inscribes destructive runes. Living creatures wither and rot within the entropic energy emanated by Ygorl's magic.

```statblock
"name": "Ygorl, Lord of Entropy (MFF)"
"size": "Large"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "325"
"hit_dice": "26d10 + 182"
"modifier": !!int "4"
"stats":
  - !!int "24"
  - !!int "18"
  - !!int "24"
  - !!int "20"
  - !!int "16"
  - !!int "26"
"speed": "40 ft., climb 40 ft., swim 40 ft."
"saves":
  - "strength": !!int "14"
  - "constitution": !!int "14"
  - "charisma": !!int "15"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+12"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+15"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+15"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+15"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"damage_immunities": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 13"
"languages": "all, telepathy 120 ft."
"cr": "23"
"traits":
  - "desc": "Ygorl's innate spellcasting ability is Charisma (spell save DC 23, +15\
      \ to hit with spell attacks). It can innately cast the following spells, requiring\
      \ no material components:\n\n**At will:** [blight](3-Mechanics/CLI/spells/blight.md),\
      \ [blink](3-Mechanics/CLI/spells/blink.md), chaos bolt*, [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [fly](3-Mechanics/CLI/spells/fly.md), [shield](3-Mechanics/CLI/spells/shield.md)\n\
      \n**3/day each:** [circle of death](3-Mechanics/CLI/spells/circle-of-death.md),\
      \ enervation*, [symbol](3-Mechanics/CLI/spells/symbol.md) (discord only)\n\n\
      **2/day each:** [finger of death](3-Mechanics/CLI/spells/finger-of-death.md),\
      \ [harm](3-Mechanics/CLI/spells/harm.md), mental prison*\n\n**1/day each:**\
      \ [power word kill](3-Mechanics/CLI/spells/power-word-kill.md), [power word\
      \ stun](3-Mechanics/CLI/spells/power-word-stun.md), [symbol](3-Mechanics/CLI/spells/symbol.md)\
      \ (death only), [weird](3-Mechanics/CLI/spells/weird.md)\n\n* Spell from Xanathar's\
      \ Guide to Everything"
    "name": "Innate Spellcasting"
  - "desc": "Each creature that is not a construct or undead that ends its turn within\
      \ 15 feet of Ygorl takes 14 (4d6) necrotic damage."
    "name": "Entropic Aura"
  - "desc": "If Ygorl fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Ygorl has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Ygorl makes three attacks: two with its scythe, and one with its Entropic\
      \ Touch."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one creature. *Hit:*\
      \ 18 (2d10 + 7) slashing damage plus 19 (3d12) necrotic damage. Any creature\
      \ reduced to 0 hit points by this attack dies, with its body and everything\
      \ it is wearing and carrying, except magic items, exploding into a cloud of\
      \ ash. The creature can be restored to life only by means of a [wish](3-Mechanics/CLI/spells/wish.md)\
      \ spell."
    "name": "Scythe"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 16 (2d8 + 7) necrotic damage, and the target must succeed on a DC 22 Constitution\
      \ saving throw or gain one level of [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion)."
    "name": "Entropic Touch"
  - "desc": "Ygorl summons 1d4 + 1 [death slaadi](3-Mechanics/CLI/bestiary/aberration/death-slaad.md).\
      \ A summoned slaad appears in an unoccupied space within 60 feet of Ygorl, acts\
      \ as an ally of Ygorl, and can't summon other slaadi. It remains for 1 minute,\
      \ until it or Ygorl dies, or until Ygorl dismisses it as an action."
    "name": "Summon Slaadi (1/Day)"
  - "desc": "Ygorl teleports, along with any equipment it is wearing or carrying,\
      \ up to 120 feet to an unoccupied space it can see."
    "name": "Teleport"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Ygorl can expend a use to take one of the following actions. Ygorl regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Ygorl makes one attack with its scythe."
    "name": "Scythe"
  - "desc": "Ygorl uses its Teleport action."
    "name": "Teleport"
  - "desc": "Each creature that is not a construct or undead within 30 feet of Ygorl\
      \ must make a DC 22 Constitution saving throw against the lord of entropy's\
      \ attempt to unmake life, taking 42 (12d6) necrotic damage on a failed save,\
      \ or half as much damage on a successful one. Ygorl then regains a number of\
      \ hit points equal to half the total damage taken by all affected creatures."
    "name": "Call the Void (Costs 3 Actions)"
"source":
  - "MFF"
"image": "3-Mechanics/CLI/bestiary/npc/token/ygorl-lord-of-entropy-mff.webp"
```
^statblock