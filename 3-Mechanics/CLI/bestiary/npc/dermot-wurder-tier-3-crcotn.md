---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/8
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/cleric
- ttrpg-cli/monster/type/humanoid/goblin
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dermot Wurder (Tier 3)"
---
# [Dermot Wurder (Tier 3)](3-Mechanics/CLI/bestiary/npc/dermot-wurder-tier-3-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 193*  

When you're the twelfth son of a poor goblin family in Jigow, the only way to make a name for yourself is to become a great champion—someone who can win bragging contests in the local taverns night after night. Young Dermot Wurder, however, wasn't interested in performing feats of strength or agility that would win him a boast-worthy epithet. Fame wasn't for him, nor was the aggressiveness that becoming famous required. He was more interested in cooking, planting flowers, and sewing clothes—doing the work that kept his family together while his carefree siblings dove off waterfalls and wrestled stray dogs.

Dermot and Ayo Jabe have known each other long enough that their first meeting has vanished into the haze of youthful pre-memory. Dermot accompanied Ayo whenever he could, packing herbs and medicines when they went exploring in the woods. When Ayo recently told him of her dream to form an adventuring party, he started training to wear heavy armor and threw himself into studying the faith of the Luxon so he could wield the blessings of the light to protect those he cares about.

Dermot is fiercely protective of his friends and furiously rebukes anyone who disparages or threatens them. His deepest need—one even he doesn't know he has—is to make a friend who will help him realize what he wants for himself.

> [!note] Battle Chatter Sample Quotes
> 
> "I'm here to make sure no one dies. Back off!" "The Luxon will protect me." "Ayo, Maggie, I could use a little help here!"
^battle-chatter-sample-quotes

## Rival Stat Blocks

Stat blocks for the rivals can be found in appendix A. Each of the rivals has three stat blocks; like the characters, they become more powerful as the adventure progresses. The Rival Stat Blocks table shows you which stat blocks to use based on the chapter you are running.

### Rival Stat Blocks

| Chapters | Stat Blocks |
|----------|-------------|
| 1 and 2 | Dermot Wurder (Tier 1) |
| 3 and 4 | Dermot Wurder (Tier 2) |
| 5, 6, and 7 | Dermot Wurder (Tier 3) |
^chapters-stat-blocks

Their journey has forced the tier 3 rivals to make decisions, sometimes out of grim necessity, that they might have not made earlier. All five suffer from ruidium corruption (see "Ruidium "in the introduction). When the characters encounter them, assume that the rivals have removed all levels of exhaustion from themselves through rest or magic, but the other effects of ruidium corruption remain.

If instead you want to weaken the rivals to make them less of a physical threat or reinforce the danger of ruidium corruption, you can give one or more of the rivals `1d4` levels of exhaustion each. In this case, you'll need to keep track of each rival's exhaustion level and the condition's corresponding effects (see "Exhaustion "in the *Player's Handbook*).

#### Useful Magic

To facilitate their efforts, Galsariad has learned the water breathing spell. Additionally, all the rivals have acquired ruidium equipment to protect them from the effects of underwater pressure.

```statblock
"name": "Dermot Wurder (Tier 3) (CRCotN)"
"size": "Small"
"type": "humanoid"
"subtype": "cleric, goblin, goblinoid"
"alignment": "Lawful Good"
"ac": !!int "20"
"ac_class": "plate, shield"
"hp": !!int "93"
"hit_dice": "17d6 + 34"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "14"
  - !!int "10"
  - !!int "20"
  - !!int "10"
"speed": "30 ft., swim 30 ft. (mariner's armor)"
"saves":
  - "wisdom": !!int "8"
  - "charisma": !!int "3"
"skillsaves":
  - "name": "Medicine"
    "desc": "+8"
  - "name": "Religion"
    "desc": "+3"
  - "name": "Survival"
    "desc": "+8"
"gear":
  - "[ruidium warhammer](3-Mechanics/CLI/items/ruidium-weapon-crcotn.md)"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common, Goblin, Orc"
"cr": "8"
"traits":
  - "desc": "Dermot wears [mariner's armor](3-Mechanics/CLI/items/mariners-armor.md)\
      \ and wields a ruidium warhammer (see appendix B). If Dermot rolls a 1 on an\
      \ attack roll made with the warhammer, he must succeed on a DC 20 Charisma saving\
      \ throw or gain 1 level of exhaustion."
    "name": "Special Equipment"
"actions":
  - "desc": "Dermot makes one Ruidium Warhammer attack and one Searing Wrath attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) bludgeoning damage, or 9 (1d10 + 4) bludgeoning damage when\
      \ used with two hands, plus 7 (2d6) psychic damage."
    "name": "Ruidium Warhammer"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 60 ft., one creature. *Hit:*\
      \ 22 (5d8) radiant damage, and the target is blinded until the end of its\
      \ next turn."
    "name": "Searing Wrath"
  - "desc": "Dermot casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 16):\n\n**At will:** guidance, light, spare the dying\n\
      \n**2/day each:** bless (at 3rd level), cure wounds (at 3rd level)\n\n**1/day:**\
      \ revivify"
    "name": "Spellcasting"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/dermot-wurder-tier-3-crcotn.webp"
```
^statblock