---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/demon
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Pazuzu"
---
# [Pazuzu](3-Mechanics/CLI/bestiary/npc/pazuzu-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 104*  

> [!quote] A quote from MINSC  
> 
> Boo once heard words coming from a flask made of iron. If I know anything, its that a flask is meant for drinking, not talking.

> [!quote] A quote from Volo  
> 
> The rumors that Pazuzu corrupted Asmodeus, presupposes that Asmodeus was originally an angel. This has never been proven! The numerous origins attributed to the lord of the Nine include that he was the first god of Law or that he served such a god and murdered her. We will likely never know the truth.

Pazuzu is a powerful demon lord, one of the eldest and most reprehensible of his ilk. He is also called the Dark Angel of the Four Winds, and the Prince of the Lower Aerial Kingdoms. He holds sway over all evil flying creatures, even among the different layers of the Abyss.

Pazuzu's home is the first layer of the Abyss, called Pazunia, known as the Plain of Infinite Portals or the Palace of 1,001 Closets. It is a harsh place with many pits and chasms marring its surface. The pits are portals that not only lead to all of the planes of the Abyss, but to other planes of existence and even mortal worlds. Only Pazuzu knows where each leads.

Unlike most demon lords, Pazuzu is not interested in the conquest of the Abyss. His passion is for corruption. He is fond of corrupting mortals, especially the innocent and honest. Some believe that Pazuzu is the entity responsible for the ultimate corruption—that of the angel Asmodeus.

Pazuzu is often credited with bringing the Blood War between Demons and Devils to fruition. Some believe he was capable of this as he is the only demon lord who has good relations with the Archdevils of Hell. Strangely, the demon lord that hates Pazuzu the most is Graz'zt, supposedly a Lord of Hell before becoming an Abyssal Lord.

When he visits the mortal world, Pazuzu often uses the names Pazrael, Imdugud, or Typhon. Whichever name he uses, he passes himself off in the guise of a benevolent entity that grants protections against pestilence and blesses childbirth. Those who use his protections are corrupted into committing vile acts, and children blessed by him are cursed to grow up with evil in their hearts.

The first and most ancient demon lord. He has been trapped in an iron flask and must be kept imprisoned until a way is found to destroy him.

> [!note] The Iron Flask
> 
> One way to use Pazuzu is to have him imprisoned in an iron flask magic item. In this scenario, the group patron gives the players the iron flask at some early point in their career and tasks them with keeping Pazuzu trapped inside until they find a way to destroy the demon lord so that he is sent screaming back to the Abyss for a century. Many different powerful entities will seek to take the iron flask from the players over the course of the campaign.
> 
> The henchmen Edwin Odesseiron and [Eo Ashmajiir](3-Mechanics/CLI/bestiary/npc/eo-ashmajiir-mabjov.md) are powerful magic users who want to possess the iron flask to augment their own power. They might compete against each other in their attempts to wrest the flask away from the players.
> 
> Archdevils such as Baalzebul and Mephistopheles also actively pursue the flask, wanting to gain favor with Asmodeus by presenting him the demon lord who supposedly led to his downfall. The players might be able to play the archdevils against each other in order to survive.
> 
> The demodands of Ust Natha's Carcerus prison might send bebilith in search of the flask. They seek to imprison the demon lord in Carceri for reasons only known to their shator overlords.
> 
> Jon Irenicus might seek to steal the iron flask, believing that Pazuzu holds the secret to escaping the dread domain of Suldanessellar. He might send members of the Order of Icarus, or the players might be tricked into summoning Jon's sister—Bodhi Irenicus.
^the-iron-flask

```statblock
"name": "Pazuzu (MaBJoV)"
"size": "Large"
"type": "fiend"
"subtype": "demon"
"alignment": "Chaotic Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "405"
"hit_dice": "30d10 + 240"
"modifier": !!int "10"
"stats":
  - !!int "23"
  - !!int "30"
  - !!int "27"
  - !!int "23"
  - !!int "18"
  - !!int "27"
"speed": "30 ft., fly 90 ft."
"saves":
  - "dexterity": !!int "18"
  - "constitution": !!int "16"
  - "charisma": !!int "16"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+12"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+16"
"damage_resistances": "acid, cold, fire"
"damage_immunities": "lightning; poison; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 22"
"languages": "all, telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "Any evil creature with a natural fly speed and a CR of 20 or less must\
      \ make a DC 21 Wisdom saving throw if they attempt to attack Pazuzu. A failed\
      \ save means their action is wasted and the attack fails. On a successful saving\
      \ throw the target is immune to this effect in the future."
    "name": "Aura of Servile Avians"
  - "desc": "If Pazuzu fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Pazuzu has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Pazuzu's weapon attacks are magical."
    "name": "Magic Weapons"
"actions":
  - "desc": "Pazuzu makes two Greatsword or Talon attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 13 (2d6 + 6) slashing damage plus 7 (2d6) necrotic damage."
    "name": "Greatsword"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 15 (2d8 + 6) slashing damage plus 9 (2d8) poison damage."
    "name": "Talon"
  - "desc": "Pazuzu exhales poisonous acid in a 100-foot line that is 5 feet wide.\
      \ Every creature hit by the acid must make a DC 21 Dexterity saving throw, taking\
      \ 70 (20d6) acid damage on a failed save, or half as much damage on a successful\
      \ one. A creature killed by this breath weapon melts and is disintegrated."
    "name": "Breath Weapons (Recharge 5-6)"
  - "desc": "Pazuzu casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 24):\n\n**At\
      \ will:** [astral projection](3-Mechanics/CLI/spells/astral-projection.md),\
      \ [blight](3-Mechanics/CLI/spells/blight.md), [charm person](3-Mechanics/CLI/spells/charm-person.md),\
      \ [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md), [dispel\
      \ magic](3-Mechanics/CLI/spells/dispel-magic.md), [hallow](3-Mechanics/CLI/spells/hallow.md),\
      \ [insect plague](3-Mechanics/CLI/spells/insect-plague.md), [telekinesis](3-Mechanics/CLI/spells/telekinesis.md),\
      \ [teleport](3-Mechanics/CLI/spells/teleport.md), [wind walk](3-Mechanics/CLI/spells/wind-walk.md)\n\
      \n**2/day each:** [dominate person](3-Mechanics/CLI/spells/dominate-person.md),\
      \ [hypnotic pattern](3-Mechanics/CLI/spells/hypnotic-pattern.md), [plane shift](3-Mechanics/CLI/spells/plane-shift.md)\
      \ (only itself and willing creatures)\n\n**1/day:** [wish](3-Mechanics/CLI/spells/wish.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Pazuzu casts [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md),\
      \ automatically dispelling any spell of 6th level or lower on the target."
    "name": "Dispel"
  - "desc": "Pazuzu uses his magic greatsword to grant him the following abilities\
      \ until the start of his next turn. Pazuzu's speed is now doubled, he gains\
      \ a +2 bonus to AC, has advantage on Dexterity saving throws, and gains one\
      \ additional Greatsword attack."
    "name": "Hasted Greatsword"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Pazuzu can expend a use to take one of the following actions. Pazuzu regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Pazuzu attempts to knock a weapon out of a target's hand. He makes a\
      \ Greatsword attack and if it hits, the target does not take damage but instead\
      \ must make a DC 22 Strength saving throw. If the target fails the saving throw,\
      \ the targeted weapon flies 10 feet away in a random direction."
    "name": "Disarm"
  - "desc": "Pazuzu attacks once with his Greatsword or Talon and then may fly up\
      \ to 60 feet away. Pazuzu's movement does not provoke opportunity attacks."
    "name": "Lethal Leap"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/pazuzu-mabjov.webp"
```
^statblock