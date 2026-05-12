---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Howling Hatred Priest"
---
# [Howling Hatred Priest](3-Mechanics/CLI/bestiary/humanoid/howling-hatred-priest-pota.md)
*Source: Princes of the Apocalypse p. 190*  

The most fanatical of the air cultists, the priests push their bodies to physical extremes in order to decrease their density and mass and become as light as leaves. Gaunt and sallow faced, with concave bellies, bulging eyes, and taut skin that enunciates every bone, these living skeletons sustain themselves on nothing more than air and fanatical devotion to the teachings of the cult. The wind serves them at a gesture.

Howling Hatred priests see themselves as living extensions of Yan-C-Bin, and they help new recruits cast off the shackles of their old lives and embrace a "higher purpose." Once the new recruits are thus purified, the priests decide whether they are worthy for indoctrination as initiates or would better serve the Howling Hatred cult as sacrifices. The priests also uphold the doctrine of their prophet, Aerisi Kalinoth, and harshly punish any initiate who strays from the path.

Most other air cultists hate the priests, though none dares to speak out against them. Those that challenge the priests often end up the subjects of rigorous new attempts at purification.

```statblock
"name": "Howling Hatred Priest (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "45"
"hit_dice": "10d8"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "10"
  - !!int "14"
  - !!int "10"
  - !!int "14"
"speed": "30 ft."
"skillsaves":
  - "name": "[Acrobatics](3-Mechanics/CLI/rules/skills.md#Acrobatics)"
    "desc": "+5"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+4"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+4"
"gear":
  - "[dagger](3-Mechanics/CLI/items/dagger.md)"
  - "[scimitar](3-Mechanics/CLI/items/scimitar.md)"
"senses": "passive Perception 10"
"languages": "Auran, Common"
"cr": "2"
"traits":
  - "desc": "The priest is a 5th-level spellcaster. Its spellcasting ability is Charisma\
      \ (spell save DC 12, +4 to hit with spell attacks). It knows the following\
      \ sorcerer spells:\n\n**Cantrips (at will):** [blade ward](3-Mechanics/CLI/spells/blade-ward.md),\
      \ gust, [light](3-Mechanics/CLI/spells/light.md), [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md),\
      \ [shocking grasp](3-Mechanics/CLI/spells/shocking-grasp.md)\n\n**1st level\
      \ (4 slots):** [feather fall](3-Mechanics/CLI/spells/feather-fall.md), [shield](3-Mechanics/CLI/spells/shield.md),\
      \ [witch bolt](3-Mechanics/CLI/spells/witch-bolt.md)\n\n**2nd level (3 slots):**\
      \ dust devil, [gust of wind](3-Mechanics/CLI/spells/gust-of-wind.md)\n\n**3rd\
      \ level (2 slots):** [gaseous form](3-Mechanics/CLI/spells/gaseous-form.md)"
    "name": "Spellcasting"
  - "desc": "The priest can hold its breath for 30 minutes."
    "name": "Hold Breath"
"actions":
  - "desc": "The priest makes two melee attacks or two ranged attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage."
    "name": "Scimitar"
  - "desc": "*Melee  or Ranged Weapon Attack:* +5 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/howling-hatred-priest-pota.webp"
```
^statblock