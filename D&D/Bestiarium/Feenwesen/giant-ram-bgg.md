---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgg
  - Monster/HG/1
  - Monster/Größe/Groß
  - Monster/Typ/Fee
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Giant Ram
---
# [Giant Ram](3-Mechanics\CLI\bestiary\fey/giant-ram-bgg.md)
*Source: Bigby Presents: Glory of the Giants p. 153*  

Giant rams are prized livestock among giants. The rams' fleece stores magical energy by absorbing ambient magic and drawing power from spells. While a ram is alive and unshorn, it uses its fleece's magic for self-defense, channeling the power it absorbs into a magical blast to drive off predators.

If the fleece is shorn from the ram without damaging the creature, it can be made into a protective magical garment. When woven into cloth, the fleece serves as a cloak of protection. It can also be woven into the lining of armor to make armor of resistance that protects against cold, fire, or lightning damage.

```statblock
"name": "Giant Ram (BGG)"
"size": "Large"
"type": "fey"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "28"
"hit_dice": "3d10 + 12"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "12"
  - !!int "18"
  - !!int "3"
  - !!int "14"
  - !!int "10"
"speed": "50 ft."
"damage_resistances": "cold, fire, lightning"
"senses": "passive Perception 12"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The ram has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 9 (2d4\
      \ + 4) bludgeoning damage plus 3 (1d6) force damage. If the ram moved at least\
      \ 20 feet straight toward the target immediately before the hit, the target\
      \ must succeed on a DC 14 Strength saving throw or have the [prone](/3-Mechanics/CLI/conditions.md#Prone)\
      \ condition."
    "name": "Ram"
  - "desc": "*Ranged Spell Attack:* +4 to hit, range 30 ft., one target. *Hit:* 7\
      \ (2d6) force damage."
    "name": "Force Bolt"
"reactions":
  - "desc": "Immediately after the ram succeeds on a saving throw against a spell\
      \ or a spell's attack misses it, the ram can make one Force Bolt attack."
    "name": "Absorbent Fleece (Recharge 6)"
"source":
  - "BGG"
"image": "/3-Mechanics/CLI/bestiary/fey/token/giant-ram-bgg.webp"
```
^statblock