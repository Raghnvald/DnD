---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Abigor"
---
# [Abigor](3-Mechanics/CLI/bestiary/npc/abigor-coa.md)
*Source: Chains of Asmodeus p. 193*  

```statblock
"name": "Abigor (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "337"
"hit_dice": "27d10 + 189"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "25"
  - !!int "20"
  - !!int "16"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "strength": !!int "15"
  - "intelligence": !!int "12"
"skillsaves":
  - "name": "Athletics"
    "desc": "+22"
  - "name": "History"
    "desc": "+12"
  - "name": "Insight"
    "desc": "+10"
  - "name": "Intimidation"
    "desc": "+17"
  - "name": "Perception"
    "desc": "+10"
  - "name": "Survival"
    "desc": "+10"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"gear":
  - "warhammer"
"senses": "darkvision 120 ft., passive Perception 20"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "22"
"traits":
  - "desc": "Magical darkness doesn't impede Abigor's darkvision."
    "name": "Devil's Sight"
  - "desc": "Abigor has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Abigor makes four attacks using its Warhammer, Throwing Hammer, or a\
      \ combination of the two."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 5 ft., one target. *Hit:*\
      \ 17 (2d8 + 8) bludgeoning damage plus 3 (1d6) thunder damage."
    "name": "Warhammer"
  - "desc": "*Ranged Weapon Attack:* +15 to hit, range 30/60 ft., one target. *Hit:*\
      \ 17 (2d8 + 8) bludgeoning damage plus 3 (1d6) thunder damage. Hammers thrown\
      \ this way fall and stick into the ground after hitting their target and a new\
      \ hammer appears in Abigor's hand."
    "name": "Throwing Hammer"
  - "desc": "Abigor causes all its hammers left on the battlefield to bristle with\
      \ thunderous energy, exploding outwards with a roar. All creatures within a\
      \ 10-foot-radius sphere centered on each hammer must make a DC 22 Constitution\
      \ saving throw. Targets take 26 (4d12) thunder damage on a failed save, or\
      \ half as much damage on a successful one. If a creature is within multiple\
      \ spheres, it must make the save multiple times, taking damage from each source."
    "name": "Thunderous Slam (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Abigor can expend a use to take one of the following actions. Abigor regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Abigor makes a Throwing Hammer attack."
    "name": "Throw Hammer"
  - "desc": "Abigor targets a hammer that it can see within 60 feet to let out a thunderous\
      \ roar. Creatures within a 10-foot-radius sphere centered on the hammer must\
      \ make a DC 22 Constitution saving throw, taking 26 (4d12) thunder damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Call Thunder (Costs 2 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/abigor-coa.webp"
```
^statblock