---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Marlos Urnrayle"
---
# [Marlos Urnrayle](3-Mechanics/CLI/bestiary/npc/marlos-urnrayle-pota.md)
*Source: Princes of the Apocalypse p. 199*  

Marlos Urnrayle is the earth prophet of Elemental Evil and the leader of the Black Earth cult in the Sumber Hills. He is a medusa of unusual power who was once a vain and cruel human nobleman. Marlos delights in petrifying his foes, especially those of great physical beauty, and smashing the remains to rubble.

Marlos wields the magical war pick Ironfang, which he found in the Fane of the Eye after being drawn to the spot by a vision. Because of his medusa curse and his possession of the elemental weapon, the other Black Earth cultists believe that he stands high in Ogrémoch's favor and are fanatically loyal to him.

## In the Earth Node

When the Temple of Black Earth is threatened, Marlos Urnrayle retreats to the Black Geode, the earth node. Within this node, Marlos gains one additional use of his Legendary Resistance trait.

```statblock
"name": "Marlos Urnrayle (PotA)"
"size": "Medium"
"type": "monstrosity"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "11"
  - !!int "18"
  - !!int "12"
  - !!int "13"
  - !!int "17"
"speed": "30 ft."
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"damage_resistances": "acid"
"gear":
  - "[ironfang](3-Mechanics/CLI/items/ironfang-pota.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., tremorsense\
  \ 60 ft., passive Perception 14"
"languages": "Common, Terran"
"cr": "8"
"traits":
  - "desc": "When Marlos drops to 0 hit points, his body transforms into mud and collapses\
      \ into a pool. Anything he is wearing or carrying is left behind."
    "name": "Earthen Defeat"
  - "desc": "Marlos can move in difficult terrain composed of anything made from earth\
      \ or stone as if it were normal terrain. He can move through solid earth and\
      \ rock as if it were difficult terrain. If he ends his turn there, he is shunted\
      \ into the nearest space he last occupied."
    "name": "Earth Passage"
  - "desc": "If Marlos fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "When a creature that can see Marlos's eyes starts its turn within 30\
      \ feet of him, Marlos can force it to make a DC 14 Constitution saving throw\
      \ if Marlos isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and can see the creature. If the saving throw fails by 5 or more, the creature\
      \ is instantly [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified). Otherwise,\
      \ a creature that fails the save begins to turn to stone and is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ The [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) creature\
      \ must repeat the saving throw at the end of its next turn, becoming [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified)\
      \ on a failure or ending the effect on a success. The petrification lasts until\
      \ the creature is freed by the [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md)\
      \ spell or other magic.\n\nUnless [surprised](3-Mechanics/CLI/rules/conditions.md#Surprised),\
      \ a creature can avert its eyes to avoid the saving throw at the start of its\
      \ turn. If the creature does so, it can't see Marlos until the start of its\
      \ next turn, when it can decide to avert its eyes again. If the creature looks\
      \ at Marlos in the meantime, it must immediately make the save.\n\nIf Marlos\
      \ sees himself reflected on a polished surface within 30 feet of him and in\
      \ an area of bright light, Marlos is, due to his curse, affected by his own\
      \ gaze."
    "name": "Petrifying Gaze"
"actions":
  - "desc": "Marlos makes three melee attacks, one with his snake hair and two with\
      \ [Ironfang](3-Mechanics/CLI/items/ironfang-pota.md)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) piercing damage plus 14 (4d6) poison damage."
    "name": "Snake Hair"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d8 + 3) piercing damage plus 4 (1d8) thunder damage."
    "name": "Ironfang"
"lair_actions":
  - "desc": "If Marlos is in the earth node while [Ogrémoch](3-Mechanics/CLI/bestiary/npc/ogremoch-pota.md)\
      \ isn't, the medusa can take lair actions. On initiative count 20 (losing initiative\
      \ ties), Marlos uses a lair action to cast [earthquake](3-Mechanics/CLI/spells/earthquake.md)\
      \ without using components. As long as he maintains [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on [earthquake](3-Mechanics/CLI/spells/earthquake.md), initiative count 20\
      \ is the start of Marlos's turn for the purpose of the spell. He can take no\
      \ other lair actions while [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on [earthquake](3-Mechanics/CLI/spells/earthquake.md).\n\nMarlos's second\
      \ option for a lair action is to draw power from the earth node to heal. When\
      \ he does so, he regains 30 (6d8 + 3) hit points."
    "name": ""
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/marlos-urnrayle-pota.webp"
```
^statblock