---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mff
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/humanoid/goblinoid
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Norker War Leader"
---
# [Norker War Leader](3-Mechanics/CLI/bestiary/humanoid/norker-war-leader-mff.md)
*Source: Mordenkainen's Fiendish Folio p. 17*  

Cruel, vicious, and lazy even by the standards of goblinoids, norkers are tough humanoids whose long, sharp fangs and thick, bony exoskeletons make them well-suited to the ranks of hobgoblin armies. Unfortunately for their would-be masters, norkers are rebellious, truculent, and prone to indolence unless watched with a keen eye and a hand that is quick to snap a whip.

## Denizens of the Deep Earth

In the ancient days, norkers were found deep within the earth. They were always few in number, and their god was a cruel, merciless tyrant who kept his children close and the outside world at a distance. This long-lost god may have been Maglubiyet's first conquest and his followers the initial, unwilling recruits into his crusade. Today, hobgoblins chafe at the suggestion that creatures as lazy and untamed as norkers could claim such an honor. For that reason alone, hobgoblin warlords are loath to use these creatures, preferring to keep them around as disposable labor in mines and quarries.

## Nasty, Brutish, and Short

Even goblins bully and harass norkers, as hobgoblins place the norkers at the bottom of the goblinoid ranks, yet the norkers' ferocity, tough hides, and sharp fangs allow them to rise up and defeat goblinoids that underestimate the norkers' strength and ferocity.. For this reason, norkers are likely encountered away from their brethren. Their natural armor and weapons make them dangerous foes even when relegated to menial labor. Only the dictates of Maglubiyet have prevented the hobgoblins from hunting down and exterminating these creatures.

## A Legacy of Hatred

Given their ancient defeat and terrible treatment at the hands of other goblinoids, the norkers have developed a peculiar sect of Maglubiyet worshipper. They call him the Great Scourge and believe that mortal life is a cruel test. Those norkers whose skin can withstand any blow and whose fangs sink deep into their enemies will be shepherded to paradise. To the norkers, all other creatures are enemies. Strong creatures can be mollified with servitude and obsequious begging, while weaker ones are victims for their fangs and clubs.

```statblock
"name": "Norker War Leader (MFF)"
"size": "Small"
"type": "humanoid"
"subtype": "goblinoid"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"ac_class": "natural armor"
"hp": !!int "39"
"hit_dice": "6d8 + 12"
"modifier": !!int "0"
"stats":
  - !!int "16"
  - !!int "10"
  - !!int "15"
  - !!int "12"
  - !!int "11"
  - !!int "13"
"speed": "30 ft."
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+5"
  - "name": "[Intimidation](3-Mechanics/CLI/rules/skills.md#Intimidation)"
    "desc": "+3"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+2"
"gear":
  - "[greataxe](3-Mechanics/CLI/items/greataxe.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 12"
"languages": "Common, Goblin"
"cr": "3"
"actions":
  - "desc": "The norker war leader makes one greataxe and one bite attack, and also\
      \ uses Fight On, You Slugs."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d6 + 3) piercing damage."
    "name": "Bite"
  - "desc": "*Melee Weapon Attack:* +5 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d12 + 3) slashing damage."
    "name": "Greataxe"
  - "desc": "The norker war leader picks up to three allied goblinoids within 60 feet\
      \ that can see it. The chosen creatures can each use their reactions to make\
      \ a single melee attack."
    "name": "Fight On, You Slugs"
"reactions":
  - "desc": "If a creature within 5 feet of the norker makes a melee attack against\
      \ it, the norker can use its reaction to cause 6 piercing damage to it."
    "name": "Defensive Rebuke"
"source":
  - "MFF"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/norker-war-leader-mff.webp"
```
^statblock