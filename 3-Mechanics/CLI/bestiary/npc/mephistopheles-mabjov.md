---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/27
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mephistopheles"
---
# [Mephistopheles](3-Mechanics/CLI/bestiary/npc/mephistopheles-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 101*  

> [!quote] A quote from Volo  
> 
> If there were ever a subject I would never dare to write about it's the lord of Cania. I don't know the real reason of how the ranger came into information on this lord of Hell, but he claims it has something to do with his hamster. His hamster! How did I ever get bamboozled into editing this tome.

Mephistopheles is the lord of Cania, the eighth level of the Nine Hells, and the most powerful archdevil next to Asmodeus himself. He is famed as Hell's most powerful wizard and the wielder of a power known as Hellfire.

Mephistopheles is an ancient entity, a being rivaling even Asmodeus in terms of age. During his time as an archdevil he had been responsible for many schemes to try and unseat the Lord of the Nine. One of his infamous schemes was an alliance between himself, Dispater, Mammon, and Geryon. They conspired to take power from the other archdevils, Baalzebul, Zariel, Belial and Moloch. With this increased power, Mephistopheles would then be able to challenge Asmodeus himself. But he was betrayed by Geryon, who had been secretly siding with Asmodeus. Despite the blatancy of his rebellion, he was the archdevil that suffered the least: not cursed like Mammon or Baalzebul; not cast down like Belial, Moloch or Geryon. This has led many to believe that there is some ancient secret to the relationship between the Asmodeus and Mephistopheles, though what it could be is a mystery none have discovered.

Mephistopheles is a brilliant tactician and strategist, and he has an unparalleled understanding of Hell's political machinations and the potential pitfalls of every scheme and alliance. He is courteous and charming when he speaks, demonstrating a wry wit while projecting an image of self-restraint and composure. But beneath this civil persona lurks a savage, barely controlled temper, and he often flies into uncontrollable rages when alone in his palace. In addition to his barely contained anger, Mephistopheles suffers from obsessive envy, and he is bitterly resentful that he is "merely" the second most powerful archdevil.

As the foremost wizard of the Nine Hells, Mephistopheles often resorts to magic when forced to defend himself. But his greatest power comes from the ability to wield Hellfire itself. Created by tapping into the profane essence of Hell, Hellfire is unimaginably, unbearably hot. Unless he chooses to suppress it, his body emanates dark flames, causing anyone who touches him to be scorched by the unholy energy. Mephistopheles can also shape Hellfire any way he wishes, making it his most potent weapon.

```statblock
"name": "Mephistopheles (MaBJoV)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "460"
"hit_dice": "40d10 + 240"
"modifier": !!int "6"
"stats":
  - !!int "22"
  - !!int "23"
  - !!int "22"
  - !!int "30"
  - !!int "28"
  - !!int "26"
"speed": "40 ft., fly 100 ft."
"saves":
  - "intelligence": !!int "18"
  - "wisdom": !!int "17"
  - "charisma": !!int "16"
"skillsaves":
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+24"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+25"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+24"
"damage_resistances": "acid; cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "27"
"traits":
  - "desc": "Magical darkness doesn't impede Mephistopheles' darkvision."
    "name": "Devil's Sight"
  - "desc": "Mephistopheles regains 20 hit points at the start of his turn. If he\
      \ takes radiant damage this trait doesn't function at the start of his next\
      \ turn. Mephistopheles only dies if he starts his turn with 0 hit points and\
      \ is unable to regenerate."
    "name": "Fiendish Regeneration"
  - "desc": "Mephistopheles doesn't provoke opportunity attacks when he flies out\
      \ of an enemy's reach."
    "name": "Flyby"
  - "desc": "Fire damage that Mephistopheles inflicts ignores resistances and immunities.\
      \ Mephistopheles is immune to this effect."
    "name": "Hellfire Mastery"
  - "desc": "If Mephistopheles fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Mephistopheles has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Mephistopheles makes three Ranseur attacks. He can replace one of the\
      \ attacks with Hellfire Lash (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:*\
      \ 20 (2d10 + 9) piercing plus 18 (4d8) fire or cold damage (Mephistopheles'\
      \ choice)."
    "name": "Ranseur, +3"
  - "desc": "A bright streak of Hellfire appears at a point that Mephistopheles can\
      \ see within 150 feet of him. Each creature in a 20-foot-radius sphere centered\
      \ on that point must make a DC 22 Dexterity saving throw. Targets take 31 (9d6)\
      \ fire damage on a failed save, or half as much damage on a successful one."
    "name": "Hellfire Implosion (Recharge 4-6)"
  - "desc": "Mephistopheles unleashes a 60-foot-long, 5-foot-wide lash of Hellfire\
      \ that ignites a 5-foot-radius sphere around where it strikes. Any targets in\
      \ the area of effect must make a DC 22 Dexterity saving throw, taking 36 (8d8)\
      \ fire damage on a failed save, or half as much on a successful one."
    "name": "Hellfire Lash (Recharge 5-6)"
  - "desc": "Mephistopheles casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 26):\n\n**At will:** [darkness](3-Mechanics/CLI/spells/darkness.md), [detect\
      \ evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md), [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md), [geas](3-Mechanics/CLI/spells/geas.md)\
      \ (duration 1 year), [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md),\
      \ [hallow](3-Mechanics/CLI/spells/hallow.md), [hold monster](3-Mechanics/CLI/spells/hold-monster.md),\
      \ [locate creature](3-Mechanics/CLI/spells/locate-creature.md), [locate object](3-Mechanics/CLI/spells/locate-object.md),\
      \ [major image](3-Mechanics/CLI/spells/major-image.md), [resurrection](3-Mechanics/CLI/spells/resurrection.md),\
      \ [scrying](3-Mechanics/CLI/spells/scrying.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md),\
      \ [wall of fire](3-Mechanics/CLI/spells/wall-of-fire.md)\n\n**1/day each:**\
      \ [meteor swarm](3-Mechanics/CLI/spells/meteor-swarm.md), [symbol](3-Mechanics/CLI/spells/symbol.md),\
      \ [wish](3-Mechanics/CLI/spells/wish.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Mephistopheles' body and any equipment he is wearing or carrying turns\
      \ to ash, then he magically teleports up to 120 feet to an unoccupied space\
      \ he can see and reforms."
    "name": "Ashen Teleport"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Mephistopheles can expend a use to take one of the following actions. Mephistopheles\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Mephistopheles uses his wings to generate a burst of heat. Each creature\
      \ within 10 feet of him must succeed on a DC 22 Dexterity saving throw or take\
      \ 9 (2d8) bludgeoning damage plus 9 (2d8) fire damage. Creatures that failed\
      \ the save also have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Hellfire Wings"
  - "desc": "Mephistopheles creates a rain of Hellfire at a point he can see within\
      \ 150 feet. Each creature within a 20-foot-radius sphere centered on that point\
      \ must make a DC 24 Dexterity saving throw. Targets take 38 (7d10) fire damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Hellfire Storm (Costs 2 Actions)"
  - "desc": "Mephistopheles summons an allied [horned devil](3-Mechanics/CLI/bestiary/fiend/horned-devil.md)\
      \ in an unoccupied space that he can see."
    "name": "Call Underling (Costs 3 Actions)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/mephistopheles-mabjov.webp"
```
^statblock