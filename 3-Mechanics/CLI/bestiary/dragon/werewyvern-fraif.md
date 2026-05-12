---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/environment/hill
- ttrpg-cli/monster/environment/mountain
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/dragon/lycanthrope
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Werewyvern"
---
# [Werewyvern](3-Mechanics/CLI/bestiary/dragon/werewyvern-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 284*  

## Werewyvern

*Changed by the Venom of the Wyvern*

Among the rarest of were-creatures, werewyverns change from their humanoid forms into lean wyverns or into draconic-humanoid hybrids. Most werewyverns possess a draconic greed and ferocity and thus often find work as bandits, mercenaries, or assassins. They are opportunistic warriors and prefer ambushes when possible. Werewyverns like to keep their wyvern form a secret until they need an upper hand in a fight or an aerial escape.

Werewyverns transmit lycanthropy through their potent venom. The curse's transmission is unpredictable and often as much a surprise to the werewyvern as it is to the victim.

```statblock
"name": "Werewyvern (FRAiF)"
"size": "Medium"
"type": "dragon"
"subtype": "lycanthrope"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"hp": !!int "152"
"hit_dice": "16d8 + 80"
"modifier": !!int "5"
"stats":
  - !!int "19"
  - !!int "15"
  - !!int "20"
  - !!int "10"
  - !!int "12"
  - !!int "12"
"speed": "30 ft., fly 40 ft. (wyvern or hybrid form only)"
"saves":
  - "dexterity": !!int "5"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
  - "name": "Stealth"
    "desc": "+5"
"gear":
  - "six javelins"
"senses": "Darkvision 120 ft., passive Perception 14"
"languages": "Common, Draconic (can't speak in wyvern form)"
"cr": "8"
"traits":
  - "desc": "The werewyvern doesn't provoke an Opportunity Attack action when it flies\
      \ out of an enemy's reach."
    "name": "Flyby (Wyvern or Hybrid Form Only)"
"actions":
  - "desc": "The werewyvern makes three attacks, using Javelin or Rend in any combination.\
      \ It can replace one of these attacks with one Stinger attack."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 30/120 ft.\
      \ *Hit:* 18 (4d6 + 4) Piercing damage."
    "name": "Javelin (Humanoid or Hybrid Form Only)"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 18 (4d6 + 4) Slashing\
      \ damage."
    "name": "Rend"
  - "desc": "*Melee Attack Roll:* +7, reach 5 ft. *Hit:* 7 (1d6 + 4) Piercing\
      \ damage plus 16 (3d10) Poison damage, and the target has the Poisoned condition\
      \ until the start of the werewyvern's next turn. If the target is a Humanoid,\
      \ it is subjected to the following effect. *Constitution Saving Throw:* DC 16.\
      \ *Failure:* The target is cursed. If the cursed target drops to 0 <span title=\"\
      Player's Handbook (2024)\">Hit Points</span>, it instead becomes a Werewyvern\
      \ under the DM's control and has 20 <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span>. *Success:* The target is immune to this werewyvern's curse\
      \ for 24 hours."
    "name": "Stinger (Wyvern or Hybrid Form Only)"
"bonus_actions":
  - "desc": "The werewyvern shape-shifts into a Medium wyvern-humanoid hybrid or a\
      \ Large wyvern, or it returns to its true humanoid form. Its game statistics,\
      \ other than its size, are the same in each form. Any equipment it is wearing\
      \ or carrying isn't transformed."
    "name": "Shape-Shift"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/dragon/token/werewyvern-fraif.webp"
```
^statblock

## Environment

hill, mountain