---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/aitfr-dn
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/monstrosity
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Kyrilla, Accursed Gorgon"
---
# [Kyrilla, Accursed Gorgon](3-Mechanics/CLI/bestiary/npc/kyrilla-accursed-gorgon-aitfr-dn.md)
*Source: Adventures in the Forgotten Realms: Deepest Night p. 12*  

Some small part of Kyrilla hopes she might be pardoned from her immortal curse one day, but her ire and spite have overtaken her heart, and the only way she can imagine escaping eternity is by impressing the gods with her tenacity. She doesn't want pity nor compassion. She wants to be feared and loathed and to press on with existence despite it all. And now that Kathikon is dead and she is alone, she cannot remember mercy.

## Personality Trait

"I am quick to judge others and find them wanting."

## Ideal

"Spite. I survive despite a curse from the gods—I'm not about to go out into the world where fools will try to kill me."

## Bond

"Kathikon was the love of my life. No one else matters to me."

## Flaw

"I never admit when I am wrong."

## Horrific Appearance

Once, Kyrilla looked much like other gorgons of her world. Now, with her curse upon her, Kyrilla's healthy greenish skin has grown sickly pale, and the segmented cables she wore like hair have gone from shiny black to matte gray and green. Her legs became a long, segmented tail. Her eyes now glow green, bright enough to create dim light in front of her. She has grown four needle-like fangs in her mouth, and her hands have become slicing claws.

She reverts to her original appearance when she dies.

## Bestowed Power

The malevolent powers bestowed to Kyrilla by her curse, as well as those given to her by the yuan-ti cult, are hardly of interest to her. She doesn't relish power but instead has taken to wallowing in misery and dwelling in her hatred for the beings that cursed her so long ago that she can hardly remember them.

## Magic Ring

Kyrilla wears a ring of water walking that she was given by an emissary from the Serpent Kingdoms long ago. It is made of a bluish jade and does not reflect light.

## Immortal Curse

Kyrilla does not require food or drink but does breathe and sleep.

```statblock
"name": "Kyrilla, Accursed Gorgon (AitFR-DN)"
"size": "Large"
"type": "monstrosity"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "127"
"hit_dice": "15d10 + 45"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "14"
  - !!int "14"
  - !!int "15"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "6"
  - "charisma": !!int "6"
"skillsaves":
  - "name": "Deception"
    "desc": "+6"
  - "name": "Insight"
    "desc": "+6"
  - "name": "Perception"
    "desc": "+6"
  - "name": "Stealth"
    "desc": "+7"
"damage_resistances": "bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "poison"
"condition_immunities": "charmed"
"gear":
  - "longbow"
"senses": "darkvision 60 ft., passive Perception 16"
"languages": "Common, Draconic, Primordial"
"cr": "10"
"traits":
  - "desc": "The first time she hits with a weapon attack on her turn, Kyrilla can\
      \ deal an extra 16 (3d10) poison damage to the target and regains a number\
      \ of hit points equal to half the damage dealt."
    "name": "Feed on Pain (2/Day)"
  - "desc": "If she fails a saving throw, Kyrilla can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "When a creature that can see Kyrilla's eyes starts its turn within 30\
      \ feet of her, Kyrilla can force it to make a DC 14 Constitution saving throw\
      \ if Kyrilla isn't incapacitated and can see the creature. If the saving throw\
      \ fails by 5 or more, the creature is instantly petrified. Otherwise, a creature\
      \ that fails the save begins to turn to stone and is restrained. The restrained\
      \ creature must repeat the saving throw at the end of its next turn, becoming\
      \ petrified on a failure or ending the effect on a success. The petrification\
      \ lasts until the creature is freed by the greater restoration spell or other\
      \ magic.\n\nUnless surprised, a creature can avert its eyes to avoid the saving\
      \ throw at the start of its turn. If the creature does so, it can't see Kyrilla\
      \ until the start of its next turn, when it can avert its eyes again. If the\
      \ creature looks at Kyrilla in the meantime, it must immediately make the save.\n\
      \nKyrilla's accursed gaze does not affect undead or constructs. If Kyrilla sees\
      \ herself reflected on a polished surface within 30 feet of her and in an area\
      \ of bright light, she is, due to her curse, affected by her own gaze."
    "name": "Petrifying Gaze"
  - "desc": "While in sunlight, Kyrilla has disadvantage on attack rolls and on Wisdom\
      \ (Perception) checks that rely on sight."
    "name": "Sunlight Sensitivity"
"actions":
  - "desc": "Kyrilla makes one attack to constrict and two attacks with her claws,\
      \ or she makes three attacks with her longbow."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 13\
      \ (3d6 + 3) slashing damage."
    "name": "Claw"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one target. *Hit:*\
      \ 10 (3d6) bludgeoning damage, and the target is grappled (escape DC 13) if\
      \ it is a Large or smaller creature. Until this grapple ends, the target is\
      \ restrained, and Kyrilla can't constrict another target."
    "name": "Constrict"
  - "desc": "*Ranged Weapon Attack:* +7 to hit, range 150/600 ft., one target. *Hit:*\
      \ 16 (3d8 + 3) piercing damage."
    "name": "Longbow"
  - "desc": "Kyrilla conjures a swarm of poisonous snakes into an empty space within\
      \ 10 feet of her. The swarm is under Kyrilla's control and acts on her turn,\
      \ immediately after her in the initiative order.\n\nIt remains in existence\
      \ for up to 1 hour. She can summon no more than three swarms per day. Kyrilla\
      \ can banish any or all of her summoned swarms with a bonus action."
    "name": "Summon Swarm of Poisonous Snakes (Recharge 5-6)"
"lair_actions":
  - "desc": "When fighting inside her lair, Kyrilla can invoke the ambient magic there\
      \ to take lair actions. On initiative count 20 (losing initiative ties), she\
      \ takes a lair action to cause one of the following effects:\n\n- Kyrilla casts\
      \ moonbeam (no components required). While maintaining concentration on this\
      \ effect, she can't take other lair actions.  \n- Kyrilla casts cloud of daggers\
      \ (no components required), except the daggers are flying snakes and the spell\
      \ deals piercing damage. While maintaining concentration on this effect, she\
      \ can't take other lair actions.  \n- Pools of liquid within 60 feet of Kyrilla\
      \ surge and froth, splashing and soaking any creature on the ground within 5\
      \ feet of such pools. Creatures that succeed on a DC 14 Dexterity saving throw\
      \ avoid getting liquid in their eyes and mouths. Kyrilla can't use this lair\
      \ action again until she has used a different one.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Kyrilla's lair is warped by her accursed nature\
      \ and the meteoric stone around her, which together create the following effects:\n\
      \n- Water sources within the lair are supernaturally fouled and poisonous. Creatures\
      \ that drink these waters must make a DC 14 Constitution saving throw or be\
      \ poisoned for 1 minute. Afflicted creatures can make a new saving throw at\
      \ the end of each of their turns, ending the condition on a success.  \n- Plants\
      \ within 1 mile of the lair suffer from a calcifying mold that dries and hardens\
      \ leaves, killing many otherwise hearty thistles and heather.  \n- Fog lightly\
      \ obscures the land within 3 miles of the lair.  "
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Kyrilla can expend a use to take one of the following actions. Kyrilla regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Kyrilla or a swarm of poisonous snakes makes a weapon attack."
    "name": "Claw"
  - "desc": "Kyrilla makes a Wisdom (Perception) check."
    "name": "Detect"
  - "desc": "Kyrilla moves up to her speed without provoking opportunity attacks."
    "name": "Slither"
"source":
  - "AitFR-DN"
"image": "3-Mechanics/CLI/bestiary/npc/token/kyrilla-accursed-gorgon-aitfr-dn.webp"
```
^statblock