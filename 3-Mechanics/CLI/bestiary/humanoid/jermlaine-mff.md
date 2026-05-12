---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mff
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/size/tiny
- ttrpg-cli/monster/type/humanoid/jermlaine
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jermlaine"
---
# [Jermlaine](3-Mechanics/CLI/bestiary/humanoid/jermlaine-mff.md)
*Source: Mordenkainen's Fiendish Folio p. 11*  

Jermlaine prove that terrible things can come in tiny packages. Their tiny, foot-tall forms can barely contain the cruelty and malevolence that courses through them. Deep in the Underdark, the jermlaine lurk among the tunnels, dungeons, and caverns inhabited by much larger, more dangerous folk. The jermlaine huddle in their small tunnels, avoiding contact with all other creatures unless they can marshal overwhelming numbers. When the odds are in their favor, they strike with a vicious determination that can overwhelm even a heavily armed drow patrol or duergar war party.

## Hateful Ambushers

Jermlaine hate and resent all larger creatures. They are acutely aware that their small size and weakness in combat makes them prey for countless Underdark creatures. This anger and resentment is channeled into vengeful scheming against creatures that enter their domain. The jermlaine keep careful watch, waiting for just the right moment to fall upon their enemies. When they strike, they emerge from their tunnels to attack in overwhelming waves. In the heat of battle, individual jermlaine gladly throw themselves on their enemies' weapons to clear the way for their allies' attacks.

## Hidden Threat

The jermlaine's skin is rough, leathery, and textured like stone. Whether by the design of some sympathetic god or through sheer luck, their hide makes them appear [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible) to [darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision). Part of the jermlaine's anger comes from attempts to hunt them down and fashion cloaks and other material from their skin. Such experiments have yet to yield a functional magic item, and the jermlaine's hatred of outsiders is driven in part by their assumption that any who meet them seek to harvest them for such experiments.

## Secret Lairs

Because they are hunted for food or for their skin, jermlaine take care to hide their lairs away from prying eyes. They dig tunnels barely large enough to fit their 1-foot tall frames, making it almost impossible for their enemies to pursue them. Jermlaine dig their tunnels along dungeon hallways and Underdark passages, hiding the entrances to keep intruders out and set up their ambushes. The jermlaine create passages in the floor, along the walls, and in the upper part of the ceiling. When they attack, they spill upon their enemies from every direction in a bid to overwhelm them with sheer numbers.

## Allied Rodents

The jermlaine can decipher the chitters and squeaks of rats, and in turn can communicate with such rodents. Underdark explorers know to keep a careful watch when encountering signs of a rat infestation. Those rodents, as creatures of the surface world, are rare in the deep Underdark. Their presence invariably signals the presence of a jermlaine colony.

```statblock
"name": "Jermlaine (MFF)"
"size": "Tiny"
"type": "humanoid"
"subtype": "jermlaine"
"alignment": "Neutral Evil"
"ac": !!int "11"
"hp": !!int "3"
"hit_dice": "1d4 + 1"
"modifier": !!int "1"
"stats":
  - !!int "4"
  - !!int "12"
  - !!int "13"
  - !!int "10"
  - !!int "11"
  - !!int "7"
"speed": "30 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"gear":
  - "[club](3-Mechanics/CLI/items/club.md)"
  - "[dart](3-Mechanics/CLI/items/dart.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 10"
"languages": "Undercommon"
"cr": "1/8"
"traits":
  - "desc": "Jermlaine are [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ to darkvision."
    "name": "Lurkers in Shadow"
  - "desc": "The jermlaine has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The jermlaine can speak to and understand rats and giant rats."
    "name": "Vermin Friend"
  - "desc": "A jermlaine adds 1d4 to its weapon damage rolls while within 5 feet\
      \ of another, conscious jermlaine."
    "name": "Swarming Rush"
"actions":
  - "desc": "*Melee Weapon Attack:* -1 to hit, reach 5 ft., one target. *Hit:* 1\
      \ (1d4 - 3) bludgeoning damage."
    "name": "Club"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 20/60 ft., one target. *Hit:*\
      \ 3 (1d4 + 1) piercing damage."
    "name": "Dart"
"source":
  - "MFF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/jermlaine-mff.webp"
```
^statblock