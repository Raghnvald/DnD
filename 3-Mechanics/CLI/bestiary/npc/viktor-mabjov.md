---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/9
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Viktor"
---
# [Viktor](3-Mechanics/CLI/bestiary/npc/viktor-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 82*  

Viktor was born into a large family of simple farmers harvesting cabbage, beets, and potatoes. His family's farmstead sits on the northern reaches of a village called Barovia. At an early age he learned about the dread master of Barovia ruling from atop Castle Ravenloft. It was his fate and the fate of every other Barovian to never leave the mist shrouded valley. The lord of Ravenloft and first vampire, Strahd Von Zarovich, would never allow that.

But Viktor's fate turned out to be different from the rest of his people. Viktor prayed to the Morninglord every day, promising to serve the Morninglord as a holy warrior against Strahd's evil. In his early 20s, when his family was pressuring him to settle down and marry, Viktor's prayers were finally answered, but not by the god that he had been praying to. Two strangers arrived in the village of Barovia. One, named Borivik, would become Viktor's most beloved friend. The other, Lothar, would introduce Viktor to a goddess who would listen to his pleas—the Raven Queen.

The three managed to escape Barovia with the help of the Raven Queen. They adventured together for many years, forming a strong bond of friendship. The Raven Queen felt her hold over Viktor slipping, as his friends provided him with love and companionship. So, she sent Viktor a gift: a gold dragon named Thraxis that would be his mount and partner. But Thraxis wasn't a normal dragon; he had been corrupted by the Shadowfell.

The whisperings of this new friend began to turn Viktor down a dark path, one that his friends were helpless to prevent. One night he convinced Lothar to return with him to the Shadowfell. Borivik refused to accompany them and so their friendship came to an end.

Viktor is sullen and without humor. His farmer's upbringing means he has no concept of formalities or subtleties. Viktor is distrustful of arcane magic and hates hags, witches, or undead entities that harness magical power.

## Viktor as a Contact

Viktor becomes a contact for the Raven Circle at 7th level. Viktor can grant memory amulets to members of the Raven Circle in exchange for a devotion token. These amulets are shaped as the face of the person that they came from. When the memory is used, you are transformed into the creature as the [polymorph](3-Mechanics/CLI/spells/polymorph.md) spell for 10 rounds. Every round that you stay in the form you must make a successful Wisdom saving throw to avoid being possessed by the memories. The possessing entity will lash out at your friends to try and inflict as much harm as possible in vengeance for utilizing its memories in such a manner. Once the 10 rounds are complete, the possessing entity departs.

**Memory Amulets from Viktor**

| Polymorph Form | Devotion Token | Required Level | Possession DC |
|----------------|----------------|----------------|---------------|
| Wolfwere | Feather | 7 | 10 |
| Skeleton warrior | Gold | 7 | 10 |
| Wolfwere alpha | Feather | 9 | 15 |
| Skeleton lord | Gold | 9 | 15 |
| Death knight | Gem | 12 | 20 |
^memory-amulets-from-viktor

```statblock
"name": "Viktor (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Neutral"
"ac": !!int "20"
"ac_class": "[plate](3-Mechanics/CLI/items/plate-armor.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "178"
"hit_dice": "21d8 + 84"
"modifier": !!int "1"
"stats":
  - !!int "18"
  - !!int "12"
  - !!int "18"
  - !!int "11"
  - !!int "11"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+7"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+4"
"gear":
  - "sun blade"
"senses": "passive Perception 10"
"languages": "Common"
"cr": "9"
"traits":
  - "desc": "Viktor has advantage on saving throws against being [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)."
    "name": "Brave"
  - "desc": "Viktor has a young gold shadow dragon that accompanies him at all times.\
      \ If Viktor dies, the young gold shadow dragon returns to the Shadowfell."
    "name": "Shadow Dragon Companion"
  - "desc": "Viktor wields a sun blade. Viktor gains a +2 bonus to attack and damage\
      \ rolls made with this weapon, which deals radiant damage instead of slashing\
      \ damage (this is already factored into Viktor's stat block). When Viktor hits\
      \ an Undead creature with this sword, that target takes an extra 4 (1d8) radiant\
      \ damage. The sword's luminous blade emits bright light in a 15-foot radius\
      \ and dim light for an additional 15 feet. The light is sunlight."
    "name": "Sun Blade"
"actions":
  - "desc": "Viktor makes two Sun Blade attacks and one Raven's Whisper attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 10 (1d8 + 6) radiant damage or 11 (1d10 + 6) radiant damage if used with\
      \ two hands."
    "name": "Sun Blade"
  - "desc": "*Ranged Spell Attack:* +7 to hit, range 60 ft., one target. *Hit:*\
      \ 22 (4d10 + 3) radiant damage."
    "name": "Raven's Whisper"
  - "desc": "Viktor casts one of the following spells, using Charisma as the spellcasting\
      \ ability (spell save DC 15):\n\n**At will:** [bless](3-Mechanics/CLI/spells/bless.md),\
      \ [shield of faith](3-Mechanics/CLI/spells/shield-of-faith.md), [thunderous\
      \ smite](3-Mechanics/CLI/spells/thunderous-smite.md)\n\n**2/day each:** [aid](3-Mechanics/CLI/spells/aid.md),\
      \ [branding smite](3-Mechanics/CLI/spells/branding-smite.md), [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md)\n\
      \n**1/day each:** [banishment](3-Mechanics/CLI/spells/banishment.md), [blinding\
      \ smite](3-Mechanics/CLI/spells/blinding-smite.md), [death ward](3-Mechanics/CLI/spells/death-ward.md),\
      \ [revivify](3-Mechanics/CLI/spells/revivify.md)"
    "name": "Spellcasting"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/viktor-mabjov.webp"
```
^statblock