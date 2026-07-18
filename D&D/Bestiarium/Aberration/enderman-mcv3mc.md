---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Enderman
Kategorie: Aberration
Größe: Mittelgroß
HG: 6
Status: WIP
linter-yaml-title-alias: Enderman
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/6
  - Monster/Typ/aberration
  - Quelle/5e/mcv3mc
aliases:
  - Enderman
status: WIP
---
# [Enderman](3-Mechanics\CLI\bestiary\aberration/enderman-mcv3mc.md)
*Source: Monstrous Compendium Volume 3: Minecraft Creatures p. 6*  

Endermen are tall, black, bipedal creatures with long, thin limbs and piercing, purple eyes. Violet particles flicker in and out of existence around them. Endermen are unnerving and enigmatic, acting in a manner that is all but impossible to interpret.

Endermen seem particularly drawn to the End, where they gather in large groups. They are uncommon visitors to other dimensions, although they appear more often in pairs in such peculiar places as the warped forests of the Nether. They shun sunlight and are hurt by water, including rain. When an Enderman becomes the target of a ranged weapon or takes damage, it teleports to a safer location nearby and makes a distinctive "voop" sound at its destination.

Endermen have no known predators. When a Humanoid looks directly at an Enderman, the Enderman becomes enraged, opens its mouth horrifyingly wide, and rushes to attack with its long arms. A defeated Enderman implodes and sometimes leaves behind an Ender pearl, which, when thrown, teleports the thrower to the place it lands.

```statblock
"name": "Enderman (MCV3MC)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Chaotic Neutral"
"ac": !!int "14"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "4"
"stats":
  - !!int "15"
  - !!int "18"
  - !!int "15"
  - !!int "10"
  - !!int "18"
  - !!int "11"
"speed": "40 ft."
"saves":
  - "strength": !!int "5"
  - "constitution": !!int "5"
"skillsaves":
  - "name": "Perception"
    "desc": "+7"
  - "name": "Stealth"
    "desc": "+7"
  - "name": "Survival"
    "desc": "+7"
"damage_resistances": "necrotic"
"senses": "darkvision 60 ft., passive Perception 17"
"languages": "Endspeech"
"cr": "6"
"traits":
  - "desc": "Whenever it takes damage or is the target of a ranged attack, the Enderman\
      \ can teleport, along with any equipment it is wearing or carrying, to an unoccupied\
      \ space it can see within 20 feet of itself (no action required). If this effect\
      \ is triggered by a ranged attack, the Enderman teleports just before the attack\
      \ hits, causing the attack to miss it. This trait is suppressed while the Enderman\
      \ has the incapacitated condition."
    "name": "Evasive Teleportation"
  - "desc": "When the Enderman drops to 0 hit points, it dies as its body implodes.\
      \ Roll a d10. On a roll of 9 or less, the Enderman leaves no remains. On a roll\
      \ of 10, the Enderman leaves behind a glowing, purple orb called an Ender pearl,\
      \ worth 500 gp. A creature can throw the pearl up to 60 feet; if the pearl lands\
      \ in an unoccupied space big enough to contain the creature, the creature teleports\
      \ to that space, along with any equipment it is wearing or carrying, and the\
      \ pearl disappears."
    "name": "Implosion"
  - "desc": "While in sunlight, the Enderman has disadvantage on attack rolls."
    "name": "Sunlight Sensitivity"
  - "desc": "The Enderman takes 1 cold damage for every 5 feet it moves in water,\
      \ for every gallon of water splashed on it, or whenever it starts its turn in\
      \ the rain."
    "name": "Water Susceptibility"
"actions":
  - "desc": "The Enderman makes two Slam attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit; reach 10 ft., one target. *Hit:* 8\
      \ (1d8 + 4) bludgeoning damage plus 9 (2d8) necrotic damage."
    "name": "Slam"
"source":
  - "MCV3MC"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/enderman-mcv3mc.webp"
```
^statblock