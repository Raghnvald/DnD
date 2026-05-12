---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/18
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/elemental
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Yan-C-Bin"
---
# [Yan-C-Bin](3-Mechanics/CLI/bestiary/npc/yan-c-bin-pota.md)
*Source: Princes of the Apocalypse p. 221*  

Yan-C-Bin (pronounced yan-see-bin) is the Prince of Evil Air. A being of great wisdom and malice, Yan-C-Bin's plots began at the forging of the worlds. Subtler than the other elemental princes, Yan-C-Bin operates unseen, studying his enemies from afar, ambushing them swiftly, and vanishing before his foes can retaliate.

His natural form is an invisible vortex of howling, swirling air 30 feet high and 15 feet wide, but Yan-C-Bin sometimes takes the shape of a gaunt, venerable, dark-skinned human with wispy white hair and glowing white eyes. When he wishes to remain unseen, Yan-C-Bin manifests only as a gust of cold wind flowing silently past.

From his floating palace in the endless, cloudy skies of the Plane of Air, Yan-C-Bin watches worlds as they change over millennia. Evil aerial creatures worship the elemental prince as a god, and claim to see Yan-C-Bin's eyes in swirling storms. Yan-C-Bin doesn't care for their offerings, their sacrifices, or their worship. His only concern is the annihilation of the material realms as they are ripped apart by the superior elemental might of air and wind.

## Yan-C-Bin's Lair

Yan-C-Bin dwells in a palace of air on the Elemental Plane of Air. In his palace and in air nodes on the Material Plane (including the Howling Caves, described in chapter 5), Yan-C-Bin is master. He can use the following actions in his lair.

```statblock
"name": "Yan-C-Bin (PotA)"
"size": "Huge"
"type": "elemental"
"alignment": "Neutral Evil"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "283"
"hit_dice": "21d12 + 147"
"modifier": !!int "7"
"stats":
  - !!int "18"
  - !!int "24"
  - !!int "24"
  - !!int "16"
  - !!int "21"
  - !!int "23"
"speed": "50 ft., fly 150 ft."
"saves":
  - "dexterity": !!int "13"
  - "wisdom": !!int "11"
  - "charisma": !!int "12"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "lightning, poison, thunder"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [prone](3-Mechanics/CLI/rules/conditions.md#Prone),\
  \ [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 120 ft., passive\
  \ Perception 15"
"languages": "Auran"
"cr": "18"
"traits":
  - "desc": "Yan-C-Bin's innate spellcasting ability is Charisma (spell save DC 20,\
      \ +12 to hit with spell attacks). He can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** [gust of wind](3-Mechanics/CLI/spells/gust-of-wind.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md), [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt.md)\n\
      \n**2/day each:** [chain lightning](3-Mechanics/CLI/spells/chain-lightning.md),\
      \ [cloudkill](3-Mechanics/CLI/spells/cloudkill.md), [haste](3-Mechanics/CLI/spells/haste.md)"
    "name": "Innate Spellcasting"
  - "desc": "Yan-C-Bin can enter a hostile creature's space and stop there. He can\
      \ move through a space as narrow as 1 inch wide without squeezing if air could\
      \ pass through that space."
    "name": "Air Form"
  - "desc": "Yan-C-Bin's slam attacks are treated as magical for the purpose of bypassing\
      \ resistance and immunity to nonmagical attacks."
    "name": "Empowered Attacks"
  - "desc": "If Yan-C-Bin fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Yan-C-Bin has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Yan-C-Bin makes two slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 10 ft., one target. *Hit:*\
      \ 20 (3d8 + 7) force damage plus 10 (3d6) lightning damage."
    "name": "Slam"
  - "desc": "Yan-C-Bin unleashes a terrible thundercrack in a 100-foot-radius sphere\
      \ centered on himself. All other creatures in the area must succeed on a DC\
      \ 24 Constitution saving throw or take 31 (9d6) thunder damage and be [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened)\
      \ for 1 minute. On a successful save, a creature takes half as much damage and\
      \ is [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened) until the start\
      \ of Yan-C-Bin's next turn."
    "name": "Thundercrack (Recharges after a Short or Long Rest)"
  - "desc": "Yan-C-Bin polymorphs into a Medium humanoid. While in polymorphed form,\
      \ a swirling breeze surrounds him, his eyes are pale and cloudy, and he loses\
      \ the Air Form trait. He can remain in polymorphed form for up to 1 hour. Reverting\
      \ to his true form requires an action."
    "name": "Change Shape"
  - "desc": "Yan-C-Bin summons up to three [air elementals](3-Mechanics/CLI/bestiary/elemental/air-elemental.md)\
      \ and loses 30 hit points for each elemental he summons. Summoned elementals\
      \ have maximum hit points, appear within 100 feet of Yan-C-Bin, and disappear\
      \ if Yan-C-Bin is reduced to 0 hit points."
    "name": "Summon Elementals (1/Day)"
"lair_actions":
  - "desc": "Yan-C-Bin dwells in a palace of air on the Elemental Plane of Air. In\
      \ his palace and in air nodes on the Material Plane (including the Howling Caves,\
      \ described in chapter 5), Yan-C-Bin is master. He can use the following actions\
      \ in his lair. On initiative count 20 (losing initiative ties), Yan-C-Bin takes\
      \ a lair action to cause one of the following effects; he can't use the same\
      \ effect two rounds in a row:\n\n- Yan-C-Bin drops the temperature of the air,\
      \ covering all surfaces with ice. This effect is identical to the [sleet storm](3-Mechanics/CLI/spells/sleet-storm.md)\
      \ spell.  \n- Yan-C-Bin controls the surrounding air as an extension of himself.\
      \ Each creature Yan-C-Bin designates must succeed at a DC 24 Constitution saving\
      \ throw or be hoisted or flung 3d6 × 10 feet through the air. A creature smashed\
      \ into a solid object or released in mid-air takes 1d6 bludgeoning damage\
      \ for every 10 feet moved or fallen.  \n- Yan-C-Bin creates a torrent of debris\
      \ within 120 feet of him that lasts until initiative count 20 on the next round.\
      \ The debris lightly obscures every creature and object in the area for the\
      \ duration. All creatures in the area must succeed at a DC 24 Wisdom saving\
      \ throw or be [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) until initiative\
      \ count 20 on the next round.  "
    "name": ""
"regional_effects":
  - "desc": "When Yan-C-Bin inhabits an elemental node, the air is at his command.\
      \ Temperatures fluctuate from blistering hot to freezing cold; thunder rolls\
      \ and lightning cracks; powerful gales bear heavy creatures and objects aloft\
      \ and hurl them with incredible force; cyclones touch down randomly, obliterating\
      \ whatever they touch.\n\n- Gale force winds tear across the landscape in a\
      \ 5-mile radius, whisking away small or light objects, dismantling roofs and\
      \ fences, tearing branches from trees, and making flight impossible. Small and\
      \ Medium creatures move at half speed through the wind; Tiny creatures exposed\
      \ to the wind are carried away with it at a rate of 40 feet per round unless\
      \ they succeed at a DC 15 Strength ([Athletics](3-Mechanics/CLI/rules/skills.md#Athletics))\
      \ check.  \n- Thunderstorms erupt in a 5-mile radius centered on Yan-C-Bin's\
      \ lair, creating deafening cracks of thunder and constant lightning. Every ten\
      \ minutes the storm rages, creatures standing beneath the open sky have a five\
      \ percent chance of being struck by lightning. A creature struck by lightning\
      \ must make a DC 21 Constitution saving throw, taking 21 (6d6) lightning damage\
      \ on a failed save, or half as much damage on a successful one.  \n- Cyclones\
      \ touch down within a 5-mile radius of Yan-C-Bin's lair. Every hour, there is\
      \ a five percent chance that characters in this area are caught in the path\
      \ of a cyclone moving 250 feet per round. Each character must succeed on a DC\
      \ 21 Constitution saving throw or take 33 (6d10) bludgeoning damage. Wooden\
      \ or flimsy structures in the path of the cyclone are destroyed.  \n- Natural\
      \ caverns and windblown canyons within 1 mile of the lair form intermittent\
      \ portals to the Elemental Plane of Air, allowing elemental creatures into the\
      \ mortal world to dwell near those locations.  \n\nIf Yan-C-Bin is destroyed\
      \ or banished back to his home plane, the regional effects fade over the next\
      \ 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Yan-C-Bin can expend a use to take one of the following actions. Yan-C-Bin\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Yan-C-Bin unleashes a peal of thunder that can be heard out to a range\
      \ of 300 feet. Each creature within 30 feet of Yan-C-Bin takes 5 (1d10) thunder\
      \ damage."
    "name": "Peal of Thunder"
  - "desc": "Yan-C-Bin magically teleports up to 120 feet to an unoccupied space he\
      \ can see. Anything Yan-C-Bin is wearing or carrying is teleported with him."
    "name": "Teleport (Costs 2 Actions)"
  - "desc": "Yan-C-Bin steals the air of one breathing creature he can see within\
      \ 60 feet of him. The target must make a DC 21 Constitution saving throw. On\
      \ a failed save, the target drops to 0 hit points and is dying. On a successful\
      \ save, the target can't breathe or speak until the start of its next turn."
    "name": "Suffocate (Costs 3 Actions)"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/npc/token/yan-c-bin-pota.webp"
```
^statblock