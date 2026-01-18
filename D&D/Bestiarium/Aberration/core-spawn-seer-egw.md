---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/egw
  - Monster/HG/13
  - Monster/Größe/Mittelgroß
  - Monster/Typ/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Core Spawn Seer
---
# [Core Spawn Seer](3-Mechanics\CLI\bestiary\aberration/core-spawn-seer-egw.md)
*Source: Explorer's Guide to Wildemount p. 286*  

Core spawn seers are humanoid arcanists corrupted by the eldritch power of the Elder Evils through blasphemous rites or accursed encounters. Ravaged by otherworldly radiation and disease, their bodies are covered in horrible protrusions of fluorescent crystals, which emit a psychedelic glow from beneath the tattered folds of their robes.

The Elder Evils assault the multiverse in strange and calamitous ways. Sometimes they breach the Material Plane by exploiting the unfathomable energy and darkness found in the world's depths. These terrestrial manifestations of loathsome alien agendas are known as core spawn, and they are as varied in their physiology as they are horrific.

Their concentration in the desolate lands of Blightshore makes the core spawn a challenge to research, and many who have sought to observe or study these nightmarish entities rarely return. Those who do return are often shells of their former selves who speak of horrifying underground labyrinths of twisting caverns and malevolent nests where other denizens of the Miskath Strand are dragged below to some infernal purpose.

## Offspring of Calamity

The aberrant creatures known as core spawn are a subterranean breed of heralds, servants, foot soldiers, and lieutenants of the Elder Evils, awakened in the depths by the cataclysmic actions of the Betrayer Gods and their minions. They often appear on the surface world in the wake of seismic events, such as that which created the bottomless Miskath Pit of Eastern Wynandir. Warlocks and cultists sometimes gather together to hasten the arrival of core spawn to the Material Plane, focusing their arcane power on areas of natural seismic instability when the signs and stars are right.

```statblock
"name": "Core Spawn Seer (EGW)"
"size": "Medium"
"type": "aberration"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "1"
"stats":
  - !!int "14"
  - !!int "12"
  - !!int "18"
  - !!int "22"
  - !!int "19"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "intelligence": !!int "11"
  - "wisdom": !!int "9"
  - "charisma": !!int "8"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_immunities": "psychic"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [frightened](/3-Mechanics/CLI/conditions.md#Frightened)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft., tremorsense\
  \ 60 ft., passive Perception 19"
"languages": "Common, Deep Speech, telepathy 120 ft., Undercommon"
"cr": "13"
"traits":
  - "desc": "The seer can traverse through nonmagical, unworked earth and stone. While\
      \ doing so, the seer doesn't disturb the material it moves through."
    "name": "Earth Glide"
  - "desc": "The seer has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The seer uses Fission Staff twice, Psychedelic Orb twice, or each one\
      \ once."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one creature. *Hit:* 9\
      \ (1d6 + 6) bludgeoning damage plus 18 (4d8) radiant damage, and the target\
      \ is knocked [prone](/3-Mechanics/CLI/conditions.md#Prone)."
    "name": "Fission Staff"
  - "desc": "The seer hurls a glimmering orb at one creature it can see within 120\
      \ of it. The target must succeed on a DC 19 Wisdom saving throw or take 27 (5d10)\
      \ psychic damage and suffer a random condition until the start of the seer's\
      \ next turn. Roll a d6 for the condition: (1-2) [blinded](/3-Mechanics/CLI/conditions.md#Blinded),\
      \ (3-4) [frightened](/3-Mechanics/CLI/conditions.md#Frightened), or (5-6) [stunned](/3-Mechanics/CLI/conditions.md#Stunned)."
    "name": "Psychedelic Orb"
"reactions":
  - "desc": "When the seer is hit by an attack, it takes only half of the triggering\
      \ damage. The first time the seer hits with a melee attack on its next turn,\
      \ the target takes an extra 1d6 radiant damage."
    "name": "Fuse Damage"
"source":
  - "EGW"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/core-spawn-seer-egw.webp"
```
^statblock