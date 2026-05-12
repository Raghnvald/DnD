---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Maelephant Nomad"
---
# [Maelephant Nomad](3-Mechanics/CLI/bestiary/fiend/maelephant-nomad-coa.md)
*Source: Chains of Asmodeus p. 245*  

Created with the sole purpose of protection, maelephants are the most loyal of the devils. They eschew personal possessions, dreams, and goals, and find happiness in the completion of their duty. While other devils may view them as simple and unintelligent, many recognize the importance and utility of maelephants. Infernal and common are often spoken languages, but maelephants also maintain their own unique language, which they use exclusively in communication with others of their kind.

## Elephantine Warriors

As their name would suggest, maelephants share many physical features with elephants. They stand on two legs, but have an elephant-like head and legs. Their trunk usually ends in a sharp spike, and their hands and feet are both clawed. When threatened, maelephants emit a cloud of toxins that cause brain damage and memory loss.

## Driven by Duty

Despite them being lower-ranked devils, their position as trustworthy guardians makes other lower devils respect maelephants. When not under active duty or protecting something, a maelephant might aimlessly wander the layers searching for a new charge. Some of these nomads wander many years before finally ending their search.

```statblock
"name": "Maelephant Nomad (CoA)"
"size": "Large"
"type": "fiend"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "chain mail"
"hp": !!int "190"
"hit_dice": "20d10 + 80"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "11"
  - !!int "18"
  - !!int "14"
  - !!int "17"
  - !!int "15"
"speed": "40 ft."
"saves":
  - "strength": !!int "11"
  - "constitution": !!int "9"
"skillsaves":
  - "name": "Athletics"
    "desc": "+16"
  - "name": "Insight"
    "desc": "+8"
  - "name": "Intimidation"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+8"
"damage_resistances": "acid; fire; lightning; bludgeoning, piercing, slashing from\
  \ nonmagical attacks"
"condition_immunities": "frightened, poisoned"
"senses": "blindsight 30 ft., darkvision 120 ft., passive Perception 18"
"languages": "Common, Infernal, Maelephant"
"cr": "14"
"traits":
  - "desc": "The maelephant has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "At the start of its turn, if the maelephant has less than half its hit\
      \ points, it regenerates 20 hit points. This trait doesn't function if the maelephant\
      \ starts its turn with less than 1 hit point."
    "name": "Regenerative"
"actions":
  - "desc": "The maelephant makes two attacks using its Claw, Trunk, or a combination\
      \ of the two."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 5 ft., one target. *Hit:*\
      \ 17 (2d10 + 6) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +11 to hit, reach 10 ft., one target. *Hit:*\
      \ 16 (3d6 + 6) piercing damage. If the target is a Medium or smaller creature,\
      \ it has the grappled condition (escape DC 18). Until this grapple ends, the\
      \ target has the restrained condition. While it is grappling a creature, the\
      \ maelephant can't use its Trunk attack against other creatures."
    "name": "Trunk"
  - "desc": "The maelephant releases a cloud of noxious gas. All creatures in a 30-foot\
      \ cone in front of the maelephant must make a DC 16 Constitution saving throw.\
      \ Targets take 42 (12d6) acid damage on a failed save, or half as much damage\
      \ on a successful one. In addition, on a failed save, the creature's Intelligence\
      \ and Charisma scores become 1. The creature can't cast spells, activate magic\
      \ items, understand language, or communicate in any intelligible way. The creature\
      \ can, however, identify its friends, follow them, and even protect them. A\
      \ feebled creature can repeat the save every minute, ending the effect on a\
      \ success."
    "name": "Noxious Breath (Recharge 5-6)"
"bonus_actions":
  - "desc": "The maelephant moves up to 40 feet towards a creature it can see and\
      \ if it moves at least 20 feet in a straight line, it may make a Claw attack.\
      \ On a hit, the target takes an additional 14 (4d6) force damage and has the\
      \ prone condition."
    "name": "Reckless Charge"
"reactions":
  - "desc": "As a reaction to taking damage, the maelephant enters a defensive stance\
      \ until the end of its next turn. While in a defensive stance, the maelephant\
      \ moves at half speed and can't take bonus actions, but its AC increases by\
      \ 5."
    "name": "Defensive Stance"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/fiend/token/maelephant-nomad-coa.webp"
```
^statblock