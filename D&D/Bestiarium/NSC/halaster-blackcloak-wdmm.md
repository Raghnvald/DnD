---
obsidianUIMode: preview
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/wdmm
  - Monster/HG/23
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Halaster Blackcloak
---
# [Halaster Blackcloak](3-Mechanics\CLI\bestiary\npc/halaster-blackcloak-wdmm.md)
*Source: Waterdeep: Dungeon of the Mad Mage p. 310*  

As the master of Undermountain, Halaster can alter the entire dungeon to some extent. His lair actions and regional effects don't extend beyond Undermountain.

Halaster, the Mad Mage of Undermountain, is the deranged individual behind most of the traps and horrors found in the great dungeon under Waterdeep. Undermountain is his home, an amusement gallery in which others perform to entertain him.

The Mad Mage knows the ever-changing ways of Undermountain as no one else does, for he is the one who controls those changes. He prefers to remain unseen, skulking about invisibly or peering through scrying sensors that resemble wide-open eyes surrounded by sparkling motes of light.

Halaster's abilities far exceed those of most mortal wizards. His expertise with magic gates allows him to travel far and wide to engage in magical research. He spends much of his time creating gates, moving them around, and casting elder runes on them. Halaster's gates connect the different levels of Undermountain, thus enabling him to bring new monsters into the dungeon to replenish those that die or escape. Even as groups of adventurers try to gain decisive control of just a small section of Undermountain's halls, Halaster constantly alters the dungeon's perils to thwart them.

Halaster's true form is that of a tall, gaunt, male human, but he uses magic to take on many other visages and shapes. No matter what form he wears, the Mad Mage giggles and mutters incessantly. Contrary to appearances, however, Halaster is alert and attentive to the activities and preparations of all beings near him. He never willingly enters combat without first casting mage armor and mind blank on himself.

```statblock
"name": "Halaster Blackcloak (WDMM)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Evil"
"ac": !!int "14"
"ac_class": "17 with mage armor"
"hp": !!int "246"
"hit_dice": "29d8 + 116"
"modifier": !!int "4"
"stats":
  - !!int "10"
  - !!int "18"
  - !!int "18"
  - !!int "24"
  - !!int "18"
  - !!int "18"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "14"
  - "wisdom": !!int "11"
"skillsaves":
  - "name": "Arcana"
    "desc": "+21"
  - "name": "History"
    "desc": "+21"
  - "name": "Perception"
    "desc": "+11"
"damage_resistances": "fire; lightning (granted by the blast scepter, see \"Special\
  \ Equipment\" below)"
"senses": "darkvision 120 ft., passive Perception 21"
"languages": "Abyssal, Celestial, Common, Draconic, Dwarvish, Elvish, Infernal, Undercommon"
"cr": "23"
"traits":
  - "desc": "Halaster is a 20th-level spellcaster. His spellcasting ability is Intelligence\
      \ (spell save DC 22, +14 to hit with spell attacks). He can cast disguise self\
      \ and invisibility at will. He can cast fly and lightning bolt once each without\
      \ expending a spell slot, but can't do so again until he finishes a short or\
      \ long rest. Halaster has the following wizard spells prepared:\n\n**Cantrips\
      \ (at will):** dancing lights, fire bolt, light, mage hand, prestidigitation\n\
      \n**1st level (4 slots):** mage armor, magic missile, shield, silent image\n\
      \n**2nd level (3 slots):** arcane lock, cloud of daggers, darkvision, knock\n\
      \n**3rd level (3 slots):** counterspell, dispel magic, fireball\n\n**4th level\
      \ (3 slots):** confusion, hallucinatory terrain, polymorph\n\n**5th level (3\
      \ slots):** Bigby's hand, geas, wall of force\n\n**6th level (2 slots):** chain\
      \ lightning, globe of invulnerability, programmed illusion\n\n**7th level (2\
      \ slots):** finger of death, symbol, teleport\n\n**8th level (1 slots):** maze,\
      \ mind blank\n\n**9th level (1 slots):** meteor swarm, wish"
    "name": "Spellcasting"
  - "desc": "Halaster wears a robe of eyes that lets him see in all directions, gives\
      \ him darkvision out to a range of 120 feet, grants advantage on Wisdom (Perception)\
      \ checks that rely on sight, and allows him to see invisible creatures and objects,\
      \ as well as into the Ethereal Plane, out to a range of 120 feet.\n\nHalaster\
      \ wields a [blast scepter](/3-Mechanics/CLI/items/blast-scepter-wdmm.md) (a\
      \ very rare magic item that requires attunement). It can be used as an arcane\
      \ focus. Whoever is attuned to the blast scepter gains resistance to fire and\
      \ lightning damage and can, as an action, use it to cast thunderwave as a 4th-level\
      \ spell (save DC 16) without expending a spell slot.\n\nHalaster also wears\
      \ a horned ring (a very rare magic item that requires attunement), which allows\
      \ an attuned wearer to ignore Undermountain's magical restrictions (see \"Alterations\
      \ to Magic\")."
    "name": "Special Equipment"
  - "desc": "When he finishes a short rest, Halaster recovers all his spell slots\
      \ of 5th level and lower."
    "name": "Arcane Recovery (1/Day)"
  - "desc": "If Halaster fails a saving throw, he can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "If Halaster dies in Undermountain, he revives after 1d10 days, with all\
      \ his hit points and any missing body parts restored. His new body appears in\
      \ a random safe location in Undermountain."
    "name": "Rejuvenation"
"actions":
  - "desc": "Halaster uses his blast scepter to cast thunderwave as a 4th-level spell.\
      \ Each creature in a 15-foot cube originating from him must make a DC 16 Constitution\
      \ saving throw. On a failed save, a creature takes 5d8 thunder damage and is\
      \ pushed 10 feet away. On a successful save, the creature takes half as much\
      \ damage and isn't pushed"
    "name": "Blast Scepter"
"lair_actions":
  - "desc": "On initiative count 20 (losing initiative ties), Halaster takes a lair\
      \ action to cause one of the following effects:\n\n- Halaster targets a volume\
      \ of unoccupied space or solid stone no larger than four 10-foot cubes within\
      \ 30 feet of him, turning the open space to solid, worked stone or vice versa.\
      \  \n- Halaster causes one door or archway within 30 feet of him to disappear\
      \ and be replaced by a blank wall, or he restores a door or an archway previously\
      \ removed in this way.  \n- Halaster deactivates or reactivates one of Undermountain's\
      \ magic gates. The gate must be within 120 feet of him.  "
    "name": ""
"regional_effects":
  - "desc": "When Halaster is in Undermountain, the following effects can occur in\
      \ any location within the dungeon or in any extraplanar extension of the dungeon:\n\
      \n- A magical scrying sensor appears, taking the form of a ghostly, 1-foot-diameter\
      \ humanoid eye surrounded by motes of light. The sensor is stationary, though\
      \ Halaster can reorient the eye to face in any direction. Halaster can see through\
      \ the eye as though he was in its space. The eye can't be harmed or dispelled,\
      \ but it winks out within an antimagic field. A scrying eye lasts until Halaster\
      \ ends the effect (no action required).  \n- A minor illusory effect is triggered,\
      \ as though Halaster had cast minor illusion in an area. Common illusions include\
      \ the echo of rattling chains, the distant sound of explosive spells being cast,\
      \ a dusty cloak or a rusty helm floating as though worn by an invisible figure,\
      \ and illusory footprints appearing on a dusty floor.  \n- Silent apparitions\
      \ of dead adventurers drift through halls and rooms as though they are lost.\
      \ An apparition can't be harmed, and it doesn't acknowledge creatures or objects\
      \ in any way. It can't be dispelled but is suppressed within an antimagic field.\
      \  "
    "name": ""
"legendary_description": "Legendary Action Uses: 3. Immediately after another creature's\
  \ turn, Halaster can expend a use to take one of the following actions. Halaster\
  \ regains all expended uses at the start of each of their turns."
"legendary_actions":
  - "desc": "Halaster casts a spell of 3rd level or lower."
    "name": "Cast Spell"
  - "desc": "Halaster expends a spell slot of 4th level or lower and gains 5 temporary\
      \ hit points per level of the slot."
    "name": "Spell Ward (Costs 2 Actions)"
"source":
  - "WDMM"
"image": "/3-Mechanics/CLI/bestiary/npc/token/halaster-blackcloak-wdmm.webp"
```
^statblock