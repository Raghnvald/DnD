---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Coldlight Walker
Status: WIP
linter-yaml-title-alias: Coldlight Walker
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/Untote
  - Quelle/5e/idrotf
aliases:
  - Coldlight Walker
---
# [Coldlight Walker](3-Mechanics\CLI\bestiary\undead/coldlight-walker-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 284*  

Some humanoids who died from extreme cold but whose spirits languish in the mortal world become coldlight walkers, burning with frigid fury at the meaninglessness of life. Their frostbitten corpses emit a spectral light so intense that mortal eyes can barely stand to look at them. They typically wear the clothing in which they died.

## God-Spawned Horrors

Gods that personify winter create coldlight walkers as embodiments of winter's wrath. These hateful spirits that were denied passage to the afterlife are preserved in their current forms to remind the living how fragile life can be.

When a coldlight walker dies, its light goes out, leaving behind a frozen, inanimate corpse that can never be raised from the dead.

```statblock
"name": "Coldlight Walker (IDRotF)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "0"
"stats":
  - !!int "15"
  - !!int "10"
  - !!int "17"
  - !!int "8"
  - !!int "10"
  - !!int "8"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "2"
  - "wisdom": !!int "3"
"damage_immunities": "cold"
"condition_immunities": "blinded, charmed, exhaustion, paralyzed, petrified, poisoned"
"senses": "darkvision 60 ft., passive Perception 10"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The walker sheds bright light in a 20-foot radius and dim light for an\
      \ additional 20 feet. As a bonus action, the walker can target one creature\
      \ in its bright light that it can see and force it to succeed on a DC 14 Constitution\
      \ saving throw or be blinded until the start of the walker's next turn."
    "name": "Blinding Light"
  - "desc": "Any creature killed by the walker freezes for 9 days, during which time\
      \ it can't be thawed, harmed by fire, animated, or raised from the dead."
    "name": "Icy Doom"
  - "desc": "The walker doesn't require air, food, drink, or sleep."
    "name": "Unusual Nature"
"actions":
  - "desc": "The walker makes two attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d8 + 2) bludgeoning damage plus 14 (4d6) cold damage."
    "name": "Slam"
  - "desc": "*Ranged Spell Attack:* +3 to hit, range 60 ft., one target. *Hit:* 25\
      \ (4d10 + 3) cold damage."
    "name": "Cold Ray"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/undead/token/coldlight-walker-idrotf.webp"
```
^statblock