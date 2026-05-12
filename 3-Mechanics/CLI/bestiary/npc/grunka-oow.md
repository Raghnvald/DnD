---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/oow
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Grunka"
---
# [Grunka](3-Mechanics/CLI/bestiary/npc/grunka-oow.md)
*Source: The Orrery of the Wanderer p. 115*  

```statblock
"name": "Grunka (OoW)"
"size": "Medium"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[chain mail](3-Mechanics/CLI/items/chain-mail.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "1"
"stats":
  - !!int "13"
  - !!int "12"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "9"
"speed": "30 ft."
"gear":
  - "[longbow](3-Mechanics/CLI/items/longbow.md)"
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Common, Goblin"
"cr": "1/2"
"traits":
  - "desc": "Once per turn, Grunka can deal an extra 7 (2d6) damage to a creature\
      \ it hits with a weapon attack if that creature is within 5 feet of an ally\
      \ of Grunka that isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)."
    "name": "Martial Advantage"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d8 + 1) slashing damage, or 6 (1d10 + 1) slashing damage if used with\
      \ two hands."
    "name": "Longsword"
  - "desc": "*Ranged Weapon Attack:* +3 to hit, range 150/600 ft., one target. *Hit:*\
      \ 5 (1d8 + 1) piercing damage."
    "name": "Longbow"
  - "desc": "The hobgoblin sprays acid in a 10-foot cone. Each creature in the area\
      \ must make a DC 10 Dexterity saving throw, taking 7 (2d6) acid damage on\
      \ a failed save, or half as much damage on a successful one.\n\nThe spray gun\
      \ has a tank that can be filled with ten standard vials of acid mixed with water,\
      \ allowing it to be used five times."
    "name": "Acid Spray Gun (Recharge 5-6)"
"source":
  - "OoW"
"image": "3-Mechanics/CLI/bestiary/npc/token/grunka-oow.webp"
```
^statblock