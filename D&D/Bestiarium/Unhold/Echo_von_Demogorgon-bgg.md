---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Echo of Demogorgon
Status: WIP
linter-yaml-title-alias: Echo of Demogorgon
tags:
  - Monster/Größe/Groß
  - Monster/HG/6
  - Monster/Typ/Unhold/demon
  - Quelle/5e/bgg
aliases:
  - Echo of Demogorgon
---
# [Echo of Demogorgon](3-Mechanics\CLI\bestiary\fiend/echo-of-demogorgon-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 132*  

> [!quote] A quote from Bigby  
> 
> No transformation wrought by the hand (or tentacle, whatever) of a demon lord is rightly understood as a "blessing."

Some legends claim the first ettins were orcs transformed by Demogorgon, the Prince of Demons, while others tie their origin to Grolantor or another god of the Ordning. Whatever the truth of their origin, ettins sometimes recognize a kindred soul in the two-headed Demogorgon and devote themselves to his service. Those who prove exceptionally valuable to Demogorgon's purposes in the Material Plane are rewarded with a "blessing" that transforms them into monstrous echoes of their demon patron.

The arms of an echo of Demogorgon transform into powerful tentacles, and the heads take on a more bestial appearance. The transformation leaves the echo frenzied with rage; the two heads shout and howl at each other with a fury that resounds with demonic magic, sowing discord and confusion around them. As the echo's monstrous heads roar and bite at each other, nearby creatures are racked with psychic pain or join in the ruckus, attacking their allies.

```statblock
"name": "Echo of Demogorgon (BGG)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "typically  Chaotic Evil"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "17"
  - !!int "10"
  - !!int "12"
  - !!int "14"
"speed": "40 ft."
"saves":
  - "strength": !!int "9"
  - "charisma": !!int "5"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+7"
"damage_resistances": "cold, fire, lightning"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 17"
"languages": "Abyssal, Giant, Orc"
"cr": "6"
"traits":
  - "desc": "The echo has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "When one of the echo's heads is asleep, its other head is awake."
    "name": "Wakeful"
"actions":
  - "desc": "The echo makes two Tentacle attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 13\
      \ (2d6 + 6) bludgeoning damage plus 9 (2d8) necrotic damage."
    "name": "Tentacle"
"bonus_actions":
  - "desc": "The echo directs its frenzied howls at one creature it can see within\
      \ 60 feet of itself. The target must succeed on a DC 13 Wisdom saving throw\
      \ or suffer one of the following effects of the echo's choice:\n\n- **Confused\
      \ Reaction.** The target must use its reaction to make a melee attack against\
      \ another creature of the echo's choice that the echo can see.  \n- **Psychic\
      \ Torment.** The target takes 13 (2d12) psychic damage.  "
    "name": "Discordant Screams"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/echo-of-demogorgon-bgg.webp"
```
^statblock