---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/psi
- ttrpg-cli/monster/cr/3
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/human
- ttrpg-cli/monster/type/humanoid/shapechanger
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Werewolf (Krallenhorde)"
---
# [Werewolf (Krallenhorde)](3-Mechanics/CLI/bestiary/humanoid/werewolf-krallenhorde-psi.md)
*Source: Plane Shift: Innistrad p. 15*  

Driven by their passions, their supernatural hunger, and the cycle of the moon, werewolves shed their tenuous humanity to embrace the savage predator within. They live along the boundary between humanity and supernatural evil, between civilization and the wilds, between light and utter darkness. Gathering in wild packs or hunting alone under the silver moon, werewolves embody the urge to violence, the rebellion against social mores and the chains of conscience, and the hunting instinct that lives within the human heart.

## The Nature of Lycanthropy

Lycanthropy—the condition that turns humans into werewolves—is a supernatural curse that causes the victim's spiritual essence to become mingled with the wild essence of nature, symbolized by the wolf. The lycanthrope can be thought of as possessing two souls, or a single soul split between two essences that constantly battle for control. When the wild wolf essence triumphs, the werewolf change occurs. This might explain why werewolves hunt humans so often; the wolf essence desires to destroy the human side and triumph over humanity, and does so symbolically through brutal murder.

### A Tenuous Hold on Humanity

A person afflicted with lycanthropy is forever in doubt of his or her own urges and instincts. In human form, a werewolf feels the pull of the wolf's essence even while fully engaged with human society. All lycanthropes feel the war of emotions in their hearts, and as the moon grows full, conscience, religion, and personal restraint wield less and less influence. The full moon makes the change inevitable, but any strong emotion or traumatic experience can also trigger the transformation.

Werewolves in either form seem to be able to tell a human-form lycanthrope by scent. Indeed, humans who are mysteriously spared during werewolf rampages are often suspected of being werewolves themselves.

### A Natural Killing Machine

Werewolves in canid form are beings of unparalleled savagery and strength. Their bodies are perfectly engineered for slaughter, with jaws capable of snapping bone and claws sharp enough to rip the entrails from a beast many times their size. Their minds are explosions of instinct and adrenaline, fed supernatural awareness from their heightened senses yet cognitively blind to almost everything but the kill. They can walk upright for manual dexterity or lope on four limbs for speed. Their howl is said to release the wolf's spirit within, a harrowing sound that fogs the air and chills the night. Werewolves in canid form cannot speak human languages, but seem to be able to communicate with each other on matters of hunting, dominance, and social hierarchy, as canines do in the wild.

If a werewolf dies in canid form, it changes back to human form, a process called death reversion.

## Transmitting the Curse

The exact means by which a person is subjected to the curse of lycanthropy is unknown and clouded by superstition. It's likely that the curse can be imposed by a variety of different means—including intentional participation in a ritual meant to invoke the curse. Sometimes, it seems that a werewolf howlpack chooses a victim; certainly, most victims share a common experience of being called to join the pack.

## Werewolf Howlpacks

Werewolves are often lone hunters, stalking and killing humans as singular monsters in towns and villages. But some werewolves form loose social groups in the wild, called howlpacks. The population of any howlpack waxes and wanes like the moon, gaining and losing members as individual lycanthropes enter or leave their canid state. Some werewolves seem to be continually drawn back to a familiar howlpack, returning to it time after time as they drop their human guise to reenter the wild.

Howlpacks can be tiny hunting parties of just a few werewolves or massive hordes of over a hundred beasts. They are typically led by single alphas (male or female) that dominate the pack. Alphas must often defend their power by defeating challengers in combat.

```statblock
"name": "Werewolf (Krallenhorde) (PSI)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Chaotic Evil"
"ac": !!int "11"
"ac_class": "12 natural armor in canid form"
"hp": !!int "58"
"hit_dice": "9d8 + 18"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "13"
  - !!int "14"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft. (40 ft. in canid form)"
"skillsaves":
  - "name": "[Perception](3-Mechanics/CLI/rules/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](3-Mechanics/CLI/rules/skills.md#Stealth)"
    "desc": "+3"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks not\
  \ made with silvered weapons"
"gear":
  - "[spear](3-Mechanics/CLI/items/spear.md)"
"senses": "passive Perception 14"
"languages": "Common (can't speak in canid form)"
"cr": "3"
"traits":
  - "desc": "The werewolf polymorphs into a wolf-humanoid canid form, or back into\
      \ its true human form. This change is dictated by the moon, but can also be\
      \ induced by trauma or strong emotion. Its statistics, other than its AC, are\
      \ the same in each form. Any equipment it is wearing or carrying isn't transformed.\
      \ It reverts to its true form if it dies."
    "name": "Shapechanger"
  - "desc": "The werewolf has advantage on Wisdom ([Perception](3-Mechanics/CLI/rules/skills.md#Perception))\
      \ checks that rely on hearing or smell."
    "name": "Keen Hearing and Smell"
  - "desc": "Vildin Rampage (Canid Form Only). When the werewolf reduces a creature\
      \ to 0 hit points with a melee attack on its turn, it can take a bonus action\
      \ to move up to half its speed and make a bite attack."
    "name": "Howlpack: Vildin"
"actions":
  - "desc": "The werewolf makes two attacks: one with its bite and one with its claws\
      \ or spear."
    "name": "Multiattack (Canid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 6\
      \ (1d8 + 2) piercing damage."
    "name": "Bite (Canid Form Only)"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7\
      \ (2d4 + 2) slashing damage."
    "name": "Claws (Canid Form Only)"
  - "desc": "*Melee  or Ranged Weapon Attack:* +4 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 5 (1d6 + 2) piercing damage, or 6 (1d8 + 2) piercing\
      \ damage if used with two hands to make a melee attack."
    "name": "Spear (Human Form Only)"
"source":
  - "PSI"
"image": "3-Mechanics/CLI/bestiary/humanoid/token/werewolf-krallenhorde-psi.webp"
```
^statblock