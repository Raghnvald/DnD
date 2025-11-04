---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/1-2
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Fist of Bane
---
# [Fist of Bane](3-Mechanics\CLI\bestiary\humanoid/fist-of-bane-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 232*  

Bane's devoted followers are warriors who seek to rule through martial strength and intimidation, cruel tyrants who use threats and gifts as needed to ensure loyalty. They enslave those too weak to resist them and shower the strong with gifts and promises of power to turn them into loyal vassals.

## Cruel Tyrants

Whenever Bane's followers gain power, they institute draconian measures to ensure that their rule is unquestioned. They stamp out all opposition while richly rewarding those who swear fealty.

## Warrior Cult

Cultists of Bane are warriors who wear heavy armor and wield maces, swords, spears, and crossbows. They paint the right gauntlet of their armor black in honor of their patron. Bane's clerics wield black maces with heads shaped to look like a closed fist.

## Cult Ranks

Bane's cultists operate according to strict military hierarchies. The lowest rank consists of the fists of Bane, foot soldiers who obey all orders without hesitation. They are led by iron consuls, cunning field officers who excel at coordinating the fists in combat. The black gauntlets are the priests who command the consuls.

```statblock
"name": "Fist of Bane (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[chain mail](/3-Mechanics/CLI/items/chain-mail-xphb.md), [shield](/3-Mechanics/CLI/items/shield-xphb.md)"
"hp": !!int "22"
"hit_dice": "4d8 + 4"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "11"
  - !!int "13"
  - !!int "10"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"condition_immunities": "[frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "passive Perception 11"
"languages": "Common"
"cr": "1/2"
"traits":
  - "desc": "The fist of Bane has advantage on all ability checks and saving throws\
      \ made during combat."
    "name": "Tactical Discipline"
"actions":
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) bludgeoning damage."
    "name": "Mace"
  - "desc": "*Ranged Weapon Attack:* +2 to hit, range 150/600 ft., one target. *Hit:*\
      \ 4 (1d8) piercing damage."
    "name": "Longbow"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/fist-of-bane-bgdia.webp"
```
^statblock