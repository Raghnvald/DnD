---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mff
- ttrpg-cli/monster/cr/1-2
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Needle Spawn"
---
# [Needle Spawn](3-Mechanics/CLI/bestiary/plant/needle-spawn-mff.md)
*Source: Mordenkainen's Fiendish Folio p. 16*  

A wise ranger knows that the sight of a needle spawn is an ill omen, for it heralds the rise of a dreaded needle lord and a war for the soul of a forest.

## Roving Corpses

Needle spawn are created by needle lords—hulking plant creatures that hail from fey domains wracked by wanton violence. When a needle lord enters a worldly forest, it spreads seed pods wherever it roams. A pod remains dormant until a humanoid dies near it or a humanoid corpse is dragged close by, whereupon the pod burrows into the corpse's decaying flesh and sprouts ropey vines covered in long, sharp needles. The vines wrap around the corpse to animate it, causing it to rise and lurch about like a zombie.

## Invasive Species

When a great battle is fought in a fey woodland, the plants of the wood sometimes take on the thirst for violence and conquest that propels the fey to war. These plants become needle lords—ogre-shaped masses of thorny vines covered with long, cruel needles that pierce flesh.

A needle lord fancies itself a conquering general, wandering in search of a forest to conquer and claim. When it sets its sights on a forest, it first focuses on spreading the seed pods that give rise to its needle spawn vassals. It then prowls the wood in search of weak or defenseless humanoids to kill, converting their corpses into needle spawn to begin growing its army.

## Unnatural Ally

A needle lord is an implacable foe. Driven only by a desire to conquer and rule, it wages endless war with its army of mobile dead against all creatures it views as a threat to its domination. It might even forge treaties with hobgoblins, kobolds, and other creatures willing to obey it, but it sees any alliance that casts it as a lesser partner as only a temporary measure. The needle lord betrays any allies at the first opportunity, as it believes that only one creature can claim dominion over a forest.

```statblock
"name": "Needle Spawn (MFF)"
"size": "Medium"
"type": "plant"
"alignment": "Chaotic Evil"
"ac": !!int "13"
"hp": !!int "16"
"hit_dice": "3d8 + 3"
"modifier": !!int "3"
"stats":
  - !!int "13"
  - !!int "17"
  - !!int "12"
  - !!int "6"
  - !!int "13"
  - !!int "6"
"speed": "30 ft., climb 20 ft."
"skillsaves":
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+5"
"condition_immunities": "[blinded](3-Mechanics/CLI/rules/conditions.md#Blinded), [deafened](3-Mechanics/CLI/rules/conditions.md#Deafened),\
  \ [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 30 ft., passive\
  \ Perception 11"
"languages": "Sylvan"
"cr": "1/2"
"traits":
  - "desc": "The needle spawn does not suffer disadvantage on ranged attacks while\
      \ within 5 feet of a hostile creature that can see it and isn't [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
      \ if the target of the attack is also within 5 feet of the needle spawn."
    "name": "Close Quarters Shooting"
"actions":
  - "desc": "The needle spawn makes up to 1d6 needle attacks, but it cannot attack\
      \ the same target more than twice during its turn."
    "name": "Needle Volley"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) slashing damage."
    "name": "Claw"
  - "desc": "*Ranged Weapon Attack:* +5 to hit, range 60 ft., one target. *Hit:*\
      \ 5 (1d4 + 3) piercing damage."
    "name": "Needle"
"source":
  - "MFF"
"image": "3-Mechanics/CLI/bestiary/plant/token/needle-spawn-mff.webp"
```
^statblock