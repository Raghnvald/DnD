---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- Quelle/5e/ggr
- monster/cr/4
- monster/size/medium
- monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Mind Drinker Vampire
---
# [Mind Drinker Vampire](3-Mechanics\CLI\bestiary\undead/mind-drinker-vampire-ggr.md)
*Source: Guildmasters' Guide to Ravnica p. 224*  

When vampires join House Dimir, they can learn to siphon mental energy and memories along with the blood of their victims. They also study the magic favored by Dimir mind mages, giving them a powerful combination of abilities ideal for espionage and infiltration.

## Szadek's Heirs

The founder of House Dimir, Szadek, was the first of the so-called mind drinkers. His secrets are passed on only to other members of his guild, and mind drinkers who leave House Dimir become enemies of the guild-the only exceptions to a rule that prohibits mind drinkers from feeding on others of their kind.

## Cell Leaders

Thanks to their particular gifts, mind drinkers are often placed as leaders of small cells of covert Dimir operatives. They rarely trust their own agents, though, and often follow their cell members to make sure those members carry out missions as ordered. The most suspicious vampires might even siphon thoughts from their subordinates to detect any hint of betrayal.

## Vampires

Creatures of the night, vampires are ageless undead beings who subsist on the blood of the living. They are fierce predators who mask their ravenous thirst behind a facade of sophistication and sensuality. Those who sip blood from golden chalices are no less voracious than those who tear out their victims' throats with their fangs; they just hide it better.

The vampires of Ravnica differ from those in the Monster Manual in important ways. They lack the traits and abilities that those other vampires boast, but also lack the weaknesses that hinder such vampires. What they have in common is an unquenchable thirst for the blood that sustains their undead existence.

```statblock
"name": "Mind Drinker Vampire (GGR)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "4"
"stats":
  - !!int "16"
  - !!int "18"
  - !!int "12"
  - !!int "19"
  - !!int "13"
  - !!int "14"
"speed": "30 ft., fly 30 ft. (hover)"
"saves":
  - "dexterity": !!int "6"
  - "intelligence": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "Deception"
    "desc": "+4"
  - "name": "Insight"
    "desc": "+3"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Stealth"
    "desc": "+6"
"damage_resistances": "necrotic"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "the languages it knew in life"
"cr": "4"
"traits":
  - "desc": "The vampire's innate spellcasting ability is Intelligence (spell save\
      \ DC 14). It can innately cast the following spells, requiring no components:\n\
      \n**At will:** message\n\n**3/day each:** charm person, hold person, mirror\
      \ image, sleep\n\n**1/day each:** gaseous form, major image"
    "name": "Innate Spellcasting (Psionics)"
  - "desc": "While in dim light or darkness, the vampire can take the Hide action\
      \ as a bonus action."
    "name": "Shadow Stealth"
  - "desc": "While in sunlight, the vampire has disadvantage on attack rolls, as well\
      \ as on Wisdom (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "The vampire makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one willing creature,\
      \ or a creature that is grappled by the vampire, incapacitated, or restrained.\
      \ *Hit:* 7 (1d6 + 4) piercing damage plus 7 (2d6) necrotic damage. The target's\
      \ hit point maximum is reduced by an amount equal to the necrotic damage taken,\
      \ and the vampire regains hit points equal to that amount. The reduction lasts\
      \ until the target finishes a long rest. The target dies if its hit point maximum\
      \ is reduced to 0."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) bludgeoning damage. The vampire can also grapple the target (escape DC\
      \ 13) if it is a creature and the vampire has a hand free."
    "name": "Unarmed Strike"
  - "desc": "The vampire targets a creature it can see within 30 feet of it. The target\
      \ must make a DC 14 Intelligence saving throw, with disadvantage if the vampire\
      \ has previously consumed the target's blood. On a failed save, the target takes\
      \ 28 (8d6) psychic damage, and the vampire discerns the target's surface emotions\
      \ and thoughts. On a successful save, the target takes half as much damage,\
      \ and the vampire discerns the target's general emotional state but not its\
      \ thoughts."
    "name": "Mind Siphon (Recharge 5-6)"
"source":
  - "GGR"
"image": "/3-Mechanics/CLI/bestiary/undead/token/mind-drinker-vampire-ggr.webp"
```
^statblock