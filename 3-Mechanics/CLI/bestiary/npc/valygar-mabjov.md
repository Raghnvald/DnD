---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Valygar"
---
# [Valygar](3-Mechanics/CLI/bestiary/npc/valygar-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 36*  

> [!quote] A quote from MINSC & BOO!  
> 
> Valygar is a grumpy one, but me and him agree on most things, including that Red Wizards need to have their big, stupid brains kicked right up their backsides.

Valygar Corthola is a ranger who was born into a wealthy family of powerful wizards. Many members of the Corthala bloodline have demonstrated magical aptitude and skill throughout its generations, and his ancestors include Lavok Corthala, a legendary necromancer.

Valygar's own mother was a mage who suffered from mental health issues, like many in her family. Valygar believed this affliction to be the result of her arcane practices. She spent much of the family's wealth on magical items to the point of obsession and wholly neglected her son and husband.

When Valygar's father died his mother was distraught. In her despair, she raised her partner as a zombie and underwent the process of becoming undead herself. Ultimately, Valygar slew both of his parents, a deed he felt he was compelled to carry out.

Convinced the family's obsessive pursuit of the arcane arts had corrupted and destroyed all he loved, Valygar grew to hate and despise those who used magic. Turning his back on his family legacy, he now specializes in hunting wizards and other magic users to rid the world of their evil practices.

He found that his skills and values were a good match for the monks of Candlekeep. Candlekeep's pursuit of ancient texts means that Valygar often comes into conflict with evil magic users.

While Valygar appears to be a man in his 50s, he is over a century in age. Normally Valygar turns his back on magical items, but he has made an exception for potions of longevity in order to reduce his physical age and continue his obsessive hunt of evil wizards. While the potions make his body younger, they have no effect on his lifespan and thus Valygar knows that death could come for him at any moment.

## Valygar as a Contact

Valygar is the primary contact for Candlekeep at low levels. Valygar can provide you with basic training for new languages and skills (this time is considered downtime), along with books that you can utilize to continue the training on your own.

**Basic Training with Valygar**

| Training | Downtime | Total Time | Cost |
|----------|----------|------------|------|
| Switching a skill | 1 day | 10 days | 100 gp |
| New tool proficiency | 5 days | 40 days | 400 gp |
| New language | 5 days | 40 days | 250 gp |
^basic-training-with-valygar

```statblock
"name": "Valygar (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Good"
"ac": !!int "17"
"ac_class": "[half plate](3-Mechanics/CLI/items/half-plate-armor.md)"
"hp": !!int "187"
"hit_dice": "25d8 + 75"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "18"
  - !!int "16"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "6"
  - "dexterity": !!int "8"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+4"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+4"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"gear":
  - "[hand crossbow](3-Mechanics/CLI/items/hand-crossbow.md)"
"senses": "passive Perception 14"
"languages": "Common, Draconic, Primordial"
"cr": "9"
"traits":
  - "desc": "Valygar has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "When Valygar deals damage to a creature that is [concentrating](3-Mechanics/CLI/rules/conditions.md#Concentration)\
      \ on a spell, that creature has disadvantage on the saving throw it makes to\
      \ maintain its [concentration](3-Mechanics/CLI/rules/conditions.md#Concentration)."
    "name": "Mage Slaying"
"actions":
  - "desc": "Valygar makes two Katana attacks and one Hand Crossbow attack or he makes\
      \ two Hand Crossbow attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, or 9 (1d10 + 4) slashing damage if used with\
      \ two hands plus 13 (3d8) poison damage."
    "name": "Katana"
  - "desc": "*Ranged Weapon Attack:* +8 to hit, range 30/120 ft., one target. *Hit:*\
      \ 7 (1d6 + 4) piercing damage."
    "name": "Hand Crossbow"
"bonus_actions":
  - "desc": "While in dim light or darkness, Valygar can take the [Hide](3-Mechanics/CLI/rules/actions.md#Hide)\
      \ action as a bonus action."
    "name": "Shadow Stealth"
"reactions":
  - "desc": "When a creature within 5 feet of Valygar casts a spell, he can use his\
      \ reaction to make a melee weapon attack against that creature."
    "name": "Disrupt Spell"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/valygar-mabjov.webp"
```
^statblock