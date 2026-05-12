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
- "Minsc and Boo!"
---
# [Minsc and Boo!](3-Mechanics/CLI/bestiary/npc/minsc-and-boo-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 68*  

Minsc is a berserker warrior from the nation of Rashemen in the utter east, though his affinity for animals speaks to his skill as a hunter and tracker as well. He originally came to the Sword Coast on a dejemma, a ritual journey to manhood, as the bodyguard of a young Wychalarn of Rashemen named Dynaheir. But Dynaheir was killed while Minsc was adventuring with the Bhaalspawn known as Abdel Adrian.

Minsc continued his adventures with Abdel until he had the misfortune of being [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified) by an evil wizard. He remained a [petrified](3-Mechanics/CLI/rules/conditions.md#Petrified) statue for nearly a century before another wizard released him. Everyone and everything that he had known had passed on, so Minsc decided not to return to Rashemen, but continue his adventures on the Sword Coast. During those adventures he met Suldil. He felt an affinity for the woman due to the fact that they both lost centuries of their lives to magic. When he has time away from his other adventures, Minsc helps track down prospective heroes who Suldil thinks might make good members of the Knights of Bahamut. Minsc secretly hopes that she will one day think that Boo will make a good member of the Knights of Bahamut.

Minsc does not have a strong hold on reality, as evidenced by his continued dependence on his animal companion Boo, a creature that he claims is a miniature giant space hamster. Apparently such things do exist somewhere in the Realms, but Minsc has surely taken too many blows to the head. Minsc has a very simplistic view of the world and is often quick to decide whether or not someone is evil and should be attacked. Fortunately, he is also kind by nature and determined to be a hero. He is somewhat unstable and is prone to flying into a rage.

## Minsc as a Contact

Minsc is the primary contact for members of the Knights of Bahamut at low levels. He is able to convince strange companions to join you in your adventures. Your group can only have one such companion at a time.

**Strange Companions via Minsc**

| Companion | Required Level | Stat Block |
|-----------|----------------|------------|
| Goo—Boo's miniature space hamster cousin | 1 | Rat |
| Murderoid—the living moon | 3 | A large point of light in the night sky. Also, a voice that speaks in your head at night... about murdering your enemies |
| Delphinid—the space dolphin | 3 | Dolphin with fly speed of 30 ft. |
| Backpack guy—the space mimic | 7 | Mimic that can only assume the form of a backpack. Refuses to fight unless worn |
| Basharin—a blind beholder | 7 | Beholder that does not have the antimagic cone trait and whose only action is bite |
^strange-companions-via-minsc

```statblock
"name": "Minsc and Boo! (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Neutral Good"
"ac": !!int "13"
"ac_class": "[studded leather](3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "187"
"hit_dice": "22d8 + 88"
"modifier": !!int "1"
"stats":
  - !!int "20"
  - !!int "12"
  - !!int "18"
  - !!int "10"
  - !!int "10"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "8"
"skillsaves":
  - "name": "[Athletics](3-Mechanics/CLI/rules/skills.md#Athletics)"
    "desc": "+9"
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Survival](3-Mechanics/CLI/rules/skills.md#Survival)"
    "desc": "+8"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
"senses": "passive Perception 14"
"languages": "Common, Sylvan"
"cr": "10"
"traits":
  - "desc": "Boo is Minsc's animal companion. Boo is a miniature giant space hamster\
      \ and has the statistics of a [rat](3-Mechanics/CLI/bestiary/beast/rat.md)."
    "name": "Boo, The Miniature Giant Space Hamster"
  - "desc": "Minsc's favored enemy is evil. When he hits an evil creature with a melee\
      \ attack he deals an additional 7 (2d6) slashing damage."
    "name": "Favored Enemy"
  - "desc": "At the start of his turn, Minsc may choose to gain advantage on all melee\
      \ weapon attack rolls during that turn, but attack rolls against him have advantage\
      \ until the start of his next turn."
    "name": "Reckless"
"actions":
  - "desc": "Minsc makes two Greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d6 + 5) slashing damage."
    "name": "Greatsword"
"bonus_actions":
  - "desc": "As a bonus action, Minsc talks to Boo and gains the inspiration to go\
      \ into a berserker fury, for 1 minute. While in this berserking fury Minsc gains\
      \ the following:\n\n- Minsc has advantage on Strength checks and Strength saving\
      \ throws.  \n- Minsc gains a +4 bonus to damage rolls when using a melee weapon.\
      \  \n- Minsc has resistance to bludgeoning, piercing, and slashing damage. \
      \ \n- Minsc can make a single melee weapon attack as a bonus action on each\
      \ of his turns.  \n- Minsc can't be [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed)\
      \ or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened). If Minsc\
      \ is [charmed](3-Mechanics/CLI/rules/conditions.md#Charmed) or [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened)\
      \ when he enters his berserking fury, the effect is suspended for the duration\
      \ of the rage  \n- If Minsc drops to 0 hit points and doesn't die outright,\
      \ he can make a DC 10 Constitution saving throw. If he succeeds, he drops to\
      \ 1 hit point instead. Each time he uses this feature after the first, the DC\
      \ increases by 5. After 24 hours, the DC resets to 10.  "
    "name": "Go for the Eyes, Boo"
"reactions":
  - "desc": "If Boo takes damage, Minsc can choose to take the damage instead."
    "name": "Run, Boo, Run"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/minsc-and-boo-mabjov.webp"
```
^statblock