---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdh
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/illuskan-human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Renaer Neverember"
---
# [Renaer Neverember](3-Mechanics/CLI/bestiary/npc/renaer-neverember-wdh.md)
*Source: Waterdeep: Dragon Heist p. 215*  

Renaer is the estranged son of Dagult Neverember, the former Open Lord of Waterdeep and the current Lord of Neverwinter. Father and son detest one another, and Renaer is least happy when he finds himself forced to deal with some mess his father left behind. Qualities that both share include striking good looks, a love of drink, and a flair for diplomacy. What Renaer lacks is his father's belligerence, ill temper, and bad judgment.

Renaer lives off a sizable inheritance left to him by his mother. Approaching middle age, he has given up adventuring and settled down somewhat. As a Harper, he spends a lot of time defending Waterdavians against those who, like his father, would deprive them of their coin and rights. He owns Neverember House, a four-story residence in the Sea Ward. Renaer spends as little time there as possible, however, since it's constantly under surveillance by spies loyal to his father. His friends have an open invitation to use the house as they please, while Renaer spends most of his free time in taverns and festhalls.

Some believe that Renaer's estrangement from his father is nothing but an act, and that anyone who bears the Neverember name is an enemy of Waterdeep. Renaer just shakes his head at such accusations and gets on with his life. He has many powerful friends to watch his back.

## Swashbuckler

Swashbucklers are charming ne'er-do-wells who live by their own codes of honor. They crave notoriety, often indulge in romantic trysts, and eke out livings as pirates and corsairs, rarely staying in one place for too long.

```statblock
"name": "Renaer Neverember (WDH)"
"size": "Medium"
"type": "humanoid"
"subtype": "Illuskan human"
"alignment": "Chaotic Good"
"ac": !!int "17"
"ac_class": "[leather armor](3-Mechanics/CLI/items/leather-armor-xphb.md)"
"hp": !!int "66"
"hit_dice": "12d8 + 12"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "12"
  - !!int "14"
  - !!int "11"
  - !!int "15"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+8"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+6"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger-xphb.md)"
  - "[rapier](3-Mechanics/CLI/items/rapier-xphb.md)"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "3"
"traits":
  - "desc": "Renaer can take the [Dash](3-Mechanics/CLI/rules/actions.md#Dash) or\
      \ [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage) action as a bonus\
      \ action on each of its turns."
    "name": "Lightfooted"
  - "desc": "While Renaer is wearing light or no armor and wielding no shield, its\
      \ AC includes its Charisma modifier."
    "name": "Suave Defense"
"actions":
  - "desc": "Renaer makes three attacks: one with a dagger and two with its rapier."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d4 + 4) piercing damage."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) piercing damage."
    "name": "Rapier"
"source":
  - "WDH"
"image": "3-Mechanics/CLI/bestiary/npc/token/renaer-neverember-wdh.webp"
```
^statblock