---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Gibberling"
---
# [Gibberling](3-Mechanics/CLI/bestiary/aberration/gibberling-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 141*  

> [!quote] A quote from Volo  
> 
> Gibberlings are appropriately named, for they babble, or should I say gibber, incessantly. They are unpredictable and thus barely worthy of any kind of research. Thus, why I didn't include them in my book "Volo's Guide to Monsters".

> [!quote] A quote from Gibberling  
> 
> SKREEEEEEEEGLURKLGLURKL! blarkblarkblarkblark. JagAjaGaJaGaJagAjAga!?

Gibberlings are small, feral humanoids believed to have originally come from the Far Realm, a distant plane characterized by chaos and madness. However, just how these creatures reached the Prime Material Plane and Faerûn is unknown. Regardless, these deadly, wild creatures have become an increasingly common sight for unfortunate travelers along the Sword Coast who stray from major roads at night. Luckily, the gibberlings' intense fear of all sources of light, including fire, make safeguarding camps and settlements a simple task.

## Madness Made Flesh

Gibberlings are short, squat creatures roughly the same height as the average gnome, though their hunched posture makes them appear to be even smaller. Thick black fur covers most of their muscular bodies, though bare patches of sickly gray skin are found on their faces, arms, and legs. Jet black eyes and a perpetual deranged grin adorn the bestial face of a gibberling, which is framed by pointed ears topped with hairy tufts.

## Chattering Hunger

Gibberlings roam the wilderness in large groups, largely preferring to stay within dense forests and caverns. They are exclusively carnivorous and do not hesitate to eat the flesh of their fallen kin. Gibberlings are rarely able to surprise their prey, as they constantly shriek, howl, and chatter. Although these vocalizations appear to be a form communication, the few linguists who study these creatures have concluded that these noises are not a language.

## Unpredictable Combatants

Even a novice adventurer could make short work of a single gibberling, though they always travel in packs. If left unchecked, these groups swell to vast hordes that devour everything in their path. Despite their animalistic behavior, gibberlings are intelligent enough to wield weapons, albeit ones stolen from victims rather than forged themselves. When such arms are unavailable, gibberlings improvise using rocks, bones, and large sticks. Gibberlings lack any sense of self-preservation; with no concept of retreat, a gibberling always fights to the death.

```statblock
"name": "Gibberling (MaBJoV)"
"size": "Small"
"type": "aberration"
"alignment": "Chaotic Neutral"
"ac": !!int "12"
"hp": !!int "7"
"hit_dice": "2d6"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "15"
  - !!int "10"
  - !!int "6"
  - !!int "8"
  - !!int "8"
"speed": "25 ft., burrow 5 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "psychic"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 9"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "While in bright light, gibberlings have disadvantage on attack rolls,\
      \ as well as on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on sight."
    "name": "Light Sensitivity"
  - "desc": "At the start of its turn, the gibberling can gain advantage on all melee\
      \ weapon attack rolls during that turn, but attack rolls against it have advantage\
      \ until the start of its next turn."
    "name": "Reckless"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 4\
      \ (1d4 + 2) piercing damage."
    "name": "Dagger"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. If the target\
      \ is a Medium or smaller creature, it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 10). All gibberlings within 5 feet of the target can\
      \ use a reaction to make a Dagger attack with advantage on the attack roll."
    "name": "Swarm"
  - "desc": "The gibberling burrows into the dirt, giving itself the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition. It has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks while it is [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Burrow"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/aberration/token/gibberling-mabjov.webp"
```
^statblock