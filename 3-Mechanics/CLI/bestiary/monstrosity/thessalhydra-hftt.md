---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/hftt
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Thessalhydra"
---
# [Thessalhydra](3-Mechanics/CLI/bestiary/monstrosity/thessalhydra-hftt.md)
*Source: Hunt for the Thessalhydra p. 41*  

The thessalhydra is a strange and terrible creature with eight heads surrounding a large, circular mouth rimmed with jagged teeth. Its maw drips with acid, and its tail ends with a pair of sharp pincers. The thessalhydra is gluttonous and damaging to any environment.

```statblock
"name": "Thessalhydra (HftT)"
"size": "Huge"
"type": "monstrosity"
"alignment": "Unaligned"
"ac": !!int "14"
"ac_class": "natural armor"
"hp": !!int "69"
"hit_dice": "6d12 + 30"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "12"
  - !!int "20"
  - !!int "5"
  - !!int "10"
  - !!int "7"
"speed": "30 ft., swim 30 ft."
"skillsaves":
  - "name": "Perception"
    "desc": "+4"
"damage_immunities": "acid"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed),\
  \ [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [stunned](3-Mechanics/CLI/rules/conditions.md#Stunned)"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": ""
"cr": "4"
"actions":
  - "desc": "The thessalhydra makes one maw attack and one Flurry of Bites."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 7 (1d6 + 4) piercing damage plus 10 (4d4) poison damage."
    "name": "Flurry of Bites"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d10 + 4) piercing damage plus 5 (1d10) acid damage."
    "name": "Maw"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 10 (1d12 + 4) slashing damage, and the target is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled).\
      \ As an action, the target can escape the grapple by succeeding on a DC 14 Strength\
      \ (Athletics) or Dexterity (Acrobatics) check (its choice). Until this grapple\
      \ ends, the thessalhydra can't use its tail pincer."
    "name": "Tail Pincer"
  - "desc": "The thessalhydra spits a glob of acid at a point it can see within 30\
      \ feet of it. Each creature within 10 feet of that point must make a DC 15 Dexterity\
      \ saving throw, taking 18 (4d8) acid damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Acid Saliva (Recharge 5-6)"
"legendary_description": "Legendary Action Uses: 2. Immediately after another creature's\
  \ turn, the thessalhydra can expend a use to take one of the following actions.\
  \ The thessalhydra regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The thessalhydra makes a Wisdom (Perception) check with advantage."
    "name": "Detect"
  - "desc": "The thessalhydra makes a tail pincer attack."
    "name": "Tail Swipe"
"source":
  - "HftT"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/thessalhydra-hftt.webp"
```
^statblock