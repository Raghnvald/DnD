---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-fcd
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Tyreus, Illusionist"
---
# [Tyreus, Illusionist](3-Mechanics/CLI/bestiary/npc/tyreus-illusionist-aitfr-fcd.md)
*Source: Adventures in the Forgotten Realms: From Cyan Depths p. 11*  

When he was young, living in the vast, internecine planar city of Ravnica, Tyreus's parents, Tyberio and Ayraea, forbade him from pursuing any study of magic or wizardry. They didn't want Tyreus embroiled in a life of danger and skullduggery—as was common in Ravnica. But Tyreus came to understand that at least part of his father's motive for forbidding magic was Tyberio's own rebellion against his adventurous parents. When he learned that his grandmother had once been a powerful mage, Tyreus wanted to follow in her footsteps.

## Power Hungry

Tyreus has always wanted to be distinctive, admired, and powerful. He saw magic as a way to achieve a greatness he felt Tyberio had tried to deny him. In secret, Tyreus sought out ways to learn magic, but as he was forced to hide his ambition and his studies, he found cohorts in the worst places. Evil mages stoked his hunger for power and eroded his conscience.

## Mundane Fury

Tyreus went months without speaking to his parents. Before he even knew they were sick, Tyberio and Ayraea passed away. Furious at his inability to help them—and their silent stubbornness—Tyreus sought the kind of power that would help him create places he could control. First, he studied the magic of illusions. He thought he could create illusions so real that he could live within them, fool others, and thus control his own destiny. Then he found another possibility.

## Selfish Pursuits

In journals Tyberio had hidden from him, written by Tyberio's mother, the wizard Sylvene, Tyreus found tales of the Stone of Creation, an artifact capable of creating places and structures seemingly from the imagination alone. Tyreus thus sought out everything he could learn about Sylvene and the Stone, leading him to another world—Faerûn—and the remote Highstar Lake, where the Stone was lost long ago.

## Lost to Ambition

It may be too late for Tyreus. He has devoted himself to his own grandeur now and lost sight of why he wanted power in the first place. He doesn't want to help anyone but himself. He sees those who would help him or share in his ambitions as threats to his own power. He doesn't want approval or alliances; he wants subservience. Whether he realizes it or not, he doesn't care whom he hurts to get what he wants.

## Personality Traits

"I laugh to buy myself time to think, even though my gut instincts are often better than most people's calculated efforts."

## Ideals

"Power. People try to take things from me, to limit or deny me, but I don't allow it. Real power is deciding other people's fates."

## Bonds

"I'll make time for other people when I have a kingdom to call my own. Then I'll know who I can trust: the people who don't get in my way."

## Flaws

"I have a bad temper. Why can't people see I know what I'm doing?"

```statblock
"name": "Tyreus, Illusionist (AitFR-FCD)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "13"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"modifier": !!int "3"
"stats":
  - !!int "10"
  - !!int "16"
  - !!int "14"
  - !!int "20"
  - !!int "15"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "10"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Arcana"
    "desc": "+12"
  - "name": "Deception"
    "desc": "+8"
  - "name": "History"
    "desc": "+10"
  - "name": "Perception"
    "desc": "+7"
"damage_resistances": "damage from spells; nonmagical bludgeoning, piercing, slashing\
  \ (from stoneskin)"
"gear":
  - "dagger"
"senses": "passive Perception 17"
"languages": "Common, Deep Speech, Draconic, Primordial, Sylvan"
"cr": "13"
"traits":
  - "desc": "Tyreus is a 16th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 18, +10 to hit with spell attacks). He has the following\
      \ wizard spells prepared.\n\n**Cantrips (at will):** fire bolt, light, mage\
      \ hand, minor illusion, shocking grasp\n\n**1st level (4 slots):** mage armor,\
      \ magic missile, shield, thunderwave\n\n**2nd level (3 slots):** invisibility*,\
      \ mirror image*, phantasmal force*\n\n**3rd level (3 slots):** counterspell,\
      \ fly, lightning bolt, major image*\n\n**4th level (3 slots):** banishment,\
      \ hallucinatory terrain*, phantasmal killer*, stoneskin\n\n**5th level (2 slots):**\
      \ conjure elemental, mislead*, telekinesis\n\n**6th level (1 slots):** disintegrate\n\
      \n**7th level (1 slots):** plane shift\n\n**8th level (1 slots):** maze\n\n\
      *(Illusion spell of 1st level or higher)"
    "name": "Spellcasting"
  - "desc": "If Tyreus fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "When Tyreus casts an illusion spell of 1st level or higher, he can choose\
      \ one inanimate, nonmagical object that is part of the illusion and make that\
      \ object real. He can do this on his turn as a bonus action while the spell\
      \ is ongoing.\n\nThe object remains real for 1 minute. The object can't deal\
      \ damage or otherwise directly harm anyone."
    "name": "Illusory Reality"
  - "desc": "As a bonus action, Tyreus projects an illusion that makes him appear\
      \ to be standing a few inches from his actual location, causing any creature\
      \ to have disadvantage on attack rolls against Tyreus. The effect ends if Tyreus\
      \ takes damage, he is incapacitated, or his speed becomes 0."
    "name": "Displacement (Recharges after Tyreus Casts an Illusion Spell of 1st Level\
      \ or Higher)"
"actions":
  - "desc": "*Melee  or Ranged Weapon Attack:* +8 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d4 + 3) piercing damage."
    "name": "Dagger"
  - "desc": "When Tyreus casts an illusion spell that has a duration of 1 minute or\
      \ longer, he can use his action to change the nature of that illusion (using\
      \ the spell's normal parameters for the illusion), provided that he can see\
      \ the illusion."
    "name": "Modify Illusion"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Tyreus can expend a use to take one of the following actions. Tyreus regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Tyreus makes an Intelligence (Investigation) or Wisdom (Perception) check."
    "name": "Scrutinize"
  - "desc": "Tyreus casts a cantrip from his spell list."
    "name": "Cast Cantrip"
  - "desc": "Tyreus uses a spell slot to cast a 1st-, 2nd-, or 3rd-level spell that\
      \ he has prepared. Doing so costs 1 legendary action per level of the spell."
    "name": "Cast Spell (Costs 1-3 Actions)"
"source":
  - "AitFR-FCD"
"image": "3-Mechanics/CLI/bestiary/npc/token/tyreus-illusionist-aitfr-fcd.webp"
```
^statblock