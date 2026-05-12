---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/22
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Jon Irenicus"
---
# [Jon Irenicus](3-Mechanics/CLI/bestiary/npc/jon-irenicus-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 73*  

> [!quote] A quote from MINSC & BOO!  
> 
> Me and Boo have traveled far and wide and wide and far. Over mountains and under mountains and beside mountains. In all these places we have fought evil...for evil is everywhere. We have fought evil that is as evil as a green dragon that assaults your senses with tremendously loud and stinky belches. But never have we fought evil quite like Jon and Bodhi.

Joneleth of the house of Icarus was at one time the most powerful wizard in the elven city of Suldanessellar, and the favorite of the city's queen, Ellesime. Despite his esteemed position, Jon was led astray by the madness of his sister, Bodhi. She convinced Jon that he shouldn't be content with the power he possessed; that he deserved more.

To seduce her brother, Bodhi shared magical secrets with Jon that she had learned from the Dark Powers of the Shadowfell. Using one of these secrets, Jon attempted to steal the life force from Suldanessellar's Tree of Life, believing it would grant him power on the level of the elven gods. The ritual failed and many elves nearly died as a result. For their crimes, Queen Ellesime cursed Jon and Bodhi, stripping them of their elven longevity and exiling them from the city. The elven people no longer recognized the siblings as their own kind and so the exiled siblings took new names. Joneleth Icarus became Jon Irenicus (an elven word meaning "unclean").

Following his exile, Irenicus became obsessed with regaining the longevity that he had lost. He spent much of his time researching forbidden magic and engaging in horrific experimentation. Within his subterranean lair beneath the city of Athkatla, he tortured and studied mortal captives by means of twisted magic. One of those captives was the Bhaalspawn Abdel Adrian, mortal son of the God of Murder. Jon sought to draw the divine spark out of Abdel and take it for himself. But Abdel escaped imprisonment and eventually hunted down and killed Jon, bringing his existence to a seemingly ignominious end.

But that was not to be Jon's final fate. Due to a pact with the Dark Powers of the Shadowfell, Jon and Bodhi were drawn into a dark reflection of the treetop city in the Domain of Dread. Trapped and unable to escape the prison of his own making, Jon is still able to inflict misery on the elves of Suldanessellar with the help of his sister and their loyal followers.

## Jon Irenicus as a Contact

Jon Irenicus becomes available as a contact at 11th level. Jon has researched the path to become a lich. He is only willing to share the secret of lichdom with a wizard who is at least 17th level and swears lifelong fealty to him.

- Mastering the Ritual: You must read the books that Jon provides you. This takes 10 weeks of downtime.  
- Building a Phylactery: You must build a phylactery. It can be a small box or any other item that has an interior space where arcane sigils can be drawn. It must be crafted from precious metals worth at least 50,000 gp in total. You must then scribe the arcane sigils of naming, binding, immortality, and dark magic in silver. This process takes 10 weeks of downtime.  
- The First Soul: You must capture a living humanoid or fiend. This humanoid or fiend must have a CR of 8 or greater.  
- Brewing the Potion: You must brew the potion of transformation. The blood of the first soul must be poured into this concoction. Brewing the potion takes 1 week and 20,000 gp worth of ingredients.  
- Performing the Ritual: Performing the final ritual requires an additional 30,000 gp in precious metals, rare herbs and incenses and various other components. The ritual takes 8 hours. At the end of it you must cast the [imprisonment](3-Mechanics/CLI/spells/imprisonment.md) spell on the first soul. Then you must drink the potion of transformation. If you succeed at a DC 15 Constitution saving throw you rise up as a lich. If you fail the saving throw you are struck dead. You cannot be raised except with a [wish](3-Mechanics/CLI/spells/wish.md) spell.  
- Lichdom: It is up to your DM whether or not you can continue play as a lich. If your DM does allow you to continue play as a lich, it is recommended that you receive no legendary actions, no lair actions, no paralyzing touch and no legendary resistance. Instead, your race becomes undead and you gain the following benefits:  
-     - Resistance to damage from Cold, Lightning and Necrotic.    
        - Immunity to Poison damage and Bludgeoning, Piercing, and Slashing from Nonmagical Attacks.    
        - Immunity to the Charmed, Exhaustion, Frightened, Paralyzed and Poisoned conditions.    
        - If you are destroyed you gain a new body in `1d10` days, regaining all of your hit points and becoming active again. The new body appears within 5 feet of your phylactery.    

```statblock
"name": "Jon Irenicus (MaBJoV)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "217"
"hit_dice": "29d8 + 87"
"modifier": !!int "3"
"stats":
  - !!int "19"
  - !!int "16"
  - !!int "16"
  - !!int "22"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "constitution": !!int "10"
  - "intelligence": !!int "13"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+20"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+13"
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold, lightning, necrotic"
"damage_immunities": "poison; bludgeoning, piercing, slashing from nonmagical attacks"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed),\
  \ [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[mace](3-Mechanics/CLI/items/mace.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 19"
"languages": "Abyssal, Celestial, Common, Elvish, Infernal, Sylvan"
"cr": "22"
"traits":
  - "desc": "If Jon Irenicus fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If he has a phylactery and he is destroyed, Jon Irenicus gains a new\
      \ body in 1d10 days, regaining all his hit points and becoming active again.\
      \ The new body appears within 5 feet of the phylactery."
    "name": "Rejuvenation"
  - "desc": "Jon Irenicus carries a rod of lordly might. He can use a bonus action\
      \ to switch it between its [Mace](3-Mechanics/CLI/items/mace.md) and Flame Tongue\
      \ attacks."
    "name": "Special Equipment"
  - "desc": "Jon Irenicus has advantage on saving throws against any effect that turns\
      \ Undead."
    "name": "Turn Resistance"
"actions":
  - "desc": "Jon Irenicus makes two Flame Tongue attacks or two Mace attacks. Each\
      \ attack is made with advantage and does an additional 13 (2d12) force damage\
      \ if it hits."
    "name": "Multiattack (only useable with Transformation)"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 11 (1d8 + 7) slashing damage and 7 (2d6) fire damage."
    "name": "Flame Tongue (Rod of Lordly Might)"
  - "desc": "*Melee Weapon Attack:* +14 to hit, reach 5 ft., one target. *Hit:*\
      \ 10 (1d6 + 7) bludgeoning damage."
    "name": "Mace (Rod of Lordly Might)"
  - "desc": "Jon Irenicus emits a 90-foot cone of necrotic energy. Each creature in\
      \ the effects area must make a DC 21 saving throw, taking 55 (10d10) necrotic\
      \ damage on a failed save, half as much damage on a successful one."
    "name": "Breath of Death (1/Day)"
  - "desc": "Jon Irenicus casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 21, +13 to hit with spell attacks):\n\
      \n**At will:** [Melf's acid arrow](3-Mechanics/CLI/spells/melfs-acid-arrow.md),\
      \ [detect magic](3-Mechanics/CLI/spells/detect-magic.md), [detect thoughts](3-Mechanics/CLI/spells/detect-thoughts.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md), [magic missile](3-Mechanics/CLI/spells/magic-missile.md),\
      \ [mage hand](3-Mechanics/CLI/spells/mage-hand.md), [mirror image](3-Mechanics/CLI/spells/mirror-image.md),\
      \ [prestidigitation](3-Mechanics/CLI/spells/prestidigitation.md), [ray of frost](3-Mechanics/CLI/spells/ray-of-frost.md),\
      \ [shield](3-Mechanics/CLI/spells/shield.md)\n\n**2/day each:** [animate dead](3-Mechanics/CLI/spells/animate-dead.md),\
      \ [dimension door](3-Mechanics/CLI/spells/dimension-door.md), [dispel magic](3-Mechanics/CLI/spells/dispel-magic.md),\
      \ [fireball](3-Mechanics/CLI/spells/fireball.md), [scrying](3-Mechanics/CLI/spells/scrying.md)\n\
      \n**1/day each:** [disintegrate](3-Mechanics/CLI/spells/disintegrate.md), [dominate\
      \ monster](3-Mechanics/CLI/spells/dominate-monster.md), [finger of death](3-Mechanics/CLI/spells/finger-of-death.md),\
      \ [power word kill](3-Mechanics/CLI/spells/power-word-kill.md), [power word\
      \ stun](3-Mechanics/CLI/spells/power-word-stun.md), [time stop](3-Mechanics/CLI/spells/time-stop.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "Jon Irenicus interrupts a creature he can see that is casting a spell.\
      \ If the spell is 3rd level or lower, it fails and has no effect. If the spell\
      \ is 4th level or higher, Jon Irenicus makes an Intelligence check (DC 10 +\
      \ the spell's level). On a success, the spell fails and has no effect. Whatever\
      \ the spell's level, the caster takes 10 (3d6) necrotic damage if the spell\
      \ fails."
    "name": "Draining Counterspell"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Jon can expend a use to take one of the following actions. Jon regains all\
  \ expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Jon Irenicus makes a drain life attack with his rod of lordly might.\
      \ If he hits a creature with his rod, the creature must make a DC 17 Constitution\
      \ saving throw. On a failed save, the creature takes an extra 14 (4d6) necrotic\
      \ damage, and Jon regains a number of hit points equal to half that necrotic\
      \ damage."
    "name": "Drain Life (1/Day)"
  - "desc": "Jon Irenicus makes a paralyze attack with his rod of lordly might. If\
      \ he hits a creature with his rod, the creature must make a DC 17 Strength saving\
      \ throw. On a failed save, the creature has the [paralyzed](3-Mechanics/CLI/rules/conditions.md#Paralyzed)\
      \ condition for 1 minute. The creature can repeat the saving throw at the end\
      \ of each of its turns, ending the effect on a success."
    "name": "Paralyze (1/Day)"
  - "desc": "Jon Irenicus uses Spellcasting."
    "name": "Cast a Spell (Costs 2 Actions)"
  - "desc": "Jon Irenicus becomes endowed with endurance and martial prowess for 1\
      \ minute or until he ends this effect by using a bonus action. While transformed,\
      \ he gains 50 temporary hit points, proficiency in Strength and Constitution\
      \ saving throw, adds his Multiattack feature, and loses his Draining Counterspell\
      \ reaction and Spellcasting action."
    "name": "Transformation (Costs 3 Actions)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/jon-irenicus-mabjov.webp"
```
^statblock