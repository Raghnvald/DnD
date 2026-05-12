---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psz
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sphinx (Type 2)"
---
# [Sphinx (Type 2)](3-Mechanics/CLI/bestiary/monstrosity/sphinx-type-2-psz.md)
*Source: Plane Shift: Zendikar p. 24*  

Utterly inscrutable, sphinxes are mysterious creatures known for their wisdom and knowledge. Closely aligned with blue mana, they are utterly devoted to gaining and possessing knowledge—but not to sharing or acting upon it. Sphinxes are content to search out the mysteries of Zendikar, then sit in quiet contemplation of what they have learned. To them, everything is an intellectual exercise, including conversation. They are famously oblique, answering questions with questions and posing riddles to test the acuity of others.

Sphinxes choose remote locations for their lairs, preferring sites of great natural beauty such as waterfalls, high promontories, and small islands. They jealously protect their lairs from other sphinxes and large predators, such as dragons, but they pay little attention to smaller visitors. A sphinx's lair is often difficult to reach, and typically involves treacherous climbing for creatures without the ability to fly. A visitor who can reach the spot is often rewarded with an audience—but those who come in search of answers are likely to leave disappointed.

Either sphinx in the Monster Manual can represent the various sphinxes of Zendikar.

```statblock
"name": "Sphinx (Type 2) (PSZ)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Neutral"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "16"
  - !!int "18"
  - !!int "18"
  - !!int "18"
"speed": "40 ft., fly 60 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+12"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+12"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 18"
"languages": "Common, Sphinx"
"cr": "11"
"traits":
  - "desc": "The sphinx is a 9th-level spellcaster. Its spellcasting ability is Intelligence\
      \ (spell save DC 16, +8 to hit with spell attacks). It requires no material\
      \ components to cast its spells. The sphinx has the following wizard spells\
      \ prepared:\n\n**Cantrips (at will):** [mage hand](3-Mechanics/CLI/spells/mage-hand.md),\
      \ [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\
      \n**1st level (4 slots):** [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [identify](3-Mechanics/CLI/spells/identify.md), [shield](3-Mechanics/CLI/spells/shield.md)\n\
      \n**2nd level (3 slots):** [darkness](3-Mechanics/CLI/spells/darkness.md), [locate\
      \ object](3-Mechanics/CLI/spells/locate-object.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\
      \n**3rd level (3 slots):** [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md),\
      \ [remove curse](3-Mechanics/CLI/spells/remove-curse.md), [tongues](3-Mechanics/CLI/spells/tongues.md)\n\
      \n**4th level (3 slots):** [banishment](3-Mechanics/CLI/spells/banishment.md),\
      \ [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility.md)\n\n\
      **5th level (1 slots):** [legend lore](3-Mechanics/CLI/spells/legend-lore.md)"
    "name": "Spellcasting"
  - "desc": "The sphinx is immune to any effect that would sense its emotions or read\
      \ its thoughts, as well as any divination spell that it refuses. Wisdom ([Insight](3-Mechanics/CLI/rules/skills.md#Insight))\
      \ checks made to ascertain the sphinx's intentions or sincerity have disadvantage."
    "name": "Inscrutable"
  - "desc": "The sphinx's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "The sphinx makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) slashing damage."
    "name": "Claw"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the sphinx (type 2) can expend a use to take one of the following actions.\
  \ The sphinx (type 2) regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The sphinx makes one claw attack."
    "name": "Claw Attack"
  - "desc": "The sphinx magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 120 feet to an unoccupied space it can see."
    "name": "Teleport (Costs 2 Actions)"
  - "desc": "The sphinx casts a spell from its list of prepared spells, using a spell\
      \ slot as normal."
    "name": "Cast a Spell (Costs 3 Actions)"
"source":
  - "PSZ"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/sphinx-type-2-psz.webp"
```
^statblock