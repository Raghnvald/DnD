---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/pota
- ttrpg-cli/monster/cr/4
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Burrowshark"
---
# [Burrowshark](3-Mechanics/CLI/bestiary/humanoid/burrowshark-pota.md)
*Source: Princes of the Apocalypse p. 196*  

Elite warriors of the earth cult, burrowsharks are fierce champions who ride trained bulettes into battle. While their powerful mounts rend and tear foes to pieces, burrowsharks leap to the ground and cut down their foes without mercy.

Burrowsharks are much like Black Earth guards, since both have uncanny footing and special armor. For burrowsharks, an additional gift of Ogrémoch's might establishes a magical bond between the burrowshark and a bulette, allowing the rider to burrow with its mount and sense what its mount senses.

```statblock
"name": "Burrowshark (PotA)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "[plate armor](3-Mechanics/CLI/items/plate-armor.md)"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "16"
  - !!int "10"
  - !!int "11"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Animal Handling](3-Mechanics/CLI/rules/skills.md#Animal%20Handling)"
    "desc": "+2"
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+6"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"gear":
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "passive Perception 12"
"languages": "Common"
"cr": "4"
"traits":
  - "desc": "The burrowshark is magically bound to a bulette trained to serve as its\
      \ mount. While mounted on its bulette, the burrowshark shares the bulette's\
      \ senses and can ride the bulette while it burrows. The bonded bulette obeys\
      \ the burrowshark's commands. If its mount dies, the burrowshark can train a\
      \ new bulette to serve as its bonded mount, a process requiring a month."
    "name": "Bond of the Black Earth"
"actions":
  - "desc": "The burrowshark makes three melee attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear"
"reactions":
  - "desc": "When the burrowshark is subjected to an effect that would move it, knock\
      \ it [prone](3-Mechanics/CLI/rules/conditions.md#Prone), or both, it can use\
      \ its reaction to be neither moved nor knocked [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Unyielding"
"source":
  - "PotA"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/burrowshark-pota.webp"
```
^statblock