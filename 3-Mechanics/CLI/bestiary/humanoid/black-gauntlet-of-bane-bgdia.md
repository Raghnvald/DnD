---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - monster/cr/6
  - monster/size/medium
  - monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Black Gauntlet of Bane
---
# [Black Gauntlet of Bane](3-Mechanics\CLI\bestiary\humanoid/black-gauntlet-of-bane-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 235*  

Bane's devoted followers are warriors who seek to rule through martial strength and intimidation, cruel tyrants who use threats and gifts as needed to ensure loyalty. They enslave those too weak to resist them and shower the strong with gifts and promises of power to turn them into loyal vassals.

## Cruel Tyrants

Whenever Bane's followers gain power, they institute draconian measures to ensure that their rule is unquestioned. They stamp out all opposition while richly rewarding those who swear fealty.

## Warrior Cult

Cultists of Bane are warriors who wear heavy armor and wield maces, swords, spears, and crossbows. They paint the right gauntlet of their armor black in honor of their patron. Bane's clerics wield black maces with heads shaped to look like a closed fist.

## Cult Ranks

Bane's cultists operate according to strict military hierarchies. The lowest rank consists of the fists of Bane, foot soldiers who obey all orders without hesitation. They are led by iron consuls, cunning field officers who excel at coordinating the fists in combat. The black gauntlets are the priests who command the consuls.

```statblock
"name": "Black Gauntlet of Bane (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[chain mail](/3-Mechanics/CLI/items/chain-mail-xphb.md)"
"hp": !!int "51"
"hit_dice": "6d8 + 24"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "11"
  - !!int "18"
  - !!int "12"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "5"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+7"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+5"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 15"
"languages": "Common"
"cr": "6"
"traits":
  - "desc": "The black gauntlet is a 5th-level spellcaster. Its spellcasting ability\
      \ is Charisma (spell save DC 15, +7 to hit with spell attacks). It has the following\
      \ cleric spells prepared:\n\n**Cantrips (at will):** [guidance](/3-Mechanics/CLI/spells/guidance-xphb.md),\
      \ [sacred flame](/3-Mechanics/CLI/spells/sacred-flame-xphb.md), [thaumaturgy](/3-Mechanics/CLI/spells/thaumaturgy-xphb.md)\n\
      \n**1st level (4 slots):** [bane](/3-Mechanics/CLI/spells/bane-xphb.md), [bless](/3-Mechanics/CLI/spells/bless-xphb.md),\
      \ [cure wounds](/3-Mechanics/CLI/spells/cure-wounds-xphb.md), [guiding bolt](/3-Mechanics/CLI/spells/guiding-bolt-xphb.md)\
      \ (see \"Actions\" below)\n\n**2nd level (3 slots):** [blindness/deafness](/3-Mechanics/CLI/spells/blindness-deafness-xphb.md),\
      \ [hold person](/3-Mechanics/CLI/spells/hold-person-xphb.md), [silence](/3-Mechanics/CLI/spells/silence-xphb.md)\n\
      \n**3rd level (2 slots):** [sending](/3-Mechanics/CLI/spells/sending-xphb.md),\
      \ [spirit guardians](/3-Mechanics/CLI/spells/spirit-guardians-xphb.md)"
    "name": "Spellcasting"
  - "desc": "When a hostile creature within 5 feet of the black gauntlet makes an\
      \ attack roll or a saving throw, it has disadvantage on the roll. Creatures\
      \ that are immune to the [frightened](/3-Mechanics/CLI/conditions.md#Frightened)\
      \ condition are immune to this trait."
    "name": "Aura of Terror"
  - "desc": "The black gauntlet has advantage on all ability checks and saving throws\
      \ made during combat."
    "name": "Tactical Discipline"
"actions":
  - "desc": "The black gauntlet makes two attacks with its mace."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) bludgeoning damage plus 13 (3d8) necrotic damage."
    "name": "Mace"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 120 ft., one creature. *Hit:*\
      \ 14 (4d6) radiant damage, and the next attack roll made against the target\
      \ before the end of the black gauntlet's next turn has advantage. If the black\
      \ gauntlet casts this spell using a spell slot of 2nd level or higher, the damage\
      \ increases by 1d6 for each slot level above 1st."
    "name": "Guiding Bolt (1st-Level Spell; Requires a Spell Slot)"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/black-gauntlet-of-bane-bgdia.webp"
```
^statblock