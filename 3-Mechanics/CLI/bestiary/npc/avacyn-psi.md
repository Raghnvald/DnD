---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/21
- ttrpg-cli/monster/size/large
- ttrpg-cli/monster/type/celestial
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Avacyn"
---
# [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md)
*Source: Plane Shift: Innistrad p. 26*  

[Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) was the archangel of Innistrad, revered across the plane as the source of hope, of protection, and of the Blessed Rest—a peaceful eternity of slumber in the grave. She offered the faithful magical wards against vampires and werewolves, a tranquil oblivion rather than the damned fate of a tormented spirit or undead abomination, and a distant hope that someday, their descendants might live in an Innistrad free from all the horrors of darkness.

Traditionally, three groups of angels known as flights or hosts served [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md), each under the leadership of a lesser archangel.

## Flight Alabaster

The practical and sympathetic angels of Flight Alabaster were instrumental in maintaining Avacyn's wards against the supernatural evils of Innistrad. They preferred the use of spells to weapons, and engaged in battle only when they had exhausted other options. As a result, angels of other flights sometimes dismissed them as overly sentimental. Alabaster angels aided priests and cathars in maintaining the protective wards on city walls and at holy sites throughout the plane, and also aided Avacyn in conducting the spirits of the dead to their ultimate fate, dissolving into Innistrad's Æthereal essence. The leader of Flight Alabaster was [Bruna](3-Mechanics/CLI/bestiary/npc/bruna-psi.md), called the Light of Alabaster.

## Host of Herons

The Host of Herons comprised the angels of birth, rebirth, and purity, whose magic was said to ward humans against harm in life. This was always the smallest flight of angels, and its primary function was the scouting and tracking of werewolves and other marauding monsters. [Sigarda](3-Mechanics/CLI/bestiary/npc/sigarda-psi.md) led the Host of Herons, wielding a scythe shaped like the head of a heron.

## Flight Goldnight

Flight Goldnight was an army of soldier-angels focused on the martial strength of the church. These angels were characterized by pragmatism and strict observance of church law. They were strategists in battle and skillful leaders during armed conflicts, cultivating a martial mindset that made them more than willing to take up arms when the need arose. The leader of Flight Goldnight was [Gisela](3-Mechanics/CLI/bestiary/npc/gisela-psi.md), called the Blade of Goldnight or the Blade of the Church.

## The Madness of Avacyn

When the Eldrazi titan Emrakul first approached Innistrad, [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) perceived her influence as a contagion that must be expunged from the world. However, unable to identify the source of that contagion, [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) was driven mad, lashing out instead at every living thing. She led the angels in a vain effort to purge this corruption from the plane, viewing the humans they once protected as part of the maddening illness. The different flights of angels even began to war against each other, drastically reducing the number of angels on the plane.

Wielding fiery swords and clad in full armor, the soldier-angels of Flight Goldnight became the scourge of all mortal life on Innistrad. None could predict what would trigger their violent judgment or where they would strike next. The angels of Flight Alabaster had always been at the forefront of the church's efforts to root out and punish demon cultists, necromancers, and other heretics. With Emrakul's approach, they grew at least as mad as [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) herself. Their fervent obsession drove the forces of the Lunarch Inquisition, the church's efforts to root out sin among the human populace. The angels prodded the church to ever greater and more desperate action.

Amid the chaos, [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) created a new angelic flight to serve as her honor guard. Armed with moonsilver spears forged from shards of the broken Helvault, these angels of the Flight of Moonsilver served as sentries and guards at Thraben Cathedral, and flew alongside [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md) into battle against any perceived threat to Innistrad.

Only [Sigarda](3-Mechanics/CLI/bestiary/npc/sigarda-psi.md) and the Host of Herons remained unaffected by Avacyn's madness, perhaps because they were the angels of purity. The survivors of this host retreated to their old haunt in Gavony's remote parish of Videns to maintain a safe distance from [Avacyn](3-Mechanics/CLI/bestiary/npc/avacyn-psi.md).

Angels that have gone mad can cast [flame strike](3-Mechanics/CLI/spells/flame-strike.md) once per day using their Innate Spellcasting trait. Additionally, the extra damage from their Angelic Weapons is half fire damage and half radiant damage.

```statblock
"name": "Avacyn (PSI)"
"size": "Large"
"type": "celestial"
"alignment": "Lawful Good"
"ac": !!int "21"
"ac_class": "natural armor"
"hp": !!int "243"
"hit_dice": "18d10 + 144"
"modifier": !!int "6"
"stats":
  - !!int "26"
  - !!int "22"
  - !!int "26"
  - !!int "25"
  - !!int "25"
  - !!int "30"
"speed": "50 ft., fly 150 ft."
"saves":
  - "intelligence": !!int "14"
  - "wisdom": !!int "14"
  - "charisma": !!int "17"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+14"
"damage_resistances": "radiant; bludgeoning, piercing, slashing from nonmagical attacks"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](3-Mechanics/CLI/rules/conditions.md#Charmed), [exhaustion](3-Mechanics/CLI/rules/conditions.md#Exhaustion),\
  \ [frightened](3-Mechanics/CLI/rules/conditions.md#Frightened), [poisoned](3-Mechanics/CLI/rules/conditions.md#Poisoned)"
"gear":
  - "[greatsword](3-Mechanics/CLI/items/greatsword.md)"
"senses": "[truesight](3-Mechanics/CLI/rules/senses.md#Truesight) 120 ft., passive\
  \ Perception 24"
"languages": "all, telepathy 120 ft."
"cr": "21"
"traits":
  - "desc": "The Avacyn's spellcasting ability is Charisma (spell save DC 25). It\
      \ can innately cast the following spells, requiring no material components:\n\
      \n**At will:** [detect evil and good](3-Mechanics/CLI/spells/detect-evil-and-good.md),\
      \ [invisibility](3-Mechanics/CLI/spells/invisibility.md) (self only)\n\n**3/day\
      \ each:** [blade barrier](3-Mechanics/CLI/spells/blade-barrier.md), [dispel\
      \ evil and good](3-Mechanics/CLI/spells/dispel-evil-and-good.md), [resurrection](3-Mechanics/CLI/spells/resurrection.md)\n\
      \n**1/day each:** [commune](3-Mechanics/CLI/spells/commune.md), [control weather](3-Mechanics/CLI/spells/control-weather.md)"
    "name": "Innate Spellcasting"
  - "desc": "The Avacyn's weapon attacks are magical. When the Avacyn hits with any\
      \ weapon, the weapon deals an extra 6d8 radiant damage (included in the attack)."
    "name": "Angelic Weapons"
  - "desc": "The Avacyn knows if it hears a lie."
    "name": "Divine Awareness"
  - "desc": "The Avacyn has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
  - "desc": "An angel of the Flight of Moonsilver wields a spear made from a shard\
      \ of the Helvault. Hit points lost to this weapon's damage can be regained only\
      \ through a short or long rest, rather than by regeneration, magic, or any other\
      \ means. Once per turn, when the angel hits a creature with an attack using\
      \ this weapon, it can wound the target. At the start of each of the wounded\
      \ creature's turns, it takes 1d4 necrotic damage for each time the angel has\
      \ wounded it, and it can then make a DC 15 Constitution saving throw, ending\
      \ the effect of all such wounds on itself on a success. Alternatively, the wounded\
      \ creature, or a creature within 5 feet of it, can use an action to make a DC\
      \ 15 Wisdom ([Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)) check, ending\
      \ the effect of such wounds on it on a success."
    "name": "Moonsilver Spear"
"actions":
  - "desc": "The Avacyn makes two greatsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +15 to hit, reach 5 ft., one target. *Hit:*\
      \ 22 (4d6 + 8) slashing damage plus 27 (6d8) radiant damage."
    "name": "Greatsword"
  - "desc": "*Ranged Weapon Attack:* +13 to hit, range 150/600 ft., one target.\
      \ *Hit:* 15 (2d8 + 6) piercing damage plus 27 (6d8) radiant damage. If the\
      \ target is a creature that has 100 hit points or fewer, it must succeed on\
      \ a DC 15 Constitution saving throw or die."
    "name": "Slaying Longbow"
  - "desc": "The Avacyn releases its greatsword to hover magically in an unoccupied\
      \ space within 5 feet of it. If the Avacyn can see the sword, the Avacyn can\
      \ mentally command it as a bonus action to fly up to 50 feet and either make\
      \ one attack against a target or return to the Avacyn's hands. If the hovering\
      \ sword is targeted by any effect, the Avacyn is considered to be holding it.\
      \ The hovering sword falls if the Avacyn dies."
    "name": "Flying Sword"
  - "desc": "The Avacyn touches another creature. The target magically regains 40\
      \ (8d8 + 4) hit points and is freed from any curse, disease, poison, blindness,\
      \ or deafness."
    "name": "Healing Touch (4/Day)"
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Avacyn can expend a use to take one of the following actions. Avacyn regains\
  \ all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "The Avacyn magically teleports, along with any equipment it is wearing\
      \ or carrying, up to 120 feet to an unoccupied space it can see."
    "name": "Teleport"
  - "desc": "The Avacyn emits magical, divine energy. Each creature of its choice\
      \ in a 10-foot radius must make a DC 23 Dexterity saving throw, taking 14 (4d6)\
      \ fire damage plus 14 (4d6) radiant damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Searing Burst (Costs 2 Actions)"
  - "desc": "The Avacyn targets one creature it can see within 30 feet of it. If the\
      \ target can see it, the target must succeed on a DC 15 Constitution saving\
      \ throw or be [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded) until magic\
      \ such as the [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md)\
      \ spell removes the blindness."
    "name": "Blinding Gaze (Costs 3 Actions)"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/npc/token/avacyn-psi.webp"
```
^statblock