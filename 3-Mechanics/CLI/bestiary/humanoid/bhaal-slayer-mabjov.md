---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/20
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bhaal, Slayer"
---
# [Bhaal, Slayer](3-Mechanics/CLI/bestiary/humanoid/bhaal-slayer-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 93*  

> [!quote] A quote from MINSC & BOO!  
> 
> When evil knocks on your door, don't ask who's there. Let your SWORD do the talking! But when you knock on evil's door, give it a good, hard KICK. And when evil asks, Who's there? tell them Boo sent you!

A wholly evil, debased and sadistic god, Bhaal—the God of Murder—is reviled by a majority of Faerûn's pantheon; his divine foes include Chauntea, Helm, Ilmater, Lathander, Lliira and Tyr.

Before his ascension to godhood, Bhaal was a power-hungry adventurer on Toril. Along with his companions Bane and Myrkul, he sought to attain the portfolio of Jergal, God of the Dead. Jergal willingly offered his realm to the Dark Three, though they couldn't decide amongst themselves who would rule. Upon Jergal's suggestion, the three divided his power, deciding how to divide it based on the outcome of a game. The three played a game of knucklebones, and Bane emerged as the victor. He claimed the domains of hatred, strife and tyranny as his own. Myrkul, coming second, chose rule over the dead. Finally, Bhaal chose the divine province of death and murder.

A century ago, Bhaal foresaw that he would die in the Time of Troubles and enacted a plan that would allow him to return to life by creating the Bhaalspawn—mortal children imbued with a fraction of his divine essence. While that plan took more than a century to come to fruition, Bhaal has indeed been reborn. Having been dead for more than a century, he now works to rebuild his following, which will augment his divine power. Some of his most powerful and devout followers include his Bhaalspawn son Sarevok and the famous sky captain Pelyious.

Bhaal has two avatar forms: a corpse-like male humanoid called the Slayer, and a huge beast known as the Ravager. He hunts victims at night in his Slayer form. When he has killed, it gives him the power to transform into the Ravager.

```statblock
"name": "Bhaal, Slayer (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "266"
"hit_dice": "28d8 + 140"
"modifier": !!int "6"
"stats":
  - !!int "24"
  - !!int "22"
  - !!int "20"
  - !!int "14"
  - !!int "16"
  - !!int "14"
"speed": "40 ft."
"saves":
  - "strength": !!int "13"
  - "dexterity": !!int "12"
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+18"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned), [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned),\
  \ [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Abyssal, Common"
"cr": "20"
"traits":
  - "desc": "During its first turn, the slayer has advantage on attack rolls against\
      \ any creature that hasn't taken a turn. Any hit the slayer scores against a\
      \ surprised creature is a critical hit."
    "name": "Assassinate"
  - "desc": "Magical darkness doesn't impede the slayer's darkvision."
    "name": "Devil's Sight"
  - "desc": "The slayer is immune to any spell or effect that would alter its form,\
      \ except for its Ravager Form ability."
    "name": "Immutable Form"
  - "desc": "If the slayer fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "The slayer has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The slayer's claw attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "The slayer makes four Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one target. *Hit:*\
      \ 16 (2d8 + 7) slashing damage plus 3 (1d6) necrotic damage. If the target\
      \ is a creature, it must succeed on a DC 19 Constitution saving throw or have\
      \ its hit point maximum reduced by an amount equal to the damage taken. The\
      \ target dies if this attack reduces its hit point maximum to 0. The reduction\
      \ lasts until removed by the [greater restoration](3-Mechanics/CLI/spells/greater-restoration.md)\
      \ spell or other magic."
    "name": "Claw"
"bonus_actions":
  - "desc": "The slayer focuses on a single creature it can see within 60 feet. Afterwards,\
      \ the first time each turn that the slayer hits that creature, the slayer does\
      \ an additional 7 (2d6) damage."
    "name": "Prey"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the slayer can expend a use to take one of the following actions. The slayer\
  \ regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The slayer disengages without provoking opportunity attacks. If it moves\
      \ within 5 feet of a creature it makes a Claw attack against the creature."
    "name": "Savage Disengage"
  - "desc": "The slayer attacks a creature that has been marked by its Prey ability.\
      \ If this attack hits and the creature has less than 40 hit points remaining\
      \ after the attack, the creature is reduced to 0 hit points."
    "name": "Finish (Costs 2 Actions)"
  - "desc": "If the slayer has killed a creature of CR/level 5 or greater that it\
      \ previously marked with its Prey ability in the last minute, it can transform\
      \ into its [ravager form](3-Mechanics/CLI/bestiary/beast/bhaal-ravager-mabjov.md).\
      \ The form lasts until dawn (minimum 1 hour)."
    "name": "Ravager Form (Costs 3 Actions)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/bhaal-slayer-mabjov.webp"
```
^statblock