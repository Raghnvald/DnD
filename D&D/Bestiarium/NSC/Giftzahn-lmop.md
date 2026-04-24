---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Giftzahn
Kategorie: Drache
Größe: Groß
HG: 8
Habitat:
  - /
status: WIP
tags:
  - Monster/Größe/Groß
  - Monster/HG/8
  - Monster/Typ/Drache
  - Quelle/5e/lmop
aliases:
  - Giftzahn
  - Venomfang
Image: NSC/token/venomfang-lmop.webp
linter-yaml-title-alias: Giftzahn
---
# Giftzahn
*Quellen: Die verlorene Mine von Phandelver S. 63*  

```statblock
"name": "Giftzahn (LMoP)"
"image": "npc/token/venomfang-lmop.webp"
"source":
  - "LMoP"
"size": "Groß"
"type": "Drache"
"alignment": "Rechtschaffen Böse"
"ac": !!int "18"
"ac_class": "Natürliche Rüstung"
"hp": !!int "136"
"hit_dice": "16d10 + 48"
"modifier": !!int "1"
"stats":
  - !!int "19"
  - !!int "12"
  - !!int "17"
  - !!int "16"
  - !!int "13"
  - !!int "15"
"speed": "12 Meter, fliegend 24 Meter, schwimmend 12 Meter"
"saves":
  - "Geschicklichkeit": !!int "4"
  - "Konstitution": !!int "6"
  - "Weisheit": !!int "4"
  - "Charisma": !!int "5"
"skillsaves":
  - "name": "[Heimlichkeit](skills.md#Stealth)"
    "desc": "+4"
  - "name": "[Täuschung](skills.md#Deception)"
    "desc": "+5"
  - "name": "[Wahrnehmung](skills.md#Perception)"
    "desc": "+7"
"damage_immunities": "Gift"
"condition_immunities": "[Vergiftet](conditions.md#Poisoned)"
"senses": "[Blindsicht](senses.md#Blindsight) 9 m., [Dunkelsicht](senses.md#Darkvision) 36 m., passive Wahrnehmung 17"
"languages": "Gemeinsprache, Drakonisch"
"cr": "8"
"traits":
  - "name": "Amphibious"
    "desc": "Giftzahn kann Luft und Wasser atmen."
"actions":
  - "name": "Mehrfachangriff"
    "desc": "Giftzahn führt bis zu drei Angriffe aus, von denen einer Biss und zwei Klaue sein können."
  - "name": "Biss"
    "desc": "*Nahkampf-Waffenangriff:* +7, Reichweite 3 Meter, ein Ziel. *Treffer:* 15 (2d10 + 4) Stichschaden plus 7 (2d6) Giftschaden."
  - "name": "Klaue"
    "desc": "*Nahkampf-Waffenangriff:* +7, Reichweite 1,5 Meter, ein Ziel. *Treffer:* 11 (2d6 + 4) Hiebschaden."
  - "name": "Giftodem (Aufladung 5-6)"
    "desc": "Giftzahn atmet in einem Kegel von 9 Metern Länge giftiges Gas aus. Alle Kreaturen im Kegel müssen einen Konstitutionsrettungswurf gegen SG 14 ablegen. Bei einem misslungenen Rettungswurf erleiden sie 42 (12d6) Giftschaden, halb so viel Schaden bei einem erfolgreichen Rettungswurf."
```
^statblock