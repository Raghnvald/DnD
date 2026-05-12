---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/giant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ogre Channeler"
---
# [Ogre Channeler](3-Mechanics/CLI/bestiary/giant/ogre-channeler-psz.md)
*Source: Plane Shift: Zendikar p. 31*  

The ogres of Zendikar are towering brutes driven by cruelty, greed, and savage ferocity. They favor the jagged mountains of Akoum but can be found on every continent. Their size and strength help protect them from the dangers of Zendikar, so they have little need of walls or roofs—which is good, since they have little skill at building. Ogre society, such as it is, revolves around leaders who gather small gangs (usually six to ten other ogres) to join them in pillaging, extorting, or slaving. The Monster Manual's [ogre](3-Mechanics/CLI/bestiary/giant/ogre.md) statistics work fine for Zendikar ogres.

Despite their low intelligence, some more clever ogres—perhaps represented as [oni](3-Mechanics/CLI/bestiary/giant/oni.md)—master the use of certain kinds of magic. The use of red mana complements an ogre's fierce and angry tendencies, and some ogres can produce fiery spells and manipulate the volcanic forces of Akoum. Other ogres channel black mana to immerse themselves in necromancy and diabolism, accentuating their amoral nature and their willingness to enslave others for their own benefit.

```statblock
"name": "Ogre Channeler (PSZ)"
"size": "Large"
"type": "giant"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[chain mail](3-Mechanics/CLI/items/chain-mail.md)"
"hp": !!int "110"
"hit_dice": "13d10 + 39"
"modifier": !!int "0"
"stats":
  - !!int "19"
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "12"
  - !!int "15"
"speed": "30 ft., fly 30 ft."
"saves":
  - "dexterity": !!int "3"
  - "constitution": !!int "6"
  - "wisdom": !!int "4"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+5"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"gear":
  - "[glaive](3-Mechanics/CLI/items/glaive.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Common, Giant"
"cr": "7"
"traits":
  - "desc": "The ogre's innate spellcasting ability is Charisma (spell save DC 13).\
      \ The ogre can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [darkness](3-Mechanics/CLI/spells/darkness.md), [invisibility](3-Mechanics/CLI/spells/invisibility.md)\n\
      \n**1/day each:** [charm person](3-Mechanics/CLI/spells/charm-person.md), [cone\
      \ of cold](3-Mechanics/CLI/spells/cone-of-cold.md), [gaseous form](3-Mechanics/CLI/spells/gaseous-form.md),\
      \ [sleep](3-Mechanics/CLI/spells/sleep.md)"
    "name": "Innate Spellcasting"
  - "desc": "The ogre's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "The ogre regains 10 hit points at the start of its turn if it has at\
      \ least 1 hit point."
    "name": "Regeneration"
"actions":
  - "desc": "The ogre makes two attacks, either with its claws or its glaive."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage."
    "name": "Claw (Oni Form Only)"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 15 (2d10 + 4) slashing damage, or 9 (1d10 + 4) slashing damage in Small\
      \ or Medium form."
    "name": "Glaive"
  - "desc": "The ogre magically polymorphs into a Small or Medium humanoid, into a\
      \ Large giant, or back into its true form. Other than its size, its statistics\
      \ are the same in each form. The only equipment that is transformed is its glaive,\
      \ which shrinks so that it can be wielded in humanoid form. If the ogre dies,\
      \ it reverts to its true form, and its glaive reverts to its normal size."
    "name": "Change Shape"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/giant/token/ogre-channeler-psz.webp"
```
^statblock