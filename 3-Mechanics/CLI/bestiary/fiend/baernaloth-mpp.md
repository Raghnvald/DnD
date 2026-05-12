---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mpp
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/yugoloth
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Baernaloth"
---
# [Baernaloth](3-Mechanics/CLI/bestiary/fiend/baernaloth-mpp.md)
*Source: Morte's Planar Parade p. 20*  

Baernaloths are tall, gaunt yugoloths who keep to the Gray Wastes of Hades. Their gray, desiccated skin stretches over their bones, and their heads resemble horned equine skulls with ember-like eyes. Sages endlessly debate the nature of baernaloths, and the *Books of Keeping*—ancient tomes detailing the true names of the first yugoloths—report no mention of baernaloths within. Some posit that these enigmatic yugoloths were created by a primal evil power before other yugoloths or that they come from an epoch before the current manifestation of the planes. Baernaloths refuse to say, but most obsess over secrets and obscene lore regarding the far-flung past and inscrutable future of the multiverse. Many of these rare scholars of the profane seek to manipulate reality on a grand scale, while others unleash horrific experiments on the planes. It's said the first demodands of Carceri were created by baernaloths.

Baernaloths spread discord and despair among any creatures they meet. They use their breath, thick with the gloom of Hades, to turn friends against each other and then savor the horror that rises when their victims realize how they've betrayed one another. Baernaloths use their wicked power to keep mortally wounded foes alive, sometimes indefinitely, to prolong their suffering. Even striking against a baernaloth brings misery—they can cause an attacker's old wounds to painfully reopen. All the while, baernaloths are disturbingly detached, observing their victims' agony without emotion.

## A Baernaloth's Lair

Whether in the hopeless realms of Hades or on the rare occasion they lurk on some other plane, baernaloths lair in remote mountain crags and secluded caves. Their lairs have ample places to house and restrain "guests," particularly those the baernaloths keep hovering at death's door.

The challenge rating of a baernaloth is 18 (20,000 XP) when it's encountered in its lair.

```statblock
"name": "Baernaloth (MPP)"
"size": "Large"
"type": "fiend"
"subtype": "yugoloth"
"alignment": "typically  Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "256"
"hit_dice": "27d10 + 108"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "14"
  - !!int "18"
  - !!int "22"
  - !!int "16"
  - !!int "21"
"speed": "40 ft."
"saves":
  - "constitution": !!int "10"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+12"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold; fire; lightning; necrotic; psychic; bludgeoning, piercing,\
  \ slashing from nonmagical attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 19"
"languages": "all, telepathy 120 ft."
"cr": "17"
"traits":
  - "desc": "If the baernaloth fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "The baernaloth has advantage on saving throws against spells and other\
      \ magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The baernaloth makes one Anguishing Bite attack and one Claw attack.\
      \ It can also use Teleport."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:*\
      \ 9 (1d10 + 4) piercing damage plus 10 (3d6) psychic damage. If the target\
      \ is a creature, it can't regain hit points until the start of the baernaloth's\
      \ next turn."
    "name": "Anguishing Bite"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 10 ft., one target. *Hit:*\
      \ 11 (2d6 + 4) slashing damage plus 17 (5d6) necrotic damage."
    "name": "Claw"
  - "desc": "The baernaloth exhales gray vapors that coalesce at a point it can see\
      \ within 120 feet of itself. The vapors fill a 20-foot-radius sphere centered\
      \ on that point, then vanish. Each non-yugoloth creature in that area must make\
      \ a DC 19 Wisdom saving throw. On a failed save, the creature takes 35 (10d6)\
      \ psychic damage and has the [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ condition until the end of its next turn. A creature [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ in this way treats its allies as foes, and the colors of its body and equipment\
      \ become shades of gray. On a successful save, the creature takes half as much\
      \ damage only."
    "name": "Miasma of Discord (Recharge 5-6)"
  - "desc": "The baernaloth has a 50 percent chance of summoning its choice of 1d4\
      \ mezzoloths, 1 arcanaloth, or 1 baernaloth (the mezzoloth and arcanaloth appear\
      \ in the Monster Manual). A summoned yugoloth appears in an unoccupied space\
      \ within 60 feet of the baernaloth, acts as an ally of the baernaloth, and can't\
      \ summon other yugoloths. It remains for 1 minute, until it or the baernaloth\
      \ dies, or until the baernaloth dismisses it as an action."
    "name": "Summon Yugoloth (1/Day)"
  - "desc": "The baernaloth teleports, along with any equipment it is wearing or carrying,\
      \ up to 120 feet to an unoccupied space it can see."
    "name": "Teleport"
  - "desc": "The baernaloth casts one of the following spells, requiring no material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 20):\n\n**At will:** [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [phantasmal force](3-Mechanics/CLI/spells/phantasmal-force.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\
      \n**1/day each:** [cloudkill](3-Mechanics/CLI/spells/cloudkill.md), [plane shift](3-Mechanics/CLI/spells/plane-shift.md)\
      \ (self only), [scrying](3-Mechanics/CLI/spells/scrying.md) (as an action)"
    "name": "Spellcasting"
"reactions":
  - "desc": "When a creature that the baernaloth can see within 60 feet of itself\
      \ hits with an attack roll or succeeds on a saving throw, the baernaloth forces\
      \ the creature to reroll the d20 and use the new result."
    "name": "Afflict Despair"
  - "desc": "When the baernaloth is damaged by another creature, that creature must\
      \ make a DC 19 Constitution saving throw, taking 14 (4d6) necrotic damage\
      \ on a failed save, or half as much damage on a successful one."
    "name": "Inescapable Pain"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), a baernaloth can take\
      \ one of the following lair actions; the baernaloth can't take the same lair\
      \ action two rounds in a row:\n\n- **Consume Suffering..** Until initiative\
      \ count 20 on the next round, when a creature in the baernaloth's lair other\
      \ than the baernaloth takes necrotic or psychic damage or drops to 0 hit points,\
      \ the baernaloth regains 10 (3d6) hit points.  \n- **Discover Secrets..**\
      \ The baernaloth uses Spellcasting to cast detect thoughts. A creature targeted\
      \ by the spell cast in this way takes 13 (3d8) psychic damage.  \n- **Recurring\
      \ Wound..** A creature that doesn't have all its hit points and that the baernaloth\
      \ can see in its lair must make a DC 19 Constitution saving throw, taking 22\
      \ (4d10) necrotic damage on a failed save, or half as much damage on a successful\
      \ one.  "
    "name": ""
"regional_effects":
  - "desc": "A region containing a baernaloth's lair becomes warped by the creature's\
      \ unnatural presence, which creates one or more of the following effects:\n\n\
      - **Persistent Anguish..** Within 10 miles of a baernaloth's lair, when a creature\
      \ casts a spell that either restores hit points or removes the charmed or frightened\
      \ condition, the spell fails and is wasted unless the caster succeeds on a DC\
      \ 19 saving throw using its spellcasting ability. Once a creature succeeds on\
      \ the saving throw, it is immune to this regional effect for 24 hours.  \n-\
      \ **Slow Healing..** Within 10 miles of a baernaloth's lair, a creature other\
      \ than the baernaloth regains only hit points equal to half its hit point maximum\
      \ when it finishes a long rest, and it regains only half the usual number of\
      \ hit points when it spends Hit Dice during a short rest.  \n\nIf the baernaloth\
      \ dies, these effects end immediately."
    "name": ""
"source":
  - "MPP"
"image": "3-Mechanics/CLI/bestiary/fiend/token/baernaloth-mpp.webp"
```
^statblock