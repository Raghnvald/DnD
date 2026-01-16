---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- new/compendium/src/5e/idrotf
- new/monster/cr/3
- new/monster/size/small
- new/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- Kobold Vampire Spawn
---
# [Kobold Vampire Spawn](3-Mechanics\CLI\bestiary\undead/kobold-vampire-spawn-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 297*  

The gnoll vampire Tekeli-li has a small number of kobold vampire spawn minions to keep it company in the Caves of Hunger (see chapter 6). The vampiric kobolds are terrified of the gnoll vampire and can't understand its commands, so they give Tekeli-li a wide berth. These ravenous undead kobolds thirst for blood and tend to swarm one foe at a time.

```statblock
"name": "Kobold Vampire Spawn (IDRotF)"
"size": "Small"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "14"
"hp": !!int "39"
"hit_dice": "6d6 + 18"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "16"
  - !!int "8"
  - !!int "8"
  - !!int "8"
"speed": "30 ft., climb 20 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "1"
"skillsaves":
  - "name": "Perception"
    "desc": "+1"
  - "name": "Stealth"
    "desc": "+6"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": "Common, Draconic"
"cr": "3"
"traits":
  - "desc": "The vampire has advantage on an attack roll against a creature if at\
      \ least one of the vampire's allies is within 5 feet of the creature and the\
      \ ally isn't incapacitated."
    "name": "Pack Tactics"
  - "desc": "The vampire regains 10 hit points at the start of its turn if it has\
      \ at least 1 hit point and isn't in sunlight or running water. If the vampire\
      \ takes radiant damage or damage from holy water, this trait doesn't function\
      \ at the start of its next turn."
    "name": "Regeneration"
  - "desc": "The vampire doesn't require air."
    "name": "Unusual Nature"
  - "desc": "The vampire has the following flaws:\n\n- **Forbiddance.** The vampire\
      \ can't enter a residence without an invitation from one of the occupants. \
      \ \n- **Harmed by Running Water.** The vampire takes 20 acid damage when it\
      \ starts its turn in running water.  \n- **Stake to the Heart.** The vampire\
      \ is destroyed if a piercing weapon made of wood is driven into its heart while\
      \ it is incapacitated in its resting place.  \n- **Sunlight Hypersensitivity.**\
      \ The vampire takes 20 radiant damage when it starts its turn in sunlight. While\
      \ in sunlight, it has disadvantage on attack rolls and ability checks.  "
    "name": "Vampire Weaknesses"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:* 6\
      \ (1d4 + 4) piercing damage plus 5 (2d4) necrotic damage. The target's hit point\
      \ maximum is reduced by an amount equal to the necrotic damage taken, and the\
      \ vampire regains hit points equal to that amount. The reduction lasts until\
      \ the target finishes a long rest. The target dies if its hit point maximum\
      \ is reduced to 0."
    "name": "Bite"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/undead/token/kobold-vampire-spawn-idrotf.webp"
```
^statblock