---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psa
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Criosphinx"
---
# [Criosphinx](3-Mechanics/CLI/bestiary/monstrosity/criosphinx-psa.md)
*Source: Plane Shift: Amonkhet p. 32*  

A rare few [sphinxes](3-Mechanics/CLI/bestiary/monstrosity/amonkhet-sphinx-psa.md) have the heads of rams instead of the humanlike faces of other [sphinxes](3-Mechanics/CLI/bestiary/monstrosity/amonkhet-sphinx-psa.md). Though they lie under the same curse as all their kind, they are less enigmatic and more aggressive, actively attacking [angels](3-Mechanics/CLI/bestiary/celestial/angel-of-amonkhet-psa.md), demons, and other agents of Bolas they encounter in the desert. They stay far from Naktamun and care little for its people. Their hatred of Bolas is driven only by his curse.

## Sphinxes

[Sphinxes](3-Mechanics/CLI/bestiary/monstrosity/amonkhet-sphinx-psa.md) are inscrutable beings, and keepers of secrets and mysteries. They have leonine bodies, hawk-like wings, and faces resembling humans, framed by great frills or manes of feathers. Their powerful forearms are also feathered, and fans of long feathers form their tails.

The [sphinxes](3-Mechanics/CLI/bestiary/monstrosity/amonkhet-sphinx-psa.md) of Amonkhet are perhaps the only creatures to remain uncorrupted by the influence of Nicol Bolas on this plane. Their impenetrable minds proved to be beyond even Bolas's ability to control—but even so, he was able to place them under a curse to guarantee their silence. A [sphinx](3-Mechanics/CLI/bestiary/monstrosity/amonkhet-sphinx-psa.md) is utterly incapable of communication—verbal or nonverbal, even written—as long as the curse remains in effect. In this way, Bolas has prevented the [sphinxes](3-Mechanics/CLI/bestiary/monstrosity/amonkhet-sphinx-psa.md) from revealing his system of lies to the people or gods of Naktamun.

```statblock
"name": "Criosphinx (PSA)"
"size": "Large"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "228"
"hit_dice": "24d10 + 96"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "18"
  - !!int "16"
  - !!int "16"
  - !!int "16"
"speed": "30 ft., fly 60 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+8"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 18"
"languages": "understands Common, Sphinx"
"cr": "13"
"traits":
  - "desc": "The sphinx is immune to any effect that would sense its emotions or read\
      \ its thoughts, as well as any divination spell that it refuses. Wisdom ([Insight](3-Mechanics/CLI/rules/skills.md#Insight))\
      \ checks made to ascertain the sphinx's intentions or sincerity have disadvantage."
    "name": "Inscrutable"
  - "desc": "The sphinx's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "The sphinx makes a ram attack and two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 17\
      \ (3d8 + 4) bludgeoning damage."
    "name": "Ram"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) slashing damage."
    "name": "Claw"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the criosphinx can expend a use to take one of the following actions. The\
  \ criosphinx regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The sphinx makes one ram attack."
    "name": "Ram Attack"
  - "desc": "The sphinx magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 120 feet to an unoccupied space it can see."
    "name": "Teleport (Costs 2 Actions)"
"source":
  - "PSA"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/criosphinx-psa.webp"
```
^statblock