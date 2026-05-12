---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Elder Vampire: Spellcasting—Wizard"
---
# [Elder Vampire: Spellcasting—Wizard](3-Mechanics/CLI/bestiary/undead/elder-vampire-spellcastingwizard-psi.md)
*Source: Plane Shift: Innistrad p. 17*  

```statblock
"name": "Elder Vampire: Spellcasting—Wizard (PSI)"
"size": "Medium"
"type": "undead"
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
  - "desc": "> [!note]\n> The [Mage](3-Mechanics/CLI/bestiary/humanoid/mage.md) has\
      \ been used as an example Wizard.\n\nThe vampire is a 9th-level spellcaster.\
      \ Its spellcasting ability is Intelligence (spell save DC 14, +6 to hit with\
      \ spell attacks). The vampire has the following wizard spells prepared:\n\n\
      **Cantrips (at will):** [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md), [light](3-Mechanics/CLI/spells/light.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1st level (4 slots):** [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor.md), [magic missile](3-Mechanics/CLI/spells/magic-missile.md),\
      \ [shield](3-Mechanics/CLI/spells/shield.md)\n\n**2nd level (3 slots):** [misty\
      \ step](3-Mechanics/CLI/spells/misty-step.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell.md),\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md), [fly](3-Mechanics/CLI/spells/fly.md)\n\
      \n**4th level (3 slots):** [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility.md),\
      \ [ice storm](3-Mechanics/CLI/spells/ice-storm.md)\n\n**5th level (1 slots):**\
      \ [cone of cold](3-Mechanics/CLI/spells/cone-of-cold.md)"
    "name": "Spellcasting"
  - "desc": "The vampire regains 10 hit points at the start of its turn if it has\
      \ at least 1 hit point. If the vampire takes radiant damage or damage from [holy\
      \ water](3-Mechanics/CLI/items/holy-water-flask.md), this trait doesn't function\
      \ at the start of the vampire's next turn."
    "name": "Regeneration"
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