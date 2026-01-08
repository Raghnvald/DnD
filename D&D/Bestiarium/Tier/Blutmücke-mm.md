---
tags:
  - Quelle/5e/mm
  - Monster/HG/1-8
  - Monster/Größe/Winzig
  - Monster/Habitat/Berg
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Küste
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wald
  - Monster/Habitat/Wüste
  - Monster/Typ/Tier
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Stirge
---
# [Stirge](3-Mechanics\CLI\bestiary\beast/stirge.md)
*Source: Monster Manual p. 284. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

This horrid flying creature looks like a cross between a large bat and an oversized mosquito. Its legs end in sharp pincers, and its long, needle-like proboscis slashes the air as it seeks its next meal.

Stirges feed on the blood of living creatures, attaching and draining them slowly. Although they pose little danger in small numbers, packs of stirges can be a formidable threat, reattaching as quickly as their weakening prey can pluck them off.

## Blood Drain

A stirge attacks by landing on a victim, finding a vulnerable spot, and plunging its proboscis into the flesh while using its pincer legs to latch on to the victim. Once the stirge has sated itself, it detaches and flies off to digest its meal.

```statblock
name: Blutmücke
image: token/stirge.webp
source: Monsterhandbuch 2014
size: Winzig
type: Bestie
alignment: gesinnungslos
ac: !!int "14"
ac_class: "natural armor"
hp: !!int "2"
hit_dice: "1d4"
modifier: !!int "3"
stats:
  - !!int "4"
  - !!int "16"
  - !!int "11"
  - !!int "2"
  - !!int "8"
  - !!int "6"
speed: "3 Meter, Fliegen 12 Meter"
senses: "Dunkelsicht 18 Meter, passive Wahrnehmung 9"
languages: 
cr: "1/8"
actions:
  - name: "Blutabsaugung"
    desc: "Nahkampf Waffenangriff +5 zum Treffen, Reichweite 1,5 m, ein Ziel. Treffer: 5 (lW4 + 3) Wuchtschaden, und die Blutmücke heftet sich an das Ziel an. Solange die Blutmücke angeheftet ist, greift sie nicht an. Stattdessen verliert das Ziel zu Beginn eines jeden Zugs der Blutmücke 5 (1W4 +3) Trefferpunkte aufgrund des Blutverlu sts. \n\n Die Blutmücke kann sich lösen, indem sie 1,5 m ihrer Bewegung verwendet. Das tut sie, nachdem sie 10 Trefferpunkte an Blut ausgesaugt hat oder wenn das Ziel stirbt. Eine Kreatur, auch das Ziel, kann eine Aktion verwenden, um die Blutmücke zu lösen."
```
^statblock

## Environment

grassland, forest, swamp, hill, urban, desert, coastal, mountain, underdark