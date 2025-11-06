---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/HG/21
  - Monster/Größe/Gigantisch
  - Monster/Typ/Drache
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Burney the Barber
Größe: Gigantisch
HG: 21
status: WIP
Habitat:
  - /
---
# [Burney the Barber](3-Mechanics\CLI\bestiary\npc/burney-the-barber-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 129*  

```statblock
"name": "Burney the Barber (BGDIA)"
"size": "Gargantuan"
"type": "dragon"
"alignment": "Chaotic Good"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "350"
"hit_dice": "20d20 + 140"
"modifier": !!int "1"
"stats":
  - !!int "27"
  - !!int "12"
  - !!int "25"
  - !!int "20"
  - !!int "17"
  - !!int "19"
"speed": "40 ft., climb 40 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "8"
  - "constitution": !!int "14"
  - "wisdom": !!int "10"
  - "charisma": !!int "11"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+17"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+8"
"damage_immunities": "acid"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)\
  \ 120 ft., passive Perception 27"
"languages": "Common, Draconic"
"cr": "21"
"traits":
  - "desc": "If Burney fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Burney has the benefits of the [healer](/3-Mechanics/CLI/feats/healer-xphb.md)\
      \ feat as well as proficiency with both the [healer's kit](/3-Mechanics/CLI/items/healers-kit-xphb.md)\
      \ and the [herbalism kit](/3-Mechanics/CLI/items/herbalism-kit-xphb.md)."
    "name": "Healer"
  - "desc": "Burney has received several blessings in her service to Bahamut:\n\n\
      - Unless Burney decided otherwise, once any creature less powerful than a deity\
      \ has taken three steps from her, they can no longer remember her or having\
      \ interacted with her specifically.  \n- Burney is under the effect of a permanent\
      \ [mind blank](/3-Mechanics/CLI/spells/mind-blank-xphb.md) spell, and cannot\
      \ be detected by magical or mundane means unless she wishes it. In exchange\
      \ for this blessing, Burney can take no direct action against the denizens of\
      \ the Nine Hells, though she can certainly enlist the help of those who can.\
      \  \n- Burney always knows the location of the Wandering Emporium and can transport\
      \ herself there as though by a [word of recall](/3-Mechanics/CLI/spells/word-of-recall-xphb.md)\
      \ spell. This explains why Burney simply seems to appear amid the fully deployed\
      \ marketplace each morning it is active to provide service and tell stories.\
      \  \n- Once each day, when Burney so desires, she can instantly transport herself\
      \ to the court of Bahamut via a powerful blessing akin to the [plane shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md)\
      \ spell.  "
    "name": "Bahamut's Blessings"
"actions":
  - "desc": "Burney can use its Frightful Presence. It then makes three attacks: one\
      \ with its bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 15 ft., one target. *Hit:* 19\
      \ (2d10 + 8) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 10 ft., one target. *Hit:* 15\
      \ (2d6 + 8) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 20 ft., one target. *Hit:* 17\
      \ (2d8 + 8) bludgeoning damage."
    "name": "Tail"
  - "desc": "Each creature of Burney's choice that is within 120 feet of Burney and\
      \ aware of it must succeed on a DC 19 Wisdom saving throw or become [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to Burney's\
      \ Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "Burney uses one of the following breath weapons.\n\n- **Acid Breath.**\
      \ Burney exhales acid in a 90-foot line that is 10 feet wide. Each creature\
      \ in that line must make a DC 22 Dexterity saving throw, taking 63 (14d8) acid\
      \ damage on a failed save, or half as much damage on a successful one.  \n-\
      \ **Slowing Breath.** Burney exhales gas in a 90-foot cone. Each creature in\
      \ that area must succeed on a DC 22 Constitution saving throw. On a failed save,\
      \ the creature can't use reactions, its speed is halved, and it can't make more\
      \ than one attack on its turn. In addition, the creature can use either an action\
      \ or a bonus action on its turn, but not both. These effects last for 1 minute.\
      \ The creature can repeat the saving throw at the end of each of its turns,\
      \ ending the effect on itself with a successful save.  "
    "name": "Breath Weapons (Recharge 5-6)"
  - "desc": "Burney magically polymorphs into a humanoid or beast that has a challenge\
      \ rating no higher than its own, or back into its true form. It reverts to its\
      \ true form if it dies. Any equipment it is wearing or carrying is absorbed\
      \ or borne by the new form (Burney's choice).\n\nIn a new form, Burney retains\
      \ its alignment, hit points, Hit Dice, ability to speak, proficiencies, Legendary\
      \ Resistance, lair actions, and Intelligence, Wisdom, and Charisma scores, as\
      \ well as this action. Its statistics and capabilities are otherwise replaced\
      \ by those of the new form, except any class features or legendary actions of\
      \ that form."
    "name": "Change Shape"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Burney can expend a use to take one of the following actions. Burney regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Burney makes a Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ check."
    "name": "Detect"
  - "desc": "Burney makes a tail attack."
    "name": "Tail Attack"
  - "desc": "Burney beats its wings. Each creature within 15 feet of Burney must succeed\
      \ on a DC 23 Dexterity saving throw or take 15 (2d6 + 8) bludgeoning damage\
      \ and be knocked [prone](/3-Mechanics/CLI/conditions.md#Prone). Burney can then\
      \ fly up to half its flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/npc/token/burney-the-barber-bgdia.webp"
```
^statblock