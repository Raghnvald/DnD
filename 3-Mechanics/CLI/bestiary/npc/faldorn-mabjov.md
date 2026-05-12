---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Faldorn"
---
# [Faldorn](3-Mechanics/CLI/bestiary/npc/faldorn-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 50*  

Faldorn is a human druid who is secretly a Shadow Master, one of the leaders of a militant sect of druids called the Shadow Druids. She is a devout follower of the beliefs of the Shadow Druids, believing that civilization is a cancer that threatens to make all the mortal races into weaklings.

Faldorn was born into the Black Raven Uthgardt tribe of the North. Her tribe resided within the Spine of the World, an icy mountain range in far northwest Faerûn. As an infant, Faldorn was offered to a Shadow Druid enclave and was later inducted into their ranks. Never knowing any other family, she grew to become a fervent worshipper of nature and the Shadow Druid's tenets. Over the decades, Faldorn rose through the ranks of her order until she eventually claimed leadership in a battle with the former Shadow Master. She returned to her Uthgardt tribe for a few years to take a husband, but abandoned him and the son that they had together after a few years.

Recently, Faldorn has taken it upon herself to infiltrate the Emerald Enclave. She joined the order and quickly rose through the ranks to become a Hierophant. She now is biding her time for one of the three members of the Elder Circle to die, so that she can take their place. Once she is a member of the Elder Circle, it will be easy for her to subvert the Emerald Enclave to do the bidding of the Shadow Druids. Her only worry is one of her former henchmen, an elven ranger named Kivan. He knows of her connections to the Shadow Druids and could potentially out her to the Elder Circle.

Faldorn is usually accompanied by corrupted fey creatures known as hamadryads. She claims that she is the only one willing to take in these sad creatures cast aside by nature.

## Faldorn as a Contact

Faldorn becomes available as a contact for the Emerald Enclave at 7th level. Faldorn can give you a small magic item that can be used to summon a powerful ally that will help you for 24 hours. You must use the item as described below to summon the ally. When the ally is summoned you must use an action and succeed at a [Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion) check to convince it to help you. Faldorn gives these items for free, but she only grants each item once.

**Summoning Allies with Faldorn**

| Item Required | Required Level | Activation | Summoned Ally | Persuasion Check DC |
|---------------|----------------|------------|---------------|---------------------|
| Magical acorn | 7 | Plant it in the ground with an action | In one round the acorn grows into an awakened tree | 10 |
| Apple | 8 | Eat the apply and spit out the seeds with an action | The seeds transform into `1d4` hamadryads | 10 |
| Decanter of oil | 9 | Use an action to burn the body of a beast killed only 1 minute earlier with the oil from the decanter | A salamander bursts from the body | 15 |
| Crown of thorns | 10 | Succeed with an attack roll to place the crown of thorns on a humanoid of CR 5 or less | The humanoid permanently transforms into a shambling mound | 15 |
| Bone Knife | 11 | Use the knife to cut out the heart of a dragon slain within 8 hours | The heart transforms into a wyvern | 10 |
| Vial of tree sap | 12 | Succeed with an attack roll to pour the sap on a Plant creature of CR 5 or less | The plant creature transforms into a treant with an evil alignment | 15 |
^summoning-allies-with-faldorn

```statblock
"name": "Faldorn (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "11"
"ac_class": "16 with [barkskin](3-Mechanics/CLI/spells/barkskin.md)"
"hp": !!int "130"
"hit_dice": "20d8 + 40"
"modifier": !!int "1"
"stats":
  - !!int "12"
  - !!int "12"
  - !!int "14"
  - !!int "12"
  - !!int "20"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+10"
  - "name": "[Nature](3-Mechanics/CLI/rules/skills.md#Nature)"
    "desc": "+11"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+10"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+15"
"senses": "passive Perception 20"
"languages": "Common, Druidic, Elvish, Sylvan"
"cr": "13"
"traits":
  - "desc": "This staff can be wielded as a magic quarterstaff that grants a +2 bonus\
      \ to attack and damage rolls made with it and grants Faldorn a +2 bonus to spell\
      \ attack rolls (already factored into Faldorn's attacks). The staff has 10 charges.\
      \ It regains 1d6 + 4 expended charges each dawn. Faldorn can use an action\
      \ to expend 1 or more of the staff's charges to cast one of the following spells\
      \ from it, with a spell save DC of 14:\n\n- 0 charges: [pass without trace](3-Mechanics/CLI/spells/pass-without-trace.md)\
      \  \n- 1 charge each: [animal friendship](3-Mechanics/CLI/spells/animal-friendship.md),\
      \ [speak with animals](3-Mechanics/CLI/spells/speak-with-animals.md)  \n- 2\
      \ charges each: [barkskin](3-Mechanics/CLI/spells/barkskin.md), [locate animals\
      \ or plants](3-Mechanics/CLI/spells/locate-animals-or-plants.md)  \n- 3 charges:\
      \ [speak with plants](3-Mechanics/CLI/spells/speak-with-plants.md)  \n- 5 charges:\
      \ [awaken](3-Mechanics/CLI/spells/awaken.md)  \n- 6 charges: [wall of thorns](3-Mechanics/CLI/spells/wall-of-thorns.md)\
      \  "
    "name": "Staff of the Woodlands"
"actions":
  - "desc": "Faldorn makes two Staff of the Woodlands attacks and uses Spellcasting.\
      \ Or she uses Spellcasting and then Change Shape if available."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) bludgeoning damage, or 7 (1d8 + 3) bludgeoning damage if wielded\
      \ with two hands plus 7 (2d6) acid damage."
    "name": "Staff of the Woodlands"
  - "desc": "A beam of dim light emerges from Faldorn in a 5-foot-wide, 300-foot-long\
      \ line. Each creature in the line must make a Constitution saving throw. On\
      \ a failed save, a creature takes 27 (6d8) radiant damage and is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ until Faldorn's next turn. On a successful save, it takes half as much damage\
      \ and isn't [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)."
    "name": "Shadowlight (Recharge 6)"
  - "desc": "Faldorn magically polymorphs into a Beast or Elemental with a challenge\
      \ rating of 6 or less, and can remain in this form for up to 9 hours. Faldorn\
      \ reverts to her true form if she dies or falls [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious).\
      \ She can revert to her true form using a bonus action on her turn. While in\
      \ a new form, Faldorn retains her game statistics and ability to speak, but\
      \ her AC, movement modes, Strength, and Dexterity are replaced by those of the\
      \ new form, and she gains any special senses, proficiencies, traits, actions,\
      \ and reactions (except class features, legendary actions, and lair actions)\
      \ that the new form has but that she lacks. She can cast her spells with verbal\
      \ or somatic components in her new form. The new form's attacks count as magical\
      \ for the purpose of overcoming resistances and immunity to nonmagical attacks."
    "name": "Change Shape (2/Day)"
  - "desc": "Faldorn casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 18):\n\n**At will:** [druidcraft](3-Mechanics/CLI/spells/druidcraft.md),\
      \ [poison spray](3-Mechanics/CLI/spells/poison-spray.md), [shillelagh](3-Mechanics/CLI/spells/shillelagh.md)\n\
      \n**2/day each:** [entangle](3-Mechanics/CLI/spells/entangle.md), [locate creature](3-Mechanics/CLI/spells/locate-creature.md),\
      \ [speak with animals](3-Mechanics/CLI/spells/speak-with-animals.md), [stoneskin](3-Mechanics/CLI/spells/stoneskin.md),\
      \ [tree stride](3-Mechanics/CLI/spells/tree-stride.md), [water breathing](3-Mechanics/CLI/spells/water-breathing.md)\n\
      \n**1/day each:** [foresight](3-Mechanics/CLI/spells/foresight.md), [heal](3-Mechanics/CLI/spells/heal.md)"
    "name": "Spellcasting"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/faldorn-mabjov.webp"
```
^statblock