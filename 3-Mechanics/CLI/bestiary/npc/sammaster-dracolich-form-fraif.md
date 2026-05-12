---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/fraif
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sammaster (Dracolich Form)"
---
# [Sammaster (Dracolich Form)](3-Mechanics/CLI/bestiary/npc/sammaster-dracolich-form-fraif.md)
*Source: Forgotten Realms: Adventures in Faerûn p. 275*  

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
"name": "Sammaster (Dracolich Form) (FRAiF)"
"size": "Huge"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "20"
"hp": !!int "276"
"hit_dice": "24d12 + 120"
"modifier": !!int "14"
"stats":
  - !!int "25"
  - !!int "10"
  - !!int "21"
  - !!int "23"
  - !!int "15"
  - !!int "21"
"speed": "40 ft., burrow 30 ft., fly 80 ft."
"saves":
  - "dexterity": !!int "7"
  - "constitution": !!int "12"
  - "intelligence": !!int "13"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "Arcana"
    "desc": "+20"
  - "name": "History"
    "desc": "+13"
  - "name": "Perception"
    "desc": "+16"
"damage_immunities": "acid, necrotic, poison"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, poisoned"
"senses": "Blindsight 60 ft., Darkvision 120 ft., passive Perception 26"
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
  - "desc": "Sammaster has a magical soul gem as his dracolich heart. The gem can't\
      \ be damaged or removed until he is reduced to 0 <span title=\"Player's Handbook\
      \ (2024)\">Hit Points</span>. If Sammaster is reduced to 0 <span title=\"Player's\
      \ Handbook (2024)\">Hit Points</span>, his dracolich form dissolves to dust.\
      \ After 1d10 days, he appears in an unoccupied space within 5 feet of his\
      \ soul gem (so long as the gem still exists), using the Sammaster (Lich Form)\
      \ stat block. The gem is a Tiny object that has AC 20; HP 50; and <span title=\"\
      Player's Handbook (2024)\">Immunity</span> to Acid, Necrotic, Poison, and Psychic\
      \ damage. The gem regains all its <span title=\"Player's Handbook (2024)\">Hit\
      \ Points</span> at the end of every turn, but it turns to dust if reduced to\
      \ 0 <span title=\"Player's Handbook (2024)\">Hit Points</span>."
    "name": "Soul Gem"
"actions":
  - "desc": "Sammaster makes three Rend attacks. He can replace one attack with a\
      \ use of Spellcasting to cast Blight or Ray of Sickness (level 6 version)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +14, reach 10 ft. *Hit:* 18 (2d10 + 7) Slashing\
      \ damage plus 18 (4d8) Necrotic damage."
    "name": "Rend"
  - "desc": "*Constitution Saving Throw:* DC 20, each creature in a 90-foot <span\
      \ title=\"Player's Handbook (2024)\">Cone</span>. *Failure:* 52 (8d12) Acid\
      \ or Necrotic damage (Sammaster's choice). *Success:* Half damage."
    "name": "Corroding Breath (Recharge 5-6)"
  - "desc": "Sammaster casts one of the following spells, requiring no Material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 21, +13\
      \ to hit with spell attacks):\n\n**At will:** Blight, Detect Magic, Dispel Magic,\
      \ Mage Hand, Prestidigitation, Ray of Sickness (level 6 version)\n\n**2/day\
      \ each:** Dimension Door, Speak with Dead\n\n**1/day each:** Create Undead (level\
      \ 8 version), Power Word Kill"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Sammaster can expend a use to take one of the following actions. Sammaster\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Sammaster moves up to half his <span title=\"Player's Handbook (2024)\"\
      >Speed</span>, and he makes one Rend attack."
    "name": "Pounce"
  - "desc": "Sammaster uses Spellcasting to cast Ray of Sickness (level 6 version)."
    "name": "Sickening Ray"
  - "desc": "*Wisdom Saving Throw:* DC 21, each creature in a 20-foot <span title=\"\
      Player's Handbook (2024)\">Emanation</span> originating from Sammaster. *Failure:*\
      \ 13 (2d12) Psychic damage, and the target has the Frightened condition until\
      \ the end of its next turn. *Failure or Success:* Sammaster can't take this\
      \ action again until the start of his next turn."
    "name": "Terrifying Presence"
"source":
  - "FRAiF"
"image": "3-Mechanics/CLI/bestiary/npc/token/sammaster-dracolich-form-fraif.webp"
```
^statblock