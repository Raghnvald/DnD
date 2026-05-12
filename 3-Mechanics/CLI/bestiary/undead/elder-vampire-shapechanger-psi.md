---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Elder Vampire: Shapechanger"
---
# [Elder Vampire: Shapechanger](3-Mechanics/CLI/bestiary/undead/elder-vampire-shapechanger-psi.md)
*Source: Plane Shift: Innistrad p. 17*  

```statblock
"name": "Elder Vampire: Shapechanger (PSI)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ not made with living wood weapons"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common"
"cr": "5"
"traits":
  - "desc": "The vampire regains 10 hit points at the start of its turn if it has\
      \ at least 1 hit point. If the vampire takes radiant damage or damage from [holy\
      \ water](3-Mechanics/CLI/items/holy-water-flask.md), this trait doesn't function\
      \ at the start of the vampire's next turn."
    "name": "Regeneration"
  - "desc": "If the vampire isn't in sunlight or running water, it can use its action\
      \ to polymorph into a Tiny bat or a Medium cloud of mist, or back into its true\
      \ form.\n\nWhile in bat form, the vampire can't speak, its walking speed is\
      \ 5 feet, and it has a flying speed of 30 feet. Its statistics, other than its\
      \ size and speed, are unchanged. Anything it is wearing transforms with it,\
      \ but nothing it is carrying does. It reverts to its true form if it dies.\n\
      \nWhile in mist form, the vampire can't take any actions, speak, or manipulate\
      \ objects. It is weightless, has a flying speed of 20 feet, can hover, and can\
      \ enter a hostile creature's space and stop there. In addition, if air can pass\
      \ through a space, the mist can do so without squeezing, and it can't pass through\
      \ water. It has advantage on Strength, Dexterity, and Constitution saving throws,\
      \ and it is immune to all nonmagical damage, except the damage it takes from\
      \ sunlight."
    "name": "Shapechanger"
"actions":
  - "desc": "The vampire makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:*\
      \ 8 (2d4 + 3) slashing damage. Instead of dealing damage, the vampire can\
      \ grapple the target (escape DC 13)."
    "name": "Claws"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one willing creature,\
      \ or a creature that is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the vampire, [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
      \ or [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* 6\
      \ (1d6 + 3) piercing damage plus 7 (2d6) necrotic damage. The target's hit\
      \ point maximum is reduced by an amount equal to the necrotic damage taken,\
      \ and the vampire regains hit points equal to that amount. The reduction lasts\
      \ until the target finishes a long rest. The target dies if this effect reduces\
      \ its hit point maximum to 0."
    "name": "Bite"
  - "desc": "The vampire obscures its form with mind-affecting magic that makes others\
      \ perceive it as a beautiful human of the same size and shape. The illusion\
      \ ends if the vampire takes a bonus action to end it or if the vampire dies.\
      \ A creature that can see the vampire can take an action to visually inspect\
      \ it, ending the mental effect on itself and seeing the vampire's true form\
      \ with a successful DC 20 Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ check."
    "name": "Vampiric Glamer"
  - "desc": "The vampire shrouds itself in a cloak of silence to a radius of 2 feet.\
      \ Within that radius, the effect is the same as the [silence](3-Mechanics/CLI/spells/silence.md)\
      \ spell."
    "name": "Aura of Silence"
"source":
  - "PSI"
```
^statblock