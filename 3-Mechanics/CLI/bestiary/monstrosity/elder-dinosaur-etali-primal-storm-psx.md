---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psx
- ttrpg-cli/monster/cr/30
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/monstrosity/titan
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Elder Dinosaur (Etali, Primal Storm)"
---
# [Elder Dinosaur (Etali, Primal Storm)](3-Mechanics/CLI/bestiary/monstrosity/elder-dinosaur-etali-primal-storm-psx.md)
*Source: Plane Shift: Ixalan p. 34*  

The opening of Orazca, the golden city—which marks the turn between the Ixalan set and Rivals of Ixalan—reveals the existence of six huge and ancient elder dinosaurs, apparently preserved for centuries. Compared to their smaller cousins, they have less brightly-colored plumage and more grayish scales, but their feathers are a bright gold that matches the city around them. They are strong-willed and ferocious, and thus are hard to control. But the power of the Immortal Sun gives the Sun Empire warriors who wield it the ability to bring these elder dinosaurs under their command.

```statblock
"name": "Elder Dinosaur (Etali, Primal Storm) (PSX)"
"size": "Gargantuan"
"type": "monstrosity"
"subtype": "titan"
"alignment": "Unaligned"
"ac": !!int "25"
"ac_class": "natural armor"
"hp": !!int "676"
"hit_dice": "33d20 + 330"
"modifier": !!int "0"
"stats":
  - !!int "30"
  - !!int "11"
  - !!int "30"
  - !!int "3"
  - !!int "11"
  - !!int "11"
"speed": "40 ft."
"saves":
  - "intelligence": !!int "5"
  - "wisdom": !!int "9"
  - "charisma": !!int "9"
"damage_immunities": "fire; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[blindsight](3-Mechanics/CLI/rules/senses.md#Blindsight) 120 ft., passive\
  \ Perception 10"
"languages": ""
"cr": "30"
"traits":
  - "desc": "If the elder dinosaur fails a saving throw, it can choose to succeed\
      \ instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "The elder dinosaur has advantage on saving throws against spells and\
      \ other magical effects."
    "name": "Magic Resistance"
  - "desc": "The elder dinosaur deals double damage to objects and structures."
    "name": "Siege Monster"
  - "desc": "These statistics are shared by all six elder dinosaurs: [Etali, Primal\
      \ Storm](3-Mechanics/CLI/bestiary/monstrosity/elder-dinosaur-etali-primal-storm-psx.md),\
      \ [Ghalta, Primal Hunger](3-Mechanics/CLI/bestiary/monstrosity/elder-dinosaur-ghalta-primal-hunger-psx.md),\
      \ [Nezahal, Primal Tide](3-Mechanics/CLI/bestiary/monstrosity/elder-dinosaur-nezahal-primal-tide-psx.md),\
      \ [Tetzimoc, Primal Death](3-Mechanics/CLI/bestiary/monstrosity/elder-dinosaur-tetzimoc-primal-death-psx.md),\
      \ [Zacama, Primal Calamity](3-Mechanics/CLI/bestiary/monstrosity/elder-dinosaur-zacama-primal-calamity-psx.md),\
      \ [Zetalpa, Primal Dawn](3-Mechanics/CLI/bestiary/monstrosity/elder-dinosaur-zetalpa-primal-dawn-psx.md)"
    "name": "Uniqueness"
  - "desc": "The elder dinosaur is always accompanied by a raging thunderstorm similar\
      \ to the effect of a [call lightning](3-Mechanics/CLI/spells/call-lightning.md)\
      \ spell. A storm cloud in the shape of a cylinder that is 10 feet tall with\
      \ a 60-foot radius instantly forms 100 feet in the air over the elder dinosaur\
      \ when it is angered or becomes violent, as long as it is outdoors. On each\
      \ of its turns, as an action, the elder dinosaur can choose a point it can see\
      \ within 120 feet of it. A bolt of lightning flashes down from the cloud to\
      \ that point. Each creature within 10 feet of that point must make a DC 20 Dexterity\
      \ saving throw, taking 21 (6d6) lightning damage on a failed save, or half\
      \ as much damage on a successful one."
    "name": "Lightning Storm"
"actions":
  - "desc": "Each creature of the elder dinosaur's choice within 120 feet of it and\
      \ aware of it must succeed on a DC 17 Wisdom saving throw or become [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ for 1 minute. A creature can repeat the saving throw at the end of each of\
      \ its turns, with disadvantage if the elder dinosaur is within line of sight,\
      \ ending the effect on itself ona success. If a creature's saving throw is successful\
      \ or the effect ends for it, the creature is immune to the elder dinosaur's\
      \ Frightful Presence for the next 24 hours."
    "name": "Frightful Presence"
  - "desc": "The elder dinosaur makes one bite attack against a Large or smaller creature\
      \ it is grappling. If the attack hits, that creature takes the bite's damage,\
      \ the target is swallowed, and the grapple ends. While swallowed, the creature\
      \ is [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) and [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ it has total cover against attacks and other effects outside the elder dinosaur,\
      \ and it takes 56 (16d6) acid damage at the start of each of the elder dinosaur's\
      \ turns. If the elder dinosaur takes 60 damage or more on a single turn from\
      \ a creature inside it, it must succeed on a DC 20 Constitution saving throw\
      \ at the end of that turn or regurgitate all swallowed creatures, which fall\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone) in a space within 10 feet\
      \ of it. If the elder dinosaur dies, a swallowed creature is no longer [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained)\
      \ by it and can escape from the corpse by using 20 feet of movement, exiting\
      \ [prone](3-Mechanics/CLI/rules/conditions.md#Prone)."
    "name": "Swallow"
  - "desc": "The elder dinosaur can use its Frightful Presence and call down two lightning\
      \ strikes from its Lightning Storm. It then makes three attacks: one with its\
      \ bite and two with its claws."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +19 to hit, reach 10 ft., one target. *Hit:*\
      \ 36 (4d12 + 10) piercing damage. If the target is a creature, it is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ (escape DC 20). Until this grapple ends, the target is [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained),\
      \ and the elder dinosaur can't bite another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +19 to hit, reach 15 ft., one target. *Hit:*\
      \ 28 (4d8 + 10) slashing damage."
    "name": "Claw"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, the elder dinosaur (etali can expend a use to take one of the following\
  \ actions. The elder dinosaur (etali regains all expended uses at the start of each\
  \ of its turns."
"legendary_actions":
  - "desc": "The elder dinosaur makes one claw attack, tail attack, wing attack, or\
      \ flipper attack."
    "name": "Attack"
  - "desc": "The elder dinosaur moves up to half its speed."
    "name": "Move"
  - "desc": "The elder dinosaur makes one bite attack or uses its Swallow."
    "name": "Chomp (Costs 2 Actions)"
"source":
  - "PSX"
"image": "3-Mechanics/CLI/bestiary/monstrosity/token/elder-dinosaur-etali-primal-storm-psx.webp"
```
^statblock