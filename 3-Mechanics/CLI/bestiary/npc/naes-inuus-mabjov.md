---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mabjov
- ttrpg-cli/monster/cr/13
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Naes Inuus"
---
# [Naes Inuus](3-Mechanics/CLI/bestiary/npc/naes-inuus-mabjov.md)
*Source: Minsc and Boo's Journal of Villainy p. 42*  

Naes Inuus is the high priest of Sune and also known as the First Heartwarder. He believes that Sune is a goddess for all beings of the realms, and his ultimate dream is to have a temple devoted to Sune in every city and village from the Sword Coast to the Sea of Fallen Stars and beyond.

Naes and his twin, Tiberius, were born in the city of Waterdeep to one of the city's most powerful noblemen. He abandoned the twins when their mother, a cleric of Sune, died during childbirth and so the children were taken in by the Church of Sune. They were raised in the Temple of Beauty in Waterdeep and grew into pious men who were favored by the goddess of love.

When they came of age, the twins set out to spread the love and beauty of Sune across the Realms. In the history of the church, none of Sune's faithful have ever been responsible for establishing as many new temples as has Naes. From Neverwinter in the North to Port Nyanzaru on the Chultan peninsula, it is difficult to find a community that doesn't have at least a shrine devoted to the goddess of beauty.

Naes's devotion to Sune leads him to be intolerant of other faiths. He believes that Sune represents civilization's best chance to survive in a world that is filled with monsters, evil and ugliness. His sermons on the virtues of Sune can come across as condescending to those whose faiths differ. Naes is self-aware enough to recognize how he can be perceived and tones down his rhetoric when dealing with potential allies.

As the high priest of Sune's faith on Faerûn, Naes leaves most of the evangelizing work to his twin brother, Tiberius. However, if there is an opportunity to convert a significant number of people to Sune's faith, Naes will leave his offices in the Temple of Beauty. He relishes these few chances to return to the road. Naes falls in love easily and if he meets a man or woman that he takes a fancy to, then he will strike up a friendship with the hope of it leading to something more.

## Naes as a Contact

Once members of the Church of Sune reach 9th level they gain access to Naes as a contact. Naes has connections with some of the most powerful noble families, dynasties and kingdoms. Because of this he is able to arrange marriages, adoptions, titles and other such things. He requires a donation to the Church of Sune before he begins work on the arrangement. The donation is significantly less for those who worship Sune. You can only be married once and you can have noble status in one city.

**Special Arrangements Through Naes**

| Arrangement | Benefit | Cost | Cost For Sune Faithful |
|-------------|---------|------|------------------------|
| Adoption or marriage to Baldur's Gate duke/duchess | You can change your subclass | 1,000 gp | 750 gp |
| Adoption or marriage to Waterdeep Hidden Lord | Gain proficiency in a skill of your choice | 500 gp | 250 gp |
| Adoption or marriage to member of Athkatla's Council of Six | Gain an uncommon magic item of your choice | 1500 gp | 1000 gp |
| Elevated to Mithral Lordship in Athkatla | Gain a rare magic item of your choice | 5,000 gp | 3,000 gp |
| Granted ownership of vacated noble estate in Baldur's Gate | Gain a feat of your choice | 10,000 gp | 7,500 gp |
| Granted noble status in Waterdeep | Gain expertise in a skill of your choice | 10,000 gp | 7,500 gp |
^special-arrangements-through-naes

```statblock
"name": "Naes Inuus (MaBJoV)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Lawful Good"
"ac": !!int "18"
"ac_class": "[breastplate](3-Mechanics/CLI/items/breastplate.md), [shield](3-Mechanics/CLI/items/shield.md)"
"hp": !!int "187"
"hit_dice": "25d8 + 75"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "14"
  - !!int "16"
  - !!int "13"
  - !!int "20"
  - !!int "14"
"speed": "30 ft."
"saves":
  - "constitution": !!int "8"
  - "wisdom": !!int "10"
"skillsaves":
  - "name": "[Insight](3-Mechanics/CLI/rules/skills.md#Insight)"
    "desc": "+10"
  - "name": "[Medicine](3-Mechanics/CLI/rules/skills.md#Medicine)"
    "desc": "+15"
  - "name": "[Persuasion](3-Mechanics/CLI/rules/skills.md#Persuasion)"
    "desc": "+7"
  - "name": "[Religion](3-Mechanics/CLI/rules/skills.md#Religion)"
    "desc": "+11"
"damage_resistances": "necrotic"
"gear":
  - "[mace](3-Mechanics/CLI/items/mace.md)"
"senses": "[darkvision](3-Mechanics/CLI/rules/senses.md#Darkvision) 60 ft., passive\
  \ Perception 15"
"languages": "Celestial, Common, Elvish"
"cr": "13"
"actions":
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 5\
      \ (1d6 + 2) bludgeoning damage plus 14 (4d6) radiant damage."
    "name": "Mace"
  - "desc": "Naes activates an aura of sunlight that lasts for 1 minute or until he\
      \ dismisses it using an action. He emits bright light in a 60-foot-radius and\
      \ dim light 30 feet beyond that. His enemies in the bright light have disadvantage\
      \ on saving throws against any spell that deals fire or radiant damage."
    "name": "Corona of Beauty"
  - "desc": "Naes dispels any magical darkness within 30 feet of him. Additionally,\
      \ each hostile creature within 30 feet of Naes that does not have total cover\
      \ must make a DC 18 Constitution saving throw, taking 60 radiant damage on a\
      \ failed saving throw, half as much damage on a successful one. A creature that\
      \ fails the saving throw has the [blinded](3-Mechanics/CLI/rules/conditions.md#Blinded)\
      \ condition for 1 minute."
    "name": "Radiant Beauty of Sune (Recharge 4-6)"
  - "desc": "Naes casts one of the following spells, using Wisdom as the spellcasting\
      \ ability (spell save DC 18):\n\n**At will:** [lesser restoration](3-Mechanics/CLI/spells/lesser-restoration.md),\
      \ [light](3-Mechanics/CLI/spells/light.md), [sanctuary](3-Mechanics/CLI/spells/sanctuary.md)\n\
      \n**2/day each:** [antilife shell](3-Mechanics/CLI/spells/antilife-shell.md),\
      \ [blade barrier](3-Mechanics/CLI/spells/blade-barrier.md)\n\n**1/day each:**\
      \ [divine word](3-Mechanics/CLI/spells/divine-word.md), [mass heal](3-Mechanics/CLI/spells/mass-heal.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "If Naes would drop to 0 hit points as a result of taking damage, or is\
      \ subjected to an effect that would kill him instantaneously without doing damage,\
      \ Naes instead drops to 1 hit point."
    "name": "Hard to Kill (1/Day)"
"source":
  - "MaBJoV"
"image": "3-Mechanics/CLI/bestiary/npc/token/naes-inuus-mabjov.webp"
```
^statblock