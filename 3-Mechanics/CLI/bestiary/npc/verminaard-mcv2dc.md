---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mcv2dc
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/cleric
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Verminaard"
---
# [Verminaard](3-Mechanics/CLI/bestiary/npc/verminaard-mcv2dc.md)
*Source: Monstrous Compendium Volume 2: Dragonlance Creatures p. 15*  

> [!quote]  
> 
> Ariakas,
> 
> As the Dragon Queen wills me to obey, here is my assessment of your servant, Verminaard of Nidus: Unchanged. The man remains a blustering dastard awash in blessings earned by his blood rather than his brains. He glories in Takhisis's favor and wields her power in manners both frivolous and brutal. In their bunks, his troops whisper of his zealotry and claim that those missing from their ranks have been sacrificed on his secret altar. I don't dismiss this possibility.
> 
> While his work progresses, it is the effort of an instrument as blunt as the mace he wields.
> 
> Verminaard thinks himself invincible, and I pray to her majesty that I'm present when she divests him of that delusion.
> 
> I hope you find these reports illuminating.
> 
> Ember

Dragon Highlord Verminaard leads the Red Dragon Army—the largest and most powerful of the Dragon Queen's forces—with fanatic zeal and ruthless might. Though prophesied to banish evil forces from the lands of Krynn, Verminaard was tempted by Takhisis and her promises of glory. Corrupted by the Dragon Queen, Verminaard rose to become one of her champions, claiming command of the fiercest among the Dragon Armies.

Verminaard's extreme devotion to Takhisis allows him to channel her unholy power on the battlefield, bolstering those under his command while raining cursed fire on his foes. His towering silhouette is often wreathed in the fire of Ember, his red dragon companion and adviser.

> [!note] Draconic Devotion
> 
> Verminaard's stat block references the Draconic Devotion monster trait. Though this trait does not appear in any of the creatures in this compendium, you will find several monsters with the Draconic Devotion trait terrorizing the lands of Krynn in the book Dragonlance: Shadow of the Dragon Queen.
^draconic-devotion

```statblock
"name": "Verminaard (MCV2DC)"
"size": "Medium"
"type": "humanoid"
"subtype": "cleric, human"
"alignment": "Lawful Evil"
"ac": !!int "20"
"ac_class": "+2 plate armor"
"hp": !!int "143"
"hit_dice": "22d8 + 44"
"modifier": !!int "1"
"stats":
  - !!int "22"
  - !!int "13"
  - !!int "15"
  - !!int "16"
  - !!int "18"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "10"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+16"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+9"
"damage_immunities": "fire"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[nightbringer](3-Mechanics/CLI/items/nightbringer-mcv2dc.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 26"
"languages": "Abyssal, Common, Draconic"
"cr": "17"
"traits":
  - "desc": "Whenever a Dragon or a creature with the Draconic Devotion trait within\
      \ 30 feet of Verminaard makes an attack roll, the creature can roll a d4 and\
      \ add the number rolled to the attack roll."
    "name": "Draconic Command"
  - "desc": "If Verminaard fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Verminaard wears +2 plate armor and wields the mace [Nightbringer](3-Mechanics/CLI/items/nightbringer-mcv2dc.md),\
      \ which grants him darkvision as well as immunity to fire damage and to the\
      \ [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) and [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ conditions (included above)."
    "name": "Special Equipment"
"actions":
  - "desc": "Verminaard makes two Nightbringer attacks and uses Malediction."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 5 ft., one target. *Hit:*\
      \ 12 (1d6 + 9) bludgeoning damage plus 10 (4d4) radiant damage. If the target\
      \ is a creature, the target must succeed on a DC 20 Constitution saving throw\
      \ or be [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) until the start\
      \ of Verminaard's next turn."
    "name": "Nightbringer"
  - "desc": "Verminaard utters an unholy word, causing profane fire to descend on\
      \ one creature Verminaard can see within 60 feet of himself. The creature must\
      \ make a DC 18 Dexterity saving throw, taking 11 (2d10) necrotic damage plus\
      \ 11 (2d10) radiant damage on a failed save or half as much damage on a successful\
      \ one."
    "name": "Malediction"
  - "desc": "Verminaard casts one of the following spells, requiring no material components\
      \ and using Wisdom as the spellcasting ability (spell save DC 18):\n\n**At will:**\
      \ [light](3-Mechanics/CLI/spells/light.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**2/day each:** [bane](3-Mechanics/CLI/spells/bane.md), [fear](3-Mechanics/CLI/spells/fear.md),\
      \ [freedom of movement](3-Mechanics/CLI/spells/freedom-of-movement.md), [greater\
      \ restoration](3-Mechanics/CLI/spells/greater-restoration.md), [hold monster](3-Mechanics/CLI/spells/hold-monster.md),\
      \ [revivify](3-Mechanics/CLI/spells/revivify.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Verminaard or one creature he can see within 60 feet of himself magically\
      \ regains 17 (2d12 + 4) hit points."
    "name": "Dragon Queen's Favor (5/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Verminaard can expend a use to take one of the following actions. Verminaard\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Verminaard moves up to his speed or commands a mount he is riding to\
      \ move up to its speed. This movement doesn't provoke opportunity attacks."
    "name": "Tactical Movement"
  - "desc": "Verminaard makes one Nightbringer attack. If this attack hits, it deals\
      \ an additional 7 (2d6) bludgeoning damage."
    "name": "Fervent Strike (Costs 2 Actions)"
  - "desc": "Verminaard uses Spellcasting."
    "name": "Cast a Spell (Costs 3 Actions)"
"source":
  - "MCV2DC"
"image": "3-Mechanics/CLI/bestiary/npc/token/verminaard-mcv2dc.webp"
```
^statblock