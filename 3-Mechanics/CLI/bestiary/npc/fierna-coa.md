---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Fierna"
---
# [Fierna](3-Mechanics/CLI/bestiary/npc/fierna-coa.md)
*Source: Chains of Asmodeus p. 225*  

Fierna rules Phlegethos alongside her father, Belial. She is emotionally intelligent, and her charisma has earned her many allies and few enemies in the Nine Hells. Although some view her as incompetent, Fierna's true intentions are hidden behind a smokescreen of brashness.

Her father, Belial, was a key player in the Reckoning, and due to his actions, Fierna was granted primary leadership of Phlegethos. Despite this political appearance, Fierna and Belial rule together, often meeting in secret to discuss strategy and upcoming plans. Some of the more ignorant archdevils view the relationship between Belial and Fierna as something to be exploited or broken. In reality, Fierna deeply respects her father, and the feeling is mutual.

Laying eyes on Fierna, one can immediately see the reasons she is so admired: she is impossibly beautiful. Her beauty is a strength, complementing her strategic mind and ingenuity.

## Fierna's Lair

Fierna's lair is a palace, a tower of crystalline stone wreathed in blue flame.

```statblock
"name": "Fierna (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "natural armor"
"hp": !!int "367"
"hit_dice": "35d8 + 210"
"modifier": !!int "7"
"stats":
  - !!int "17"
  - !!int "25"
  - !!int "22"
  - !!int "22"
  - !!int "22"
  - !!int "29"
"speed": "30 ft., fly 60 ft."
"saves":
  - "dexterity": !!int "15"
  - "constitution": !!int "14"
  - "wisdom": !!int "14"
  - "charisma": !!int "17"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+15"
  - "name": "Deception"
    "desc": "+25"
  - "name": "Insight"
    "desc": "+14"
  - "name": "Intimidation"
    "desc": "+17"
  - "name": "Perception"
    "desc": "+14"
  - "name": "Persuasion"
    "desc": "+25"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"damage_immunities": "cold, fire, poison"
"condition_immunities": "charmed, poisoned"
"senses": "darkvision 120 ft., passive Perception 24"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "When a creature starts their turn within 120 feet of Fierna, they must\
      \ succeed on a DC 22 Wisdom saving throw or have the frightened condition until\
      \ they leave the aura. A creature that succeeds on the saving throw is immune\
      \ to this effect for 1 hour."
    "name": "Fear Aura"
  - "desc": "Fierna regains 20 hit points at the start of her turn. If she takes radiant\
      \ damage this trait doesn't function at the start of her next turn. Fierna dies\
      \ only if she starts her turn with 0 hit points and is unable to regenerate."
    "name": "Fiendish Regeneration"
  - "desc": "If Fierna fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Fierna has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Fire conjured by Fierna becomes Hellfire. It ignores resistances and\
      \ immunities to fire damage, deals double damage to creatures vulnerable to\
      \ fire or necrotic damage, can't be extinguished through any means, and is capable\
      \ of melting stone or igniting inflammable objects."
    "name": "Princess of Hellfire"
"actions":
  - "desc": "Fierna makes three attacks using Flame Blade, Mote of Flame, or a combination\
      \ of the two."
    "name": "Multiattack"
  - "desc": "*Melee Spell Attack:* +20 to hit, reach 5 ft., one target. *Hit:* 23\
      \ (4d6 + 9) fire damage."
    "name": "Flame Blade"
  - "desc": "Fierna targets a creature she can see within 90 feet of her. The target\
      \ must make a DC 25 Dexterity saving throw, taking 22 (3d8 + 9) fire damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Mote of Flame"
"reactions":
  - "desc": "When hit by a melee attack and Fierna can see her attacker, she covers\
      \ herself in Hellfire, and the attacker takes 13 (3d8) fire damage."
    "name": "Wreath of Flames"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Fierna can take one\
      \ lair action to cause the following effect or one from the archdevil lair action\
      \ list (page 214); she can't take the same lair action two rounds in a row:\n\
      \n- **Fiery Reversal.** Fierna exchanges places with a creature she can see\
      \ within 30 feet of her. Both her old location and her new location erupt into\
      \ flames that persist for 1 minute. Anyone entering either flame must succeed\
      \ on a DC 21 Constitution saving throw or take 28 (8d6) fire damage.  \n\n\
      - **Attack.** The archdevil uses one of their available melee or ranged attacks\
      \ against a single foe.  \n- **Cast a Spell.** The archdevil uses their Spellcasting\
      \ feature to cast an available spell. If the spell normally requires concentration,\
      \ it lasts for the full duration instead.  \n- **Deceitful Whispers.** The archdevil\
      \ whispers to a creature they can see within 30 feet. The target must make a\
      \ DC 22 Wisdom saving throw. On a failed save, the target has the charmed condition\
      \ until the start of their next turn and must use their reaction immediately\
      \ to make an attack against one of the archdevil's enemies, chosen by the archdevil.\
      \  \n- **Fiendish Fortitude.** The archdevil recharges one of their expended\
      \ abilities.  \n- **Frenzy.** The archdevil casts Haste on themself. The effect\
      \ ends at initiative count 20 of the next round.  \n- **Summon Underlings.**\
      \ The archdevil summons allied devils. The devils summoned depends on the archdevil\
      \ using this feature. The summoned devils appear in unoccupied spaces which\
      \ the archdevil can see. The [Summoned Underlings](3-Mechanics/CLI/tables/archdevil-lair-action-list-summoned-underlings-coa.md)\
      \ table shows which devils each archdevil can summon.  \n- **Teleport.** The\
      \ archdevil teleports themself to an area they can see within 120 feet.  \n\
      - **Trap.** The archdevil casts the Hold Monster spell.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Fierna's lair is corrupted by her presence, which\
      \ creates the following effect:\n\n- **Smoke-cloud.** A vast fog rises 3 feet\
      \ above ground within 1 mile of the lair, completely obscuring the ground. Any\
      \ creature having the prone condition at the start of their turn must succeed\
      \ on a DC 22 Constitution saving throw or take 7 (2d12) necrotic damage from\
      \ choking on the noxious fumes.  \n\nIf Fierna dies, the effects fade over the\
      \ course of 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Fierna can expend a use to take one of the following actions. Fierna regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Fierna makes a Flame Blade attack."
    "name": "Blade"
  - "desc": "Fierna chooses a point she can see within 150 feet of her. All creatures\
      \ in a 20-foot-radius sphere centered on that point must make a DC 25 Dexterity\
      \ saving throw, taking 28 (8d6) fire damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Conjure Hellfire (Costs 2 Actions)"
  - "desc": "Fierna summons an allied spined devil in an unoccupied space that she\
      \ can see."
    "name": "Call Underling (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/fierna-coa.webp"
```
^statblock