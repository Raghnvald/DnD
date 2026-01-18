---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/idrotf
  - Monster/HG/5
  - Monster/Größe/Groß
  - Monster/Typ/Monstrosität/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Spitting Mimic
---
# [Spitting Mimic](3-Mechanics\CLI\bestiary\monstrosity/spitting-mimic-idrotf.md)
*Source: Icewind Dale: Rime of the Frostmaiden p. 302*  

Mimics are shape-shifting monsters described in the *Monster Manual*. The variant presented here is a particularly large and voracious specimen—the result of Netherese experiments on ordinary mimics—that spits acid.

```statblock
"name": "Spitting Mimic (IDRotF)"
"size": "Large"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "85"
"hit_dice": "10d10 + 30"
"modifier": !!int "1"
"stats":
  - !!int "21"
  - !!int "12"
  - !!int "17"
  - !!int "9"
  - !!int "15"
  - !!int "10"
"speed": "20 ft."
"skillsaves":
  - "name": "Stealth"
    "desc": "+7"
"damage_immunities": "acid"
"condition_immunities": "prone"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": ""
"cr": "5"
"traits":
  - "desc": "The mimic can use its action to polymorph into an object or back into\
      \ its true, amorphous form. Its statistics are the same in each form. Any equipment\
      \ it is wearing or carrying isn't transformed. It reverts to its true form if\
      \ it dies."
    "name": "Shapechanger"
  - "desc": "The mimic adheres to anything that touches it. A Huge or smaller creature\
      \ adhered to the mimic is also grappled by it (escape DC 16). Ability checks\
      \ made to escape this grapple have disadvantage."
    "name": "Adhesive (Object Form Only)"
  - "desc": "While the mimic remains motionless, it is indistinguishable from an ordinary\
      \ object."
    "name": "False Appearance (Object Form Only)"
  - "desc": "The mimic has advantage on attack rolls against any creature grappled\
      \ by it."
    "name": "Grappler"
  - "desc": "The mimic has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The mimic attacks three times: twice with its pseudopods and once with\
      \ its bite."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:* 10\
      \ (1d10 + 5) bludgeoning damage. If the mimic is in object form, the target\
      \ is subjected to its Adhesive trait."
    "name": "Pseudopods"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one creature. *Hit:* 10\
      \ (1d10 + 5) piercing damage plus 7 (2d6) acid damage."
    "name": "Bite"
  - "desc": "The mimic spits acid at one creature it can see within 30 feet of it.\
      \ The target must make a DC 14 Dexterity saving throw, taking 32 (9d6 + 1) acid\
      \ damage on failed save, or half as much damage on a successful one."
    "name": "Spit Acid (Recharge 5-6)"
"source":
  - "IDRotF"
"image": "/3-Mechanics/CLI/bestiary/monstrosity/token/spitting-mimic-idrotf.webp"
```
^statblock