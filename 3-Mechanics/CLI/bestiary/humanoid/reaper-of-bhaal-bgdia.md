---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/bgdia
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Reaper of Bhaal"
---
# [Reaper of Bhaal](3-Mechanics/CLI/bestiary/humanoid/reaper-of-bhaal-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 233*  

Bhaal's cultists emulate their deity, carrying out gruesome murders to spread fear and horror. They are charming and disarming when they wish, but in combat their true, bloodthirsty nature comes to the fore.

## Bloodletters

All cultists of Bhaal learn to call upon their god's power to leave their victims vulnerable to their long-bladed knives. When Bhaal's magic works its power, stab wounds erupt in terrible gouts of blood. Seemingly minor wounds plunge deep into a victim's body and cause terrible pain and bleeding.

## Killers from the Shadows

Bhaal's followers are cunning murderers who kill to strike fear and thrive on sowing terror in the cities they inhabit. They can call upon their god's power to blend into the shadows with ease, or even turn invisible for a crucial moment.

## Cult Ranks

Low-ranking cultists of Bhaal are called night blades, whom Bhaal blesses with darkvision and superior stealth. Reapers are the next rank up. They gain the ability to turn invisible and can use Bhaal's magic to evade suspicion. The highest rank are the death's heads, who can take on the skull-faced guise of their deity to terrify their prey. In combat, they intimidate foes by shrugging off the deadliest attacks with ease, showing that resisting Bhaal's schemes is futile.

```statblock
"name": "Reaper of Bhaal (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"hp": !!int "27"
"hit_dice": "5d8 + 5"
"modifier": !!int "5"
"stats":
  - !!int "11"
  - !!int "20"
  - !!int "13"
  - !!int "15"
  - !!int "12"
  - !!int "16"
"speed": "40 ft."
"skillsaves":
  - "name": "Intimidation"
    "desc": "+5"
  - "name": "Perception"
    "desc": "+3"
  - "name": "Persuasion"
    "desc": "+5"
  - "name": "Stealth"
    "desc": "+9"
"gear":
  - "dagger"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Common"
"cr": "2"
"traits":
  - "desc": "The reaper's innate spellcasting ability is Charisma (spell save DC 13).\
      \ It can innately cast the following spells, requiring no material components:\n\
      \n**1/day each:** charm person, disguise self, sanctuary"
    "name": "Innate Spellcasting"
  - "desc": "As long as the reaper is not incapacitated, hostile creatures within\
      \ 5 feet of it gain vulnerability to piercing damage unless they have resistance\
      \ or immunity to such damage."
    "name": "Aura of Murder"
"actions":
  - "desc": "The reaper makes two dagger attacks and uses Shroud Self."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +7 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d4 + 5) piercing damage."
    "name": "Dagger"
  - "desc": "The reaper magically turns invisible until the start of its next turn.\
      \ This invisibility ends if the reaper makes an attack roll, makes a damage\
      \ roll, or casts a spell."
    "name": "Shroud Self"
"source":
  - "BGDIA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/reaper-of-bhaal-bgdia.webp"
```
^statblock