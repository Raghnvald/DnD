---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Iron Consul
---
# [Iron Consul](3-Mechanics\CLI\bestiary\humanoid/iron-consul-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 232*  

Bane's devoted followers are warriors who seek to rule through martial strength and intimidation, cruel tyrants who use threats and gifts as needed to ensure loyalty. They enslave those too weak to resist them and shower the strong with gifts and promises of power to turn them into loyal vassals.

## Cruel Tyrants

Whenever Bane's followers gain power, they institute draconian measures to ensure that their rule is unquestioned. They stamp out all opposition while richly rewarding those who swear fealty.

## Warrior Cult

Cultists of Bane are warriors who wear heavy armor and wield maces, swords, spears, and crossbows. They paint the right gauntlet of their armor black in honor of their patron. Bane's clerics wield black maces with heads shaped to look like a closed fist.

## Cult Ranks

Bane's cultists operate according to strict military hierarchies. The lowest rank consists of the fists of Bane, foot soldiers who obey all orders without hesitation. They are led by iron consuls, cunning field officers who excel at coordinating the fists in combat. The black gauntlets are the priests who command the consuls.

```statblock
"name": "Iron Consul (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "[chain mail](/3-Mechanics/CLI/items/chain-mail-xphb.md)"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "0"
"stats":
  - !!int "17"
  - !!int "11"
  - !!int "16"
  - !!int "12"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+5"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 14"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "The iron consul has advantage on all ability checks and saving throws\
      \ made during combat."
    "name": "Tactical Discipline"
"actions":
  - "desc": "The iron consul makes one attack with its spear and can use its Voice\
      \ of Command ability."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d6 + 3) piercing damage, or 7 (1d8 + 3) piercing\
      \ damage when used with two hands to make a melee attack."
    "name": "Spear"
  - "desc": "The iron consul selects up to two allies within 90 feet of it that can\
      \ hear its commands. Each ally can immediately use its reaction to make one\
      \ melee attack."
    "name": "Voice of Command"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/iron-consul-bgdia.webp"
```
^statblock