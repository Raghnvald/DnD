---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/1-4
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/plant
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vegepygmy Scavenger"
---
# [Vegepygmy Scavenger](3-Mechanics/CLI/bestiary/plant/vegepygmy-scavenger-qftis.md)
*Source: Quests from the Infinite Staircase p. 218*  

Vegepygmies rely on scavengers to salvage materials from their surroundings. Vegepygmy scavengers use stealth to bring food, tools, and weapons back to the colony. These scavengers leverage their nimbleness and natural camouflage to evade foes and pelt them with slings from the cover of leafy foliage.

## Vegepygmies

Also called mold folk, vegepygmies are fungal creatures that spring forth from the body of a Humanoid or Giant killed by russet mold, a poisonous fungus rumored to have originated from beyond the stars.

Vegepygmies gather in small bands, communicating with a combination of gestures, hisses, and rhythmic taps. While vegepygmies can sustain themselves by absorbing nutrients from soil and other organic matter, they prefer a carnivorous diet achieved through hunting and scavenging. Vegepygmies can live indefinitely so long as the climate remains hospitable to their fungal bodies.

To learn more about vegepygmies, see Monsters of the Multiverse.

```statblock
"name": "Vegepygmy Scavenger (QftIS)"
"size": "Small"
"type": "plant"
"alignment": "typically  Neutral"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "13"
"hit_dice": "3d6 + 3"
"modifier": !!int "2"
"stats":
  - !!int "7"
  - !!int "14"
  - !!int "13"
  - !!int "6"
  - !!int "11"
  - !!int "7"
"speed": "30 ft."
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Sleight of Hand](3-Mechanics/CLI/rules/skills.md#Sleight%20of%20Hand)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+4"
"damage_resistances": "lightning, piercing"
"gear":
  - "[sling](3-Mechanics/CLI/items/sling.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": "Vegepygmy"
"cr": "1/4"
"traits":
  - "desc": "The vegepygmy has advantage on Dexterity ([Stealth](3-Mechanics/CLI/rules/skills.md#Stealth))\
      \ checks it makes in any terrain with ample obscuring vegetation."
    "name": "Plant Camouflage"
  - "desc": "The vegepygmy regains 3 hit points at the start of its turn. If it takes\
      \ cold, fire, or necrotic damage, this trait doesn't function at the start of\
      \ the vegepygmy's next turn. The vegepygmy dies only if it starts its turn with\
      \ 0 hit points and doesn't regenerate."
    "name": "Regeneration"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) slashing damage."
    "name": "Claw"
  - "desc": "*Ranged Weapon Attack:* +4 to hit, range 30/120 ft., one target. *Hit:*\
      \ 4 (1d4 + 2) bludgeoning damage."
    "name": "Sling"
"bonus_actions":
  - "desc": "The vegepygmy takes the [Disengage](3-Mechanics/CLI/rules/actions.md#Disengage)\
      \ or [Hide](3-Mechanics/CLI/rules/actions.md#Hide) action."
    "name": "Nimble Escape"
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/plant/token/vegepygmy-scavenger-qftis.webp"
```
^statblock