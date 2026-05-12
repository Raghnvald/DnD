---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead/wizard
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sammaster (Lich Form)"
---
# [Sammaster (Lich Form)](3-Mechanics/CLI/bestiary/npc/sammaster-lich-form-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 276*  

## Sammaster

*Lich Founder of a Dracolich Cult*

Sammaster founded and led the Cult of the Dragon, a secret, evil organization dedicated to transforming living dragons into undead inheritors of a world blasted of life. Sammaster was slain centuries ago but now exists as a lich with his essence tied to a powerful dracolich form.

## History

Sammaster was a keenly intelligent wizard born centuries ago. A quick study throughout his itinerant apprenticeship, Sammaster primarily studied magic relating to dragons. After learning all he could from other archmages, including Elminster and Alustriel Silverhand, Sammaster delved into new frontiers of necromancy and enchantment. He created the process to transform dragons into dracoliches, magically bound dragons to his service, and learned how to drive dragons across Faerûn into a berserk rage. He considered his intellect beyond morality and became paranoid, resentful, and megalomaniacal.

Sammaster's travels brought him into contact with people who revered dragons as icons of primeval might. Masquerading his desire to dominate dragonkind as devotion, Sammaster established himself

as leader of these disparate zealots, whom he named the Cult of the Dragon. He perverted their fascination with his necromantic lore, revealing that dracoliches were destined to rule Faerûn. His Cult of the Dragon devotes itself to helping evil dragons become dracoliches to bring this evil new age to fruition.

Sammaster was killed in battle, but had prepared contingencies for his demise. He drew on the warped resurrection of dracoliches to become a lich himself. He continues to lead the Cult of the Dragon from the shadows, developing new ways to control and corrupt dragonkind.

## Personality

Sammaster presents a charming and handsome facade, but he can't conceal his morbid fascination with undead dragonkind for long. His only true allies are the inner circle of the Cult of the Dragon, from whom he commands obedience.

Sammaster rarely remains in one place for long, as he thinks no one can oversee the Cult of the Dragon activities across the Realms as efficiently as he can. Sammaster personally checks in on the cult's most important plots, often surprising his minions with his presence.

Rather than keep a soul jar as liches do, Sammaster keeps a magical soul gem in the same fashion as dracoliches. When destroyed in his lich form, Sammaster revives in the form of a dracolich with his soul gem as its heart. He can be permanently destroyed only by vanquishing this dracolich form and then destroying the soul gem before it reconstitutes him as a lich once again.

Would-be heroes have believed themselves victorious against Sammaster in the past, but the clever wizard returns each time to steer the Cult of the Dragon into more desperate and sinister plots.

```statblock
"name": "Sammaster (Lich Form) (FRAiF)"
"size": "Medium"
"type": "undead"
"subtype": "wizard"
"alignment": "Chaotic Evil"
"ac": !!int "18"
"hp": !!int "322"
"hit_dice": "43d8 + 129"
"modifier": !!int "16"
"stats":
  - !!int "12"
  - !!int "14"
  - !!int "16"
  - !!int "23"
  - !!int "15"
  - !!int "21"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "9"
  - "constitution": !!int "10"
  - "intelligence": !!int "13"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+20"
  - "name": "History"
    "desc": "+13"
  - "name": "Perception"
    "desc": "+9"
"damage_resistances": "acid, cold, lightning"
"damage_immunities": "necrotic, poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "Blindsight 60 ft., Darkvision 120 ft., passive Perception 19"
"languages": "Common, Draconic, Infernal"
"cr": "22"
"traits":
  - "desc": "If Sammaster fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Creatures within 60 feet of Sammaster can't regain <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span>."
    "name": "Life Suppression"
  - "desc": "Sammaster has <span title=\"Player's Handbook (2024)\">Advantage</span>\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
  - "desc": "If Sammaster is reduced to 0 <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span> while his magical soul gem exists, his lich form dissolves\
      \ to dust. After 1d10 days, he appears in the space of his soul gem, using\
      \ the Sammaster (Dracolich Form) stat block. The gem is a Tiny object that has\
      \ AC 20; HP 50; and <span title=\"Player's Handbook (2024)\">Immunity</span>\
      \ to Acid, Necrotic, Poison, and Psychic damage. The gem regains all its <span\
      \ title=\"Player's Handbook (2024)\">Hit Points</span> at the end of every turn,\
      \ but it turns to dust if reduced to 0 <span title=\"Player's Handbook (2024)\"\
      >Hit Points</span>. If the gem is destroyed, Sammaster can create a new one\
      \ by completing an 8-hour ritual using a gem worth 1,000+ GP, which the ritual\
      \ consumes, and by expending 5,000 GP."
    "name": "Soul Gem"
"actions":
  - "desc": "Sammaster makes three attacks, using Corrosive Burst or Paralyzing Touch\
      \ in any combination. He can replace two attacks with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +13, reach 5 ft. or range 120 ft. *Hit:*\
      \ 38 (5d12 + 6) Acid or Necrotic damage (Sammaster's choice)."
    "name": "Corrosive Burst"
  - "desc": "*Melee Attack Roll:* +13, reach 5 ft. *Hit:* 16 (3d6 + 6) Cold damage,\
      \ and the target has the Paralyzed condition until the start of Sammaster's\
      \ next turn."
    "name": "Paralyzing Touch"
  - "desc": "Sammaster casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 21):\n\n\
      **At will:** Cone of Cold, Detect Magic, Dispel Magic, Invisibility, Mage Hand,\
      \ Prestidigitation\n\n**2/day each:** Speak with Dead, Wall of Force\n\n**1/day\
      \ each:** Create Undead (level 8 version), Disintegrate, Power Word Kill"
    "name": "Spellcasting"
"reactions":
  - "desc": "Sammaster casts Counterspell or Shield in response to the spell's trigger,\
      \ using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Sammaster can expend a use to take one of the following actions. Sammaster\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Sammaster teleports up to 60 feet to an unoccupied space he can see,\
      \ and each creature within 10 feet of the space he left takes 19 (3d12) Necrotic\
      \ damage."
    "name": "Deathly Teleport"
  - "desc": "Sammaster makes one Corrosive Burst attack."
    "name": "Dissolve"
  - "desc": "*Wisdom Saving Throw:* DC 21, each creature in a 20-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from Sammaster. *Failure:*\
      \ 13 (2d12) Psychic damage, and the target has the Frightened condition until\
      \ the end of its next turn. *Failure or Success:* Sammaster can't take this\
      \ action again until the start of his next turn."
    "name": "Terrifying Presence"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/npc/token/sammaster-lich-form-fraif.webp"
```
^statblock