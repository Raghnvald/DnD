---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/bgdia
  - Monster/cr/1-4
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Night Blade
---
# [Night Blade](3-Mechanics\CLI\bestiary\humanoid/night-blade-bgdia.md)
*Source: Baldur's Gate: Descent Into Avernus p. 233*  

Bhaal's cultists emulate their deity, carrying out gruesome murders to spread fear and horror. They are charming and disarming when they wish, but in combat their true, bloodthirsty nature comes to the fore.

## Bloodletters

All cultists of Bhaal learn to call upon their god's power to leave their victims vulnerable to their long-bladed knives. When Bhaal's magic works its power, stab wounds erupt in terrible gouts of blood. Seemingly minor wounds plunge deep into a victim's body and cause terrible pain and bleeding.

## Killers from the Shadows

Bhaal's followers are cunning murderers who kill to strike fear and thrive on sowing terror in the cities they inhabit. They can call upon their god's power to blend into the shadows with ease, or even turn [invisible](/3-Mechanics/CLI/conditions.md#Invisible) for a crucial moment.

## Cult Ranks

Low-ranking cultists of Bhaal are called night blades, whom Bhaal blesses with [darkvision](/3-Mechanics/CLI/senses.md#Darkvision) and superior stealth. Reapers are the next rank up. They gain the ability to turn [invisible](/3-Mechanics/CLI/conditions.md#Invisible) and can use Bhaal's magic to evade suspicion. The highest rank are the death's heads, who can take on the skull-faced guise of their deity to terrify their prey. In combat, they intimidate foes by shrugging off the deadliest attacks with ease, showing that resisting Bhaal's schemes is futile.

```statblock
"name": "Night Blade (BGDIA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "2"
"stats":
  - !!int "11"
  - !!int "15"
  - !!int "12"
  - !!int "10"
  - !!int "11"
  - !!int "14"
"speed": "40 ft."
"skillsaves":
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60, passive Perception\
  \ 10"
"languages": "Common"
"cr": "1/4"
"traits":
  - "desc": "As long as the night blade is not [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated),\
      \ hostile creatures within 5 feet of it gain vulnerability to piercing damage\
      \ unless they have resistance or immunity to such damage."
    "name": "Aura of Murder"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 4 (1d4 + 2) piercing damage."
    "name": "Dagger"
"source":
  - "BGDIA"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/night-blade-bgdia.webp"
```
^statblock