---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Barachiel"
---
# [Barachiel](3-Mechanics/CLI/bestiary/npc/barachiel-coa.md)
*Source: Chains of Asmodeus p. 263*  

Barachiel is an aasimar that was born in the city of Elturel; a bastion of justice and symbol of good in the Forgotten Realms. His mother was the angel Zariel, the patron of Elturel. Barachiel grew up to become a Hellrider—the holy warriors that defend the city of Elturel. However, he gave up his freedom to become an agent of Mount Celestia so that he could try and save his mother. Zariel had been seduced and corrupted by Asmodeus. Now, as an archdevil, she rules the first layer of the Nine Hells.

Barachiel believes in justice, mercy, virtue, and compassion. Since his transformation into an angelic being, his memories of his former life have faded. However, the Hellrider Ramius was his beloved companion, and that memory has stayed with him.

```statblock
"name": "Barachiel (CoA)"
"size": "Medium"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "plate"
"hp": !!int "136"
"hit_dice": "16d8 + 64"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "18"
  - !!int "11"
  - !!int "14"
  - !!int "20"
"speed": "30 ft., fly 50 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "7"
"damage_resistances": "necrotic, poison"
"condition_immunities": "exhaustion, frightened, poisoned"
"gear":
  - "greatsword"
"senses": "passive Perception 12"
"languages": "Celestial, Common, Infernal"
"cr": "13"
"actions":
  - "desc": "Barachiel makes three Greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 11\
      \ (2d6 + 4) slashing damage plus 22 (5d8) radiant damage."
    "name": "Greatsword"
  - "desc": "Barachiel wreathes his sword in white flame, then makes a Greatsword\
      \ attack. On a hit, the target takes an additional 45 (7d12) fire damage plus\
      \ 45 (7d12) radiant damage. The target must succeed on a DC 18 Charisma saving\
      \ throw or have the stunned condition until the end of their next turn."
    "name": "Purifying Flames (Recharge 4-6)"
"reactions":
  - "desc": "Barachiel adds 5 to his AC against one attack. To do so, Barachiel must\
      \ see the attacker and be wielding a melee weapon."
    "name": "Parry"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/barachiel-coa.webp"
```
^statblock