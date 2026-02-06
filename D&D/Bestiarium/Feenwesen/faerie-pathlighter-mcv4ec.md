---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mcv4ec
  - Monster/HG/2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Fee
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Faerie Pathlighter
---
# [Faerie Pathlighter](3-Mechanics\CLI\bestiary\fey/faerie-pathlighter-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Faerie pathlighters pry into human lives, sometimes to help (like a classic fairy godparent) and sometimes to harm. In the wilds of Eldraine, faerie pathlighters often serve as protectors for the lost, the glow of their guiding lanterns leading weary travelers to respite.

A faerie pathlighter has an almost angelic appearance. Their large, white wings become more translucent toward the edges. Motes of magical light drift around their heads, and a faint white aura surrounds their bodies.

> [!quote]  
> 
> For good or ill, most fae can't resist meddling in the adventures of any knight they meet.

## Faeries

The faeries of Eldraine are winged, elfin creatures similar to sprites or pixies. Unpredictable, unreliable, and amoral, they lurk in the wilds and harass travelers they perceive as intruders.

> [!note] Ouphes
> 
> Ouphes are curious creatures found throughout the wilds of Eldraine. While often seen as foolish, ouphes are magically connected to the natural world and know more about the secret lives of trees, mushrooms, and moss than most mortals. While ouphes are related to Eldraine's faeries, the faeries treat them like distant (and somewhat embarrassing) cousins. Ouphes can be represented with the stat blocks for pixies or sprites.
^ouphes

```statblock
"name": "Faerie Pathlighter (MCV4EC)"
"size": "Medium"
"type": "fey"
"alignment": "typically  Chaotic Good"
"ac": !!int "12"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "2"
"stats":
  - !!int "10"
  - !!int "14"
  - !!int "12"
  - !!int "13"
  - !!int "17"
  - !!int "18"
"speed": "30 ft., fly 30 ft. (hover)"
"skillsaves":
  - "name": "Insight"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+5"
  - "name": "Survival"
    "desc": "+5"
"senses": "passive Perception 15"
"languages": "Common, Sylvan"
"cr": "2"
"traits":
  - "desc": "The faerie sheds dim light in a 15-foot radius."
    "name": "Faerie Illumination"
"actions":
  - "desc": "The faerie makes two Shining Strike attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +6 to hit, reach 5 ft. or range 30 ft.,\
      \ one target. *Hit:* 7 (2d6) radiant damage, and if the target is a creature,\
      \ it must succeed on a DC 14 Dexterity saving throw or be wreathed in light\
      \ until the end of the faerie's next turn. While a creature is wreathed in light,\
      \ attack rolls against the creature have advantage, and the creature can't benefit\
      \ from the invisible condition."
    "name": "Shining Strike"
  - "desc": "The faerie casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability:\n\n**At will:** dancing lights,\
      \ detect magic, prestidigitation\n\n**1/day:** locate creature"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The faerie summons a 30-foot-radius sphere of magical light centered\
      \ on itself, which lasts for 1 minute or until the faerie has the incapacitated\
      \ condition. Each creature of the faerie's choice (other than the faerie) that\
      \ starts its turn in that area gains 5 temporary hit points and has advantage\
      \ on Wisdom saving throws and Wisdom checks until the start of its next turn.\n\
      \nThe sphere is bright light, sheds dim light for an additional 30 feet, and\
      \ moves with the faerie. If any of the sphere's area overlaps with an area of\
      \ darkness created by a spell of 3rd level or lower, the spell that created\
      \ the darkness is dispelled."
    "name": "Guiding Light (2/Day)"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/fey/token/faerie-pathlighter-mcv4ec.webp"
```
^statblock