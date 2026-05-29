---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Assassin
Kategorie: Humanoid
Größe: Mittelgroß
status: WIP
linter-yaml-title-alias: Assassin
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/8
  - Monster/Typ/Humanoid/any-race
  - Quelle/5e/mm
aliases:
  - Assassin
---
# [Assassin](3-Mechanics\CLI\bestiary\humanoid/assassin.md)
*Source: Monster Manual p. 343. Available in the <span title='Systems Reference Document (5.1)'>SRD</span>*  

Trained in the use of poison, assassins are remorseless killers who work for nobles, guildmasters, sovereigns, and anyone else who can afford them.

```statblock
"name": "Assassin"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "15"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor.md)"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"modifier": !!int "3"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "14"
  - !!int "13"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "6"
  - "intelligence": !!int "4"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+6"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+9"
"damage_resistances": "poison"
"senses": "passive Perception 13"
"languages": "Thieves' cant plus any two languages"
"cr": "8"
"traits":
  - "desc": "During its first turn, the assassin has advantage on attack rolls against\
      \ any creature that hasn't taken a turn. Any hit the assassin scores against\
      \ a [surprised](/3-Mechanics/CLI/conditions.md#Surprised) creature is a critical\
      \ hit."
    "name": "Assassinate"
  - "desc": "If the assassin is subjected to an effect that allows it to make a Dexterity\
      \ saving throw to take only half damage, the assassin instead takes no damage\
      \ if it succeeds on the saving throw, and only half damage if it fails."
    "name": "Evasion"
  - "desc": "The assassin deals an extra 14 (4d6) damage when it hits a target with\
      \ a weapon attack and has advantage on the attack roll, or when the target is\
      \ within 5 feet of an ally of the assassin that isn't [incapacitated](/3-Mechanics/CLI/conditions.md#Incapacitated)\
      \ and the assassin doesn't have disadvantage on the attack roll."
    "name": "Sneak Attack (1/Turn)"
"actions":
  - "desc": "The assassin makes two shortsword attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +6 to hit, reach 5 ft., one target. *Hit:* 6 (1d6\
      \ + 3) piercing damage, and the target must make a DC 15 Constitution saving\
      \ throw, taking 24 (7d6) poison damage on a failed save, or half as much damage\
      \ on a successful one."
    "name": "Shortsword"
  - "desc": "*Ranged Weapon Attack:* +6 to hit, range 80/320 ft., one target. *Hit:*\
      \ 7 (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution\
      \ saving throw, taking 24 (7d6) poison damage on a failed save, or half as much\
      \ damage on a successful one."
    "name": "Light Crossbow"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/humanoid/token/assassin.webp"
```
^statblock

## Environment

urban

> [!statblock] Assassine
> ![](Assassine.png#token)
> *Mittelgroßer Humanoide (jede Rasse), jede nicht-gute Gesinnung*
> 
> - **Rüstungsklasse** 15  ([Beschlagenes Leder](Kompendium/Gegenstände/Beschlagenes-Leder.md))
> - **Trefferpunkte** 78 (`12W8 + 24`)
> - **Bewegungsrate** 9 Meter.
> 
> |STR|GES|KON|INT|WEI|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> |11 (+0)|16 (+3)|14 (+2)|13 (+1)|11 (+0)|10 (+0)|
> 
> - **Übungsbonus** +3
> - **Rettungswürfe** Geschicklichkeit +6, Intelligenz +4
> - **Fertigkeiten** Akrobatik: +6, Täuschung: +3, Wahrnehmung: +3, Heimlichkeit: +9
> - **Sinne** passive Wahrnehmung 13
> - **Schadensresistenzen** Gift
>
> - **Sprachen** Diebesjargon plus zwei beliebige Sprachen
> - **Herausforderungsgrad** 8 (3900 EP)
> 
> ## Merkmale
> 
> ***Meucheln.*** In seinem ersten Zug hat der Assassine Vorteil bei Angriffswürfen gegen jede Kreatur, die noch nicht am Zug war. Jeder Treffer, den der Assassine gegen eine überraschte Kreatur erzielt, ist ein kritischer Treffer.
> 
> ***Ausweichen.*** Wenn der Assassine einem Effekt ausgesetzt ist, der es ihm erlaubt, einen Rettungswurf auf Geschicklichkeit zu machen, um nur die Hälfte des Schadens zu erleiden, erleidet der Assassine keinen Schaden, wenn der Rettungswurf gelingt, und nur die Hälfte, wenn er scheitert.
> 
> ***Schleichangriff.*** Einmal pro Runde fügt der Assassine 14 (`4W6`) zusätzlichen Schaden zu, wenn er ein Ziel mit einem Waffenangriff trifft und Vorteil beim Angriffswurf hat oder wenn sich das Ziel innerhalb von 1,5 Metern von einem Verbündeten des Assassinen befindet, der nicht außer Gefecht gesetzt [incapacitated](rules/conditions.md#incapacitated) ist und der Assassine keinen Nachteil beim Angriffswurf hat.
> 
> ## Aktionen
> 
> ***Mehrfachangriff.*** Der Meuchelmörder führt zwei Kurzschwertangriffe aus.
> 
> ***Kurzschwert.*** *Nahkampfangriff*: +6 zum Treffen, Reichweite 1,5m, ein Ziel. *Treffer*: 6 (`1W6 + 3`) Stichschaden, und das Ziel muss einen Rettungswurf auf Konstitution SG 15 machen. Bei einem misslungenen Rettungswurf erleidet es 24 (`7W6`) Giftschaden, bei einem erfolgreichen Rettungswurf halb so viel Schaden.
> 
> ***Leichte Armbrust.*** *Fernkampfangriff*: +6 zum Treffen, Reichweite 24m / 36m, ein Ziel.. *Treffer:* 7 (`1W8 + 3`) Stichschaden, und das Ziel muss einen Rettungswurf auf Konstitution SG 15 machen. Bei einem misslungenen Rettungswurf erleidet es 24 (`7W6`) Giftschaden, bei einem erfolgreichen Rettungswurf halb so viel Schaden.

^statblock

## Vorkommen

Stadt