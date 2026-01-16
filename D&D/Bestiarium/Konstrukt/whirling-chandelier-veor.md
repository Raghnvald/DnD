---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/veor
- ttrpg-cli/monster/cr/7
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/construct
statblock: inline
statblock-link: "#^statblock"
aliases:
- Whirling Chandelier
---
# [Whirling Chandelier](3-Mechanics\CLI\bestiary\construct/whirling-chandelier-veor.md)
*Source: Vecna: Eve of Ruin p. 239*  

Compared to other animated objects, whirling chandeliers seem to have capricious personalities. Victims typically perceive a whirling chandelier's Blazing Vortex as mischievousness or outright malevolence, though the chandelier lacks any understanding of such concepts. A whirling chandelier makes tactical decisions only as a means to perform its master's orders to the best of its ability.

```statblock
"name": "Whirling Chandelier (VEoR)"
"size": "Large"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "105"
"hit_dice": "14d10 + 28"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "15"
  - !!int "15"
  - !!int "3"
  - !!int "5"
  - !!int "1"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_resistances": "fire"
"damage_immunities": "poison, psychic"
"condition_immunities": "blinded, charmed, deafened, exhaustion, frightened, paralyzed,\
  \ petrified, poisoned"
"senses": "blindsight 60 ft. (blind beyond this radius), passive Perception 7"
"languages": "understands Common but can't speak"
"cr": "7"
"traits":
  - "desc": "If the chandelier is motionless at the start of combat, it has advantage\
      \ on its initiative roll. Moreover, if a creature hasn't observed the chandelier\
      \ move or act, that creature must succeed on a DC 18 Intelligence (Investigation)\
      \ check to discern that the chandelier is animate."
    "name": "False Appearance"
  - "desc": "Any creature that starts its turn within 5 feet of the chandelier takes\
      \ 7 (2d6) fire damage."
    "name": "Fiery Aura"
"actions":
  - "desc": "The chandelier makes three Chain attacks, three Lamp attacks, or a combination\
      \ thereof."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 15 ft., one target. *Hit:* 13\
      \ (2d8 + 4) bludgeoning damage, and the target must succeed on a DC 15 Strength\
      \ saving throw or be pulled into an unoccupied space within 5 feet of the chandelier."
    "name": "Chain"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 9 (2d4\
      \ + 4) bludgeoning damage plus 13 (3d8) fire damage."
    "name": "Lamp"
  - "desc": "Each creature within 20 feet of the chandelier and not behind total cover\
      \ must succeed on a DC 14 Constitution saving throw or take 36 (8d8) fire damage\
      \ and have the blinded condition until the start of the chandelier's next turn."
    "name": "Blazing Vortex (Recharge 5-6)"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/construct/token/whirling-chandelier-veor.webp"
```
^statblock