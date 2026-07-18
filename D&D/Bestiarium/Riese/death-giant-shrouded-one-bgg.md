---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Death Giant Shrouded One
Status: WIP
linter-yaml-title-alias: Death Giant Shrouded One
tags:
  - Monster/Größe/Riesig
  - Monster/HG/15
  - Monster/Typ/Riese/wizard
  - Quelle/5e/bgg
aliases:
  - Death Giant Shrouded One
---
# [Death Giant Shrouded One](3-Mechanics\CLI\bestiary\giant/death-giant-shrouded-one-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 127*  

A death giant shrouded one has learned the secrets of death magic—some say from the Raven Queen herself. A shrouded one collects the skulls of fallen kin and inscribes the death rune on a prized skull from this grisly collection. Abandoning armor in favor of gloomy robes, the shrouded one uses rune magic to create a shadowy scythe blade at the end of a staff and to conjure an aura of tormented souls for protection.

## Death Giants

Long ago, a large band of cloud giants traveled to the Shadowfell in search of a way to preserve their collapsing empire. Desperate to save themselves and their way of life, they collectively made a bet with the Raven Queen, a mysterious god of death and memory who dwells on that plane. Accounts of that bet and its outcome vary: some say the Raven Queen answered every riddle the giants posed until the giants collapsed from exhaustion, while others describe a series of increasingly improbable events favoring the Raven Queen in every wager. What is certain is that the giants severely underestimated the Raven Queen. When they lost their wager, the Shadowfell became their home, and they have grudgingly served the Raven Queen ever since.

Over time, the Shadowfell transformed these giants; their bodies shriveled, and their complexions took on a deep-purple hue. They became the first death giants, and their descendants haunt the Shadowfell to this day, searching both that plane and the Material Plane for souls that might please their divine queen.

> [!quote] A quote from Diancastra  
> 
> Most giants know better than to make regular use of the death rune.

> [!quote] A quote from Bigby  
> 
> "Know better"? Perhaps, but there's no denying that death giants can make excellent use of it.

```statblock
"name": "Death Giant Shrouded One (BGG)"
"size": "Huge"
"type": "giant"
"subtype": "wizard"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "195"
"hit_dice": "17d12 + 85"
"modifier": !!int "2"
"stats":
  - !!int "27"
  - !!int "14"
  - !!int "20"
  - !!int "23"
  - !!int "16"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "constitution": !!int "10"
  - "intelligence": !!int "11"
  - "wisdom": !!int "8"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+11"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+8"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
"damage_immunities": "necrotic"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 18"
"languages": "Common, Giant"
"cr": "15"
"traits":
  - "desc": "The giant has a death rune inscribed on a giant's skull in its possession.\
      \ While holding or wearing the skull bearing the rune, the giant can use its\
      \ Reaping Scythe action and Shroud of Souls bonus action.\n\nThe skull bearing\
      \ the death rune has AC 18; 35 hit points; and immunity to necrotic, poison,\
      \ and psychic damage. The skull regains all its hit points at the end of every\
      \ turn, but it turns to dust if reduced to 0 hit points or when the giant dies.\
      \ If the rune is destroyed, the giant can inscribe a death rune on another skull\
      \ in its possession when it finishes a short or long rest."
    "name": "Death Rune"
"actions":
  - "desc": "The giant makes three Soul Burst attacks. Alternatively, if the giant\
      \ has its death rune, it can make three Reaping Scythe attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +11 to hit, reach 10 ft. or range 120\
      \ ft., one target. *Hit:* 28 (4d10 + 6) necrotic damage. If the target has the\
      \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened) condition, the giant\
      \ gains temporary hit points equal to the damage dealt."
    "name": "Soul Burst"
  - "desc": "*Melee Spell Attack:* +11 to hit, reach 15 ft., one creature. *Hit:*\
      \ 38 (7d10) necrotic damage, and the target can't regain hit points until the\
      \ end of its next turn. The target dies if it is reduced to 0 hit points by\
      \ this attack."
    "name": "Reaping Scythe (Requires Death Rune)"
  - "desc": "The giant casts one of the following spells, using Intelligence as the\
      \ spellcasting ability:\n\n**At will:** [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)\n\n**3/day each:**\
      \ [speak with dead](/3-Mechanics/CLI/spells/speak-with-dead-xphb.md), [Tenser's\
      \ floating disk](/3-Mechanics/CLI/spells/tensers-floating-disk-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The giant magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 40 feet to an unoccupied space it can see. Each creature\
      \ within 10 feet of the location the giant left must succeed on a DC 19 Wisdom\
      \ saving throw or have the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition until the end of that creature's next turn."
    "name": "Frightening Teleport (Recharge 4-6)"
  - "desc": "The giant shrouds itself in a torrent of souls. While the giant is shrouded,\
      \ each creature that starts its turn within 5 feet of the giant must succeed\
      \ on a DC 19 Wisdom saving throw or have disadvantage on saving throws until\
      \ the end of that creature's next turn. The shroud disappears after 1 minute,\
      \ when the giant dies, when the giant uses this bonus action again, or when\
      \ the giant's death rune is destroyed."
    "name": "Shroud of Souls (Requires Death Rune)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/giant/token/death-giant-shrouded-one-bgg.webp"
```
^statblock