---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/26
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Ancient Time Dragon"
---
# [Ancient Time Dragon](3-Mechanics/CLI/bestiary/dragon/ancient-time-dragon-mpp.md)
*Source: Morte's Planar Parade p. 48*  

These sleek dragons harness the power of time to manipulate the past, present, and future. Time dragon wyrmlings are born with shining scales and have horns that are barely more than nubs. As they master the flow of time, their horns grow with branching, rainbow-hued veins suggestive of time's paths and possibilities.

Ancient time dragons can create temporal gates connected to specific times and places in the multiverse. Using these, they and allied creatures can travel anywhere in time to affect fate-determining moments or to banish threats beyond the flow of time. As a result of their ability to travel between ages, time dragons often seem unstuck from the usual flow of time and have a flexible view of what is, what was, and what will be.

Time dragons prize historical records, objects representative of lost cultures, and treasures from long-gone creators. They are fascinated by time-manipulation magic and forgotten knowledge. Those who stumble upon a time dragon's hoard might find invaluable historical information from eras past.

## A Time Dragon's Lair

Time dragons often lair in the ruins of ancient civilizations or temples to dead gods and do their utmost to preserve these historical sites. A time dragon's insatiable desire for knowledge means it's likely to have more than one such lair.

The challenge rating of an ancient or adult time dragon increases by 1 when it's encountered in its lair.

```statblock
"name": "Ancient Time Dragon (MPP)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "typically  Neutral"
"ac": !!int "22"
"ac_class": "natural armor"
"hp": !!int "536"
"hit_dice": "29d20 + 232"
"modifier": !!int "2"
"stats":
  - !!int "28"
  - !!int "14"
  - !!int "26"
  - !!int "27"
  - !!int "18"
  - !!int "23"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "10"
  - "constitution": !!int "16"
  - "wisdom": !!int "12"
  - "charisma": !!int "14"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+16"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+24"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+20"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+18"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 30"
"languages": "all"
"cr": "26"
"traits":
  - "desc": "If the dragon dies, its soul coalesces into a steely egg and teleports\
      \ to a random plane of existence. The egg is immune to all damage and hatches\
      \ into a time dragon wyrmling after 1d100 years. The dragon retains all memories\
      \ and knowledge it gained in its previous life."
    "name": "Cycle of Rebirth"
  - "desc": "If the dragon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (5/Day)"
"actions":
  - "desc": "The dragon makes three Rend attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 15 ft., one target. *Hit:*\
      \ 22 (3d8 + 9) slashing damage plus 10 (3d6) force damage."
    "name": "Rend"
  - "desc": "The dragon exhales a wave of shimmering light in a 90-foot cone. Nonmagical\
      \ objects and vegetation in that area that aren't being worn or carried crumble\
      \ to dust. Each creature in that area must make a DC 24 Constitution saving\
      \ throw. On a failed save, a creature takes 52 (8d12) force damage and is\
      \ magically weakened as it is desynchronized from the time stream. While the\
      \ creature is in this state, attack rolls against it have advantage, it has\
      \ the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) condition, and\
      \ other creatures have resistance to all damage it deals. On a successful save,\
      \ the creature takes half as much damage only. A weakened creature can repeat\
      \ the saving throw at the end of each of its turns, ending the effect on itself\
      \ after it succeeds on three of these saves."
    "name": "Time Breath (Recharge 5-6)"
  - "desc": "The dragon conjures a 20-foot-diameter, circular portal in the space\
      \ between its horns or in an unoccupied space it can see within 30 feet of itself.\
      \ The portal links to a precise location on any plane of existence at a point\
      \ in time up to 8,000 years from the present, whether past or future. The portal\
      \ lasts for 24 hours or until the dragon's [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ ends (as if [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell). The portal has a front and a back on each plane where it appears.\
      \ Travel through the portal is possible only by moving through its front. Anything\
      \ that does so is transported to the destination, appearing in the unoccupied\
      \ space nearest to the portal. Deities and other planar rulers can prevent portals\
      \ created by the dragon from opening in the rulers' presence or anywhere within\
      \ their domains."
    "name": "Time Gate (1/Day)"
"reactions":
  - "desc": "After using Legendary Resistance or in response to being hit by an attack\
      \ roll, the dragon makes one Rend attack."
    "name": "Reactive Rend"
  - "desc": "Immediately after a creature the dragon can see ends its turn, the dragon\
      \ targets a creature it can see within 90 feet of itself that is weakened by\
      \ its Time Breath. Until the weakened effect ends on the target, its speed becomes\
      \ 0, and its speed can't increase."
    "name": "Slow Time"
  - "desc": "The dragon halves the damage it takes from an attack made against it,\
      \ provided it can see the attacker. The dragon can then immediately teleport,\
      \ along with any equipment it is wearing or carrying, up to 60 feet to an unoccupied\
      \ space it can see."
    "name": "Time Slip"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), the dragon can take\
      \ one of the following lair actions; the ancient or adult dragon can't take\
      \ the same lair action two rounds in a row:\n\n- **Temporal Fling..** The dragon\
      \ attempts to fling a creature it can see within 60 feet of itself forward through\
      \ time. The target must succeed on a DC 18 Wisdom saving throw or take 26 (4d12)\
      \ psychic damage and move 1 round forward in time. A target moved forward in\
      \ time vanishes for the duration. When the effect ends, the target reappears\
      \ in the space it left or in an unoccupied space nearest to that space if it's\
      \ occupied.  \n- **Temporal Lag..** The dragon slows time for each creature\
      \ within 60 feet of itself. Until initiative count 20 of the next round, the\
      \ affected creature can move or take an action on its turn, not both. The creature\
      \ also can't take a reaction or a bonus action.  \n- **Timeline Divergence..**\
      \ The dragon chooses a space it can fit into within its lair. The dragon exists\
      \ simultaneously in its space and the chosen space until initiative count 20\
      \ on the next round. Whenever it moves or takes an action, the dragon chooses\
      \ which version is moving or acting. If an effect or attack can target both\
      \ the dragon's spaces at the same time, the dragon is affected only once.  "
    "name": ""
"regional_effects":
  - "desc": "The region surrounding an ancient or adult time dragon's lair is altered\
      \ by the dragon's magic, creating one or more of the following effects:\n\n\
      - **Time Dilations.** Time fluctuates within 3 miles of the lair. Short rests\
      \ taken within this area take 10 minutes or 2 hours (your choice).  \n- **Timelessness.**\
      \ Beasts, Humanoids, and Plants within 3 miles of the lair age only 1 year for\
      \ every 10 years that pass.  \n\nIf the dragon dies, these effects fade over\
      \ the course of 1d10 days."
    "name": ""
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/dragon/token/ancient-time-dragon-mpp.webp"
```
^statblock