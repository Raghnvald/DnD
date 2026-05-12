---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/imr
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thessalkraken"
---
# [Thessalkraken](3-Mechanics/CLI/bestiary/monstrosity/thessalkraken-imr.md)
*Source: Infernal Machine Rebuild p. 87*  

The alchemist Thessalar created unknown numbers of misshapen magical creatures, including his many thessalbeasts. Among the largest was the thessalkraken—a slightly smaller variant of the legendary kraken, resembling that great tentacled titan but with a jagged-toothed maw that drips constantly with acid.

A thessalkraken lives in the dark depths, usually a sunken rift or a cavern filled with detritus, treasure, and the remains of sacrificial victims.

```statblock
"name": "Thessalkraken (IMR)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"modifier": !!int "0"
"stats":
  - !!int "24"
  - !!int "11"
  - !!int "20"
  - !!int "19"
  - !!int "15"
  - !!int "17"
"speed": "20 ft., swim 60 ft."
"saves":
  - "strength": !!int "12"
  - "dexterity": !!int "5"
  - "constitution": !!int "10"
  - "intelligence": !!int "9"
  - "wisdom": !!int "7"
"damage_immunities": "acid; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 12"
"languages": "understands Abyssal, Celestial, Infernal, and Primordial but can't speak,\
  \ telepathy 120 ft."
"cr": "14"
"traits":
  - "desc": "The thessalkraken can breathe air and water."
    "name": "Amphibious"
  - "desc": "The thessalkraken ignores difficult terrain, and magical effects can't\
      \ reduce its speed or cause it to be [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ It can spend 5 feet of movement to escape from nonmagical restraints or being\
      \ [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)."
    "name": "Freedom of Movement"
"actions":
  - "desc": "The thessalkraken makes one bite attack and two tentacle attacks. It\
      \ can replace each tentacle attack with one use of Fling."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 20 (3d8 + 7) piercing damage plus 5 (1d10) acid damage. If the target\
      \ is a Medium or smaller creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the thessalkraken, that creature is swallowed, and the grapple ends. While\
      \ swallowed, the creature is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained), it has total\
      \ cover against attacks and other effects outside the thessalkraken, and it\
      \ takes 21 (6d6) acid damage at the start of each of the thessalkraken's turns.\n\
      \nIf the thessalkraken takes 35 damage or more on a single turn from a creature\
      \ inside it, it must succeed on a DC 23 Constitution saving throw at the end\
      \ of that turn or regurgitate all swallowed creatures, which fall [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ in a space within 10 feet of the thessalkraken. If the thessalkraken dies,\
      \ a swallowed creature is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 10 feet of movement, exiting [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 20 ft., one target. *Hit:*\
      \ 17 (3d6 + 7) slashing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 16). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained).\
      \ The thessalkraken has ten tentacles, each of which can grapple one target."
    "name": "Tentacle"
  - "desc": "One Medium or smaller object held or creature [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the thessalkraken is thrown up to 40 feet in a random direction and knocked\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone). If a thrown target strikes\
      \ a solid surface, the target takes 3 (1d6) bludgeoning damage for every 10\
      \ feet it was thrown. If the target is thrown at another creature, that creature\
      \ must succeed on a DC 16 Dexterity saving throw or take the same damage and\
      \ be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Fling"
  - "desc": "The thessalkraken spits a glob of acid at a point it can see within 60\
      \ feet of it. Each creature within 10 feet of that point must make a DC 18 Dexterity\
      \ saving throw, taking 22 (4d10) acid damage on a failed save, or half as\
      \ much damage on a successful one."
    "name": "Acid Saliva (Recharge 5-6)"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), the thessalkraken takes\
      \ a lair action to cause one of the following magical effects:\n\n- A strong\
      \ current moves through the thessalkraken's lair. Each creature within 60 feet\
      \ of the thessalkraken must succeed on a DC 18 Strength saving throw or be pushed\
      \ up to 60 feet away from the thessalkraken. On a success, the creature is pushed\
      \ 10 feet away from the thessalkraken.  \n- Creatures in the water within 60\
      \ feet of the thessalkraken have vulnerability to acid damage until initiative\
      \ count 20 on the next round.  \n- The alluring gleam of treasure beneath the\
      \ water in the thessalkraken's lair compels potential victims to draw near.\
      \ Each creature within 120 feet of the thessalkraken must succeed on a DC 18\
      \ Wisdom saving throw or move 10 feet closer to the thessalkraken if able to\
      \ do so.  "
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the thessalkraken can expend a use to take one of the following actions.\
  \ The thessalkraken regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The thessalkraken makes one tentacle attack."
    "name": "Tentacle Attack"
  - "desc": "The thessalkraken uses Fling."
    "name": "Fling"
  - "desc": "While underwater, the thessalkraken expels an ink cloud in a 60-foot\
      \ radius. The cloud spreads around corners, and that area is heavily obscured\
      \ to creatures other than the thessalkraken. Each creature other than the thessalkraken\
      \ that ends its turn there must succeed on a DC 18 Constitution saving throw,\
      \ taking 16 (3d10) poison damage on a failed save, or half as much damage\
      \ on a successful one. A strong current disperses the cloud, which otherwise\
      \ disappears at the end of the thessalkraken's next turn."
    "name": "Ink Cloud (Costs 3 Actions)"
"source":
  - "IMR"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/thessalkraken-imr.webp"
```
^statblock