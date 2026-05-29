---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Nightmare Haunt
Kategorie: Aberration
Größe: Mittelgroß
HG: 5
status: WIP
linter-yaml-title-alias: Nightmare Haunt
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/5
  - Monster/Typ/aberration
  - Quelle/5e/mcv4ec
aliases:
  - Nightmare Haunt
---
# [Nightmare Haunt](3-Mechanics\CLI\bestiary\aberration/nightmare-haunt-mcv4ec.md)
*Source: Monstrous Compendium Volume 4: Eldraine Creatures*  

Nightmare haunts are terrors from the minds of Eldraine's sleeping citizens, made tangible by the planeswalker Ashiok. These creatures can hurt the body and also attack the minds of dreamers afflicted by the Wicked Slumber.

Nightmare haunts appear as horrifying shadow creatures with forms evocative of their victims' deepest fears. Due to the collective trauma experienced by the people of Eldraine during the Phyrexian invasion, many nightmare haunts take the shape of those terrifying invaders, having multiple limbs and inhuman visages. Smoky purplish energy wafts from their forms, suggesting their connection to the Wicked Slumber.

> [!note] The Wicked Slumber
> 
> During the Phyrexian invasion of Eldraine, the high fae monarch Talion, the Kindly Lord, and a trio of witch sisters performed a grand ritual to create a sleeping curse. Even with the Phyrexians defeated, the curse remains and spreads unchecked through Eldraine due to interference from the planeswalker Ashiok and Eriette, one of the witches who helped create the curse. The Wicked Slumber affects rich and poor alike, causing them to fall into an endless sleep or roam as sleepwalkers. Animals are also affected, and even tree boughs droop as if exhausted in areas where the Wicked Slumber is prominent. Purple tendrils of wispy nightmares spread like vines across those areas and surround the bodies of those who sleep.
> 
> Heroes throughout Eldraine have ventured out to find a cure for the Wicked Slumber, but no one has yet discovered how to break the enchantment. It has even affected one of the Kindly Lord's daughters, the famed duelist Obyra. Meanwhile, Eriette and Ashiok conspire to build a nightmare realm in the ruins of Castle Ardenvale at the heart of the Wicked Slumber, replacing the virtuous court with one composed of sleepwalkers and dreamers guarded by nightmare haunts.
^the-wicked-slumber

```statblock
"name": "Nightmare Haunt (MCV4EC)"
"size": "Medium"
"type": "aberration"
"alignment": "typically  Neutral Evil"
"ac": !!int "13"
"hp": !!int "44"
"hit_dice": "8d8 + 8"
"modifier": !!int "3"
"stats":
  - !!int "14"
  - !!int "17"
  - !!int "13"
  - !!int "9"
  - !!int "12"
  - !!int "17"
"speed": "30 ft., climb 30 ft."
"damage_immunities": "psychic"
"condition_immunities": "blinded, charmed, exhaustion, frightened"
"senses": "blindsight 120 ft. (can't see beyond this radius), passive Perception 11"
"languages": "Deep Speech, telepathy 120 ft."
"cr": "5"
"traits":
  - "desc": "The nightmare haunt has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
  - "desc": "At the start of its turn, the nightmare haunt gains a number of temporary\
      \ hit points equal to 5 times the number of unconscious creatures within 30\
      \ feet of itself."
    "name": "Somnophage"
"actions":
  - "desc": "The nightmare haunt makes two Claw attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) slashing damage plus 9 (2d8) psychic damage."
    "name": "Claw"
  - "desc": "The nightmare haunt creates spectral tendrils that cover the ground in\
      \ a 20-foot square that it can see within 30 feet of itself for 1 minute or\
      \ until it uses this action again. When a creature other than the nightmare\
      \ haunt enters the affected area for the first time or starts its turn there,\
      \ the creature must succeed on a DC 14 Strength saving throw or take 11 (2d10)\
      \ necrotic damage and have the restrained condition. The affected ground is\
      \ also considered difficult terrain for creatures other than the nightmare haunt\
      \ for the duration of its effect.\n\nA creature that starts its turn in the\
      \ area and is already restrained by the tendrils must repeat the saving throw.\
      \ On a failed save, it has the unconscious condition and instead of the restrained\
      \ condition caused by the tendrils. On a successful save, the effect ends on\
      \ the creature. An unconscious creature remains asleep until it is no longer\
      \ in the area with tendrils, takes any damage, or is targeted by a remove curse\
      \ spell or similar magic."
    "name": "Tendrils of Slumber (Recharge 5-6)"
"bonus_actions":
  - "desc": "While in dim light or darkness, the nightmare haunt takes the Hide action."
    "name": "Shadow Stealth"
"source":
  - "MCV4EC"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/nightmare-haunt-mcv4ec.webp"
```
^statblock