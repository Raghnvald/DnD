---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Darkweaver"
---
# [Darkweaver](3-Mechanics/CLI/bestiary/aberration/darkweaver-mpp.md)
*Source: Morte's Planar Parade p. 25*  

Arachnid predators of the Shadowfell, darkweavers inhabit caves, dungeons, and other dark locales throughout the multiverse, including Undersigil and the windswept darkness of Pandemonium. A darkweaver lurks in the shadows of its lair, waiting for hapless prey to pass by. When a target approaches, the darkweaver fires webs of pure shadow at its quarry, then drags the victim into the darkness.

Darkweavers are fascinated by sensations—particularly taste—and how creatures from across the planes experience reality. For them, the act of eating is an experience to be drawn out and savored, with every meal considered in all its facets. Whether its fare is a demon, an archon, a struggling halfling, or a catatonic mule, all such meals are culinary delights for a darkweaver, served up from the cosmic kitchen that is the multiverse. These spider-like terrors appreciate second-hand descriptions of sensations, especially those they're unlikely to experience in their home environment. A darkweaver's captive might delay being consumed by sharing tales of its experiences, particularly great meals, with the monster. Some might even convince a darkweaver to release them if they promise to return with rare spices or one-of-a-kind meals. Those who manage to escape a darkweaver should think twice about returning to the creature's lair, though, as darkweavers prioritize their appetites over bargains.

## A Darkweaver's Lair

Darkweavers dwell in lightless caverns, preferring locations touched by pitch-black planes, such as Pandemonium or the Shadowfell. Darkweavers tend to inhabit isolated sites where they can weave webs of shadow undisturbed.

A darkweaver encountered in its lair has a challenge rating of 11 (7,200 XP).

## Darkweaver Webs

A darkweaver's web has a 50 percent chance of having `1d6` cocoons. Roll on the Darkweaver Cocoon Contents table to determine what might be inside each of these shadowy masses.

| dice: d6 | Category |
|----------|----------|
| 1 | Roll a die. If you roll an even number, the cocoon contains the bones of a Humanoid. If you roll an odd number, the cocoon contains the bones of a non-Humanoid creature, such as a flumph or a mule. |
| 2 | A swarm of insects that might be a darkweaver's young |
| 3 | A corpse holding a jar of universal solvent with a slightly stuck lid |
| 4 | A collection of menus from restaurants in Sigil |
| 5 | `4d12` gold pieces amid a digested slurry |
| 6 | A halfling commoner or musteval guardinal that the darkweaver forgot about |
^category

```statblock
"name": "Darkweaver (MPP)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Chaotic Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "149"
"hit_dice": "23d8 + 46"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "17"
  - !!int "14"
  - !!int "17"
  - !!int "14"
  - !!int "15"
"speed": "50 ft., climb 50 ft."
"saves":
  - "dexterity": !!int "7"
  - "wisdom": !!int "6"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+7"
"damage_resistances": "cold"
"damage_immunities": "necrotic"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 16"
"languages": "Abyssal, Deep Speech, telepathy 120 ft."
"cr": "10"
"traits":
  - "desc": "While the darkweaver is in dim light or darkness, attack rolls against\
      \ it are made with disadvantage unless the darkweaver has the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Shadowy Form"
  - "desc": "The darkweaver can climb difficult surfaces, including upside down on\
      \ ceilings, without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "The darkweaver takes 10 radiant damage when it starts its turn in sunlight.\
      \ While in sunlight, it has disadvantage on attack rolls and ability checks."
    "name": "Sunlight Hypersensitivity"
"actions":
  - "desc": "The darkweaver makes two Shadow Web attacks and one Bite attack. It can\
      \ use Reel after any of these attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (3d6 + 3) piercing damage plus 17 (5d6) necrotic damage, and if the\
      \ target is a creature, the target's hit point maximum is reduced by an amount\
      \ equal to the necrotic damage taken. This reduction lasts until the target\
      \ finishes a long rest. The target dies if its hit point maximum is reduced\
      \ to 0."
    "name": "Bite"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, reach 120 ft., one creature. *Hit:*\
      \ 16 (3d10) necrotic damage, and the target has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ condition (escape DC 15). The shadow web can be attacked and destroyed (AC\
      \ 16; 20 hit points; vulnerability to radiant damage; immunity to bludgeoning,\
      \ necrotic, poison, and psychic damage). The darkweaver can grapple up to six\
      \ creatures at a time using its shadow web."
    "name": "Shadow Web"
  - "desc": "The darkweaver pulls each creature it has [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ up to 60 feet toward itself."
    "name": "Reel"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), a darkweaver can take\
      \ one of the following lair actions; the darkweaver can't take the same lair\
      \ action two rounds in a row:\n\n- **Extinguish..** All nonmagical flames within\
      \ 30 feet of the darkweaver are extinguished. In addition, if this area overlaps\
      \ with an area of light created by a spell of 2nd level or lower, the spell\
      \ that created the light is dispelled.  \n- **Shadow Fears..** The darkweaver\
      \ instills frightful magic into its webs. Each creature grappled by the darkweaver's\
      \ Shadow Web must make a DC 15 Wisdom saving throw. On a failed save, the creature\
      \ has the frightened condition until the end of its next turn.  \n- **Shadow\
      \ Step..** If the darkweaver is in dim light or darkness, it teleports, along\
      \ with any equipment it is wearing or carrying, to an unoccupied space it can\
      \ see within 60 feet of itself that is in dim light or darkness.  "
    "name": ""
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/aberration/token/darkweaver-mpp.webp"
```
^statblock