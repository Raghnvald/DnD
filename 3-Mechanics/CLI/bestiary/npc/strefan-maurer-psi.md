---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Strefan Maurer"
---
# [Strefan Maurer](3-Mechanics/CLI/bestiary/npc/strefan-maurer-psi.md)
*Source: Plane Shift: Innistrad p. 33*  

The history of Strefan Maurer runs parallel to that of Strahd von Zarovich. After his father's death, Strefan studied magic and forged a pact with the demon Shilgengar in return for the promise of immortality. After murdering his brother Sergei and drinking his blood, Strefan journeyed to Markov Manor and consulted with Edgar Markov. Together, they worked with Shilgengar to create the twelve bloodlines of vampires on Innistrad. Maurer Estate (Castle Ravenloft) was not spirited away to a demiplane—it was already on Innistrad, itself a place of nightmares. And Strefan is not trapped here, so he is not seeking a successor in hopes of escaping. Newcomers to his domain do attract his attention, though, as the possibility of meeting a new consort is always on Strefan's mind.

Strefan's statistics are unchanged from the statistics of Strahd in the Curse of Strahd adventure, except that he lacks the Vampire Weaknesses feature. Instead, Strefan has the weaknesses shared by Innistrad vampires (see that earlier section).

```statblock
"name": "Strefan Maurer (PSI)"
"size": "Medium"
"type": "undead"
"subtype": "shapechanger"
"alignment": "Lawful Evil"
"ac": !!int "16"
"ac_class": "natural armor"
"hp": !!int "144"
"hit_dice": "17d8 + 68"
"modifier": !!int "4"
"stats":
  - !!int "18"
  - !!int "18"
  - !!int "18"
  - !!int "20"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "9"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+15"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+10"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+14"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 22"
"languages": "Abyssal, Common, Draconic, Elvish, Giant, Infernal"
"cr": "15"
"traits":
  - "desc": "Strefan is a 9th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 18, +10 to hit with spell attacks). He has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** [mage hand](3-Mechanics/CLI/spells/mage-hand.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](3-Mechanics/CLI/spells/ray-of-frost.md)\n\
      \n**1st level (4 slots):** [comprehend languages](3-Mechanics/CLI/spells/comprehend-languages.md),\
      \ [fog cloud](3-Mechanics/CLI/spells/fog-cloud.md), [sleep](3-Mechanics/CLI/spells/sleep.md)\n\
      \n**2nd level (3 slots):** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [gust of wind](3-Mechanics/CLI/spells/gust-of-wind.md), [mirror image](3-Mechanics/CLI/spells/mirror-image.md)\n\
      \n**3rd level (3 slots):** [animate dead](3-Mechanics/CLI/spells/animate-dead.md),\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md), [nondetection](3-Mechanics/CLI/spells/nondetection.md)\n\
      \n**4th level (3 slots):** [blight](3-Mechanics/CLI/spells/blight.md), [greater\
      \ invisibility](3-Mechanics/CLI/spells/greater-invisibility.md), [polymorph](3-Mechanics/CLI/spells/polymorph.md)\n\
      \n**5th level (1 slots):** [animate objects](3-Mechanics/CLI/spells/animate-objects.md),\
      \ [scrying](3-Mechanics/CLI/spells/scrying.md)"
    "name": "Spellcasting"
  - "desc": "If Strefan isn't in running water or sunlight, he can use his action\
      \ to polymorph into a Tiny bat, a Medium wolf, or a Medium cloud of mist, or\
      \ back into his true form.\n\nWhile in bat or wolf form, Strefan can't speak.\
      \ In bat form, his walking speed is 5 feet, and he has a flying speed of 30\
      \ feet. In wolf form, his walking speed is 40 feet. His statistics, other than\
      \ his size and speed, are unchanged. Anything he is wearing transforms with\
      \ him, but nothing he is carrying does. He reverts to his true form if he dies.\n\
      \nWhile in mist form, Strefan can't take any actions, speak, or manipulate objects.\
      \ He is weightless, has a flying speed of 20 feet, can hover, and can enter\
      \ a hostile creature's space and stop there. In addition, if air can pass through\
      \ a space, the mist can do so without squeezing, and he can't pass through water.\
      \ He has advantage on Strength, Dexterity, and Constitution saving throws, and\
      \ he is immune to all nonmagical damage, except the damage he takes from sunlight."
    "name": "Shapechanger"
  - "desc": "If Strefan fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "When Strefan drops to 0 hit points outside his coffin, he transforms\
      \ into a cloud of mist (as in the Shapechanger trait) instead of falling [unconscious](3-Mechanics/CLI/rules/conditions.md#Unconscious),\
      \ provided that he isn't in running water or sunlight. If he can't transform,\
      \ he is destroyed.\n\nWhile he has 0 hit points in mist form, he can't revert\
      \ to his vampire form, and he must reach his coffin within 2 hours or be destroyed.\
      \ Once in his coffin, he reverts to his vampire form. He is then [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ until he regains at least 1 hit point. After 1 hour in his coffin with 0 hit\
      \ points, he regains 1 hit point."
    "name": "Misty Escape"
  - "desc": "Strefan regains 20 hit points at the start of his turn if he has at least\
      \ 1 hit point and isn't in running water or sunlight. If he takes radiant damage\
      \ or damage from [holy water](3-Mechanics/CLI/items/holy-water-flask.md), this\
      \ trait doesn't function at the start of his next turn."
    "name": "Regeneration"
  - "desc": "Strefan can climb difficult surfaces, including upside down on ceilings,\
      \ without having to make an ability check."
    "name": "Spider Climb"
  - "desc": "Weapons cut from living wood are particularly effective against vampires,\
      \ though any weapon can harm or kill them. A vampire can't cross running water\
      \ that shows the reflection of the moon, and water blessed by Avacyn ([holy\
      \ water](3-Mechanics/CLI/items/holy-water-flask.md)) burns vampire flesh like\
      \ acid. A vampire's reflection in silver (including a silver-backed glass mirror)\
      \ appears as the vampire would have looked without the vampiric condition—neither\
      \ its true appearance nor its glamer, but a normal human, flaws and all. For\
      \ that reason, vampires go to great lengths to avoid mirrors, and the presence\
      \ of silver in any form is unsettling to them."
    "name": "Vampire Vulnerabilities"
"actions":
  - "desc": "Strefan makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 8\
      \ (1d8 + 4) slashing damage, plus 14 (4d6) necrotic damage. If the target\
      \ is a creature, Strefan can grapple it (escape DC 18) instead of dealing the\
      \ slashing damage."
    "name": "Unarmed Strike (Vampire or Wolf Form Only)"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one willing creature,\
      \ or a creature that is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by Strefan, [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
      \ or [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* 7\
      \ (1d6 + 4) piercing damage plus 10 (3d6) necrotic damage. The target's\
      \ hit point maximum is reduced by an amount equal to the necrotic damage taken,\
      \ and Strefan regains hit points equal to that amount. The reduction lasts until\
      \ the target finishes a long rest. The target dies if its hit point maximum\
      \ is reduced to 0. A humanoid slain in this way and then buried in the ground\
      \ rises the following night as a [vampire spawn](3-Mechanics/CLI/bestiary/undead/vampire-spawn.md)\
      \ under Strefan's control."
    "name": "Bite"
  - "desc": "Strefan targets one humanoid he can see within 30 feet of him. If the\
      \ target can see Strefan, the target must succeed on a DC 17 Wisdom saving throw\
      \ against this magic or be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed).\
      \ The [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) target regards\
      \ Strefan as a trusted friend to be heeded and protected. The target isn't under\
      \ Strefan's control, but it takes Strefan's requests and actions in the most\
      \ favorable way and lets Strefan bite it.\n\nEach time Strefan or his companions\
      \ do anything harmful to the target, it can repeat the saving throw, ending\
      \ the effect on itself on a success. Otherwise, the effect lasts 24 hours or\
      \ until Strefan is destroyed, is on a different plane of existence than the\
      \ target, or takes a bonus action to end the effect."
    "name": "Charm"
  - "desc": "Strefan magically calls 2d4 [swarms of bats](3-Mechanics/CLI/bestiary/beast/swarm-of-bats.md)\
      \ or [swarms of rats](3-Mechanics/CLI/bestiary/beast/swarm-of-rats.md), provided\
      \ that the sun isn't up. While outdoors, Strefan can call 3d6 [wolves](3-Mechanics/CLI/bestiary/beast/wolf.md)\
      \ instead. The called creatures arrive in 1d4 rounds, acting as allies of\
      \ Strefan and obeying his spoken commands. The beasts remain for 1 hour, until\
      \ Strefan dies, or until he dismisses them as a bonus action."
    "name": "Children of the Night (1/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Strefan can expend a use to take one of the following actions. Strefan regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Strefan moves up to his speed without provoking opportunity attacks."
    "name": "Move"
  - "desc": "Strefan makes one unarmed strike."
    "name": "Unarmed Strike"
  - "desc": "Strefan makes one bite attack."
    "name": "Bite (Costs 2 Actions)"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/npc/token/strefan-maurer-psi.webp"
```
^statblock