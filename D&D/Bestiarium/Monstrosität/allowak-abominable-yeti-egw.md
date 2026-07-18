---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Allowak Abominable Yeti
Kategorie: Monstrosität
Größe: Riesig
HG: "9"
Habitat:
  - /
Image: token/allowak-abominable-yeti-egw.webp
Status: WIP
linter-yaml-title-alias: Allowak Abominable Yeti
tags:
  - Monster/Größe/Riesig
  - Monster/HG/9
  - Monster/Typ/Monstrosität
  - Quelle/5e/egw
aliases:
  - Allowak Abominable Yeti
status: WIP
---
# [Allowak Abominable Yeti](3-Mechanics\CLI\bestiary\monstrosity/allowak-abominable-yeti-egw.md)
*Source: Explorer's Guide to Wildemount p. 126*  

A yeti's windborne howl sounds out across remote mountains, striking fear into the hearts of the scattered miners and herders that dwell there. These hulking creatures stalk alpine peaks in a ceaseless hunt for food. Their snow-white fur lets them move like ghosts against the frozen landscape. A yeti's icy simian eyes can freeze its prey in place.

When Aeor fell into Foren, the impact threw a monolithic, purple crystal miles away from the crash site. The stone pierced the body of an abominable yeti named Allowak, but the crystal's magic preserved the yeti's corpse and absorbed Allowak's soul. When other yetis touched the crystal, their intellect increased and their innate desire to slaughter faded away. A society of the monstrosities living in huts and keeping mammoths for food sprung up around the crystal. These peaceful yetis abhor their more savage kin.

## A Secret Place

The yetis of Allowak's Sanctuary keep their home a secret, for they worry that outsiders might try to steal the crystal. Although the crystal's effects seem permanent, the yetis fear that if it were removed from Allowak's remains, they would lose their newfound intelligence. If outsiders get close to the village, the yetis patrolling the village's borders approach and act like the more common and savage members of their species. The yetis of Allowak's Sanctuary do not kill unless forced to, but they will cause injury to guard their secret.

In recent years, the yetis have acquired books and journals from explorers who died close to their camp. The tomes gave the yetis an understanding of the world beyond Eiselcross.

```statblock
"name": "Allowak Abominable Yeti (EGW)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Neutral"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "137"
"hit_dice": "11d12 + 66"
"modifier": !!int "0"
"stats":
  - !!int "24"
  - !!int "10"
  - !!int "22"
  - !!int "16"
  - !!int "13"
  - !!int "10"
"speed": "40 ft., climb 40 ft."
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+4"
"damage_immunities": "cold"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": "Common, Yeti"
"cr": "9"
"traits":
  - "desc": "If the yeti takes fire damage, it has disadvantage on attack rolls and\
      \ ability checks until the end of its next turn."
    "name": "Fear of Fire"
  - "desc": "The yeti has advantage on Wisdom ([Perception](/3-Mechanics/CLI/skills.md#Perception))\
      \ checks that rely on smell."
    "name": "Keen Smell"
  - "desc": "The yeti has advantage on Dexterity ([Stealth](/3-Mechanics/CLI/skills.md#Stealth))\
      \ checks made to hide in snowy terrain."
    "name": "Snow Camouflage"
"actions":
  - "desc": "The yeti can use its Chilling Gaze and makes two claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d6 + 7) slashing damage plus 7 (2d6) cold damage."
    "name": "Claw"
  - "desc": "The yeti targets one creature it can see within 30 feet of it. If the\
      \ target can see the yeti, the target must succeed on a DC 18 Constitution saving\
      \ throw against this magic or take 21 (6d6) cold damage and then be [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ for 1 minute, unless it is immune to cold damage. The target can repeat the\
      \ saving throw at the end of each of its turns, ending the effect on itself\
      \ on a success. If the target's saving throw is successful, or if the effect\
      \ ends on it, the target is immune to this yeti's gaze for 1 hour."
    "name": "Chilling Gaze"
  - "desc": "The yeti exhales a 30-foot cone of frigid air. Each creature in that\
      \ area must make a DC 18 Constitution saving throw, taking 45 (10d8) cold damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Cold Breath (Recharge 6)"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/allowak-abominable-yeti-egw.webp"
```
^statblock