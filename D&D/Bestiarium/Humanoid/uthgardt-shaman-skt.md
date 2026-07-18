---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Uthgardt Shaman
Status: WIP
linter-yaml-title-alias: Uthgardt Shaman
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/2
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/skt
aliases:
  - Uthgardt Shaman
---
# [Uthgardt Shaman](3-Mechanics\CLI\bestiary\humanoid/uthgardt-shaman-skt.md)
*Source: Storm King's Thunder p. 243*  

The Uthgardt are suspicious and resentful of most kinds of magic. Seldom do they choose to become shamans. Instead, the role is thrust upon those who are born with a strong connection to the spirit world. To be a shaman is to stand with one foot in the land of the living and the other in the land of the dead. Those who walk the shadowed path between two lands do so because the spirits of the dead compel them. Other Uthgardt fear and respect a shaman's power.

An Uthgardt shaman must possess a sacred bundle to cast spells. A sacred bundle is made up of sticks, bones, feathers, tufts of fur, and stones that have been "touched" by spirits. It takes a month for a shaman to assemble a sacred bundle, and a shaman can use only one such bundle at a time. A sacred bundle benefits only the shaman who created it, and it doesn't replace the normal components of a spell.

In addition to the spells that all Uthgardt shamans can cast, a shaman of a particular tribe gains additional spells based on tribal affiliation (see the "Uthgardt Sha man Tribal Spells" sidebar).

By communing with their ancestors' spirits, Uthgardt shamans can also learn secret rituals. These rituals almost always require some sort of blood sacrifice, and their effects are usually transformative. For example, some Black Raven shamans know a ritual that allows them to hatch giant ravens from normal raven eggs, and some shamans of the Griffon tribe can transform them selves into griffons by performing a ritual that requires them to drink copious amounts of horse blood.

## Uthgardt Shaman Tribal Spells

Depending on an Uthgardt shaman's tribe, the shaman's Innate Spellcasting feature gains additional spells the shaman can cast once per day.

Black Lion: chill touch, feign death, revivify

Black Raven: animal messenger (raven only), polymorph (self only; into a raven only)

Blue Bear: enhance ability (bear's endurance only), heroism

Elk: find steed (cast as 1 action; elk only), haste

Gray Wolf: beast sense (wolf or dire wolf only), moonbeam, speak with animals (wolf or dire wolf only)

Great Worm: crusader's mantle, hypnotic pattern

Griffon: beast sense (birds only), fly

Sky Pony: gust of wind, witch bolt

Red Tiger: enhance ability (cat's grace only), jump

Thunderbeast: enhance ability (bull's strength only), pass without trace

Tree Ghost: barkskin, speak with plants

```statblock
"name": "Uthgardt Shaman (SKT)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Any alignment"
"ac": !!int "13"
"ac_class": "hide armor"
"hp": !!int "38"
"hit_dice": "7d8 + 7"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "13"
  - !!int "10"
  - !!int "15"
  - !!int "12"
"speed": "30 ft."
"skillsaves":
  - "name": "Medicine"
    "desc": "+4"
  - "name": "Nature"
    "desc": "+4"
  - "name": "Perception"
    "desc": "+4"
  - "name": "Survival"
    "desc": "+6"
"senses": "passive Perception 14"
"languages": "Bothii, Common"
"cr": "2"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if wielded with two hands."
    "name": "Spear"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 80/320 ft., one target. *Hit:*\
      \ 4 (1d6 + 1) piercing damage."
    "name": "Shortbow"
  - "desc": "The shaman casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 12; +4 to hit with spell attacks):\n\n**At will:**\
      \ dancing lights, mage hand, message, thaumaturgy\n\n**1/day each:** augury\
      \ (cast as 1 action), bestow curse, cordon of arrows, detect magic, speak with\
      \ dead, spirit guardians"
    "name": "Spellcasting (Requires a Sacred Bundle)"
"source":
  - "SKT"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/uthgardt-shaman-skt.webp"
```
^statblock