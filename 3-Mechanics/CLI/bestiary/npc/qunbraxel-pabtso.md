---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/pabtso
  - monster/cr/9
  - monster/size/medium
  - monster/type/aberration/mind-flayer
  - monster/type/aberration/warlock
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Qunbraxel
---
# [Qunbraxel](3-Mechanics\CLI\bestiary\npc/qunbraxel-pabtso.md)
*Source: Phandelver and Below: The Shattered Obelisk p. 135*  

Qunbraxel is an arrogant mind flayer warlock. Qunbraxel is always attended by four loyal grimlocks. They swap this duty with other grimlocks nearby, although Qunbraxel can hardly be bothered to tell one grimlock minion from another.

Cut off from any elder brain Qunbraxel considers worthy, the mind flayer hopes to join the Ilvaash fanatics and receive power and insight from the Far Realm.

```statblock
"name": "Qunbraxel (PaBTSO)"
"size": "Medium"
"type": "aberration"
"subtype": "mind flayer, warlock"
"alignment": "Lawful Evil"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md)"
"hp": !!int "112"
"hit_dice": "15d8 + 45"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "14"
  - !!int "17"
  - !!int "19"
  - !!int "15"
  - !!int "19"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "8"
  - "wisdom": !!int "6"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+8"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": "Deep Speech, telepathy 60 ft., Undercommon"
"cr": "9"
"traits":
  - "desc": "Qunbraxel has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Qunbraxel makes two Eldritch Bolt attacks, or one Eldritch Bolt attack\
      \ and one Tentacle attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one creature. *Hit:* 15\
      \ (2d10 + 4) psychic damage. If the target is Medium or smaller, it has the\
      \ [grappled](/3-Mechanics/CLI/conditions.md#Grappled) condition (escape DC 16)\
      \ and must succeed on a DC 16 Intelligence saving throw or have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition until the grapple ends."
    "name": "Tentacle"
  - "desc": "*Ranged Spell Attack:* +8 to hit, range 120 ft., one target. *Hit:* 20\
      \ (3d10 + 4) force damage."
    "name": "Eldritch Bolt"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one Humanoid with the\
      \ [stunned](/3-Mechanics/CLI/conditions.md#Stunned) condition who is [grappled](/3-Mechanics/CLI/conditions.md#Grappled)\
      \ by Qunbraxel. *Hit:* 55 (10d10) piercing damage. If this damage reduces the\
      \ target to 0 hit points, Qunbraxel kills it by extracting and devouring its\
      \ brain."
    "name": "Extract Brain"
  - "desc": "Qunbraxel magically emits psychic energy in a 60-foot cone. Each creature\
      \ in that area must succeed on a DC 16 Intelligence saving throw or take 26\
      \ (5d8 + 4) psychic damage and have the [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ condition for 1 minute. A [stunned](/3-Mechanics/CLI/conditions.md#Stunned)\
      \ creature can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Mind Blast (Recharge 5-6)"
  - "desc": "Qunbraxel casts one of the following spells, requiring no spell components\
      \ and using Charisma as the spellcasting ability (spell save DC 16):\n\n**At\
      \ will:** [detect magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md), [detect\
      \ thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [levitate](/3-Mechanics/CLI/spells/levitate-xphb.md),\
      \ [mage armor](/3-Mechanics/CLI/spells/mage-armor-xphb.md) (self only), [mage\
      \ hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md) (the hand is invisible),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**2/day\
      \ each:** [confusion](/3-Mechanics/CLI/spells/confusion-xphb.md), [sending](/3-Mechanics/CLI/spells/sending-xphb.md),\
      \ [telekinesis](/3-Mechanics/CLI/spells/telekinesis-xphb.md)\n\n**1/day each:**\
      \ [dominate monster](/3-Mechanics/CLI/spells/dominate-monster-xphb.md), [plane\
      \ shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md) (self only)"
    "name": "Spellcasting (Psionics)"
"source":
  - "PaBTSO"
"image": "/3-Mechanics/CLI/bestiary/npc/token/qunbraxel-pabtso.webp"
```
^statblock