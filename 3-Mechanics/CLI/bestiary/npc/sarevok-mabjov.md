---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sarevok"
---
# [Sarevok](3-Mechanics/CLI/bestiary/npc/sarevok-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 124*  

Sarevok Anchev is a powerful Deathbringer, an elite group of warriors trained to kill their enemies with a single, seemingly random strike in combat. He is also one of the Bhaalspawn, the mortal offspring of the dead god Bhaal. Sarevok attempted to reclaim the divine seat of the Lord of Murder vacated by his immortal father's demise, but his plans were thwarted when he was slain by his half-brother, Abdel Adrian, who rejected his heritage and fought against his Bhaalspawn siblings.

Sarevok's spirit was sent to the Abyss as punishment. There he eventually crossed paths with Abdel a second time when his noble-hearted brother ventured into the lower realms on a dangerous quest to stop another Bhaalspawn named Melissan. Sarevok agreed to help Abdel kill Melissan, on the condition that Abdel helped him escape the eternal torments of the Abyss.

Abdel agreed, and Sarevok was reborn into the mortal world. After his rebirth, Sarevok was true to his word, and the two brothers fought side-by-side against their half-sister. Ultimately Melissan was defeated, and Sarevok was granted a second chance at life.

With his prodigious strength, his legendary skill in battle, and the Sword of Chaos—a life-stealing, enchanted blade—Sarevok became one of the most famous mercenaries in Faerûn. Yet his many accomplishments brought him no joy. He felt no thrill at victory in battle, no delight in the routing of his enemies. The power he accumulated was bitter as ashes on his tongue, and he became a man haunted by his former life. The realization that no earthly achievements could ever compare to what he once almost had—immortality and godhood—left him broken and empty.

Sarevok plunged into a deep despair. To numb his pain, he indulged in every vice imaginable, squandering his wealth and health on alcohol and drugs. While his divine heritage slowed his aging, it did not stop it entirely, and after decades of self-abuse he was eventually reduced to an old man begging in the streets of Baldur's Gate.

This was how his father—Bhaal, the reborn god of murder—found him. But even though it was dimmed, Bhaal recognized his own divine spark in the pathetic old man, and he sensed Sarevok still had potential. Bhaal recruited him to become the high priest of his fledgling clergy, giving Sarevok new purpose... and another chance to become an agent of death and destruction.

```statblock
"name": "Sarevok (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Evil"
"ac": !!int "21"
"ac_class": "plate armor of Bhaal"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "0"
"stats":
  - !!int "20"
  - !!int "10"
  - !!int "18"
  - !!int "11"
  - !!int "16"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "9"
  - "wisdom": !!int "8"
"skillsaves":
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+5"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+12"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+5"
"damage_immunities": "acid, necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[longsword](3-Mechanics/CLI/items/longsword.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Abyssal, Common, Infernal"
"cr": "15"
"traits":
  - "desc": "Sarevok has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "If Sarevok is killed he gains a new body in 24 hours, regaining all his\
      \ hit points and becoming active again. The new body appears on the altar of\
      \ the temple of Bhaal beneath Baldur's Gate. This ability ceases to function\
      \ if a cleric of good alignment casts [Hallow](3-Mechanics/CLI/spells/hallow.md)\
      \ on the altar in the temple of Bhaal."
    "name": "Rejuvenation"
"actions":
  - "desc": "Sarevok makes two Longsword attacks. He may replace one of the attacks\
      \ with a use of Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 9 (1d8 + 5) slashing damage or 10 (1d10 + 5) if wielded in two hands.\
      \ If the target is a creature, it must succeed on a DC 16 Constitution saving\
      \ throw or be cursed by Bhaal. The cursed target can't regain hit points. The\
      \ curse lasts until removed by the [remove curse](3-Mechanics/CLI/spells/remove-curse.md)\
      \ spell or other magic."
    "name": "Longsword"
  - "desc": "Sarevok makes a Longsword attack. If he hits the target and has advantage\
      \ on the attack roll, then he deals an additional 21 (6d6) poison damage.\
      \ If the target is a creature, it must succeed on a DC 16 Constitution saving\
      \ throw or have the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition for 10 minutes."
    "name": "Assassin's Strike"
  - "desc": "Sarevok casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 16):\n\n**At will:** [resistance](3-Mechanics/CLI/spells/resistance.md),\
      \ [sacred flame](3-Mechanics/CLI/spells/sacred-flame.md), [thaumaturgy](3-Mechanics/CLI/spells/thaumaturgy.md)\n\
      \n**1/day each:** [animate dead](3-Mechanics/CLI/spells/animate-dead.md), [command](3-Mechanics/CLI/spells/command.md),\
      \ [contagion](3-Mechanics/CLI/spells/contagion.md), [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md),\
      \ [divination](3-Mechanics/CLI/spells/divination.md), [harm](3-Mechanics/CLI/spells/harm.md),\
      \ [hold person](3-Mechanics/CLI/spells/hold-person.md), [silence](3-Mechanics/CLI/spells/silence.md)"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Sarevok can expend a use to take one of the following actions. Sarevok regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Sarevok makes a Longsword attack."
    "name": "Attack"
  - "desc": "Sarevok casts [sacred flame](3-Mechanics/CLI/spells/sacred-flame.md)."
    "name": "Unholy Flame"
  - "desc": "Sarevok unleashes Bhaal's power. Creatures within 30 feet of Sarevok,\
      \ including ones behind barriers and around corners, can't regain hit points\
      \ until the end of Sarevok's next turn."
    "name": "Channel Bhaal's Hate (Costs 2 Actions)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/sarevok-mabjov.webp"
```
^statblock