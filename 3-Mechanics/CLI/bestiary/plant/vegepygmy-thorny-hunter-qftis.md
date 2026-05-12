---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vegepygmy Thorny Hunter"
---
# [Vegepygmy Thorny Hunter](3-Mechanics/CLI/bestiary/plant/vegepygmy-thorny-hunter-qftis.md)
*Source: Quests from the Infinite Staircase p. 219*  

Thorny hunters are bestial vegepygmies derived from the corpses of bears, dogs, and other quadrupedal Beasts. Thorny hunters act like bloodhounds, following their master's orders to hunt prey with deadly ferocity.

## Vegepygmies

Also called mold folk, vegepygmies are fungal creatures that spring forth from the body of a Humanoid or Giant killed by russet mold, a poisonous fungus rumored to have originated from beyond the stars.

Vegepygmies gather in small bands, communicating with a combination of gestures, hisses, and rhythmic taps. While vegepygmies can sustain themselves by absorbing nutrients from soil and other organic matter, they prefer a carnivorous diet achieved through hunting and scavenging. Vegepygmies can live indefinitely so long as the climate remains hospitable to their fungal bodies.

To learn more about vegepygmies, see Monsters of the Multiverse.

```statblock
"name": "Vegepygmy Thorny Hunter (QftIS)"
"size": "Medium"
"type": "plant"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "13"
  - !!int "2"
  - !!int "10"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+4"
"damage_resistances": "lightning, piercing"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": ""
"cr": "2"
"traits":
  - "desc": "The vegepygmy has advantage on attack rolls against a creature if at\
      \ least one of the vegepygmy's allies is within 5 feet of the creature and the\
      \ ally doesn't have the [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
  - "desc": "The vegepygmy has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks it makes in any terrain with ample obscuring vegetation."
    "name": "Plant Camouflage"
  - "desc": "The vegepygmy regains 5 hit points at the start of its turn. If it takes\
      \ cold, fire, or necrotic damage, this trait doesn't function at the start of\
      \ the vegepygmy's next turn. The vegepygmy dies only if it starts its turn with\
      \ 0 hit points and doesn't regenerate."
    "name": "Regeneration"
  - "desc": "At the start of its turn, the vegepygmy deals 2 (1d4) piercing damage\
      \ to any creature grappling it."
    "name": "Thorny Body"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d8 + 2) piercing damage. If the target is a creature, it must succeed\
      \ on a DC 12 Strength saving throw or have the [prone](3-Mechanics/CLI/rules/conditions.md#Prone)\
      \ condition."
    "name": "Bite"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/plant/token/vegepygmy-thorny-hunter-qftis.webp"
```
^statblock