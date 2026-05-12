---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kelubar Demodand"
---
# [Kelubar Demodand](3-Mechanics/CLI/bestiary/fiend/kelubar-demodand-mpp.md)
*Source: Morte's Planar Parade p. 27*  

Kelubars, sometimes called slimy demodands, are the bureaucrats of Carceri, existing as intermediaries between farastus and shators. They are squat, and their skin drips with a foul-smelling, acidic slime. Kelubars revel in the subservience of others, and they prefer to do battle with words—or at least to send in their farastu minions—rather than fight directly.

## Demodands

Demodands, also called gehreleths, are Fiends from the Tarterian Depths of Carceri. Cast into the prison plane long ago for forgotten transgressions, these bitter, wicked creatures have appointed themselves the jailers of the plane. Demodands viciously defend the few known portals that lead out of Carceri and ruthlessly torment other creatures trapped there.

Demodands that manage to leave Carceri know they're doomed to return; a demodand that dies outside Carceri re-forms there in a torturous process that takes `2d20` days. Even those who survive on other planes find themselves eventually dragged back, pulled by some planar tether.

```statblock
"name": "Kelubar Demodand (MPP)"
"size": "Medium"
"type": "fiend"
"alignment": "typically  Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"modifier": !!int "1"
"stats":
  - !!int "22"
  - !!int "13"
  - !!int "18"
  - !!int "14"
  - !!int "15"
  - !!int "18"
"speed": "30 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
"damage_resistances": "cold, fire"
"damage_immunities": "acid, poison"
"condition_immunities": "[paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 12"
"languages": "Abyssal, Demodand, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "A creature that touches the kelubar or hits it with a melee attack while\
      \ within 5 feet of it takes 5 (2d4) acid damage."
    "name": "Acidic Secretions"
  - "desc": "The kelubar ignores difficult terrain, and magical effects can't reduce\
      \ its speed. It can spend 5 feet of movement to automatically remove the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition from itself."
    "name": "Boundless Movement"
  - "desc": "The kelubar has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The kelubar makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:*\
      \ 11 (1d10 + 6) piercing damage plus 18 (4d8) acid damage."
    "name": "Bite"
  - "desc": "The kelubar spits acid in a line 60 feet long and 5 feet wide. Each creature\
      \ in that area must make a DC 17 Dexterity saving throw, taking 27 (6d8) acid\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Spit Acid"
  - "desc": "The kelubar has a 40 percent chance of summoning its choice of 1d2\
      \ farastu demodands or 1 kelubar demodand. A summoned demodand appears in an\
      \ unoccupied space within 60 feet of the kelubar, acts as an ally of the kelubar,\
      \ and can't summon other demodands. It remains for 1 minute, until it or the\
      \ kelubar dies, or until the kelubar dismisses it as an action."
    "name": "Summon Demodand (1/Day)"
  - "desc": "The kelubar casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 17):\n\
      \n**At will:** [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self\
      \ only)\n\n**1/day each:** [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md),\
      \ [scrying](3-Mechanics/CLI/spells/scrying.md) (as an action)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The kelubar magically creates a cloud of greenish fog that fills a 20-foot-radius\
      \ sphere centered on a point within 120 feet of itself. The cloud remains for\
      \ 1 minute or until the kelubar uses this bonus action again. The cloud is heavily\
      \ obscured and difficult terrain. Any creature that starts its turn in the cloud\
      \ or enters the cloud for the first time on a turn must succeed on a DC 17 Constitution\
      \ saving throw or have the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition until the end of its next turn."
    "name": "Nauseating Fog (Recharge 6)"
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/fiend/token/kelubar-demodand-mpp.webp"
```
^statblock