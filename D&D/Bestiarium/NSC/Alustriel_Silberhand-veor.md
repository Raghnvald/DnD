---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Alustriel Silberhand
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/21
  - Monster/Typ/Humanoid/human
  - Monster/Typ/Humanoid/wizard
  - Quelle/5e/veor
aliases:
  - Alustriel Silverhand
linter-yaml-title-alias: Alustriel Silverhand
---
# Alustriel Silberhand
*Quelle: Vecna: Vorabend der Verdammnis S. 241*  

Alustriel Silberhand, die Strahlende Dame, ist schon seit Jahrhunderten eine einflussreiche Magiern und Verfechterin des Guten auf der Welt Toril. Sie ist eine der Sieben Schwestern - unsterbliche Töchter von Mystra, Göttin der Magie. Deren göttliche Energie trägt Alustriel in sich, was ihr erhebliche Macht über arkane Magie gewährt. 

Ihr jugendliches Erscheinungsbild als menschliche Frau mit silbernem Haar lässt in keiner Weise auf ihre übernatürlich lange Lebensspanne schließen. Meist trägt Alustriel lange Roben und führt einen Stab mit Einhornkopf - ihren _Stab von Silbrigmond_. 

## Persönlichkeit 

Alustriel möchte Freundlichkeit verbreiten, Tugend belohnen und im ganzen Multiversum eine Kultur des Mitgefühls etablieren. Sie ist gut darin, Allianzen zu schmieden und Bedrohungen der Kräfte des Guten zu eliminieren. Alustriel ist weit gereist und hat in allen Ebenen sichere Zufluchten geschaffen - zum Beispiel ihr Heiligtum in der Stadt Sigil. Persönlicher Ruhm und Reichtum interessieren sie nicht. Sie beeinflusst das Multiversum ruhig, aber stetig. 

## Geschichte

Wie andere Erwählte von Mystra ist auch Alustriel bestrebt, das Gewebe zu bewahren, die primäre Inkarnation der Magie, die Tori! durchdringt. Sie glaubt, dass das Gewebe jene begünstigt, die mit Gnade und Mitgefühl handeln und ein sicheres Leben für alle schaffen wollen, und dass es alle Anstrengungen stärkt, Unrecht zu beseitigen und das Böse zu bekämpfen. 

Nirgends sind Alustriel und ihre Taten besser bekannt als in den Silbermarschen und deren Hauptstadt Silbrigmond. Alustriel regiert seitJahrhunderten in Silbrigmond, einst getarnt als Magierin Elue Dualen, später in ihrer wahren Gestalt. Sie hat geholfen, Silbrigmonds berühmte Mondbrücke zu errichten, und hat die Schule der Herrin mitgegründet - die erste Schule Faeruns, an der Magier nicht als Lehrlinge, sondern als Studenten unterrichtet wurden. 

Alustriel ist vor über hundert Jahren von ihrem Amt als Hochmagierin Silbrigmonds zurückgetreten. Heute regiert ihr Sohn Methrammar Aerasume die Stadt und führt das Erbe seiner Mutter fort. 

Alustriel hat vor und nach ihrer Amtszeit als Silbrigmonds Hochmagierin zahllose Abenteuer bestanden. Sie ist mit berühmten Abenteurern wie Drizzt Do'Urden befreundet, hat mit bekannten Organisationen wie den Harfnern zusammengearbeitet und dem Bösen schon oft einen Strich durch die Rechnung gemacht. 

```statblock
"name": "Alustriel Silverhand (VEoR)"
"size": "Medium"
"type": "humanoid"
"subtype": "human, wizard"
"alignment": "Chaotic Good"
"ac": !!int "15"
"ac_class": "18 with mage armor"
"hp": !!int "272"
"hit_dice": "32d8 + 128"
"modifier": !!int "5"
"stats":
  - !!int "12"
  - !!int "20"
  - !!int "18"
  - !!int "24"
  - !!int "23"
  - !!int "22"
"speed": "30 ft."
"saves":
  - "constitution": !!int "11"
  - "intelligence": !!int "14"
  - "wisdom": !!int "13"
"skillsaves":
  - "name": "Arcana"
    "desc": "+14"
  - "name": "History"
    "desc": "+14"
  - "name": "Insight"
    "desc": "+13"
  - "name": "Religion"
    "desc": "+14"
"damage_resistances": "radiant"
"damage_immunities": "poison"
"condition_immunities": "charmed, exhaustion, poisoned"
"senses": "passive Perception 16"
"languages": "Common, Draconic, Elvish"
"cr": "21"
"traits":
  - "desc": "Whenever a creature on the same plane of existence as Alustriel speaks\
      \ Alustriel's name, Alustriel hears her name and the next nine words the speaker\
      \ utters."
    "name": "Ear of the Chosen"
  - "desc": "If Alustriel fails a saving throw, she can choose to succeed instead."
    "name": "Legendary Resistance (3/Day)"
  - "desc": "Alustriel carries a magic staff known as the Staff of Silverymoon. In\
      \ the hands of anyone other than Alustriel, the Staff of Silverymoon is a Staff\
      \ of Power."
    "name": "Special Equipment"
"actions":
  - "desc": "Alustriel makes three Staff of Silverymoon attacks or two Reproving Ray\
      \ attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +12 to hit, reach 5 ft., one target. *Hit:* 14\
      \ (2d8 + 5) bludgeoning damage plus 38 (7d10) radiant damage."
    "name": "Staff of Silverymoon"
  - "desc": "*Ranged Spell Attack:* +14 to hit, range 120 ft., one target. *Hit:*\
      \ 65 (9d12 + 7) force damage, and if the target is a creature, it must make\
      \ a DC 22 Charisma saving throw. On a failed save, the target has the incapacitated\
      \ condition until the start of Alustriel's next turn. On a successful save,\
      \ the target's speed is reduced by 10 feet until the start of Alustriel's next\
      \ turn."
    "name": "Reproving Ray"
  - "desc": "Alustriel summons a 60-foot cone of silver fire. Each creature in that\
      \ area must make a DC 22 Dexterity saving throw, taking 77 (14d10) radiant damage\
      \ on a failed save or half as much damage on a successful one. Additionally,\
      \ Alustriel or one creature of her choice within 60 feet of her then regains\
      \ 10 (3d6) hit points."
    "name": "Argent Blaze (Requires Silver Fire)"
  - "desc": "Alustriel casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 22):\n\n**At will:** Dancing Lights, Detect\
      \ Magic, Mage Armor (self only), Mage Hand\n\n**2/day each:** Detect Thoughts,\
      \ Dispel Magic, Tongues\n\n**1/day each:** Telepathy, Teleport, Time Stop"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "Brilliant silver fire harmlessly wreathes Alustriel and empowers her.\
      \ The silver fire lasts for 1 hour or until she has the incapacitated condition\
      \ or uses another bonus action to quench it. While wreathed in silver fire,\
      \ Alustriel gains truesight within 30 feet and can use her Argent Blaze action.\
      \ In addition, Alustriel is unaffected by magic that would ascertain her alignment,\
      \ creature type, thoughts, or truthfulness."
    "name": "Silver Fire (2/Day)"
"reactions":
  - "desc": "Alustriel interrupts a creature she can see within 60 feet of herself\
      \ that is casting a spell. If the spell is 5th level or lower, it fails and\
      \ has no effect. If the spell is 6th level or higher, Alustriel makes an Intelligence\
      \ check (DC 10 plus the spell's level). On a successful check, the spell fails\
      \ and has no effect. Whatever the spell's level, the caster takes 11 (2d10)\
      \ radiant damage if the spell fails."
    "name": "Shining Counterspell"
"source":
  - "VEoR"
"image": "/3-Mechanics/CLI/bestiary/npc/token/alustriel-silverhand-veor.webp"
```
^statblock