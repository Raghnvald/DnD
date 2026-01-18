---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/wdh
  - Monster/HG/4
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Konstrukt
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Nimblewright
---
# [Nimblewright](3-Mechanics\CLI\bestiary\construct/nimblewright-wdh.md)
*Source: Waterdeep: Dragon Heist p. 212*  

A nimblewright is a magical construct created to serve as a guard or assassin. Composed predominantly of lightweight wood and powered by magic, it can pass for humanoid while wearing clothing. Some nimblewrights wear plain clothing, while others are clad in flashier attire. A nimblewright is emotionless, its face frozen in whatever expression was given to it by its creator.

## Duelist

A nimblewright moves like a dancer and fights like a swashbuckler, using dodges and parries to avoid damage while deftly skewering its foes.

## Constructed Nature

A nimblewright doesn't require air, food, drink, or sleep. Damage it takes can be repaired with mending spells, but a nimblewright reduced to 0 hit points is permanently destroyed.

```statblock
"name": "Nimblewright (WDH)"
"size": "Medium"
"type": "construct"
"alignment": "Unaligned"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "45"
"hit_dice": "6d8 + 18"
"modifier": !!int "4"
"stats":
  - !!int "12"
  - !!int "18"
  - !!int "17"
  - !!int "8"
  - !!int "10"
  - !!int "6"
"speed": "60 ft."
"saves":
  - "dexterity": !!int "6"
"skillsaves":
  - "name": "Acrobatics"
    "desc": "+8"
  - "name": "Perception"
    "desc": "+2"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "exhaustion, frightened, petrified, poisoned"
"senses": "darkvision 60 ft., passive Perception 12"
"languages": "understands one language known to its creator but can't speak"
"cr": "4"
"traits":
  - "desc": "The nimblewright has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
  - "desc": "The nimblewright's weapon attacks are magical."
    "name": "Magic Weapons"
  - "desc": "As long as it has at least 1 hit point remaining, the nimblewright regains\
      \ 1 hit point when a mending spell is cast on it."
    "name": "Repairable"
  - "desc": "The nimblewright has advantage on Strength and Dexterity saving throws\
      \ made against effects that would knock it prone."
    "name": "Sure-Footed"
"actions":
  - "desc": "The nimblewright makes three attacks: two with its rapier and one with\
      \ its dagger."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) piercing damage."
    "name": "Rapier"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d4\
      \ + 4) piercing damage. Or Ranged Weapon Attack: +6 to hit, range 20/60 ft.,\
      \ one target. *Hit:* 6 (1d4 + 4) piercing damage."
    "name": "Dagger"
"reactions":
  - "desc": "The nimblewright adds 2 to its AC against one melee attack that would\
      \ hit it. To do so, the nimblewright must see the attacker and be wielding a\
      \ melee weapon."
    "name": "Parry"
"source":
  - "WDH"
"image": "/3-Mechanics/CLI/bestiary/construct/token/nimblewright-wdh.webp"
```
^statblock