---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Achaierai"
---
# [Achaierai](3-Mechanics/CLI/bestiary/monstrosity/achaierai-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 131*  

Dwelling mostly in the Underdark, achaierai are cunning avian quadrupeds originally from the plane of Acheron. Tribalistic and organized, they possess a strong—if skewed—sense of justice and will often band together to seek bloody vengeance against those who have wronged their kin. They are highly intelligent, with a strong streak of sadistic cruelty, compelling them to devise new and inventive strategies of torture for their victims.

## Deadly Foes

Achaierai have razor sharp beaks, and each of their four legs are tipped with savage talons that can rip an opponent to shreds. They typically hunt in flocks, using coordinated strategy to maximize the efficiency of their attacks. If an achaierai is threatened, it can expel a toxic cloud to distract its enemies and flee... only to resume the fight again later under more favorable conditions.

## A Community of Cruelty

Social creatures by nature, the achaierai typically form small flocks of up to a half-dozen members. However, these flocks are not family. The leader is simply the largest and strongest member, and in times of food scarcity the weakest members are routinely cannibalized. Achaierai can only breed on their home plane. To increase their numbers in the Underdark, they capture wizards and torture them until they summon more of their kind from Acheron. Because of this, wizards are the only captives the carnivorous achaierai don't eventually eat.

## A Cycle of Vengeance

Flocks of achaierai have been known to band together to wage war upon a svirfneblin village or drow outpost. These attacks come with little warning, and there are typically no survivors as the ravenous achaierai devour everything in sight. For this reason, the other Underdark races despise the achaierai, and will even work together to wipe out a flock whenever one is discovered. Inevitably, this triggers retaliation from other achaierai, leading to an endless cycle of vicious and bloody reprisals.

```statblock
"name": "Achaierai (MaBJoV)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "90"
"hit_dice": "12d10 + 24"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "10"
  - !!int "12"
  - !!int "14"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 14"
"languages": "Infernal"
"cr": "5"
"traits":
  - "desc": "The achaierai has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The achaierai makes two attacks with its Talons and one attack with its\
      \ Beak."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (3d6 + 4) piercing damage."
    "name": "Beak"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 10 ft., one target. *Hit:*\
      \ 8 (1d8 + 4) slashing damage."
    "name": "Talons"
"bonus_actions":
  - "desc": "The achaierai takes the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ action."
    "name": "Spring Attack"
"reactions":
  - "desc": "After taking damage the achaierai can use its reaction to release a cloud\
      \ of poisonous gas in a 10-foot-radius. All creatures in the cloud take 7 (2d6)\
      \ poison damage and must succeed on a DC 15 Constitution saving throw or be\
      \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) for 1 minute. While\
      \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) the target is confused\
      \ as if from a [confusion](3-Mechanics/CLI/spells/confusion.md) spell. At the\
      \ end of its turns, the affected target can repeat the Constitution saving throw.\
      \ If it succeeds the confusion ends. Achaierai are immune to the effects of\
      \ this cloud."
    "name": "Defensive Cloud"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/achaierai-mabjov.webp"
```
^statblock