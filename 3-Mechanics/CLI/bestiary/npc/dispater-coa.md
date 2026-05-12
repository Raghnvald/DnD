---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/27
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Dispater"
---
# [Dispater](3-Mechanics/CLI/bestiary/npc/dispater-coa.md)
*Source: Chains of Asmodeus p. 222*  

Despite frequent shifts in leadership among other archdevils, Dispater has maintained his position as the ruler of Dis since its creation. Known for his vigilance and caution, he rarely leaves his tower, and even less frequently leaves the Iron City. Those who know his plans, including Asmodeus, know that he hopes to one day rule each layer of the Nine Hells.

Dispater remains one of the foremost suppliers of weapons across all the planes, which helps keep his position in Dis secure. As well, his advisors are carefully chosen and he maintains very few friendships.

Those that attempt battle with the Iron Lord find victory nigh impossible. In addition to his stratagem and defense, Dispater maintains extremely powerful abilities and a legion of minions. Outwitting him can't be done, and anyone unfortunate enough to catch him off guard is quickly disposed of.

Dispater remains calm and controlled in conversation. He prefers wherever possible to engage in gentlemanly debates rather than aggressive arguments. Unlike other archdevils, he almost never forces an individual into doing something, preferring to persuade or deceive instead. Fittingly, his skin is an iron-black color and his signature staff, wrought from the same iron as the tower he lives in, is always in hand.

## Dispater's Lair

The ruler of Dis makes his lair inside the Iron Tower. Within these confines he is vastly more protected.

```statblock
"name": "Dispater (CoA)"
"size": "Large"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor, [wrought-iron tower](3-Mechanics/CLI/items/wrought-iron-tower-coa.md)"
"hp": !!int "412"
"hit_dice": "33d10 + 231"
"modifier": !!int "3"
"stats":
  - !!int "28"
  - !!int "17"
  - !!int "25"
  - !!int "25"
  - !!int "22"
  - !!int "24"
"speed": "30 ft."
"saves":
  - "strength": !!int "17"
  - "dexterity": !!int "11"
  - "constitution": !!int "15"
  - "intelligence": !!int "15"
"skillsaves":
  - "name": "Arcana"
    "desc": "+23"
  - "name": "Insight"
    "desc": "+22"
  - "name": "Intimidation"
    "desc": "+15"
  - "name": "Perception"
    "desc": "+14"
  - "name": "Persuasion"
    "desc": "+15"
  - "name": "Stealth"
    "desc": "+11"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, frightened, poisoned"
"gear":
  - "[wrought-iron tower](3-Mechanics/CLI/items/wrought-iron-tower-coa.md)"
"senses": "darkvision 120 ft., passive Perception 24"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "27"
"traits":
  - "desc": "Magical darkness doesn't impede Dispater's darkvision."
    "name": "Devil's Sight"
  - "desc": "When a creature starts their turn within 120 feet of Dispater, they must\
      \ succeed on a DC 22 Wisdom saving throw or have the frightened condition until\
      \ they leave the aura. A creature that succeeds on the saving throw is immune\
      \ to this effect for 1 hour."
    "name": "Fear Aura"
  - "desc": "Dispater regains 20 hit points at the start of his turn. If he takes\
      \ radiant damage this trait doesn't function at the start of his next turn.\
      \ Dispater dies only if he starts his turn with 0 hit points and is unable to\
      \ regenerate."
    "name": "Fiendish Regeneration"
  - "desc": "If Dispater fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Dispater has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "Any nonmagical weapon or ammunition made of metal that hits Dispater\
      \ corrodes. After its hit, the weapon or ammunition is destroyed."
    "name": "Rust Metal"
"actions":
  - "desc": "Dispater makes four attacks using his Wrought- Iron Tower, Iron Column,\
      \ or a combination of the two. He can replace one of the attacks with Superheat\
      \ Metal (if available)."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +20 to hit, reach 10 ft., one target. *Hit:*\
      \ 21 (2d8 + 12) bludgeoning damage plus 7 (2d6) fire damage. Dispater may\
      \ replace the bludgeoning damage with damage of a type that the target is vulnerable\
      \ to instead."
    "name": "Wrought-Iron Tower"
  - "desc": "*Ranged Spell Attack:* +15 to hit, range 60 ft., one target. *Hit:*\
      \ 21 (2d8 + 12) bludgeoning damage plus 7 (2d6) fire damage. Dispater may\
      \ replace the bludgeoning damage with damage of a type that the target is vulnerable\
      \ to instead."
    "name": "Iron Column"
  - "desc": "Dispater targets a metal object he can see within 90 feet of him. The\
      \ metal glows white-hot, burning all that touches it. If the object was held\
      \ by a creature, the creature must succeed on a DC 23 Dexterity saving throw\
      \ to drop the object or take 45 (10d8) fire damage. If the object is attached\
      \ to a creature, or they couldn't feasibly drop it, they automatically fail\
      \ the save. The object returns to room temperature at the end of Dispater's\
      \ turn."
    "name": "Superheat Metal (Recharge 4-6)"
  - "desc": "Dispater conjures a storm of iron nails and launches them forward in\
      \ a 90-foot-long, 5-foot-wide line. All creatures within the line must make\
      \ a DC 23 Dexterity saving throw, taking 40 (16d4) piercing damage on a failed\
      \ save, or half as much damage on a successful one. Nails launched from this\
      \ ability stick into soft surfaces or fall to the ground after the attack finishes."
    "name": "Nail Spray (2/Day)"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Dispater can take one\
      \ lair action to cause the following effect or one from the archdevil lair action\
      \ list (page 214); he can't take the same lair action two rounds in a row:\n\
      \n- **Buckle.** The area in a 120-foot-radius around Dispater bends and twists,\
      \ becoming difficult terrain. Dispater's Superheat Metal ability is recharged.\
      \  \n\n- **Attack.** The archdevil uses one of their available melee or ranged\
      \ attacks against a single foe.  \n- **Cast a Spell.** The archdevil uses their\
      \ Spellcasting feature to cast an available spell. If the spell normally requires\
      \ concentration, it lasts for the full duration instead.  \n- **Deceitful Whispers.**\
      \ The archdevil whispers to a creature they can see within 30 feet. The target\
      \ must make a DC 22 Wisdom saving throw. On a failed save, the target has the\
      \ charmed condition until the start of their next turn and must use their reaction\
      \ immediately to make an attack against one of the archdevil's enemies, chosen\
      \ by the archdevil.  \n- **Fiendish Fortitude.** The archdevil recharges one\
      \ of their expended abilities.  \n- **Frenzy.** The archdevil casts Haste on\
      \ themself. The effect ends at initiative count 20 of the next round.  \n- **Summon\
      \ Underlings.** The archdevil summons allied devils. The devils summoned depends\
      \ on the archdevil using this feature. The summoned devils appear in unoccupied\
      \ spaces which the archdevil can see. The [Summoned Underlings](3-Mechanics/CLI/tables/archdevil-lair-action-list-summoned-underlings-coa.md)\
      \ table shows which devils each archdevil can summon.  \n- **Teleport.** The\
      \ archdevil teleports themself to an area they can see within 120 feet.  \n\
      - **Trap.** The archdevil casts the Hold Monster spell.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Dispater's lair is corrupted by his presence, which\
      \ creates the following effect:\n\n- **Din.** Within 6 miles of the lair, the\
      \ sound of metal working is near inescapable. Any creature attempting a short\
      \ or long rest may do so, but must make a DC 21 Constitution saving throw afterwards.\
      \ Failure negates any benefits of the rest.  \n\nIf Dispater dies, the effects\
      \ fade over the course of 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Dispater can expend a use to take one of the following actions. Dispater\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Dispater makes a Wrought-Iron Tower attack."
    "name": "Staff"
  - "desc": "*Melee Spell Attack:* +15 to hit, reach 5 ft., one target. *Hit:* 40\
      \ (6d10 + 7) force damage, and the target must make a DC 23 Constitution saving\
      \ throw. On a failed save, the target's flesh begins to harden, and the creature's\
      \ movement speed is halved for 1 minute. If the creature is harmed by Flesh\
      \ to Iron again, while still partly iron, the rest of the creature also turns\
      \ to iron, killing them."
    "name": "Flesh to Iron (Costs 2 Actions)"
  - "desc": "Dispater summons an allied erinyes in an unoccupied space that he can\
      \ see."
    "name": "Call Underling (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/dispater-coa.webp"
```
^statblock