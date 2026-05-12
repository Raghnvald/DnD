---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/egw
- ttrpg-cli/monster/cr/16
- ttrpg-cli/monster/size/gargantuan
- ttrpg-cli/monster/type/fiend
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Udaak"
---
# [Udaak](3-Mechanics/CLI/bestiary/fiend/udaak-egw.md)
*Source: Explorer's Guide to Wildemount p. 301*  

Known commonly as the brutes of Xhorhas, these enormous creatures resemble an immense, demonic cross between ox and gorilla. Udaaks are solitary wanderers, found most commonly along the edges of settled lands in the barrens of Eastern Wynandir. Though they often scavenge for food, a hungry udaak will attack almost any prey, its four sets of red eyes and its tangle of teeth and tusks striking fear into the heart of any creature.

Living Siege Engine. Originally brought to Exandria from the Abyss, udaaks lost their connection to that realm after the Divergence and have roamed the world freely ever since. In recent years, the warmasters of the Kryn Dynasty have developed arcane collars that can keep an udaak under control, and they have begun using these dread creatures in the war against the Dwendalian Empire.

```statblock
"name": "Udaak (EGW)"
"size": "Gargantuan"
"type": "fiend"
"alignment": "Neutral Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "165"
"hit_dice": "10d20 + 60"
"modifier": !!int "2"
"stats":
  - !!int "26"
  - !!int "14"
  - !!int "22"
  - !!int "3"
  - !!int "11"
  - !!int "10"
"speed": "50 ft."
"saves":
  - "strength": !!int "13"
  - "constitution": !!int "11"
"damage_vulnerabilities": "thunder"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "frightened, grappled, poisoned, restrained"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": ""
"cr": "16"
"traits":
  - "desc": "If the udaak moves at least 20 feet straight toward a target and then\
      \ hits it with a slam attack on the same turn, the target takes an extra 27\
      \ (6d8) bludgeoning damage. If the target is a creature, it must succeed on\
      \ a DC 21 Strength saving throw or be pushed up to 20 feet away from the udaak\
      \ and knocked prone."
    "name": "Charge"
  - "desc": "The udaak deals double damage to objects and structures."
    "name": "Siege Monster"
"actions":
  - "desc": "The udaak makes three attacks: one with its bite and two with its slam."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 5 ft., one creature. *Hit:*\
      \ 21 (2d12 + 8) piercing damage, and the target is grappled (escape DC 21).\
      \ Until this grapple ends, the target is restrained, and the udaak can't bite\
      \ another target."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +13 to hit, reach 10 ft., one target. *Hit:*\
      \ 21 (3d8 + 8) bludgeoning damage."
    "name": "Slam"
  - "desc": "The udaak makes one bite attack against a Large or smaller target it\
      \ is grappling. If the attack hits, the target is also swallowed, and the grapple\
      \ ends. A swallowed creature is blinded and restrained, it has total cover against\
      \ attacks and other effects outside the udaak, and it takes 21 (6d6) acid\
      \ damage at the start of each of the udaak's turns.\n\nIf the udaak takes 30\
      \ damage or more on a single turn from a creature inside it, the udaak must\
      \ succeed on a DC 21 Constitution saving throw at the end of that turn or regurgitate\
      \ all swallowed creatures, which fall prone in a space within 10 feet of the\
      \ udaak. If the udaak dies, a swallowed creature is no longer restrained by\
      \ it and can escape from the corpse by using 20 feet of movement, exiting prone."
    "name": "Swallow"
"source":
  - "EGW"
"image": "3-Mechanics/CLI/bestiary/fiend/token/udaak-egw.webp"
```
^statblock