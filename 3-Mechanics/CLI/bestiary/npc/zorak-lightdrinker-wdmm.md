---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/wdmm
- ttrpg-cli/monster/cr/14
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zorak Lightdrinker"
---
# [Zorak Lightdrinker](3-Mechanics/CLI/bestiary/npc/zorak-lightdrinker-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 204*  

```statblock
"name": "Zorak Lightdrinker (WDMM)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "plate armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "17"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "necrotic; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"gear":
  - "[dwarven thrower](3-Mechanics/CLI/items/dwarven-thrower-xdmg.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 17"
"languages": "Common, Dwarvish"
"cr": "14"
"traits":
  - "desc": "Zorak has advantage on saving throws against poison, and has resistance\
      \ against poison damage."
    "name": "Dwarven Resilience"
  - "desc": "If Zorak isn't in sunlight or running water, he can use his action to\
      \ polymorph into a Tiny bat or a Medium cloud of mist, or back into his true\
      \ form.\n\nWhile in bat form, Zorak can't speak, his walking speed is 5 feet,\
      \ and he has a flying speed of 30 feet. His statistics, other than his size\
      \ and speed, are unchanged. Anything he is wearing transforms with it, but nothing\
      \ he is carrying does. He reverts to his true form if he dies.\n\nWhile in mist\
      \ form, Zorak can't take any actions, speak, or manipulate objects. He is weightless,\
      \ has a flying speed of 20 feet, can hover, and can enter a hostile creature's\
      \ space and stop there. In addition, if air can pass through a space, the mist\
      \ can do so without squeezing, and he can't pass through water. He has advantage\
      \ on Strength, Dexterity, and Constitution saving throws, and he is immune to\
      \ all nonmagical damage, except the damage he takes from sunlight."
    "name": "Shapechanger"
  - "desc": "If Zorak fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "When he drops to 0 hit points outside his resting place, Zorak transforms\
      \ into a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious),\
      \ provided that he isn't in sunlight or running water. If he can't transform,\
      \ he is destroyed.\n\nWhile he has 0 hit points in mist form, he can't revert\
      \ to his vampire form, and he must reach his resting place within 2 hours or\
      \ be destroyed. Once in his resting place, he reverts to his vampire form. He\
      \ is then [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed) until he\
      \ regains at least 1 hit point. After spending 1 hour in his resting place with\
      \ 0 hit points, he regains 1 hit point."
    "name": "Misty Escape"
  - "desc": "Zorak regains 20 hit points at the start of his turn if he has at least\
      \ 1 hit point and isn't in sunlight or running water. If Zorak takes radiant\
      \ damage or damage from [holy water](3-Mechanics/CLI/items/holy-water-xphb.md),\
      \ this trait doesn't function at the start of Zorak's next turn."
    "name": "Regeneration"
  - "desc": "Zorak can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "Zorak has the following flaws:\n\n- **Forbiddance.** Zorak can't enter\
      \ a residence without an invitation from one of the occupants.  \n- **Harmed\
      \ by Running Water.** Zorak takes 20 acid damage if he ends his turn in running\
      \ water.  \n- **Stake to the Heart.** If a piercing weapon made of wood is driven\
      \ into Zorak's heart while Zorak is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ in his resting place, Zorak is [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ until the stake is removed.  \n- **Sunlight Hypersensitivity.** Zorak takes\
      \ 20 radiant damage when he starts his turn in sunlight. While in sunlight,\
      \ he has disadvantage on attack rolls and ability checks  "
    "name": "Vampire Weaknesses"
"actions":
  - "desc": "Zorak makes two attacks with his [dwarven thrower](3-Mechanics/CLI/items/dwarven-thrower-xdmg.md),\
      \ only one of which can be a ranged attack."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +12 to hit, reach 5 ft. or range\
      \ 20/60 ft., one target. *Hit:* 11 (1d8 + 7) bludgeoning damage, or 12 (1d10\
      \ + 7) bludgeoning damage when used with two hands to make a melee attack.\
      \ On a ranged attack that hits, the hammer deals an extra 1d8 bludgeoning\
      \ damage (2d8 if the target is a giant). *Hit or Miss:* If thrown, the weapon\
      \ flies back to Zorak's hand after the attack."
    "name": "Dwarven Thrower"
  - "desc": "Zorak makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one creature. *Hit:*\
      \ 8 (1d8 + 4) bludgeoning damage. Instead of dealing damage, Zorak can grapple\
      \ the target (escape DC 18)."
    "name": "Unarmed Strike (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one willing creature,\
      \ or a creature that is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by Zorak, [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
      \ or [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* 7\
      \ (1d6 + 4) piercing damage plus 10 (3d6) necrotic damage. The target's\
      \ hit point maximum is reduced by an amount equal to the necrotic damage taken,\
      \ and Zorak regains hit points equal to that amount. The reduction lasts until\
      \ the target finishes a long rest. The target dies if this effect reduces his\
      \ hit point maximum to 0. A humanoid slain in this way and then buried in the\
      \ ground rises the following night as a [vampire spawn](3-Mechanics/CLI/bestiary/undead/vampire-spawn-xmm.md)\
      \ under Zorak's control."
    "name": "Bite (Bat or Vampire Form Only)"
  - "desc": "Zorak targets one humanoid he can see within 30 feet of it. If the target\
      \ can see Zorak, the target must succeed on a DC 17 Wisdom saving throw against\
      \ this magic or be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) by\
      \ Zorak. The [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) target regards\
      \ Zorak as a trusted friend to be heeded and protected. Although the target\
      \ isn't under Zorak's control, it takes Zorak's requests or actions in the most\
      \ favorable way it can, and it is a willing target for Zorak's bite attack.\n\
      \nEach time Zorak or Zorak's companions do anything harmful to the target, it\
      \ can repeat the saving throw, ending the effect on itself on a success. Otherwise,\
      \ the effect lasts 24 hours or until Zorak is destroyed, is on a different plane\
      \ of existence than the target, or takes a bonus action to end the effect."
    "name": "Charm"
  - "desc": "Zorak magically calls 2d4 swarms of [bats](3-Mechanics/CLI/bestiary/beast/swarm-of-bats-xmm.md)\
      \ or [rats](3-Mechanics/CLI/bestiary/beast/swarm-of-rats-xmm.md), provided that\
      \ the sun isn't up. While outdoors, Zorak can call 3d6 [wolves](3-Mechanics/CLI/bestiary/beast/wolf-xmm.md)\
      \ instead. The called creatures arrive in 1d4 rounds, acting as allies of\
      \ Zorak and obeying his spoken commands. The beasts remain for 1 hour, until\
      \ Zorak dies, or until Zorak dismisses them as a bonus action."
    "name": "Children of the Night (1/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Zorak can expend a use to take one of the following actions. Zorak regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Zorak moves up to his speed without provoking opportunity attacks."
    "name": "Move"
  - "desc": "Zorak makes one unarmed strike."
    "name": "Unarmed Strike"
  - "desc": "Zorak makes one bite attack."
    "name": "Bite (Costs 2 Actions)"
"source":
  - "WDMM"
"image": "3-Mechanics/CLI/bestiary/npc/token/zorak-lightdrinker-wdmm.webp"
```
^statblock