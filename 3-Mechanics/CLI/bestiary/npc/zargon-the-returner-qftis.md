---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/qftis
- ttrpg-cli/monster/cr/17
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Zargon the Returner"
---
# [Zargon the Returner](3-Mechanics/CLI/bestiary/npc/zargon-the-returner-qftis.md)
*Source: Quests from the Infinite Staircase p. 223*  

Zargon the Returner is an elder evil—an undying abomination from eons past with an insatiable appetite. A tentacled, slime-covered horror with a cyclopic red eye and an indestructible horn, Zargon corrupts creatures it doesn't devour, transforming its victims into amorphous servants.

No one knows Zargon's true origin. The creature was one of the first inhabitants of the Nine Hells, predating even the arrival of Asmodeus, the plane's foremost ruler. Long-lived devils and occult sages theorize Zargon and its kind were invaders from another plane—or another reality entirely.

When Asmodeus ascended the infernal hierarchy, he and his legions wiped out most of the plane's earlier inhabitants, but Zargon proved beyond even Asmodeus' might. No matter what blistering wrath Asmodeus brought to bear on Zargon, the aberration continually re-formed from its horn. Finally, Asmodeus cast Zargon's horn from the Nine Hells in disgust, banishing the elder evil to the Material Plane. The horn was driven deep into the earth where it fell, entombing Zargon below.

Eventually a civilization arose above Zargon's prison. The elder evil whispered through dreams and nightmares to the people of Cynidicea, the realm's capital, until one day, a crew of Cynidiceans accidentally dug through to the Returner's prison. Zargon emerged, devouring many of the city's inhabitants and drowning many more in its slime. The city soon fell. Those who survived Zargon's rampage turned to it in worship, sacrificing their own to appease their so-called god. Appeased by these living offerings, Zargon returned to the tunnels beneath Cynidicea, where its cult grew.

## Zargon's Lair

Zargon's lair is a slimy cavern beneath the lost city of Cynidicea. The elder evil lurks in the depths, feasting on sacrifices cast down by its worshipers.

```statblock
"name": "Zargon the Returner (QftIS)"
"size": "Huge"
"type": "aberration"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "253"
"hit_dice": "22d12 + 110"
"modifier": !!int "0"
"stats":
  - !!int "22"
  - !!int "10"
  - !!int "20"
  - !!int "14"
  - !!int "18"
  - !!int "18"
"speed": "40 ft., swim 80 ft."
"saves":
  - "dexterity": !!int "6"
  - "charisma": !!int "10"
"skillsaves":
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+8"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+10"
"damage_resistances": "cold; fire; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "acid, poison"
"condition_immunities": "[exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 20"
"languages": "all, telepathy 120 ft."
"cr": "17"
"traits":
  - "desc": "If Zargon fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day)"
  - "desc": "Zargon regains 20 hit points at the start of each of its turns. If Zargon\
      \ takes cold or fire damage, this trait doesn't function at the start of Zargon's\
      \ next turn. Zargon dies only if it starts its turn with 0 hit points and doesn't\
      \ regenerate."
    "name": "Regeneration"
  - "desc": "Zargon can't be targeted by divination magic or perceived through magical\
      \ scrying sensors."
    "name": "Shrouded Being"
  - "desc": "When Zargon dies, its body dissolves into foul slime, leaving only its\
      \ horn behind. Zargon re-forms in 1d10 days, regrowing from the horn. The\
      \ horn is immune to all damage and can be destroyed only by submerging it in\
      \ a cleansing waterfall on one of the Upper Planes for 101 days. While the horn\
      \ is submerged in this way, Zargon doesn't re-form, and the horn slowly dissolves,\
      \ sending corrupting slime downriver that permanently fouls the water for 10\
      \ miles from the place where the horn dissolved. The fouled water is unfit to\
      \ drink, chokes aquatic wildlife, and withers plants."
    "name": "Slimy Demise"
"actions":
  - "desc": "Zargon makes two Barbed Tentacle attacks, one Bite attack, and one Gore\
      \ attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 20 ft., one target. *Hit:*\
      \ 15 (2d8 + 6) piercing damage. If the target is a Large or smaller creature,\
      \ it has the [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled) condition\
      \ (escape DC 20), and Zargon can pull the creature up to 20 feet straight toward\
      \ itself. Zargon has six tentacles, each of which can grapple one creature.\
      \ Zargon can move at its full speed while dragging creatures it is grappling."
    "name": "Barbed Tentacle"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:*\
      \ 19 (2d12 + 6) piercing damage plus 7 (2d6) acid damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 10 ft., one target. *Hit:*\
      \ 15 (2d8 + 6) force damage, and a 10-foot-radius [invisible](3-Mechanics/CLI/rules/conditions.md#Invisible)\
      \ sphere of antimagic, like that created by an [Antimagic Field](3-Mechanics/CLI/spells/antimagic-field.md)\
      \ spell, surrounds the target. The sphere is centered on the target, moves with\
      \ the target, and lasts until the end of Zargon's next turn."
    "name": "Gore"
  - "desc": "Zargon spews slime in a 60-foot cone. Each creature in that area that\
      \ isn't an Aberration or Ooze must make a DC 19 Constitution saving throw. On\
      \ a failed save, the creature takes 38 (7d10) acid damage and has the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition for 1 minute. On a successful save, the creature takes half as much\
      \ damage only. A [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned) creature\
      \ can repeat the saving throw at the end of each of its turns, ending the effect\
      \ on itself on a success.\n\nA creature reduced to 0 hit points by the acid\
      \ damage dies and dissolves into a puddle of slime that rises as a gibbering\
      \ mouther at the start of Zargon's next turn. The creature obeys Zargon's commands\
      \ and takes its turn immediately after Zargon's. Only a [Wish](3-Mechanics/CLI/spells/wish.md)\
      \ spell can reverse this transformation and restore the creature to life."
    "name": "Slime Wave (Recharge 5-6)"
"reactions":
  - "desc": "When a creature casts a spell that targets Zargon or would deal damage\
      \ to it, Zargon attempts to absorb the magic into its horn. The creature must\
      \ make a DC 19 Charisma saving throw. On a failed save, the creature takes 6\
      \ (1d12) force damage, and the spell it cast fails and is wasted."
    "name": "Defiant Essence"
  - "desc": "When a creature ends its turn within 30 feet of Zargon, Zargon sprays\
      \ toxic slime at the creature. The target must make a DC 19 Dexterity saving\
      \ throw (with disadvantage if it has the [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)\
      \ condition). On a failed save, the creature takes 7 (2d6) poison damage.\
      \ On a successful save, it takes half as much damage."
    "name": "Slime Spray"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Zargon can take one\
      \ of the following lair actions; it can't take the same lair action two rounds\
      \ in a row:\n\n- **Dissolution.** Zargon dissolves into a glob of slime, seeps\
      \ to an unoccupied space anywhere in the lair without provoking opportunity\
      \ attacks, then re-forms.  \n- **Spell Breaker.** Zargon targets up to two creatures\
      \ it can see within the lair. All spells of 5th level or lower affecting the\
      \ targets end.  \n- **Sucking Slime.** Zargon creates a 20-foot-radius puddle\
      \ of slime on the ground centered on a point within the lair. The slime is difficult\
      \ terrain, and each creature in that area when the slime appears has the grappled\
      \ condition (escape DC 15). Aberrations and Oozes are unaffected by the slime.\
      \ The slime lasts until Zargon dies or until it uses this lair action again.\
      \  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Zargon's lair is warped by Zargon's unnatural presence,\
      \ creating one or more of the following effects:\n\n- **Arcane Enervation.**\
      \ Enemies of Zargon within 1 mile of the lair have disadvantage on saving throws\
      \ made to maintain concentration.  \n- **Corrupted Water.** Rain and water sources\
      \ within 1 mile of the lair are tainted. A creature that drinks the water must\
      \ succeed on a DC 15 Constitution saving throw or have the poisoned condition\
      \ until it finishes a long rest.  \n- **Eerie Weather.** The area within 10\
      \ miles of the lair experiences strange weather patterns that defy the region's\
      \ typical climate.  \n\nIf Zargon dies, these effects fade over the course of\
      \ 1d10 days."
    "name": ""
"source":
  - "QftIS"
"image": "3-Mechanics/CLI/bestiary/npc/token/zargon-the-returner-qftis.webp"
```
^statblock