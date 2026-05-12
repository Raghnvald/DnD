---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psk
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Angel"
---
# [Angel](3-Mechanics/CLI/bestiary/celestial/angel-psk.md)
*Source: Plane Shift: Kaladesh p. 27*  

Angels are mysterious, detached beings seldom glimpsed by mortal eyes. They are the living incarnations of white mana, and embody its inherent tendencies toward order and harmony. Some inventors view angels in the context of the Aether Cycle as an expression of a Great Design. Given divine inspiration and an utterly perfect stage of innovation, an angel is the constructed result—a living invention. Their masks, headdresses, and armor give them an almost mechanical appearance, but they are living beings with brightly colored skin almost entirely concealed beneath their armor and decorative robes. Because of their perfection, angels are believed to be immune to the final stages of the Aether Cycle, which would involve their destruction.

The people of Kaladesh do not worship angels or beseech their intervention in mortal affairs, and such prayers would go unheard anyway. The solitary angels interact with each other only in formal, nuanced rituals whose meanings are obscure. But the sight of an angel is thought to be a good omen, and in particular, it is believed to presage success with invention.

Use the statistics of a [deva](3-Mechanics/CLI/bestiary/celestial/deva.md) for an angel on Kaladesh. Some angels (such as the one shown on the Angel of Invention card (https://gatherer.wizards.com/pages/card/Details.aspx?multiverseid=547813)) wield four swords with their four arms. When such an angel uses the Multiattack action, it makes four attacks rather than two. However, its weapons deal only an extra `1d10` radiant damage from its Angelic Weapons trait, so that each sword attack deals 7 (`1d6 + 4`) slashing damage plus 5 (`1d10`) radiant damage on a hit.

```statblock
"name": "Angel (PSK)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "17"
  - !!int "20"
  - !!int "20"
"speed": "30 ft., fly 90 ft."
"saves":
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[mace](3-Mechanics/CLI/items/mace.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "The angel's spellcasting ability is Charisma (spell save DC 17). The\
      \ angel can innately cast the following spells, requiring only verbal components:\n\
      \n**At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md)\n\
      \n**1/day each:** [commune](3-Mechanics/CLI/spells/commune.md), [raise dead](3-Mechanics/CLI/spells/raise-dead.md)"
    "name": "Innate Spellcasting"
  - "desc": "The deva's weapon attacks are magical. When the deva hits with any weapon,\
      \ the weapon deals an extra 1d10 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "The angel has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The deva makes four melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) slashing damage plus 13 (1d10) radiant damage."
    "name": "Shortsword"
  - "desc": "The angel touches another creature. The target magically regains 20 (4d8\
      \ + 2) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (3/Day)"
  - "desc": "The angel magically polymorphs into a humanoid or beast that has a challenge\
      \ rating equal to or less than its own, or back into its true form. It reverts\
      \ to its true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (the angel's choice).\n\nIn a new form, the angel\
      \ retains its game statistics and ability to speak, but its AC, movement modes,\
      \ Strength, Dexterity, and special senses are replaced by those of the new form,\
      \ and it gains any statistics and capabilities (except class features, legendary\
      \ actions, and lair actions) that the new form has but that it lacks."
    "name": "Change Shape"
"source":
  - "PSK"
"image": "3-Mechanics/CLI/bestiary/celestial/token/angel-psk.webp"
```
^statblock