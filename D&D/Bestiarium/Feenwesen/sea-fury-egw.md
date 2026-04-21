---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Sea Fury
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/12
  - Monster/Typ/Fee
  - Quelle/5e/egw
aliases:
  - Sea Fury
---
# [Sea Fury](3-Mechanics\CLI\bestiary\fey/sea-fury-egw.md)
*Source: Explorer's Guide to Wildemount p. 299*  

In times of great danger, sea hags form massive covens to channel powerful magic against outside threats. But when the threat is vanquished, these covens often destroy themselves from within. One sea hag grows more powerful than the others, killing its kin one by one and siphoning their magical power as it does so.

Driven to madness by the power it claims—and by the loneliness that is the cost of its killing spree—the hag becomes a sea fury, which hoards treasure, spreads rumors, and does everything within its power to lure sailors and explorers to its lair. By doing so, it hopes to break its loneliness for a time—and then to destroy its new playthings when they have outlived their usefulness.

```statblock
"name": "Sea Fury (EGW)"
"size": "Medium"
"type": "fey"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d8 + 42"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "15"
  - !!int "16"
  - !!int "12"
  - !!int "12"
  - !!int "18"
"speed": "30 ft., swim 50 ft."
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "cold; fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"condition_immunities": "[paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 15"
"languages": "Aquan, Common, Giant"
"cr": "12"
"traits":
  - "desc": "The sea fury's innate spellcasting ability is Charisma (spell save DC\
      \ 16, +8 to hit with spell attacks). It can innately cast the following spells,\
      \ requiring no material components:\n\n**At will:** [witch bolt](/3-Mechanics/CLI/spells/witch-bolt-xphb.md)\n\
      \n**1/day each:** [bestow curse](/3-Mechanics/CLI/spells/bestow-curse-xphb.md),\
      \ [fear](/3-Mechanics/CLI/spells/fear-xphb.md), [thunderwave](/3-Mechanics/CLI/spells/thunderwave-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "The sea fury can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the sea fury fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The sea fury has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The sea fury makes two attacks with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (2d8 + 4) slashing damage."
    "name": "Claws"
  - "desc": "The sea fury targets one [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ creature it can see within 30 feet of it. The target must succeed on a DC\
      \ 16 Wisdom saving throw or drop to 0 hit points."
    "name": "Death Glare"
"lair_actions":
  - "desc": "A sea fury lurks in the caverns where its coven once dwelled, decorating\
      \ the walls with the bones of its slain kin, as well as baubles stolen from\
      \ sunken wrecks.\n\nOn initiative count 20 (losing initiative ties), the sea\
      \ fury can take a lair action to cause one of the following magical effects,\
      \ but can't use the same effect two rounds in a row:\n\n- Caverns, tunnels,\
      \ and pools of water within 120 feet of the sea fury become foggy or murky,\
      \ to the extent that the area becomes heavily obscured.  \n- The sea fury conjures\
      \ a 15-foot cube of water that fills an unoccupied space it can see within 30\
      \ feet of it, then moves the water in a straight line up to 60 feet, after which\
      \ the water disperses. Any creature that comes into contact with the rushing\
      \ [wave](/3-Mechanics/CLI/items/wave-xdmg.md) must succeed on a DC 16 Strength\
      \ saving throw or be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone) by\
      \ it and pushed 15 feet along its course.  \n- The sea fury calls forth the\
      \ spirit of a dead sailor or sea hag that met its end in the lair. This spirit\
      \ has the statistics of a [specter](/3-Mechanics/CLI/bestiary/undead/specter-xmm.md)\
      \ and lasts until the sea fury uses another lair action. The specter appears\
      \ in an unoccupied space within 30 feet of the sea fury and obeys the sea fury's\
      \ commands.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing a sea fury's lair is warped by the sea fury's magic,\
      \ which creates the following effects:\n\n- Sea water within 5 miles of the\
      \ lair becomes coarse and choppy, as if whipped by an unseen wind.  \n- Sea\
      \ grass within 1 mile of the lair is imbued with a foul mockery of life, grasping\
      \ ineffectually at any creature that passes within 5 feet of it.  \n- Ordinary\
      \ [crabs](/3-Mechanics/CLI/bestiary/beast/crab-xmm.md) and [octopi](/3-Mechanics/CLI/bestiary/beast/octopus-xmm.md)\
      \ within 1 mile of the lair grow in size to become [giant crabs](/3-Mechanics/CLI/bestiary/beast/giant-crab-xmm.md)\
      \ and [giant octopi](/3-Mechanics/CLI/bestiary/beast/giant-octopus-xmm.md),\
      \ respectively. These creatures serve the sea fury as spies and guards.  "
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the sea fury can expend a use to take one of the following actions. The\
  \ sea fury regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The sea fury transforms into a wave of foaming seawater, along with whatever\
      \ it is wearing or carrying, and moves up to its speed without provoking opportunity\
      \ attacks. While in this form, it can't be [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ or [restrained](/3-Mechanics/CLI/conditions.md#Restrained). It reverts to\
      \ its true form at the end of this movement."
    "name": "As Water"
  - "desc": "The sea fury conjures an apparition of one of its dead sisters, which\
      \ appears in an unoccupied space the sea fury can see within 30 feet of it.\
      \ Enemies of the sea fury that can see the apparition must succeed on a DC 16\
      \ Wisdom saving throw or be [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ of it until it vanishes at the end of the sea fury's next turn."
    "name": "Fearsome Apparition (Costs 2 Actions)"
  - "desc": "The sea fury disgorges a [swarm of poisonous snakes](/3-Mechanics/CLI/bestiary/beast/swarm-of-venomous-snakes-xmm.md),\
      \ which occupies the same space as the sea fury, acts on its own initiative\
      \ count, and attacks as directed by the sea fury. The sea fury can control up\
      \ to three of these swarms at a time."
    "name": "Conjure Snakes (Costs 3 Actions)"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/fey/token/sea-fury-egw.webp"
```
^statblock