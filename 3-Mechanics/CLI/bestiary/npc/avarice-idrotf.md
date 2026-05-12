---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/idrotf
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/tiefling
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Avarice"
---
# [Avarice](3-Mechanics/CLI/bestiary/npc/avarice-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 269*  

Avarice is a cruel and vindictive tiefling trained in the arcane tradition of evocation. She likes using her magic to destroy things, and her hunger for magic items knows no bounds. Her supreme confidence means that she never backs down from a challenge, even when the odds are clearly stacked against her. Seeing other wizards as a threat, paranoia rules her life.

Avarice has been a member of the Arcane Brotherhood for almost two years. She fantasizes about rising to fame and prominence in record time and hopes that plundering the lost Netherese city of Ythryn will turn her fantasies into reality.

The tiefling has the secret support of the archdevil Levistus, having traded her soul years ago for her first taste of magical power. Levistus speaks to her in dreams and guides her path. Shortly after Avarice arrived in Ten-Towns, Levistus urged her to seek out the Black Sword. Avarice didn't know who or what the Black Sword was until she was approached by cultists of Levistus bearing swordlike shards of chardalyn worn as pendants around their necks. These self-styled Knights of the Black Sword offered her sanctuary in the keep of Caer-Dineval, where they are based. Although she doesn't trust the cultists, they treat her with more respect than anyone else does, and the keep is a safer location than most other places in Ten-Towns.

## Companions

Avarice has a pair of loyal [gargoyles](3-Mechanics/CLI/bestiary/elemental/gargoyle.md) named Gargle and Gurgle who serve her as bodyguards and scouts. Avarice uses her [Rary's telepathic bond](3-Mechanics/CLI/spells/rarys-telepathic-bond.md) spell to stay in telepathic contact with her gargoyles before sending them off on any mission. Avarice also has the support of the Knights of the Black Sword, if she needs to call on their talents.

## Familiar

Avarice's familiar throughout the adventure is a squawking raven named Skelm. It uses the [raven](3-Mechanics/CLI/bestiary/beast/raven.md) stat block in the "Monster Manual" but is a fiend instead of a beast.

## Spellbook

Avarice's spellbook has white leather covers and vellum pages. The tiefling's personal sigil is burned into the front cover. The book contains the spells Avarice has prepared plus the following additional spells: [burning hands](3-Mechanics/CLI/spells/burning-hands.md), [cone of cold](3-Mechanics/CLI/spells/cone-of-cold.md), [find familiar](3-Mechanics/CLI/spells/find-familiar.md), [ice storm](3-Mechanics/CLI/spells/ice-storm.md), [lightning bolt](3-Mechanics/CLI/spells/lightning-bolt.md), [rope trick](3-Mechanics/CLI/spells/rope-trick.md), [thunderwave](3-Mechanics/CLI/spells/thunderwave.md), [tongues](3-Mechanics/CLI/spells/tongues.md), [wall of fire](3-Mechanics/CLI/spells/wall-of-fire.md), and [wall of force](3-Mechanics/CLI/spells/wall-of-force.md).

```statblock
"name": "Avarice (IDRotF)"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Lawful Evil"
"ac": !!int "13"
"hp": !!int "84"
"hit_dice": "13d8 + 26"
"modifier": !!int "3"
"stats":
  - !!int "8"
  - !!int "16"
  - !!int "14"
  - !!int "17"
  - !!int "10"
  - !!int "9"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+6"
"damage_resistances": "cold, fire"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common, Draconic, Infernal, Orc, Yeti"
"cr": "7"
"traits":
  - "desc": "Avarice is a 10th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 14; +6 to hit with spell attacks). She has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md)\
      \ (see \"Actions\" below), [mage hand](3-Mechanics/CLI/spells/mage-hand.md),\
      \ [message](3-Mechanics/CLI/spells/message.md), [minor illusion](3-Mechanics/CLI/spells/minor-illusion.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\n**1st level\
      \ (4 slots):** [detect magic](3-Mechanics/CLI/spells/detect-magic.md), [mage\
      \ armor](3-Mechanics/CLI/spells/mage-armor.md), [magic missile](3-Mechanics/CLI/spells/magic-missile.md)\n\
      \n**2nd level (3 slots):** [flaming sphere](3-Mechanics/CLI/spells/flaming-sphere.md),\
      \ [knock](3-Mechanics/CLI/spells/knock.md), [scorching ray](3-Mechanics/CLI/spells/scorching-ray.md)\n\
      \n**3rd level (3 slots):** [counterspell](3-Mechanics/CLI/spells/counterspell.md),\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md), [fly](3-Mechanics/CLI/spells/fly.md)\n\
      \n**4th level (3 slots):** [banishment](3-Mechanics/CLI/spells/banishment.md),\
      \ [fire shield](3-Mechanics/CLI/spells/fire-shield.md)\n\n**5th level (2 slots):**\
      \ [Bigby's hand](3-Mechanics/CLI/spells/bigbys-hand.md), [Rary's telepathic\
      \ bond](3-Mechanics/CLI/spells/rarys-telepathic-bond.md)"
    "name": "Spellcasting"
  - "desc": "When Avarice dies, her corpse freezes for 9 days, during which time it\
      \ can't be thawed, harmed by fire, animated, or raised from the dead."
    "name": "Icy Doom"
  - "desc": "Avarice wields a staff of frost with 10 charges (see \"Actions\" below)."
    "name": "Special Equipment"
"actions":
  - "desc": "*Ranged Spell Attack:* +6 to hit, range 120 ft., one target. *Hit:*\
      \ 11 (2d10) fire damage."
    "name": "Fire Bolt (Cantrip)"
  - "desc": "While holding this staff, Avarice can expend 1 or more of its charges\
      \ to cast one of the following spells from it (spell save DC 14): [cone of cold](3-Mechanics/CLI/spells/cone-of-cold.md)\
      \ (5 charges), [fog cloud](3-Mechanics/CLI/spells/fog-cloud.md) (1 charge),\
      \ [ice storm](3-Mechanics/CLI/spells/ice-storm.md) (4 charges), or [wall of\
      \ ice](3-Mechanics/CLI/spells/wall-of-ice.md) (4 charges). The staff regains\
      \ 1d6 + 4 charges daily at dawn. If its last charge is expended, roll a d20;\
      \ on a 1, the staff turns to water and is destroyed."
    "name": "Staff of Frost"
"reactions":
  - "desc": "When Avarice is damaged by a creature that she can see within 60 feet\
      \ of her, she can banish that creature to a frigid extradimensional prison for\
      \ 1 minute. While there, the creature is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ and takes 5 (1d10) cold damage at the start of each of its turns. At the\
      \ end of each of its turns, the creature can make a DC 14 Charisma saving throw,\
      \ escaping the prison on a success and reappearing in the space it left or in\
      \ the nearest unoccupied space if that space is occupied. A creature that dies\
      \ in the prison is trapped there indefinitely."
    "name": "Banishing Rebuke (Recharges after a Long Rest)"
"source":
  - "IDRotF"
"image": "3-Mechanics/CLI/bestiary/npc/token/avarice-idrotf.webp"
```
^statblock