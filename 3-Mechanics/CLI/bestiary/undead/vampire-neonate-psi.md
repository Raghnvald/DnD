---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/5
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/undead
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Vampire Neonate"
---
# [Vampire Neonate](3-Mechanics/CLI/bestiary/undead/vampire-neonate-psi.md)
*Source: Plane Shift: Innistrad p. 17*  

The vampires of Innistrad form a civilization that stands alongside and in direct competition with humanity, presenting the greatest danger to human life on the plane. Like werewolves, vampires were originally human, and they view themselves as successors to the weak human race—even as they grudgingly recognize that they require humans to feed upon. Vampires are the embodiment of self-indulgent desire, pursuing hedonistic cravings that humans suppress out of a sense of morality and propriety. In their stately manor houses, sprawling courts, and towering castles, four great family lines of vampires show varying degrees of aggressiveness toward their human prey.

## The Nature of Vampirism

Vampirism on Innistrad is an anointing that persists and is perpetuated by magic—not a curse or a disease, but a physical state that the vampires somewhat euphemistically call a "condition of the blood."

### Vampire Appearance

Vampires have distinctive eyes, appearing as pools of gold or silver surrounded by black. Their hair is often black but can also be deep purple, dark magenta, burgundy, or even dark blue-green. Some vampires wear wigs for variety, novelty, or to disguise themselves more easily among humans. They have pale skin that is cool to the touch. Their canine teeth are slightly pronounced at all times, and they extend significantly when they bite to feed. Vampires also tend to have long and slightly curved fingernails.

### Vampiric Glamer

Many vampires learn a unique form of mind-affecting magic that enables them to move among humans undetected. Called the glamer, this power alters what nearby humans think they're perceiving, as opposed to true illusion magic that masks the subject's appearance. As such, particularly strong-willed humans can sometimes shake off the effects of the glamer to see a vampire's true form.

### Vampire Vulnerabilities

Weapons cut from living wood are particularly effective against vampires, though any weapon can harm or kill them. A vampire can't cross running water that shows the reflection of the moon, and water blessed by Avacyn ([holy water](3-Mechanics/CLI/items/holy-water-flask.md)) burns vampire flesh like acid. A vampire's reflection in silver (including a silver-backed glass mirror) appears as the vampire would have looked without the vampiric condition—neither its true appearance nor its glamer, but a normal human, flaws and all. For that reason, vampires go to great lengths to avoid mirrors, and the presence of silver in any form is unsettling to them.

### The Unquenchable Thirst

A vampire needs to consume the blood of living humans for sustenance. At a minimum, during any given cycle of the moon, a vampire must drink as much blood as an average adult human contains (about five liters). Without enough blood, the vampire dries and shrivels, eventually crumbling to dust. Given the opportunity, most vampires will happily consume more blood than they strictly need.

Typically, a vampire drinks so much blood from a human that the victim dies, but sometimes the vampire is interrupted and the human survives and recovers. Such survivors are often met with suspicion and fear, but they never become vampires unless an actual exchange of blood has occurred—which is always a deliberate act on the vampire's part. These survivors are often plagued by unsettling (and sometimes disturbingly erotic) dreams, but they suffer no other lasting consequences.

### Vampire Personality

The selfish and arrogant vampires view humans as cattle in comparison to the elegance and sophistication of vampire society. Of course, that "sophistication" consists mostly of treachery and debauchery, where grudges and betrayals are a source of amusement. The vampires' endless revels, feasts, romances, and intrigues are rife with decadence and hedonism. They overindulge in everything, including sex, food, drink, entertainment, sleep, and scheming.

## Vampire Bloodlines

Innistrad's ancient history speaks of a human alchemist and healer named Edgar Markov, who sought to preserve his own life and the lives of his family. As old age began to claim him, he despaired of finding an alchemical solution and turned to black magic. Not long after, the demon Shilgengar appeared to Markov and revealed a means by which he could achieve immortality: a dark ritual that involved drinking an angel's blood.

The vampires of Innistrad are all descended from twelve ancient sires—the congregation that participated in Markov's blasphemous ritual. Of these twelve bloodlines, four constitute the vast majority of Innistrad's vampires: Markov, Voldaren, Falkenrath, and Stromkirk.

```statblock
"name": "Vampire Neonate (PSI)"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "15"
"ac_class": "natural armor"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "3"
"stats":
  - !!int "16"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "10"
  - !!int "12"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+6"
"damage_resistances": "necrotic; bludgeoning, piercing, slashing from nonmagical attacks\
  \ not made with living wood weapons"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 13"
"languages": "Common"
"cr": "5"
"traits":
  - "desc": "The vampire regains 10 hit points at the start of its turn if it has\
      \ at least 1 hit point. If the vampire takes radiant damage or damage from [holy\
      \ water](3-Mechanics/CLI/items/holy-water-flask.md), this trait doesn't function\
      \ at the start of the vampire's next turn."
    "name": "Regeneration"
"actions":
  - "desc": "The vampire makes two attacks, only one of which can be a bite attack."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one creature. *Hit:*\
      \ 8 (2d4 + 3) slashing damage. Instead of dealing damage, the vampire can\
      \ grapple the target (escape DC 13)."
    "name": "Claws"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one willing creature,\
      \ or a creature that is [grappled](3-Mechanics/CLI/rules/conditions.md#Grappled)\
      \ by the vampire, [incapacitated](3-Mechanics/CLI/rules/conditions.md#Incapacitated),\
      \ or [restrained](3-Mechanics/CLI/rules/conditions.md#Restrained). *Hit:* 6\
      \ (1d6 + 3) piercing damage plus 7 (2d6) necrotic damage. The target's hit\
      \ point maximum is reduced by an amount equal to the necrotic damage taken,\
      \ and the vampire regains hit points equal to that amount. The reduction lasts\
      \ until the target finishes a long rest. The target dies if this effect reduces\
      \ its hit point maximum to 0."
    "name": "Bite"
  - "desc": "The vampire obscures its form with mind-affecting magic that makes others\
      \ perceive it as a beautiful human of the same size and shape. The illusion\
      \ ends if the vampire takes a bonus action to end it or if the vampire dies.\
      \ A creature that can see the vampire can take an action to visually inspect\
      \ it, ending the mental effect on itself and seeing the vampire's true form\
      \ with a successful DC 20 Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ check."
    "name": "Vampiric Glamer"
  - "desc": "The vampire shrouds itself in a cloak of silence to a radius of 2 feet.\
      \ Within that radius, the effect is the same as the [silence](3-Mechanics/CLI/spells/silence.md)\
      \ spell."
    "name": "Aura of Silence"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/undead/token/vampire-neonate-psi.webp"
```
^statblock