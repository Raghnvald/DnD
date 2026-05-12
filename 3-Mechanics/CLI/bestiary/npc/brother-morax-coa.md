---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Brother Morax"
---
# [Brother Morax](3-Mechanics/CLI/bestiary/npc/brother-morax-coa.md)
*Source: Chains of Asmodeus p. 186*  

```statblock
"name": "Brother Morax (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "337"
"hit_dice": "25d10 + 200"
"modifier": !!int "6"
"stats":
  - !!int "24"
  - !!int "22"
  - !!int "27"
  - !!int "14"
  - !!int "16"
  - !!int "18"
"speed": "40 ft."
"saves":
  - "strength": !!int "14"
  - "dexterity": !!int "13"
  - "constitution": !!int "15"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+20"
  - "name": "Athletics"
    "desc": "+21"
  - "name": "Intimidation"
    "desc": "+11"
  - "name": "Medicine"
    "desc": "+10"
  - "name": "Stealth"
    "desc": "+13"
  - "name": "Survival"
    "desc": "+10"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 13"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "21"
"traits":
  - "desc": "For each Brittle Spine a creature has, the creature takes 3 (1d6) poison\
      \ damage at the start of each of their turns, and when Morax activates Burrow\
      \ or Deep Burrow. Spines can only be removed by a Regeneration spell or similar,\
      \ or by killing Morax."
    "name": "Brittle Spine"
  - "desc": "Magical darkness doesn't impede Morax's darkvision."
    "name": "Devil's Sight"
  - "desc": "Morax has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Whenever Morax is hit with a melee attack, the attacker takes 7 (2d6)\
      \ piercing damage and gains 1 Brittle Spine."
    "name": "Spined Hide"
  - "desc": "If Morax is reduced to 0 hit points while Brother Adramalech still lives,\
      \ Morax regenerates 50 hit points at the start of his next turn. This regeneration\
      \ is interrupted if Brother Adramalech is reduced to 0 hit points before the\
      \ start of Morax's turn."
    "name": "Unbreakable Bond"
"actions":
  - "desc": "Morax makes four attacks using his Claw, Spine Fling, or a combination\
      \ of the two."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 17 (3d6 + 7) slashing damage, and the target gains 1 Brittle Spine."
    "name": "Claw"
  - "desc": "*Ranged Weapon Attack:* +13 to hit, range 30/60 ft., one target. *Hit:*\
      \ 12 (1d12 + 6) piercing damage, and the target gains 1 Brittle Spine."
    "name": "Spine Fling"
  - "desc": "Morax immediately deals Brittle Spine ongoing damage to all creatures\
      \ that have at least one Brittle Spine that he can see."
    "name": "Deep Burrow"
  - "desc": "Morax shoves an arm into the ground, rapidly growing bones that erupt\
      \ at a point he can see within 100 feet of him. Each creature in a 60-foot-radius\
      \ sphere centered on that point must make a DC 21 Dexterity saving throw, taking\
      \ 28 (8d6) piercing damage on a failed save, or half as much damage on a successful\
      \ one. Creatures that fail the save gain 2 Brittle Spines, while creatures that\
      \ succeed only gain 1 Brittle Spine."
    "name": "Bone Spikes (Recharge 6)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Brother can expend a use to take one of the following actions. Brother regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Morax makes a Claw attack."
    "name": "Claw"
  - "desc": "Morax gestures at a creature he can see that has at least 1 Brittle Spine.\
      \ That creature must succeed on a DC 21 Constitution saving throw or the number\
      \ of Brittle Spines it has doubles."
    "name": "Bone Splinters (Costs 2 Actions)"
  - "desc": "Morax bristles the spines within a creature that he can see. The target\
      \ immediately takes Brittle Spine ongoing damage."
    "name": "Burrow (Costs 2 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/brother-morax-coa.webp"
```
^statblock