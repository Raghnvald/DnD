---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Ghoul
linter-yaml-title-alias: Ghoul
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/HG/1
  - Monster/Typ/Untote
  - Quelle/5e/xmm
aliases:
  - Ghoul
---
# Ghul
*Quelle: Monsterhandbuch (2024) p. 101. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)* 

Ghule erheben sich aus den Leichen von Kannibalen jnd Halunken mit verkommenen Gelüsten. Sie schließen sich zu Rudeln zusammen, um gemeinsam ihre Gier zu stillen

## Ghule

*Fresser der Toten*

- **Habitat.** Stadt, Sumpf, Unterreich  
- **Schätze.** Beliebig

In den verrotteten Ecken der Welt jagen Rudel von Ghulen gierig nach Leichen und Kreaturen, die bald Leichen sein werden. Ghule sind hagere belebte Kadaver mit unnatürlich langen Zungen. Sie hausen in Katakomben und Ruinen, wo sie den Inhalt von Gräbern verschlingen. Mit ihren üblen Klauen können sie Kreaturen lähmen.

> [!quote] Anrufung von Doresain, König der Ghule
> 
> Auf einer Ebene voller Zähne in einem Tempel aus Dreck verschwendet der hungernde König keinen Bissen. Jeder Sarg ist ein Festmahl. Jeder Grabstein ein Tablett. Dies ist die Zeit des Schlemmens!

```statblock
"name": "Ghoul (XMM)"
"size": "Medium"
"type": "undead"
"alignment": "Chaotic Evil"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "5d8"
"modifier": !!int "2"
"stats":
  - !!int "13"
  - !!int "15"
  - !!int "10"
  - !!int "7"
  - !!int "10"
  - !!int "6"
"speed": "30 ft."
"damage_immunities": "poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Common"
"cr": "1"
"actions":
  - "desc": "The ghoul makes two Bite attacks."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage\
      \ plus 3 (1d6) Necrotic damage."
    "name": "Bite"
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 4 (1d4 + 2) Slashing damage.\
      \ If the target is a creature that isn't an Undead or elf, it is subjected to\
      \ the following effect. *Constitution Saving Throw:* DC 10. *Failure:* The target\
      \ has the [Paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed) condition until\
      \ the end of its next turn."
    "name": "Claw"
"source":
  - "XMM"
"image": "/3-Mechanics/CLI/bestiary/undead/token/ghoul-xmm.webp"
```
^statblock

## Environment

swamp, underdark, urban