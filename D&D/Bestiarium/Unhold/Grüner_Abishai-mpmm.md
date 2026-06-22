---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Green Abishai
Kategorie: Unhold
image: token/green-abishai-mpmm.webp
linter-yaml-title-alias: Green Abishai
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/HG/15
  - Monster/Typ/Unhold/devil
  - Quelle/5e/mpmm
  - Quelle/5e/veor
aliases:
  - Green Abishai
---
# Grüner Abishai
*Quelle: Mordenkainen präsentiert: Monster des Multiversums S. 39*  

Grüne Abishai sind geschickt darin, Geheimnisse zu lüften und an sensible Informationen zu gelangen. Dank ihrer Magie und ihren diplomatischen Fertigkeiten können sie sogar die abgefeimtesten Gegner manipulieren. 

## Abishai

Jeder Abishai war einmal ein Sterblicher, der vor seinem Tod irgendwie Tiamats Gunst erlangt hat. Zur Belohnung wurde seine Seele in einen drakonischen Teufel verwandelt und dient Tiamat in den Neun Höllen.Jede Art von Abishai gemahnt an einen der fünf Drachenköpfe Tiamats: schwarz, blau, grün, rot und weiß. 

Tiamat entsendet die Abishai auch als Agenten, um ihre Interessen in den Höllen und im Multiversum durchzusetzen. Bisweilen haben ihre Boten schlichte Aufgaben, etwa Kultisten Botschaften zu überbringen. Andere müssen große Gruppen anführen, Zielpersonen töten und in Armeen dienen. Abishai sind Tiamat in jedem Fall fanatisch ergeben und stets bereit, ihr Leben für sie zu opfern, falls nötig. 

Sie stehen außerhalb der Hierarchie der Neun Höllen, haben ihre eigene Befehlskette und gehorchen letztlich Tiamat - und auch Asmodeus, wenn er sie nutzen will. Auch andere Erzteufel können Abishai befehlen, für sie zu arbeiten. Aber sie tun es selten, denn es ist nie klar, ob ein Abishai gerade Tiamat oder Asmodeus gehorcht. Tiamats Befehle zu durchkreuzen ist riskant, und jede Einmischung in Asmodeus' Pläne bringt den sicheren Untergang. 

```statblock
"name": "Green Abishai (MPMM)"
"size": "Medium"
"type": "fiend"
"subtype": "devil"
"alignment": "Typically  Lawful Evil"
"ac": !!int "18"
"ac_class": "natural armor"
"hp": !!int "195"
"hit_dice": "26d8 + 78"
"modifier": !!int "3"
"stats":
  - !!int "12"
  - !!int "17"
  - !!int "16"
  - !!int "17"
  - !!int "12"
  - !!int "19"
"speed": "30 ft., fly 40 ft."
"saves":
  - "intelligence": !!int "8"
  - "charisma": !!int "9"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+6"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Persuasion](/3-Mechanics/CLI/skills.md#Persuasion)"
    "desc": "+9"
"damage_resistances": "cold; bludgeoning, piercing, slashing from nonmagical attacks\
  \ that aren't silvered"
"damage_immunities": "fire, poison"
"condition_immunities": "[poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 120 ft., passive Perception\
  \ 16"
"languages": "Draconic, Infernal, telepathy 120 ft."
"cr": "15"
"traits":
  - "desc": "Magical darkness doesn't impede the abishai's [darkvision](/3-Mechanics/CLI/senses.md#Darkvision)."
    "name": "Devil's Sight"
  - "desc": "The abishai has advantage on saving throws against spells and other magical\
      \ effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The abishai makes two Fiendish Claw attacks, or it makes one Fiendish\
      \ Claw attack and uses Spellcasting."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 12\
      \ (2d8 + 3) force damage. If the target is a creature, it must succeed on a\
      \ DC 16 Constitution saving throw or take 16 (3d10) poison damage and become\
      \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) for 1 minute. The [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ target can repeat the saving throw at the end of each of its turns, ending\
      \ the effect on itself on a success."
    "name": "Fiendish Claw"
  - "desc": "The abishai casts one of the following spells, requiring no material\
      \ components and using Charisma as the spellcasting ability (spell save DC 17):\n\
      \n**At will:** [alter self](/3-Mechanics/CLI/spells/alter-self-xphb.md), [major\
      \ image](/3-Mechanics/CLI/spells/major-image-xphb.md)\n\n**3/day each:** [charm\
      \ person](/3-Mechanics/CLI/spells/charm-person-xphb.md), [detect thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md),\
      \ [fear](/3-Mechanics/CLI/spells/fear-xphb.md)\n\n**1/day each:** [confusion](/3-Mechanics/CLI/spells/confusion-xphb.md),\
      \ [dominate person](/3-Mechanics/CLI/spells/dominate-person-xphb.md), [mass\
      \ suggestion](/3-Mechanics/CLI/spells/mass-suggestion-xphb.md)"
    "name": "Spellcasting"
"source":
  - "MPMM"
"image": "/3-Mechanics/CLI/bestiary/fiend/token/green-abishai-mpmm.webp"
```
^statblock

> [!statblock] Grüner Abishai
> ![[token/green-abishai-mpmm.webp|right|100]]
> *Mittelgroßer Unhold (Teufel), typischerweise Rechtschaffen Böse*
> 
> - **Rüstungsklasse** 18 (natürliche Rüstung)
> - **Trefferpunkte** 195 (`26d8 + 78`)
> - **Bewegungsrate** 9 Meter, Flug 12 Meter
> 
> |STR|GES|KON|INT|WEI|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> | 12 (+1)|17 (+3)|16 (+3)|17 (+3)|12 (+1)|19 (+4)|
> 
> - **Rettungswürfe** INT +8, CHA +9
> - **Fertigkeiten** [[|Motiv erkennen]] +6, [[|Täuschung]] +9, [[|Überreden]] +9, [[|Wahrnehmung]] +6
> - **Schadensresistenzen** Kälte; Hieb, Stich und Wucht durch nichtmagische Angriffe ohne Silber 
> - **Schadensimmunitäten** Feuer, Gift
> - **Zustandsimmunitäten** [[|Vergiftet]] <br><br>
> - **Sinne** [[|Dunkelsicht]] 36 Meter, passive Wahrnehmung 16
> - **Sprachen** Diabolisch, Drakonisch, Telepathie 36 Meter
> - **Herausforderungsgrad** 15 (13.000 EP)
> - **Übungsbonus** +3
> 
> ## Merkmale
> 
> ***Teufelsblick.*** Magische Dunkelheit behindert nicht den Dunkelsicht des Abishais.
> 
> ***Magieresistenz.*** Der Abishai hat Vorteil auf Rettungswürfe gegen Zauber und andere magische Effekte.
> 
> ## Aktionen
> 
> ***Mehrfachangriff.*** Der Abishai führt zwei Angriff mit den teuflischen Klauen aus, oder er führt einen Angriff mit den teuflischen Klauen aus und nutzt seine Zauberwirken.
> 
> ***Teuflische Klaue.*** *Nahkampf-Waffenangriff:* +8 zum Treffen, Reichweite 1,5 Meter, ein Ziel. *Treffer:* 12 (`2W8 + 3`) Kraftschaden. Wenn das Ziel eine Kreatur ist, muss es einen SG 16 Konstitutionsrettungswurf bestehen oder erleidet zusätzlich 16 (`3W10`) Giftschaden und ist für 1 Minute *vergiftet*. Das *vergiftete* Ziel kann am Ende jedes seiner Züge einen neuen Rettungswurf ablegen, um den Effekt zu beenden.
> 
> ***Zauberwirken.*** Der Abishai wirkt einen der folgenden Zauber, ohne materielle Komponenten zu benötigen, und verwendet Charisma als zaubernde Fähigkeit (SG 17):
> 
> - **Jederzeit:** *Gestalt ändern*, *Großes Bild*
> - **3×/Tag:** *Mensch bezaubern*, *Gedanken lesen*, *Angst*
> - **1×/Tag:** *Verwirrung*, *Menschen beherrschen*, *Massenvorschlag*

## Environment

urban