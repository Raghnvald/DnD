---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/crcotn
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Alyxian the Dispossessed"
---
# [Alyxian the Dispossessed](3-Mechanics/CLI/bestiary/npc/alyxian-the-dispossessed-crcotn.md)
*Source: Critical Role: Call of the Netherdeep p. 180*  

```statblock
"name": "Alyxian the Dispossessed (CRCotN)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Evil"
"ac": !!int "15"
"ac_class": "leather armor, shield"
"hp": !!int "153"
"hit_dice": "18d8 + 72"
"modifier": !!int "2"
"stats":
  - !!int "19"
  - !!int "15"
  - !!int "18"
  - !!int "13"
  - !!int "14"
  - !!int "20"
"speed": "30 ft."
"saves":
  - "strength": !!int "9"
  - "constitution": !!int "9"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "Insight"
    "desc": "+7"
  - "name": "Perception"
    "desc": "+7"
  - "name": "Persuasion"
    "desc": "+10"
"condition_immunities": "charmed, exhaustion, frightened, paralyzed, petrified, stunned"
"gear":
  - "spear"
"senses": "darkvision 120 ft., passive Perception 17"
"languages": "Celestial, Common, Elvish, telepathy 120 ft."
"cr": "13"
"traits":
  - "desc": "Alyxian can't be surprised and can't be changed into another form against\
      \ his will."
    "name": "Divinely Blessed"
  - "desc": "If Alyxian fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (2/Day)"
  - "desc": "Alyxian carries a magic dagger that he uses to make Stoneheart Dagger\
      \ attacks. In the hands of creatures other than Alyxian, the dagger is nonmagical\
      \ and has no special properties."
    "name": "Special Equipment"
"actions":
  - "desc": "Alyxian makes two Spear attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Weapon Attack:* +9 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 7 (1d6 + 4) piercing damage, or 8 (1d8 + 4) piercing\
      \ damage when used with two hands to make a melee attack, plus 9 (2d8) radiant\
      \ damage."
    "name": "Spear"
  - "desc": "*Melee  or Ranged Weapon Attack:* +9 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 11 (3d4 + 4) force damage, and if the target is\
      \ a creature, it must succeed on a DC 17 Constitution saving throw or become\
      \ petrified as the dagger lodges itself in the target's body. While the dagger\
      \ is lodged in the target, magic can't end the petrified condition on it and\
      \ Alyxian can't make Stoneheart Dagger attacks. A creature within reach of the\
      \ petrified target can use an action to try to remove the dagger, doing so with\
      \ a successful DC 17 Strength check."
    "name": "Stoneheart Dagger"
"bonus_actions":
  - "desc": "Alyxian's Stoneheart Dagger teleports into his free hand, provided he\
      \ has one."
    "name": "Summon Dagger"
"reactions":
  - "desc": "Alyxian adds 3 to his AC against one attack roll that would hit him.\
      \ To do so, Alyxian must see the attacker and be wielding a melee weapon."
    "name": "Parry"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Alyxian can take one\
      \ of the following lair actions; he can't take the same lair action two rounds\
      \ in a row:\n\n- **Avandra's Grasp.** Alyxian uses the power of Avandra's ruined\
      \ temple (area H2) to create a watery tendril that rises out of the lake. One\
      \ creature Alyxian can see that's not submerged in the lake must succeed on\
      \ a DC 15 Dexterity saving throw or be restrained by the tendril. The tendril\
      \ is a Large object that has AC 10, 15 hit points, and immunity to poison and\
      \ psychic damage. The tendril disappears when it is reduced to 0 hit points\
      \ or the next time Alyxian takes a lair action.  \n- **Corellon's Charm.** Alyxian\
      \ causes a magical wisp of light to emerge from Corellon's ruined temple (area\
      \ H3). The wisp enters the body of one creature Alyxian can see that isn't inside\
      \ Corellon's ruined temple or atop the rocky island that supports it. The creature\
      \ must succeed on a DC 15 Wisdom saving throw or be charmed by Alyxian until\
      \ initiative count 20 of the next round.  \n- **Sehanine's Torment.** Alyxian\
      \ uses the power of Sehanine's ruined temple (area H4) to create a watery form\
      \ in the space of one creature that is either standing on the lake or submerged\
      \ in it. The watery form assumes the vague likeness of the creature whose space\
      \ it occupies and makes one melee weapon attack (+7 to hit) against it. On\
      \ a hit, the attack deals 8 (1d8 + 4) bludgeoning damage. Whether it hits\
      \ or misses, the watery form disappears after making its attack.  \n\n**Prayers\
      \ to the Gods.** A character can use an action to pray to Avandra, Corellon,\
      \ or Sehanine in the deity's prayer site. The character must succeed on a DC\
      \ 15 Wisdom (Religion) check, and the check has advantage if the character is\
      \ a worshiper of that god. On a successful check, the profane ruins atop the\
      \ island melt away, and Alyxian can no longer use the lair action associated\
      \ with that prayer site. In addition, Alyxian takes 14 (4d6) psychic damage,\
      \ regardless of his current form."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Alyxian can expend a use to take one of the following actions. Alyxian regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Alyxian makes one Spear or Stoneheart Dagger attack."
    "name": "Attack"
  - "desc": "Alyxian moves up to his speed. This movement doesn't provoke opportunity\
      \ attacks."
    "name": "Warrior's Stride"
  - "desc": "A gem-sized shard of ruidium appears at a point Alyxian can see within\
      \ 120 feet of himself and explodes. Each creature, other than Alyxian, in a\
      \ 10-foot-radius sphere centered on that point must succeed on a DC 18 Charisma\
      \ saving throw or gain 1 level of exhaustion. If a creature isn't suffering\
      \ from ruidium corruption, it becomes corrupted when it fails the saving throw."
    "name": "Ruidium Shard (Costs 2 Actions)"
"source":
  - "CRCotN"
"image": "3-Mechanics/CLI/bestiary/npc/token/alyxian-the-dispossessed-crcotn.webp"
```
^statblock