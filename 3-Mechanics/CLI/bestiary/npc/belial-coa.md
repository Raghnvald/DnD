---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/coa
- ttrpg-cli/monster/cr/25
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/fiend/devil
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Belial"
---
# [Belial](3-Mechanics/CLI/bestiary/npc/belial-coa.md)
*Source: Chains of Asmodeus p. 221*  

Belial maintains his image as the most carnal of all archdevils, and enjoys inflicting pain as much as experiencing pleasure. Despite his indulgences, Belial demonstrates charisma, passion, and intelligence, and is almost always scheming. He is confident to a fault, with vanity and desire being his greatest weaknesses.

Phlegethos has been ruled by Belial, together with his daughter, Fierna, for almost as long as Dispater has ruled his Iron City. Belial considers himself an "old school" devil, alongside his friendly rivals Levistus and Dispater. Glasya's recent rise to power has him concerned for his continued relevance in the political landscape, forcing him to direct his scheming inwards.

During the Reckoning, Belial remained relatively neutral, until the end, when he allied with Baalzebul. Some argue that his alliance was just another scheme meant to misdirect Asmodeus—an idea further cemented when, instead of being deposed, Belial was forced to cede the throne to his daughter. For a time, he continued to rule from the shadows, but influence from Glasya on Fierna has encouraged the fiery lord to rule in tandem. Belial manages much of the political and official sides of the realm, including maintaining the infernal court. He occasionally sends avatars to other planes, which quickly seek out pleasure before continuing their assigned task.

Similar to his daughter, Belial remains one of the most attractive archdevils. His rugged good looks and masculine physique serve to compliment his devilish features, of which he has many. Sharp horns and glowing eyes adorn his face, with midnight-black wings and a tail decorating the rest of his body. Depending on his mood, Belial's skin either takes on an ashy-grey complexion, or smolders red like dying coal. Priding himself on his sensual appearance, Belial dresses provocatively while maintaining high fashion, truly embodying his carnal desires.

## Belial's Lair

This fierce archdevil currently makes his lair in an obsidian palace built within the confines of Abriymoch, but his reach extends throughout the entirety of the city.

```statblock
"name": "Belial (CoA)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Lawful Evil"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "420"
"hit_dice": "40d8 + 240"
"modifier": !!int "3"
"stats":
  - !!int "25"
  - !!int "17"
  - !!int "22"
  - !!int "22"
  - !!int "22"
  - !!int "29"
"speed": "30 ft., fly 60 ft."
"saves":
  - "strength": !!int "15"
  - "dexterity": !!int "11"
  - "constitution": !!int "14"
  - "wisdom": !!int "14"
"skillsaves":
  - "name": "Athletics"
    "desc": "+15"
  - "name": "Deception"
    "desc": "+25"
  - "name": "Insight"
    "desc": "+14"
  - "name": "Intimidation"
    "desc": "+17"
  - "name": "Perception"
    "desc": "+14"
  - "name": "Persuasion"
    "desc": "+25"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "charmed, poisoned"
"gear":
  - "[ranseur of torture](3-Mechanics/CLI/items/ranseur-of-torture-coa.md)"
"senses": "darkvision 120 ft., passive Perception 24"
"languages": "Celestial, Common, Draconic, Infernal, telepathy 120 ft."
"cr": "25"
"traits":
  - "desc": "All damage dealt by Belial can only be restored through magical means."
    "name": "Deep Wounds"
  - "desc": "Magical darkness doesn't impede Belial's darkvision."
    "name": "Devil's Sight"
  - "desc": "When a creature starts their turn within 120 feet of Belial, they must\
      \ succeed on a DC 22 Wisdom saving throw or have the frightened condition until\
      \ they leave the aura. A creature that succeeds on the saving throw is immune\
      \ to this effect for 1 hour."
    "name": "Fear Aura"
  - "desc": "Belial regains 20 hit points at the start of his turn. If he takes radiant\
      \ damage this trait doesn't function at the start of his next turn. Belial dies\
      \ only if he starts his turn with 0 hit points and doesn't regenerate."
    "name": "Fiendish Regeneration"
  - "desc": "If Belial fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Belial has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "Belial makes three attacks using his Ranseur of Torture."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +18 to hit, reach 10 ft., one target. *Hit:*\
      \ 21 (2d10 + 10) piercing damage plus 5 (1d10) necrotic damage, and the\
      \ target must make a DC 23 Constitution saving throw. On a failed save, the\
      \ target's movement speed is reduced by 5 feet until the end of their next turn.\
      \ This penalty can stack."
    "name": "Ranseur of Torture"
  - "desc": "Belial creates a wall of fire on a solid surface within 120 feet of him.\
      \ The wall is 20 feet high and 1 foot thick, and Belial can make the wall up\
      \ to 60 feet long or create a ringed wall up to 20 feet in diameter. The wall\
      \ is opaque and lasts until Belial dismisses it. When the wall appears, each\
      \ creature within its area must make a DC 25 Dexterity saving throw, taking\
      \ 36 (8d8) fire damage on a failed save, or half as much damage on a successful\
      \ one. A creature that ends its turn inside the wall, or within 5 feet of it,\
      \ must repeat the save."
    "name": "Walls of Phlegethos"
  - "desc": "Belial draws a magic symbol at a point he can see within 120 feet of\
      \ him. All creatures within a 20-foot-radius sphere centered on the symbol must\
      \ make a DC 25 Intelligence saving throw. Targets take 45 (10d8) psychic damage\
      \ on a failed save, or half as much damage on a successful one. Creatures that\
      \ fail the save immediately use their reaction to make a melee attack against\
      \ a random creature within their reach, then move their full movement in a random\
      \ direction."
    "name": "Symbol of Insanity (Recharge 4-6)"
"reactions":
  - "desc": "As a reaction to taking damage, Belial immediately regenerates half the\
      \ damage he took."
    "name": "Pleasure in Pain"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Belial can take one\
      \ lair action to cause the following effect or one from the archdevil lair action\
      \ list (page 214); he can't take the same lair action two rounds in a row:\n\
      \n- **Slow Torture.** Every creature within 100 feet whose movement is currently\
      \ reduced because of the Ranseur of Torture, takes 11 (2d10) fire damage and\
      \ 11 (2d10) piercing damage.  \n\n- **Attack.** The archdevil uses one of\
      \ their available melee or ranged attacks against a single foe.  \n- **Cast\
      \ a Spell.** The archdevil uses their Spellcasting feature to cast an available\
      \ spell. If the spell normally requires concentration, it lasts for the full\
      \ duration instead.  \n- **Deceitful Whispers.** The archdevil whispers to a\
      \ creature they can see within 30 feet. The target must make a DC 22 Wisdom\
      \ saving throw. On a failed save, the target has the charmed condition until\
      \ the start of their next turn and must use their reaction immediately to make\
      \ an attack against one of the archdevil's enemies, chosen by the archdevil.\
      \  \n- **Fiendish Fortitude.** The archdevil recharges one of their expended\
      \ abilities.  \n- **Frenzy.** The archdevil casts Haste on themself. The effect\
      \ ends at initiative count 20 of the next round.  \n- **Summon Underlings.**\
      \ The archdevil summons allied devils. The devils summoned depends on the archdevil\
      \ using this feature. The summoned devils appear in unoccupied spaces which\
      \ the archdevil can see. The [Summoned Underlings](3-Mechanics/CLI/tables/archdevil-lair-action-list-summoned-underlings-coa.md)\
      \ table shows which devils each archdevil can summon.  \n- **Teleport.** The\
      \ archdevil teleports themself to an area they can see within 120 feet.  \n\
      - **Trap.** The archdevil casts the Hold Monster spell.  "
    "name": ""
"regional_effects":
  - "desc": "The region containing Belial's lair is corrupted by his presence, which\
      \ creates the following effect:\n\n- **Smoke-cloud.** A vast fog rises 3 feet\
      \ above ground within 1 mile of the lair, completely obscuring the ground. Any\
      \ creature having the prone condition at the start of their turn must succeed\
      \ on a DC 22 Constitution saving throw or take 7 (2d12) necrotic damage from\
      \ choking on the noxious fumes.  \n\nIf Belial dies, the effects fade over the\
      \ course of 1d10 days."
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Belial can expend a use to take one of the following actions. Belial regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Belial makes a Ranseur of Torture attack."
    "name": "Ranseur"
  - "desc": "Belial causes molten stone to erupt from a point he can see within 90\
      \ feet of him. All creatures within a 20-foot-radius sphere centered on that\
      \ point must make a DC 23 Dexterity saving throw. Targets take 28 (8d6) fire\
      \ damage on a failed save, or half as much damage on a successful one."
    "name": "Eruption (Costs 2 Actions)"
  - "desc": "Belial summons an allied horned devil in an unoccupied space that he\
      \ can see."
    "name": "Call Underling (Costs 3 Actions)"
"source":
  - "CoA"
"image": "3-Mechanics/CLI/bestiary/npc/token/belial-coa.webp"
```
^statblock