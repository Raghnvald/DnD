---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/15
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Bodhi Irenicus"
---
# [Bodhi Irenicus](3-Mechanics/CLI/bestiary/npc/bodhi-irenicus-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 77*  

> [!quote] A quote from Volo  
> 
> Van Richten might think he has the market cornered on books about the undead, but he'd be wrong. I've done a great deal of research on vampires, which you can read about in my upcoming book "Volo's Guide to Spirits and Specters". Then you can judge who is the expert about undead.

Bodhi was born in the elven city of Suldanessellar. She was the sister of the city's greatest mage, Joneleth Icarus, and shared his interest in the arcane arts, even if she didn't have his talent for it. Jealous of her brother's prestige, she left Suldanessellar, searching for secrets that might make her the equal of Jon. During her journeys she came across the wandering folk known as the Vistani.

The Vistani showed her paths into the foul regions of the Shadowfell, where Bodhi encountered the sinister Dark Powers. Bodhi made a pact with these enigmatic beings and they showed her secrets that would allow her to draw power directly from the elven gods.

Returning to Suldanessellar, Bodhi shared the secrets she had discovered with Joneleth. Her whispers enflamed his desire to gain even greater power. She and her brother embarked on a plot to achieve godhood by draining Suldanessellar's Tree of Life of its magical essence. The ritual would have killed most of the elves in the city, but the pair were thwarted by Ellesime, the city's queen.

For their crimes, the siblings were cursed—stripped of their elven longevity and exiled from their home. Bodhi was enraged at what had happened to her. Despite her brother's protests, she returned to Suldanessellar to try and murder the queen. She slaughtered dozens of her kin before Ellesime finally killed her. But Bodhi did not stay dead. Instead, the Dark Powers of the Shadowfell brought her back as a vampire so that she could continue to corrupt her brother and bring about his final downfall as well.

With her newfound powers, Bodhi helped her brother capture dozens of powerful individuals from across the nation of Amn. One of the victims she brought to her brother for torture and experimentation was the Bhaalspawn named Abdel Adrian, mortal son of the God of Murder. Abdel and his half-sister Imoen escaped and sought vengeance against Bodhi. Eventually they tracked her down and staked her in the heart while she slept in her sarcophagus.

But that wasn't the end of Bodhi's story. Her brother suffered his final downfall shortly after her death, completing the pact Bodhi had originally made with the Dark Powers of the Shadowfell. As a result, she and her brother were drawn into a dark reflection of the treetop city in the Domain of Dread. Despite being trapped there, Bodhi and her brother still find ways to torment the elves of Suldanessellar, even as they seek to escape their prison.

Bodhi is exceptionally cruel, sadistic, and evil, delighting in playing with her prey before their destruction. Like her brother, she holds a deep hatred for the elven community she was born into and was later exiled from.

## Bodhi Irenicus as a Contact

Bodhi is the primary contact for members of the Order of Icarus at low levels. Bodhi is willing to allow those that she favors to drink from her blood. Doing so grants you one of the supernatural gifts below. You can only ever have one gift from Bodhi.

**Supernatural Gifts from Bodhi Irenicus**

| Supernatural Gift | Benefits | Required Level |
|-------------------|----------|----------------|
| Death's gift | You have the benefits of a periapt of wound closure | 1 |
| Nightmare's gift | You have the benefits of a ring of feather falling | 1 |
| Lich's gift | You have advantage on saving throws against spells and other magical effects | 5 |
| Spider's gift | You can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check | 5 |
| Panther's gift | You can cast the [polymorph](3-Mechanics/CLI/spells/polymorph.md) spell once per day without using any verbal or somatic components You can only cast it on yourself and it must be a panther | 7 |
| Vampire's gift | You can cast the [dominate person](3-Mechanics/CLI/spells/dominate-person.md) spell once per day without using any verbal or somatic components | 9 |
^supernatural-gifts-from-bodhi-irenicus

```statblock
"name": "Bodhi Irenicus (MaBJoV)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "212"
"hit_dice": "25d8 + 100"
"modifier": !!int "5"
"stats":
  - !!int "18"
  - !!int "20"
  - !!int "18"
  - !!int "16"
  - !!int "15"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "10"
  - "wisdom": !!int "7"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+7"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+15"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical weapons"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 120 ft., passive\
  \ Perception 17"
"languages": "Common, Elvish, Sylvan"
"cr": "15"
"traits":
  - "desc": "If Bodhi fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Bodhi regains 20 hit points at the start of her turn if she has at least\
      \ 1 hit point and isn't in sunlight. If she takes radiant damage, this trait\
      \ doesn't function at the start of her next turn."
    "name": "Regeneration"
  - "desc": "If Bodhi is destroyed, her body immediately appears in her resting place.\
      \ She is [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed) until she\
      \ regains at least 1 hit point. After spending 24 hours in her resting place\
      \ with 0 hit points, she regains 1 hit point. While [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ in this manner, if a creature within 60 feet says her name 9 times, Bodhi\
      \ is permanently destroyed."
    "name": "Rejuvenation"
  - "desc": "Bodhi deals an extra 28 (8d6) damage when she hits a target with a\
      \ weapon attack and has advantage on the attack roll, or when the target is\
      \ within 5 feet of an ally of Bodhi that isn't incapacitated and Bodhi doesn't\
      \ have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
  - "desc": "Bodhi can climb difficult surfaces, including upside down on ceilings,\
      \ without needing to make an ability check."
    "name": "Spider Climb"
  - "desc": "If a creature says Bodhi Irenicus's full name 9 times in a row, Bodhi\
      \ hears her name and becomes aware of the creature. Bodhi knows the exact location\
      \ and name of the creature that spoke her name. She can then choose, as a free\
      \ action, to teleport to a location adjacent to the creature. She must choose\
      \ to do this within 1 minute of hearing her name. This power works even if the\
      \ creature is on a different plane of existence. 1 minute after teleporting,\
      \ Bodhi teleports back to where she was located when she heard her name spoken.\
      \ This occurs even if Bodhi is unwilling and even if she is in an antimagic\
      \ effect."
    "name": "Summoned By Name (1/Day)"
  - "desc": "Bodhi Irenicus has the following flaws:\n\n- **Elvish Song.** Bodhi can't\
      \ abide a song performed in the elvish language. A creature that can speak the\
      \ elvish language can use an action to sing an elven song. If Bodhi is within\
      \ 60 feet of the singer and can hear the song, she has disadvantage on attacks\
      \ and saving throws.  \n- **Stake to the Heart.** If a piercing weapon made\
      \ of wood is driven into Bodhi's heart while she is [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated)\
      \ in her resting place, Bodhi is [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ until the stake is removed.  \n- **Sunlight Hypersensitivity.** Bodhi takes\
      \ 20 radiant damage when she starts her turn in sunlight. While in sunlight,\
      \ she has disadvantage on attack rolls and ability checks.  "
    "name": "Vampire Weaknesses"
"actions":
  - "desc": "Bodhi makes three Unarmed Strike attacks, one of which can be a Bite\
      \ attack instead."
    "name": "Multiattack (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one creature. *Hit:*\
      \ 9 (1d8 + 5) bludgeoning damage. Instead of dealing damage, Bodhi can grapple\
      \ a Medium-sized or smaller target (escape DC 18)."
    "name": "Unarmed Strike (Vampire Form Only)"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one creature. *Hit:*\
      \ 8 (1d6 + 5) piercing damage plus 14 (4d6) necrotic damage. The target's\
      \ hit point maximum is reduced by an amount equal to the necrotic damage taken,\
      \ and Bodhi regains hit points equal to that amount. The reduction lasts until\
      \ the target finishes a long rest. The target dies if this effect reduces its\
      \ hit point maximum to 0. A Humanoid slain in this way and then buried in the\
      \ ground rises the following night as a vampire spawn under Bodhi's control."
    "name": "Bite (Panther or Vampire Form Only)"
  - "desc": "If Bodhi isn't in sunlight, she can polymorph into a Medium panther or\
      \ back into her true form. While in panther form, Bodhi Irenicus can't speak,\
      \ her walking speed is 40 feet, and she has a climb speed of 30 feet. Her statistics,\
      \ other than her size and speed, are unchanged. Anything she is wearing transforms\
      \ with her, but nothing she is carrying does. She reverts to her true form if\
      \ she dies."
    "name": "Change Shape"
  - "desc": "Bodhi targets one Humanoid she can see within 30 feet of her. If the\
      \ target can see Bodhi, the target must succeed on a DC 17 Wisdom saving throw\
      \ or be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) by Bodhi. The\
      \ [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) target regards Bodhi\
      \ as a trusted friend to be heeded and protected. Although the target isn't\
      \ under Bodhi's control, it takes Bodhi's requests or actions in the most favorable\
      \ way it can. Each time Bodhi or her allies do anything harmful to the target,\
      \ it can repeat the saving throw, ending the effect on itself on a success.\
      \ Otherwise, the effect lasts 24 hours or until Bodhi is destroyed, is on a\
      \ different plane of existence than the target, or takes a bonus action to end\
      \ the effect."
    "name": "Charm"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Bodhi can expend a use to take one of the following actions. Bodhi regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Bodhi moves up to her speed without provoking opportunity attacks."
    "name": "Move"
  - "desc": "Bodhi makes one Unarmed Strike."
    "name": "Unarmed Strike"
  - "desc": "Bodhi makes one Bite attack."
    "name": "Bite (Costs 2 Actions)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/bodhi-irenicus-mabjov.webp"
```
^statblock