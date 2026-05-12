---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Avatar of Baalzebul"
---
# [Avatar of Baalzebul](3-Mechanics/CLI/bestiary/fiend/avatar-of-baalzebul-coa.md)
*Source: Chains of Asmodeus p. 38*  

```statblock
"name": "Avatar of Baalzebul (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "285"
"hit_dice": "30d8 + 150"
"modifier": !!int "1"
"stats":
  - !!int "21"
  - !!int "13"
  - !!int "20"
  - !!int "17"
  - !!int "18"
  - !!int "20"
"speed": "20 ft., fly 30 ft."
"saves":
  - "strength": !!int "11"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "Deception"
    "desc": "+11"
  - "name": "Insight"
    "desc": "+10"
  - "name": "Intimidation"
    "desc": "+11"
  - "name": "Persuasion"
    "desc": "+11"
"damage_vulnerabilities": "radiant"
"damage_resistances": "acid; cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, poisoned"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "all, telepathy 120 ft."
"cr": "18"
"traits":
  - "desc": "Any creature that starts its turn within 10 feet of the avatar must succeed\
      \ on a DC 19 Constitution saving throw or have the poisoned condition until\
      \ the start of their next turn. On a successful saving throw, the creature is\
      \ immune to this stench for 1 hour."
    "name": "Stench of the Slug"
"actions":
  - "desc": "The avatar makes four Sickening Claw attacks. It can replace one of the\
      \ attacks with Insect Gorge (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:*\
      \ 9 (1d8 + 5) slashing damage plus 13 (3d8) acid damage. The target's hit\
      \ point maximum is reduced by the acid damage taken. The reduction lasts until\
      \ the target finishes a long rest. The target dies if this effect reduces its\
      \ hit point maximum to 0."
    "name": "Sickening Claw"
  - "desc": "The avatar disgorges a swarm of biting flies at a point it can see within\
      \ 300 feet of itself. Each creature within a 20-foot-radius sphere centered\
      \ on that point must make a DC 19 Constitution saving throw. A creature takes\
      \ 55 (10d10) piercing damage on a failed save, or half as much damage on a\
      \ successful one. The biting flies persist for 1 minute or until the avatar\
      \ is slain. A creature must also make this saving throw when it enters the insects'\
      \ area for the first time on a turn or ends its turn there."
    "name": "Insect Gorge (Recharge 4-6)"
  - "desc": "The avatar causes caustic slime to emanate from itself, covering a 15-foot-radius\
      \ circle. Each creature within the slime must succeed on a DC 19 Dexterity saving\
      \ throw or have the grappled condition (escape DC 17). A grappled creature takes\
      \ 21 (6d6) acid damage at the start of its turn."
    "name": "Caustic Slimepool (1/Day)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/avatar-of-baalzebul-coa.webp"
```
^statblock