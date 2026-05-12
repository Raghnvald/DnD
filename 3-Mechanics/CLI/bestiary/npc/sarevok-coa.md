---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Sarevok"
---
# [Sarevok](3-Mechanics/CLI/bestiary/npc/sarevok-coa.md)
*Source: Chains of Asmodeus p. 48*  

Sarevok Anchev is a powerful Deathstalker. He is also one of the Bhaalspawn, the mortal offspring of the dead god Bhaal. Sarevok attempted to reclaim the divine seat of the Lord of Murder vacated by his immortal father's demise, but his plans were thwarted when he was slain by his half-brother, Abdel Adrian, who rejected his heritage and fought against his Bhaalspawn siblings.

Sarevok's spirit was sent to the Abyss as punishment. There he eventually crossed paths with Abdel a second time when his noble-hearted brother ventured into the lower realms on a dangerous quest to stop another Bhaalspawn named Melissan. Sarevok agreed to help Abdel kill Melissan, on the condition that Abdel helped him escape the eternal torments of the Abyss.

Abdel agreed, and Sarevok was reborn into the mortal world. After his rebirth, Sarevok was true to his word, and the two brothers fought side by side against their half-sister. Ultimately Melissan was defeated, and Sarevok was granted a second chance at life.

With his prodigious strength, his legendary skill in battle, and the Sword of Chaos—a life-stealing, enchanted blade—Sarevok became a famous (and feared) mercenary. Yet his many accomplishments brought him no joy. He felt no thrill at victory in battle, no delight in the routing of his enemies. The power he accumulated was bitter as ashes on his tongue, and he became a man haunted by his former life. The realization that no earthly achievements could ever compare to what he once almost had—immortality and godhood—left him broken and empty.

Sarevok plunged into a deep despair. To numb his pain, he indulged in every vice imaginable, squandering his wealth and health on alcohol, drugs, and fleeting comforts. While his divine heritage slowed his aging, it did not stop it entirely, and after decades of self-abuse he was eventually reduced to an old man begging in the streets of Baldur's Gate.

This was how his father—Bhaal, the reborn god of murder—found him. Bhaal recognized his own divine spark in the pathetic old man, and he sensed Sarevok still had potential. Bhaal recruited him to become the high priest of his fledgling clergy, giving Sarevok new purpose... and another chance to become an agent of death and destruction.

```statblock
"name": "Sarevok (CoA)"
"size": "Medium"
"type": "humanoid"
"alignment": "Neutral Evil"
"ac": !!int "21"
"ac_class": "plate armor of Bhaal"
"hp": !!int "190"
"hit_dice": "20d8 + 100"
"modifier": !!int "0"
"stats":
  - !!int "23"
  - !!int "10"
  - !!int "21"
  - !!int "11"
  - !!int "18"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "11"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "History"
    "desc": "+6"
  - "name": "Intimidation"
    "desc": "+14"
  - "name": "Religion"
    "desc": "+6"
"damage_immunities": "acid, necrotic, poison"
"condition_immunities": "charmed, frightened, poisoned"
"gear":
  - "longsword"
"senses": "darkvision 60 ft., passive Perception 14"
"languages": "Abyssal, Common, Infernal"
"cr": "17"
"traits":
  - "desc": "Sarevok has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "If Sarevok is killed, he gains a new body in 24 hours, regaining all\
      \ his hit points. The new body appears on the altar of the temple of Bhaal beneath\
      \ Baldur's Gate. This ability ceases to function if a cleric of good alignment\
      \ casts Hallow on the altar in the temple of Bhaal."
    "name": "Rejuvenation"
"actions":
  - "desc": "Sarevok makes three Longsword attacks. He can replace one of the attacks\
      \ with Flames of Bhaal or Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5ft., one target. *Hit:* 10\
      \ (1d8 + 6) slashing damage or 11 (1d10 + 6) if wielded in two hands. The\
      \ target must succeed on a DC 18 Constitution saving throw or be cursed by Bhaal,\
      \ preventing it from regaining hit points. The curse lasts until removed by\
      \ the Remove Curse spell or similar effect."
    "name": "Longsword"
  - "desc": "Sarevok causes flames to engulf one creature that he can see within 60\
      \ feet. The target must succeed on a DC 18 Dexterity saving throw or take 18\
      \ (4d8) necrotic damage. This damage can't be restored except by a Lesser\
      \ Restoration spell or similar effect."
    "name": "Flames of Bhaal"
  - "desc": "Sarevok casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 18):\n\n**At will:** Resistance, Thaumaturgy\n\n**1/day\
      \ each:** Animate Dead, Antimagic Field, Astral Projection, Blade Barrier, Command,\
      \ Contagion, Dispel Magic, Divination, Etherealness, Fire Storm, Harm, Hold\
      \ Person, Silence"
    "name": "Spellcasting"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Sarevok can expend a use to take one of the following actions. Sarevok regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Sarevok makes a Longsword attack."
    "name": "Slash"
  - "desc": "Sarevok uses Flames of Bhaal."
    "name": "Unholy Flame"
  - "desc": "Sarevok unleashes Bhaal's power. Creatures within 30 feet of Sarevok,\
      \ including ones behind barriers and around corners, can't regain hit points\
      \ until the end of Sarevok's next turn."
    "name": "Channel Bhaal's Hate (Costs 2 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/sarevok-coa.webp"
```
^statblock