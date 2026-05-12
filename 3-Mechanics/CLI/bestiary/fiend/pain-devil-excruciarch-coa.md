---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/12
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pain Devil (Excruciarch)"
---
# [Pain Devil (Excruciarch)](3-Mechanics/CLI/bestiary/fiend/pain-devil-excruciarch-coa.md)
*Source: Chains of Asmodeus p. 249*  

Another type of devil devoted to torture, excruciarchs are also competent fighters and mercenaries. Due to their reputation as torturers of devils, they're often looked down upon by other devils, occasionally even beaten or killed, and as a result they frequently travel together. Their cruelty is known across the Nine Hells, and their revelry in pain gives them their name. Another defining feature of pain devils is their greed: they serve no particular master, their loyalty must be purchased.

## Masked Devils

Excruciarchs appear almost humanoid in size and shape. Their skin is usually pale shades of white or red, and hair doesn't grow anywhere on their body. To conceal their identity and lend themselves some form of protection, almost all pain devils wear masks made from various types of leather, often adorned with spikes, horns, or ridges.

## Devoted to Pain

When an excruciarch enters battle, they activate a unique ability to inflict pain upon their adversaries. Excruciarchs thrive on even their own pain and they almost always fight to the death.

```statblock
"name": "Pain Devil (Excruciarch) (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "171"
"hit_dice": "18d8 + 90"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "20"
  - !!int "11"
  - !!int "10"
  - !!int "13"
"speed": "30 ft."
"saves":
  - "strength": !!int "8"
  - "constitution": !!int "9"
"skillsaves":
  - "name": "Deception"
    "desc": "+5"
  - "name": "Insight"
    "desc": "+4"
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+4"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "poisoned"
"senses": "darkvision 120 ft., passive Perception 14"
"languages": "Celestial, Common, Infernal, telepathy 120 ft."
"cr": "12"
"traits":
  - "desc": "Any creature hostile to the excruciarch that starts its turn within 20\
      \ feet of the excruciarch takes 10 (4d4) slashing damage, unless the excruciarch\
      \ is incapacitated."
    "name": "Aura of Torment"
  - "desc": "Magical darkness doesn't impede the excruciarch's darkvision."
    "name": "Devil's Sight"
  - "desc": "The excruciarch has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The excruciarch gains a +1 bonus to attack and damage rolls for each\
      \ creature it damaged on its previous turn."
    "name": "Sadism"
"actions":
  - "desc": "The excruciarch makes two Scourge attacks. It can replace one of the\
      \ attacks with Storm of Steel (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 10 ft., one target. *Hit:*\
      \ 13 (2d8 + 4) bludgeoning damage plus 13 (2d8 + 4) slashing damage."
    "name": "Scourge"
  - "desc": "The excruciarch swings its scourge wildly around itself. All creatures\
      \ within 15 feet of the excruciarch must make a DC 16 Dexterity saving throw.\
      \ Targets take 31 (6d8 + 4) slashing damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Storm of Steel (Recharge 4-6)"
"reactions":
  - "desc": "As a reaction to a creature resisting damage dealt by the excruciarch,\
      \ it turns its gaze on that creature, negating any resistances and immunities\
      \ that creature has until the start of the excruciarch's next turn."
    "name": "Vulnerable Gaze"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/pain-devil-excruciarch-coa.webp"
```
^statblock