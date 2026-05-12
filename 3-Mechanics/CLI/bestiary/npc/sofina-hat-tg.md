---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hat-tg
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sofina"
---
# [Sofina](3-Mechanics/CLI/bestiary/npc/sofina-hat-tg.md)
*Source: Honor Among Thieves: Thieves' Gallery*  

Sofina is a Red Wizard of Thay, an elite practitioner of magic with ties to Thay's tyrannical magocracy. Sofina specializes in necromancy. Death magic and fear are both tools in her arsenal.

As Red Wizards are shunned outside Thay, Sofina conceals her affiliations and coldly rebuffs any who seek her friendship. A canny operator, she has patiently moved her pieces into place, and her grand designs now begin to take shape.

```statblock
"name": "Sofina (HAT-TG)"
"size": "Medium"
"type": "humanoid"
"subtype": "wizard"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "161"
"hit_dice": "19d8 + 76"
"modifier": !!int "2"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "18"
  - !!int "20"
  - !!int "14"
  - !!int "8"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "10"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+10"
  - "name": "History"
    "desc": "+10"
  - "name": "Insight"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "passive Perception 12"
"languages": "Abyssal, Common, Draconic, Infernal, Thayan"
"cr": "15"
"traits":
  - "desc": "Sofina wears a magic robe that grants her a +2 bonus to AC and a +1 bonus\
      \ to saving throws (included above)."
    "name": "Special Equipment"
"actions":
  - "desc": "Sofina makes three Necrotic Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +10 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 32 (5d10 + 5) necrotic damage."
    "name": "Necrotic Strike"
  - "desc": "Sofina magically calls down a meteor swarm that detonates in four 40-foot-radius\
      \ spheres, each one centered on a point she can see within 1 mile of herself.\
      \ These spheres can overlap. Each creature in one or more of these spheres must\
      \ make a DC 18 Dexterity saving throw, taking 35 (10d6) fire damage and 35\
      \ (10d6) bludgeoning damage on a failed saving throw, or half as much damage\
      \ on a successful one. A creature in multiple spheres takes this damage only\
      \ once."
    "name": "Swarm of Meteors (1/Day)"
  - "desc": "Sofina casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 18):\n\n**At will:** mage hand, message, prestidigitation\n\
      \n**2/day each:** bestow curse, Bigby's hand, dimension door, mage armor, Otiluke's\
      \ resilient sphere, thunderwave\n\n**1/day each:** Evard's black tentacles,\
      \ finger of death, time stop"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Sofina magically summons the spirit of a Thayan assassin, which appears\
      \ as a wraith (see the Monster Manual). The summoned wraith appears in an unoccupied\
      \ space within 60 feet of Sofina, whom it obeys. The summoned wraith takes its\
      \ turn immediately after Sofina. It lasts for 1 hour, until it or Sofina dies,\
      \ or until Sofina dismisses it as a bonus action."
    "name": "Summon Wraith (1/Day)"
"source":
  - "HAT-TG"
"image": "3-Mechanics/CLI/bestiary/npc/token/sofina-hat-tg.webp"
```
^statblock