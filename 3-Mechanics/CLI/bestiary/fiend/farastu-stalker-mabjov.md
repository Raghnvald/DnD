---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Farastu Stalker"
---
# [Farastu Stalker](3-Mechanics/CLI/bestiary/fiend/farastu-stalker-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 135*  

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
"name": "Farastu Stalker (MaBJoV)"
"size": "Medium"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "71"
"hit_dice": "11d8 + 22"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "13"
  - !!int "14"
  - !!int "8"
  - !!int "12"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "strength": !!int "7"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+7"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "acid, poison"
"condition_immunities": "[poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 11"
"languages": "Abyssal"
"cr": "7"
"traits":
  - "desc": "The farastu secretes a thick, tar-like slime and it can choose to use\
      \ this slime to secure enemies that it has [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ or to make weapons become attached to it. It is able to end the adhesion with\
      \ a bonus action, causing all items and creatures secured to it to be released.\
      \ The adhesion also ends after the farastu dies."
    "name": "Adhesive Slime"
  - "desc": "Magical darkness doesn't impede the farastu's darkvision."
    "name": "Devil's Sight"
  - "desc": "The farastu has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The farastu has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "The farastu's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "At the start of its turn, the farastu can gain advantage on all melee\
      \ weapon attack rolls it makes during that turn, but attack rolls against it\
      \ have advantage until the start of its next turn."
    "name": "Reckless"
"actions":
  - "desc": "The farastu makes one Bite attack and two Claws attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (1d6 + 4) slashing damage. The target is held fast by the farastu's adhesive\
      \ slime ([grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition,\
      \ escape DC 15) if the farastu isn't already grappling a creature."
    "name": "Claws"
"reactions":
  - "desc": "After taking damage from a melee weapon, the farastu uses its reaction\
      \ to attach the weapon to its hide. The attacker must make a DC 15 Dexterity\
      \ saving throw. On a failure, the weapon becomes attached to the farastu's adhesive\
      \ hide until the farastu dies or releases the weapon. A creature can also use\
      \ an action to make a DC 15 Strength check, prying the weapon free from the\
      \ farastu, if successful."
    "name": "Adhesive Hide"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/fiend/token/farastu-stalker-mabjov.webp"
```
^statblock