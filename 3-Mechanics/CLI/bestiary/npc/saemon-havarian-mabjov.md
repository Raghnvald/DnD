---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/10
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Saemon Havarian"
---
# [Saemon Havarian](3-Mechanics/CLI/bestiary/npc/saemon-havarian-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 122*  

> [!quote] A quote from MINSC  
> 
> Fool me once, shame on you; fool me twice, watch it! Fool me three times and you're a pirate! Never trust a pirate! This is something me and Boo agree wholeheartedly on.

Saemon Havarian is a flamboyant and opportunistic sea-captain and a wizard with a knack for getting out of trouble, often by putting others in it in his stead. He has been sailing the Sea of Swords for decades. During this time, he has amassed a huge fortune, mostly through double crosses, unsavory business deals, and piracy.

Saemon is almost always accompanied by a small band of sirenes. These beautiful fey creatures are not only famed for their haunting song, but also as deadly warriors. How Saemon managed to earn their loyalty is a topic of discussion in seaports up and down the Sword Coast.

On the surface, Saemon's life looks truly blessed. With his vast fortune he has managed to buy his way into Athkatla's Council of Six, rising from a simple ship's captain, to merchant lord, to the head of one of the most powerful families in the nation of Amn. But there is a dark secret that haunts him; a looming shadow even he has not been able to connive his way out from under.

While Saemon appears to be 60 years old, he is actually almost double that age. Seven decades ago, years ago, he had a heart attack during a pirate raid against Calishite merchant ships. While it looked like fate had finally caught up with him, one of his Calishite prisoners offered him a way out in exchange for his freedom. The merchant, a follower of the Archdevil Baalzebul, granted Saemon another century of life if he signed over his soul.

Now the clock is ticking for the sea captain. While he still has almost a quarter of a century left before his bargain ends, he has no intention of spending eternity in Hell. He is desperate for a way out of his deal, and recently Baalzebul gave Saemon the impression that he could buy his way out of the contract by giving the Archdevil access to political power in Athkatla. But since joining the Council of Six, it has become increasingly clear to Saemon that Baalzebul will never rip up his soul contract; the sea captain has been on the other side of enough double crosses to see one coming his way.

```statblock
"name": "Saemon Havarian (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Neutral"
"ac": !!int "14"
"ac_class": "17 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "156"
"hit_dice": "24d8 + 48"
"modifier": !!int "4"
"stats":
  - !!int "19"
  - !!int "18"
  - !!int "14"
  - !!int "18"
  - !!int "11"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "strength": !!int "8"
  - "dexterity": !!int "8"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+8"
  - "name": "[Deception](3-Mechanics/CLI/rules/skills.md#Deception)"
    "desc": "+6"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+6"
"gear":
  - "[handaxe](3-Mechanics/CLI/items/handaxe.md)"
"senses": "passive Perception 10"
"languages": "Common, Infernal, Undercommon"
"cr": "10"
"traits":
  - "desc": "Saemon wears a quiver of Ehlonna (holding [40 handaxes](3-Mechanics/CLI/items/handaxe.md))."
    "name": "Special Equipment"
"actions":
  - "desc": "Saemon makes three Handaxe attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +8 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d6 + 4) slashing damage plus 3 (1d6) force\
      \ damage."
    "name": "Handaxe"
  - "desc": "Saemon casts one of the following spells, using Intelligence as the spellcasting\
      \ ability (spell save DC 16):\n\n**At will:** [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md),\
      \ [light](3-Mechanics/CLI/spells/light.md), [mage hand](3-Mechanics/CLI/spells/mage-hand.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md)\n\n**2/day\
      \ each:** [counterspell](3-Mechanics/CLI/spells/counterspell.md), [detect magic](3-Mechanics/CLI/spells/detect-magic.md),\
      \ [mage armor](3-Mechanics/CLI/spells/mage-armor.md), [magic missile](3-Mechanics/CLI/spells/magic-missile.md),\
      \ [misty step](3-Mechanics/CLI/spells/misty-step.md), [suggestion](3-Mechanics/CLI/spells/suggestion.md)\n\
      \n**1/day each:** [fly](3-Mechanics/CLI/spells/fly.md), [greater invisibility](3-Mechanics/CLI/spells/greater-invisibility.md),\
      \ [ice storm](3-Mechanics/CLI/spells/ice-storm.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Saemon conjures a swirling yellow barrier and until the start of his\
      \ next turn he adds +5 to his AC, including against the triggering attack, and\
      \ he takes no damage from magic missile."
    "name": "Arcane Shield"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Saemon can expend a use to take one of the following actions. Saemon regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Saemon makes a ranged Handaxe attack."
    "name": "Hurl"
  - "desc": "Saemon uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "Saemon casts [animate objects](3-Mechanics/CLI/spells/animate-objects.md),\
      \ targeting up to 10 handaxes he has thrown at enemies. If there are not 10\
      \ handaxes available, then he provides the remaining handaxes from his quiver\
      \ of Ehlonna. Handaxes are Tiny objects."
    "name": "Animate Objects (Costs 3 Actions)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/saemon-havarian-mabjov.webp"
```
^statblock