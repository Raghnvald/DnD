---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Froghemoth Elder"
---
# [Froghemoth Elder](3-Mechanics/CLI/bestiary/monstrosity/froghemoth-elder-qftis.md)
*Source: Quests from the Infinite Staircase p. 198*  

Froghemoths are massive amphibious predators with starry origins. A froghemoth has four tentacles, a rubbery hide, a long prehensile tongue, and three bulbous eyes branching from an extendable stalk.

Though most froghemoths lurk in swamps, those raised in unnatural environs—as well as those that dine on smaller, weaker hatchlings—are unmatched in strength and hunger. These ancient specimens, known as froghemoth elders, possess alien abilities and warp the ecosystems in which they dwell.

To learn more about froghemoths, see *Mordenkainen Presents: Monsters of the Multiverse*.

## A Froghemoth Elder's Lair

Froghemoth elders lair in unnatural ecosystems that facilitate their growth, such as wrecked spaceships, primordial bogs, and radioactive pools.

```statblock
"name": "Froghemoth Elder (QftIS)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "207"
"hit_dice": "18d12 + 90"
"modifier": !!int "1"
"stats":
  - !!int "25"
  - !!int "13"
  - !!int "20"
  - !!int "2"
  - !!int "14"
  - !!int "8"
"speed": "30 ft., swim 30 ft."
"saves":
  - "strength": !!int "12"
  - "constitution": !!int "10"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "fire, lightning"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 22"
"languages": ""
"cr": "15"
"traits":
  - "desc": "The froghemoth can breathe air and water."
    "name": "Amphibious"
  - "desc": "If the froghemoth fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If the froghemoth takes lightning damage, it suffers two effects until\
      \ the end of its next turn: its speed is halved, and it has disadvantage on\
      \ Dexterity saving throws."
    "name": "Shock Susceptibility"
"actions":
  - "desc": "The froghemoth makes one Bite attack and two Tentacle attacks, and it\
      \ can use Tongue."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 23 (3d10 + 7) piercing damage, and the target is swallowed if it is a Medium\
      \ or smaller creature. A swallowed creature has the [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained) conditions,\
      \ has total cover against attacks and other effects outside the froghemoth,\
      \ and takes 10 (3d6) acid damage at the start of each of the froghemoth's\
      \ turns.\n\nThe froghemoth's gullet can hold up to three creatures at a time.\
      \ If the froghemoth takes 25 damage or more on a single turn from a creature\
      \ inside it, the froghemoth must succeed on a DC 20 Constitution saving throw\
      \ at the end of that turn or regurgitate all swallowed creatures, each of which\
      \ lands in a space within 10 feet of the froghemoth and has the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. If the froghemoth dies, any swallowed creatures are no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse using 10 feet of movement, exiting with\
      \ the [prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 20 ft., one target. *Hit:*\
      \ 20 (3d8 + 7) bludgeoning damage, and the target has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 20). Until this grapple ends, the froghemoth can't use\
      \ this tentacle on another target. The froghemoth has four tentacles."
    "name": "Tentacle"
  - "desc": "The froghemoth targets one Large or smaller creature that it can see\
      \ within 25 feet of it. The target must make a DC 20 Strength saving throw.\
      \ On a failed save, the target is pulled into an unoccupied space within 5 feet\
      \ of the froghemoth."
    "name": "Tongue"
"reactions":
  - "desc": "When a creature the froghemoth can see damages the froghemoth, the froghemoth\
      \ swivels its eyestalk toward the creature and pierces the creature's mind with\
      \ its otherworldly gaze. That creature must make a DC 18 Intelligence saving\
      \ throw, taking 7 (2d6) psychic damage on a failed save or half as much damage\
      \ on a successful one."
    "name": "Alien Gaze"
  - "desc": "Immediately after a creature the froghemoth can see ends its turn, the\
      \ froghemoth jumps up to half its speed. Each creature within 5 feet of the\
      \ froghemoth when it lands must succeed on a DC 20 Strength saving throw or\
      \ have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone) condition."
    "name": "Leap"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), the froghemoth can take\
      \ one of the following lair actions; the froghemoth can't take the same lair\
      \ action two rounds in a row:\n\n- **Croak.** The froghemoth lets out an ear-splitting\
      \ croak. Each creature within 30 feet of it must make a DC 18 Wisdom saving\
      \ throw. On a failed save, the creature has the deafened and frightened conditions\
      \ until the end of its next turn.  \n- **Hypnotic Visions.** One creature of\
      \ the froghemoth's choice within 60 feet of it must make a DC 15 Wisdom saving\
      \ throw. On a failed save, the target is mesmerized by otherworldly visions\
      \ and has the charmed condition until the end of the target's next turn. While\
      \ charmed in this way, the target has the incapacitated condition, and its speed\
      \ is 0.  "
    "name": ""
"regional_effects":
  - "desc": "The region within 1 mile of a froghemoth elder's lair is altered by the\
      \ froghemoth's unearthly presence, creating one or more of the following effects:\n\
      \n- **Alien Flora.** Strange, invasive plants with bright colors and odd patterns\
      \ sprout up around the lair.  \n- **Mutations.** Wildlife encountered near the\
      \ lair often sport mutations, such as extra limbs or eyes, glowing secretions,\
      \ or vestigial tentacles.  \n\nIf the froghemoth elder dies, these effects fade\
      \ over the course of 1d10 days."
    "name": ""
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/froghemoth-elder-qftis.webp"
```
^statblock