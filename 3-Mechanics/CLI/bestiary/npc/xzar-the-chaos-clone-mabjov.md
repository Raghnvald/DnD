---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/11
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Xzar the Chaos Clone"
---
# [Xzar the Chaos Clone](3-Mechanics/CLI/bestiary/npc/xzar-the-chaos-clone-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 128*  

> [!quote] A quote from Volo  
> 
> I have long wondered what a creature without a soul would be like. It is unfortunate that the first example is also insane.

Xzar was a talented necromancer known for his erratic and bizarre behavior. He worked with the Zhentarim for a number of years with a halfling partner named Montaron or "Monty," as Xzar called him. The two of them got involved in the Bhaalspawn incident more than a century ago and their partnership dissolved soon after.

Xzar decided to attempt a magical ritual that would turn him into a lich. While successful at achieving this goal, once he embraced undeath he quickly descended into insanity. Xzar lost track of his phylactery and thus didn't feed it the souls required to fuel his undead state. Several decades later his body had crumbled to dust and Xzar had devolved into a demilich.

Before becoming a lich, Xzar had created a clone as a contingency against death. A clone usually remains inert until a soul reanimates the body. But the Slaad Lord Ssendam was able to animate the clone body by using the power of the Chaos Phage. The animated clone has the base personality of Xzar, along with his magical skills with necromancy.

This reanimated Xzar is missing a soul and because of this he does not feel whole. This has made him even more erratic than the original Xzar. Xzar is desperate to create a new soul for himself and everything he does is in pursuit of that goal. He does revere his Slaad creator, but mostly because Ssendam has promised to aid him in his quest to create a soul.

Xzar is pragmatic and manipulative enough to appear amicable while sizing up potential allies (or victims). Many of Xzar's casual observations come out as gibberish, though they can often have cryptic meanings.

```statblock
"name": "Xzar the Chaos Clone (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "15"
"ac_class": "18 with [mage armor](3-Mechanics/CLI/spells/mage-armor.md)"
"hp": !!int "121"
"hit_dice": "22d8 + 22"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "16"
  - !!int "12"
  - !!int "20"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "9"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](3-Mechanics/CLI/rules/skills.md#Arcana)"
    "desc": "+13"
  - "name": "[History](3-Mechanics/CLI/rules/skills.md#History)"
    "desc": "+13"
"damage_resistances": "acid, cold, fire, lightning, thunder"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 10"
"languages": "Abyssal, Common, Infernal, Primordial, Undercommon, telepathy 60 ft."
"cr": "11"
"traits":
  - "desc": "Xzar's infusion with the Chaos Phage gives him the following benefits:\n\
      \n- Xzar regains 10 hit points at the start of his turn if he has at least 1\
      \ hit point  \n- Xzar has advantage on saving throws against spells and other\
      \ magical effects  \n- Xzar has resistance to acid, cold, fire, lightning, thunder\
      \  \n- Xzar has darkvision and telepathy to 60 feet  "
    "name": "Chaos Phage"
  - "desc": "When Xzar kills a creature that is neither a Construct nor Undead with\
      \ a spell of 1st level or higher, Xzar regains hit points equal to twice the\
      \ spell's level, or three times if it is a necromancy spell."
    "name": "Grim Harvest (1/Turn)"
  - "desc": "Since Xzar doesn't have a soul, resurrection magic is able to work upon\
      \ him no matter how much time has passed. For example, the [revivify](3-Mechanics/CLI/spells/revivify.md)\
      \ spell would work on Xzar even a week after he died. However, spells like true\
      \ resurrection and wish are unable to bring Xzar back to life if no body exists."
    "name": "No Soul"
"actions":
  - "desc": "Xzar makes two Deprive attacks and uses Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +9 to hit, reach 5 ft., or range 120\
      \ ft., one target. *Hit:* 27 (4d10 + 5) necrotic damage."
    "name": "Deprive"
  - "desc": "Negative energy erupts from Xzar, intensified by the Chaos Phage. Any\
      \ creature in a 60-foot-radius sphere around Xzar (but not including Xzar) must\
      \ make a DC 17 Constitution saving throw. A creature takes 36 (8d6) necrotic\
      \ damage on a failed save, or half as much damage on a successful one. A Humanoid\
      \ killed by this ability rises at the start of Xzar's next turn as a zombie\
      \ under his command."
    "name": "Death Eruption (1/Day)"
  - "desc": "Xzar casts one of the following spells, requiring no material components\
      \ and using Intelligence as the spellcasting ability (spell save DC 17, +9\
      \ to hit with spell attacks):\n\n**At will:** [acid splash](3-Mechanics/CLI/spells/acid-splash.md),\
      \ [fire bolt](3-Mechanics/CLI/spells/fire-bolt.md), [mage hand](3-Mechanics/CLI/spells/mage-hand.md)\n\
      \n**2/day each:** [animate dead](3-Mechanics/CLI/spells/animate-dead.md)*, [blight](3-Mechanics/CLI/spells/blight.md)*,\
      \ [false life](3-Mechanics/CLI/spells/false-life.md)*, [mage armor](3-Mechanics/CLI/spells/mage-armor.md),\
      \ [ray of enfeeblement](3-Mechanics/CLI/spells/ray-of-enfeeblement.md)*, [ray\
      \ of sickness](3-Mechanics/CLI/spells/ray-of-sickness.md)*, [scrying](3-Mechanics/CLI/spells/scrying.md),\
      \ [vampiric touch](3-Mechanics/CLI/spells/vampiric-touch.md)*\n\n**1/day each:**\
      \ abi-dalzim's horrid wilting*, [finger of death](3-Mechanics/CLI/spells/finger-of-death.md)*\n\
      \n*Necromancy spell of 1st level or higher"
    "name": "Spellcasting"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/xzar-the-chaos-clone-mabjov.webp"
```
^statblock