---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/26
- ttrpg-cli/monster/size/huge
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Mammon"
---
# [Mammon](3-Mechanics/CLI/bestiary/npc/mammon-coa.md)
*Source: Chains of Asmodeus p. 230*  

Perhaps the richest being in all the realms, there is nothing that Mammon loves more than wealth. Where other devils obsess over souls and power, Mammon is perfectly content to continually increase his material possessions. Interestingly, he is one of the only archdevils willing to make deals with mortals over strictly monetary terms. Whether he maintains his end of the deal, however, is a completely different story. Anyone that interacts with Mammon immediately recognizes his two-faced approach—the devil will say or do anything, if he thinks it will benefit him in the end.

Aside from hunting for coin, Mammon also enjoys hunting for sport. If anger strikes him (and it does so often), he will frequently summon up a steed and hounds to partake in a trophy hunt.

Anything he has designated as prey rarely escapes his fervor, though he quickly grows bored once his quarry is caught.

Scheming and betrayal are like breathing for Mammon, and conversely so is bootlicking. Some argue that his punishment after the Reckoning was severely reduced due to his shameless groveling before Asmodeus. In fact, he was the first of all archdevils to surrender during the coup, even selling out some of his co-conspirators.

Despite all his faults, one thing Mammon has mastered is the soul trade. Even Asmodeus recognizes that no archdevil can manage and distribute souls as well as Mammon. Perhaps his expertise comes from the massive profit that can be made from managing souls, or perhaps he wanted to find somewhere to belong—nobody knows for sure.

## Mammon's Lair

Mammon's lair is in a tomb-like palace, within Minauros, and like most structures in the city is in a perpetual state of sinking into the swamp.

```statblock
"name": "Mammon (CoA)"
"size": "Huge"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "464"
"hit_dice": "32d12 + 256"
"modifier": !!int "3"
"stats":
  - !!int "28"
  - !!int "17"
  - !!int "26"
  - !!int "22"
  - !!int "25"
  - !!int "25"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "11"
  - "constitution": !!int "16"
  - "wisdom": !!int "15"
  - "charisma": !!int "15"
"skillsaves":
  - "name": "Arcana"
    "desc": "+14"
  - "name": "Deception"
    "desc": "+15"
  - "name": "Insight"
    "desc": "+15"
  - "name": "Intimidation"
    "desc": "+23"
  - "name": "Investigation"
    "desc": "+14"
  - "name": "Persuasion"
    "desc": "+23"
"damage_resistances": "acid; cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, poisoned"
"senses": "darkvision 120 ft., truesight 120 ft., passive Perception 17"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "26"
"traits":
  - "desc": "Magical darkness doesn't impede Mammon's darkvision."
    "name": "Devil's Sight"
  - "desc": "Mammon regains 20 hit points at the start of his turn. If he takes radiant\
      \ damage this trait doesn't function at the start of his next turn. Mammon only\
      \ dies if he starts his turn with 0 hit points and is unable to regenerate."
    "name": "Fiendish Regeneration"
  - "desc": "If Mammon fails a saving throw, he can choose to succeed instead"
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Mammon has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Mammon uses Fearful Gaze, then makes four attacks using Tail Swipe, Constrict,\
      \ or a combination of the two."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:*\
      \ 31 (4d10 + 9) bludgeoning damage. If the target is a Large or smaller creature,\
      \ it has the grappled condition (escape DC 21). While grappled, the creature\
      \ also has the restrained condition, and Mammon can't make Tail Swipe attacks."
    "name": "Tail Swipe"
  - "desc": "Mammon focuses his gaze in a 90-foot cone in front of him. Each creature\
      \ of his choice within the cone must make a DC 23 Wisdom saving throw, taking\
      \ 19 (3d12) psychic damage on a failed save, or half as much damage on a successful\
      \ one. Creatures that fail the save have the frightened condition until the\
      \ end of their next turn."
    "name": "Fearful Gaze"
  - "desc": "Mammon tightens his grip around a creature he has grappled. The target\
      \ takes 35 (4d12 + 9) bludgeoning damage."
    "name": "Constrict"
  - "desc": "Mammon attempts to turn one creature he can see within 60 feet of him\
      \ into solid gold. The target must make a DC 23 Constitution saving throw. On\
      \ a failed save, the target's flesh begins to harden, and it has the restrained\
      \ condition. A restrained creature must repeat the saving throw at the end of\
      \ each turn. If it successfully saves three times, the effect ends. If it fails\
      \ three times, it turns to gold and now has the petrified condition. Successes\
      \ and failures don't need to be consecutive."
    "name": "Golden Gaze (Recharge 6)"
"reactions":
  - "desc": "As a reaction to taking damage, Mammon causes the attacker's valuables\
      \ to glow red hot. This deals 3 (1d6) fire damage to the attacker for every\
      \ 100 gold (or equivalent in gems, jewelry, and other coinage) that it currently\
      \ carries."
    "name": "Pain Tax"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Mammon can take one\
      \ lair action to cause the following effect or one from the archdevil lair action\
      \ list (page 214); he can't take the same lair action two rounds in a row:\n\
      \n- **Greedy.** A creature of Mammon's choice automatically fails their next\
      \ saving throw.  \n\n- **Attack.** The archdevil uses one of their available\
      \ melee or ranged attacks against a single foe.  \n- **Cast a Spell.** The archdevil\
      \ uses their Spellcasting feature to cast an available spell. If the spell normally\
      \ requires concentration, it lasts for the full duration instead.  \n- **Deceitful\
      \ Whispers.** The archdevil whispers to a creature they can see within 30 feet.\
      \ The target must make a DC 22 Wisdom saving throw. On a failed save, the target\
      \ has the charmed condition until the start of their next turn and must use\
      \ their reaction immediately to make an attack against one of the archdevil's\
      \ enemies, chosen by the archdevil.  \n- **Fiendish Fortitude.** The archdevil\
      \ recharges one of their expended abilities.  \n- **Frenzy.** The archdevil\
      \ casts Haste on themself. The effect ends at initiative count 20 of the next\
      \ round.  \n- **Summon Underlings.** The archdevil summons allied devils. The\
      \ devils summoned depends on the archdevil using this feature. The summoned\
      \ devils appear in unoccupied spaces which the archdevil can see. The [Summoned\
      \ Underlings](3-Mechanics/CLI/tables/archdevil-lair-action-list-summoned-underlings-coa.md)\
      \ table shows which devils each archdevil can summon.  \n- **Teleport.** The\
      \ archdevil teleports themself to an area they can see within 120 feet.  \n\
      - **Trap.** The archdevil casts the Hold Monster spell.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Mammon's lair is corrupted by his presence, which\
      \ creates the following effect:\n\n- **Rotting Vegetation.** Within 3 miles\
      \ of the lair, the plant life is even more sickly and decayed, and the water\
      \ is polluted and toxic. A creature that isn't a Fiend that eats or drinks from\
      \ these sources must succeed on a DC 19 Constitution saving throw or die.  \n\
      \nIf Mammon dies, the effects fade over the course of 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Mammon can expend a use to take one of the following actions. Mammon regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Mammon changes his form into that of a pit fiend, maintaining his statistics\
      \ but losing his actions. He gains the actions and mobility of a pit fiend,\
      \ including its weapon, and maintains his legendary actions and lair actions.\
      \ Mammon's serpentine abilities can still recharge while he is in pit fiend\
      \ form. If Mammon is already a pit fiend, this action changes him back into\
      \ his serpentine form."
    "name": "Change Form"
  - "desc": "Mammon recharges Golden Gaze."
    "name": "Golden Touch (Costs 2 Actions)"
  - "desc": "Mammon summons an allied horned devil in an unoccupied space that he\
      \ can see."
    "name": "Call Underling (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/mammon-coa.webp"
```
^statblock