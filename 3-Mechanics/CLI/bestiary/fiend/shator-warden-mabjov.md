---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Shator Warden"
---
# [Shator Warden](3-Mechanics/CLI/bestiary/fiend/shator-warden-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 137*  

> [!quote] A quote from MINSC & BOO!  
> 
> Me and Boo like many sticky things, most especially donuts and Boo's favorite, candied pecans. But some sticky things belong on the pointy end of a sword.

> [!quote] A quote from Volo  
> 
> Demodands are difficult to study since they usually never leave their native plane of Carceri. However, the prison in Ust Natha presents a unique opportunity to view them up close. Not that I enjoyed the experience.

Demodands are primal creations of evil and implacable agents of destruction. Exiled to Carceri for their chaotic taint, they are also known as gehreleths or leths.

## Wardens of the Damned

Though they are trapped in Carceri, the demodands do not consider themselves prisoners. Instead, they are the self-appointed wardens and jailors of the Tarterian Depths. They derive pleasure from tormenting and terrorizing their fellow captives through acts of brutality, cruelly taunting them the entire time. However, they make no distinction between those actually condemned to Carceri, and planar travelers just passing through. As far as the demodand are concerned, all must be prevented from escaping at any cost.

## A Trio of the Grotesque

Demodands have three castes, each with a form so repulsive even other denizens of the Lower Planes view them with disgust. The farastu are forced to do the most menial tasks, under orders from their kelubar and shator superiors. When around weaker creatures they are vicious bullies; around more powerful beings they become whimpering cowards. The kelubars are the bureaucrats of the demodands, acting as intermediaries between the lowly farastu and their shator overlords. The kelubar decide which prisoners are rewarded, and which should be punished with extra torments. The shators make up the ruling caste, effectively serving as prison wardens to the lower-ranked guards.

## The Memory of Eons

Each shator possesses an obsidian triangle. These powerful magical artifacts grant the demodands access to the collective memory of their kind; a shared recollection stretching back to the very dawn of time. The shators primarily use the triangles to track the identity of every being that has ever escaped Carceri, concocting elaborate, generation-spanning strategies to recapture these fugitive souls.

```statblock
"name": "Shator Warden (MaBJoV)"
"size": "Large"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "119"
"hit_dice": "14d10 + 42"
"modifier": !!int "0"
"stats":
  - !!int "24"
  - !!int "11"
  - !!int "17"
  - !!int "14"
  - !!int "16"
  - !!int "20"
"speed": "30 ft., fly 60 ft."
"saves":
  - "strength": !!int "12"
  - "constitution": !!int "8"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+12"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+8"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+10"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 13"
"languages": "Abyssal, Common"
"cr": "14"
"traits":
  - "desc": "Magical darkness doesn't impede the shator's darkvision."
    "name": "Devil's Sight"
  - "desc": "The shator has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The shator has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The shator's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "The shator makes one Bite attack or one Poisonous Spit attack (if available)\
      \ and then makes two Claws attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 16 (2d8 + 7) piercing damage plus 10 (3d6) acid damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 11 (1d8 + 7) slashing damage plus 7 (2d6) acid damage."
    "name": "Claws"
  - "desc": "The shator exhales poisonous spit in a 20-foot line that is 5 feet wide.\
      \ Each creature in that line must make a DC 18 Dexterity saving throw, taking\
      \ 22 (5d8) acid damage on a failed save and having the [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ condition for 1 minute. A creature can repeat the saving throw at the end\
      \ of each of its turns, ending the effect on a success."
    "name": "Poisonous Spit (Recharge 5-6)"
  - "desc": "The shator casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 18):\n\n**At\
      \ will:** [clairvoyance](3-Mechanics/CLI/spells/clairvoyance.md), [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [fear](3-Mechanics/CLI/spells/fear.md), [invisibility](3-Mechanics/CLI/spells/invisibility.md)\
      \ (self only), [spider climb](3-Mechanics/CLI/spells/spider-climb.md), [tongues](3-Mechanics/CLI/spells/tongues.md)\n\
      \n**2/day each:** [cloudkill](3-Mechanics/CLI/spells/cloudkill.md), [dispel\
      \ magic](3-Mechanics/CLI/spells/dispel-magic.md), [plane shift](3-Mechanics/CLI/spells/plane-shift.md),\
      \ [Tasha's hideous laughter](3-Mechanics/CLI/spells/tashas-hideous-laughter.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The shator rolls a d6. A result of 1-2 summons in two allied [farastu\
      \ stalkers](3-Mechanics/CLI/bestiary/fiend/farastu-stalker-mabjov.md), a result\
      \ of 3-4 summons in one allied [shator warden](3-Mechanics/CLI/bestiary/fiend/shator-warden-mabjov.md)."
    "name": "Summon Demodand (1/Day)"
"reactions":
  - "desc": "When hit with a melee attack, the shator expels a toxic slime. The attacker\
      \ must succeed on a DC 18 Dexterity saving throw or have the [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ condition for 1 minute. A creature can repeat the saving throw at the end\
      \ of each of its turns, ending the effect on a success."
    "name": "Poisonous Slime"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/fiend/token/shator-warden-mabjov.webp"
```
^statblock