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
- "Baalzebul"
---
# [Baalzebul](3-Mechanics/CLI/bestiary/npc/baalzebul-coa.md)
*Source: Chains of Asmodeus p. 219*  

Baalzebul, is an archdevil and the lord of Maladomini, the seventh layer of the Nine Hells. He is known as both the Lord of Lies and the Lord of the Flies because his tightly woven web of intrigue traps even the smallest fly. In recent centuries he was cursed with a new hideous form by Asmodeus. This form earned him a new title—The Slug Archduke.

Baalzebul was originally known as Triel, one of the most powerful and beautiful angels to be found in Celestia. Triel's selfish acts in the name of achieving his perfection resulted in his corruption and exile from Celestia. After his fall, Asmodeus, perhaps out of some lingering sense of sympathy, quickly promoted Baalzebul to the ranks of devilish nobility. Baalzebul's ruthless lust for power served him well and before long he not only displaced the ancient, original Lord of Maladomini but managed to become the only archdevil to rule two layers of the Nine Hells, although he ruled Malbolge through the devil Moloch.

However, Baalzebul's pride continued to be his undoing. When he attempted to take Asmodeus's throne, his schemes were discovered and thwarted.

Asmodeus inflicted a series of bizarre penalties upon Baalzebul. He was cursed to appear as a slug for one year per lie he had told to a devil, and any deal he struck with a mortal would result in a disaster for the participant. His castle was turned to excrement and filled with filth and his dominion of Malbolge was stripped from him.

Despite his punishments, Baalzebul is still dangerously cunning and charismatic. Even while trapped in the form of a slug, he remained the Lord of Lies, whose every deception was made with ease. Every one of his untruths is told with a specific purpose in mind, and only other devils are safe from his lies.

> [!note] Baalzebul's Two Forms
> 
> When dealing with enemies or unfortunate subordinates, Baalzebul generally manifests as a powerful winged creature. However, the characters are most likely to encounter this archdevil in his slug form after he has incurred Asmodeus's wrath again. The accompanying stat block works for both forms except that Baalzebul's movement in his slug form is replaced with: 20 ft., burrow 20 ft., climb 20 ft.
^baalzebuls-two-forms

## Baalzebul's Lair

Baalzebul's lair resides within whichever city is the newest he has constructed.

```statblock
"name": "Baalzebul (CoA)"
"size": "Huge"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "19"
"ac_class": "natural armor"
"hp": !!int "540"
"hit_dice": "40d12 + 280"
"modifier": !!int "2"
"stats":
  - !!int "28"
  - !!int "15"
  - !!int "25"
  - !!int "21"
  - !!int "24"
  - !!int "26"
"speed": "30 ft., fly 60 ft."
"saves":
  - "strength": !!int "17"
  - "constitution": !!int "15"
  - "intelligence": !!int "13"
  - "charisma": !!int "16"
"skillsaves":
  - "name": "Athletics"
    "desc": "+17"
  - "name": "Deception"
    "desc": "+24"
  - "name": "Insight"
    "desc": "+15"
  - "name": "Intimidation"
    "desc": "+16"
  - "name": "Persuasion"
    "desc": "+16"
"damage_resistances": "acid; cold; bludgeoning, piercing, slashing from nonmagical\
  \ attacks that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, exhaustion, frightened, poisoned"
"senses": "darkvision 120 ft., tremorsense 10 ft., passive Perception 17"
"languages": "all, telepathy 120 ft."
"cr": "26"
"traits":
  - "desc": "Magical darkness doesn't impede Baalzebul's darkvision."
    "name": "Devil's Sight"
  - "desc": "Baalzebul regains 20 hit points at the start of his turn. If he takes\
      \ radiant damage this trait doesn't function at the start of his next turn.\
      \ Baalzebul dies only if he starts his turn with 0 hit points and doesn't regenerate."
    "name": "Fiendish Regeneration"
  - "desc": "Insects don't attack Baalzebul, and he can issue orders to them."
    "name": "Lord of Flies"
  - "desc": "If Baalzebul fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Baalzebul has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "A creature that starts its turn within 10 feet of Baalzebul must succeed\
      \ on a DC 21 Constitution saving throw or have the poisoned condition until\
      \ the start of its next turn. On a successful save, a creature is immune to\
      \ this stench for 1 hour."
    "name": "Stench of the Slug (Slug Form Only)"
"actions":
  - "desc": "Baalzebul uses Heart of Pestilence (if available), then makes three Slam\
      \ attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +17 to hit, reach 10 ft., one target. *Hit:*\
      \ 19 (3d6 + 9) bludgeoning damage plus 7 (2d6) necrotic damage."
    "name": "Slam"
  - "desc": "Baalzebul causes refuse and caustic liquid to spill from the ground at\
      \ a point he can see within 300 feet. Each creature in a 15-foot-radius sphere\
      \ centered on that point must make a DC 21 Constitution saving throw. Targets\
      \ take 36 (8d8) acid damage on a failed save, or half as much on a successful\
      \ one. Creatures that fail the save have the poisoned condition for 1 minute."
    "name": "Pungent Eruption (Slug Form Only, Recharge 4-6)"
  - "desc": "Baalzebul channels pestilence into his body, sickening creatures within\
      \ 50 feet that can see him. Sickened creatures must make a DC 21 Charisma saving\
      \ throw, followed by a DC 21 Constitution saving throw. Failing the Charisma\
      \ save makes a creature have the frightened condition, while failing the Constitution\
      \ save makes a creature weak. While weakened, a creature deals half damage on\
      \ melee attacks. Both effects last for 1 minute or until a Greater Restoration\
      \ spell or similar is cast."
    "name": "Heart of Pestilence (Recharge 5-6)"
  - "desc": "Baalzebul casts one of the following spells, requiring no material components\
      \ and using Charisma as the spellcasting ability (spell save DC 24):\n\n**At\
      \ will:** Animate Dead, Darkness, Detect Evil and Good, Detect Magic, Dispel\
      \ Evil and Good, Hallow, Hold Monster, Suggestion, Teleport, True Seeing\n\n\
      **1/day each:** Symbol (pain or insanity), Wish"
    "name": "Spellcasting (Winged Form Only)"
"bonus_actions":
  - "desc": "Baalzebul magically teleports, along with any equipment he is wearing\
      \ and carrying, up to 120 feet to an unoccupied space he can see."
    "name": "Displace"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Baalzebul can take one\
      \ lair action to cause the following effect or one from the archdevil lair action\
      \ list (page 214); he can't take the same lair action two rounds in a row:\n\
      \n- **Protective Burrow.** Baalzebul uses his burrow speed to dig into the ground.\
      \ He gains half-cover when buried 10 feet and three-quarters cover at 20 feet.\
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
  - "desc": "The region containing Baalzebul's lair is corrupted by his presence,\
      \ which creates the following effect:\n\n- **Filth.** Within 1 mile of the lair,\
      \ stinking piles of filth accumulate as if from nowhere. The entire area is\
      \ covered with garbage and feces and is treated as difficult terrain.  \n\n\
      If Baalzebul dies, the effects fade over the course of 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Baalzebul can expend a use to take one of the following actions. Baalzebul\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Baalzebul makes a Slam attack."
    "name": "Pummel"
  - "desc": "Baalzebul uses Displace."
    "name": "Teleport"
  - "desc": "Baalzebul disgorges a swarm of biting flies at a point he can see within\
      \ 300 feet of himself. Each creature within a 20-foot-radius sphere centered\
      \ on that point must make a DC 21 Constitution saving throw. A creature takes\
      \ 44 (8d10) piercing damage on a failed save, or half as much damage on a\
      \ successful one. The biting flies persist for 1 minute, or until Baalzebul\
      \ uses this ability again. Creatures that enter the flies' area or end their\
      \ turn inside it must repeat the saving throw."
    "name": "Insect Gorge (Costs 2 Actions)"
  - "desc": "Baalzebul summons an allied bone devil in an unoccupied space that he\
      \ can see."
    "name": "Call Underling (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/baalzebul-coa.webp"
```
^statblock