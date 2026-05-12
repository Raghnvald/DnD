---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/sdw
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/dragon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Lhammaruntosz"
---
# [Lhammaruntosz](3-Mechanics/CLI/bestiary/npc/lhammaruntosz-sdw.md)
*Source: Sleeping Dragon's Wake*  

Lhammaruntosz, a bronze dragon with the ability to heal quickly, spent decades defending Leilon and the surrounding area as the captain of the Scaly Eye, a fleet that battled pirates and other threats. To honor her deeds, the Swords of Leilon constructed the Bronze Shrine, a massive temple to Bahamut, god of metallic dragons, in a cliff overlooking the sea. The shrine's face is carved in Lhammaruntosz's likeness and includes quarters for the rest of the Scaly Eye and a magic statue of Bahamut, which the dragon can use to commune with the deity.

In recent decades Lhammaruntosz has retreated inside the shrine, becoming reclusive due to a attack by a disguised demon which has driven her mad. She leaves on rare occasions to hunt for food, returning as soon as possible. Members of the Scaly Eye still live within the Bronze Shrine, as Lhammaruntosz has ordered them to stay on as her guardians.

```statblock
"name": "Lhammaruntosz (SDW)"
"size": "Huge"
"type": "dragon"
"alignment": "Lawful Good"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "212"
"hit_dice": "17d12 + 102"
"modifier": !!int "0"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "23"
  - !!int "16"
  - !!int "15"
  - !!int "19"
"speed": "40 ft., fly 80 ft., swim 40 ft."
"saves":
  - "dexterity": !!int "5"
  - "constitution": !!int "11"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"damage_immunities": "lightning"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 60 ft., [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision)\
  \ 120 ft., passive Perception 22"
"languages": "Common, Draconic"
"cr": "16"
"traits":
  - "desc": "Lhammaruntosz is an 8th-level spellcaster. Her spellcasting ability is\
      \ Charisma (spell save DC 17; +9 to hit with spell attacks). She has the following\
      \ sorcerer spells prepared:\n\n**Cantrips (at will):** [light](3-Mechanics/CLI/spells/light-xphb.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand-xphb.md), [mending](3-Mechanics/CLI/spells/mending-xphb.md)\n\
      \n**1st level (4 slots):** [charm person](3-Mechanics/CLI/spells/charm-person-xphb.md),\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic-xphb.md), [expeditious\
      \ retreat](3-Mechanics/CLI/spells/expeditious-retreat-xphb.md), [sleep](3-Mechanics/CLI/spells/sleep-xphb.md)\n\
      \n**2nd level (3 slots):** [darkness](3-Mechanics/CLI/spells/darkness-xphb.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility-xphb.md), [suggestion](3-Mechanics/CLI/spells/suggestion-xphb.md)\n\
      \n**3rd level (3 slots):** [dispel magic](3-Mechanics/CLI/spells/dispel-magic-xphb.md),\
      \ [protection from energy](3-Mechanics/CLI/spells/protection-from-energy-xphb.md)\n\
      \n**4th level (2 slots):** [dimension door](3-Mechanics/CLI/spells/dimension-door-xphb.md),\
      \ [stoneskin](3-Mechanics/CLI/spells/stoneskin-xphb.md)"
    "name": "Spellcasting"
  - "desc": "Lhammaruntosz's spellcasting ability is Charisma (spell save DC 17).\
      \ She can innately cast the following spells, requiring no material components:\n\
      \n**1/day each:** [create food and water](3-Mechanics/CLI/spells/create-food-and-water-xphb.md),\
      \ [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [fog cloud](3-Mechanics/CLI/spells/fog-cloud-xphb.md),\
      \ [speak with animals](3-Mechanics/CLI/spells/speak-with-animals-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Lhammaruntosz can breathe air and water."
    "name": "Amphibious"
  - "desc": "If Lhammaruntosz fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Lhammaruntosz regains 5 hit points at the start of her turn."
    "name": "Regeneration"
"actions":
  - "desc": "Lhammaruntosz can use her Frightful Presence. She then makes three attacks:\
      \ one with her bite and two with her claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:*\
      \ 18 (2d10 + 7) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 14 (2d6 + 7) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 15 ft., one target. *Hit:*\
      \ 16 (2d8 + 7) bludgeoning damage."
    "name": "Tail"
  - "desc": "Each creature of Lhammaruntosz's choice that is within 120 feet of her\
      \ and aware of her must succeed on a DC 17 Wisdom saving throw or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, ending the effect on itself on a success. If a creature's saving\
      \ throw is successful or the effect ends for it, the creature is immune to Lhammaruntosz's\
      \ Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "Lhammaruntosz uses one of the following breath weapons."
    "name": "Breath Weapons (Recharge 5-6)"
  - "desc": "Lhammaruntosz exhales lightning in a 90-foot line that is 5 feet wide.\
      \ Each creature in that line must make a DC 19 Dexterity saving throw, taking\
      \ 66 (12d10) lightning damage on a failed save, or half as much damage on\
      \ a successful one."
    "name": "Lightning Breath"
  - "desc": "Lhammaruntosz exhales repulsion energy in a 30-foot cone. Each creature\
      \ in that area must succeed on a DC 19 Strength saving throw. On a failed save,\
      \ the creature is pushed 60 feet away from the dragon."
    "name": "Repulsion Breath"
  - "desc": "Lhammaruntosz magically polymorphs into a humanoid or beast that has\
      \ a challenge rating no higher than her own, or back into her true form. She\
      \ reverts to her true form if she dies. Any equipment she is wearing or carrying\
      \ is absorbed or borne by the new form (Lhammaruntosz's choice).\n\nIn a new\
      \ form, Lhammaruntosz retains her alignment, hit points, Hit Dice, ability to\
      \ speak, proficiencies, Legendary Resistance, lair actions, and Intelligence,\
      \ Wisdom, and Charisma scores, as well as this action. Her statistics and capabilities\
      \ are otherwise replaced by those of the new form, except any class features\
      \ or legendary actions of that form."
    "name": "Change Shape"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Lhammaruntosz can expend a use to take one of the following actions. Lhammaruntosz\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Lhammaruntosz makes a Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ check."
    "name": "Detect"
  - "desc": "Lhammaruntosz makes a tail attack."
    "name": "Tail Attack"
  - "desc": "Lhammaruntosz beats its wings. Each creature within 10 feet of Lhammaruntosz\
      \ must succeed on a DC 20 Dexterity saving throw or take 14 (2d6 + 7) bludgeoning\
      \ damage and be knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone).\
      \ Lhammaruntosz can then fly up to half her flying speed."
    "name": "Wing Attack (Costs 2 Actions)"
"source":
  - "SDW"
"image": "3-Mechanics/CLI/bestiary/npc/token/lhammaruntosz-sdw.webp"
```
^statblock