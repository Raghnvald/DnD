---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/mm
  - Monster/HG/1-8
  - Monster/Habitat/Wald
  - Monster/Größe/Klein
  - Monster/Typ/Pflanze
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Twig Blight
---
# [Twig Blight](3-Mechanics\CLI\bestiary\plant/twig-blight.md)
*Source: Monster Manual p. 32. Available in the Basic Rules (2014)*  

Twig blights can root in soil, which they do when living prey are scarce. While rooted, they resemble woody shrubs. When it pulls its roots free of the ground to move, a twig blight's branches twist together to form a humanoid-looking body with a head and limbs.

Twig blights seek out campsites and watering holes, rooting there to set up ambushes for potential victims coming to drink or rest. Huddled together in groups, twig blights blend in with an area's natural vegetation or with piles of debris or firewood.

Given how dry they are, twig blights are particularly susceptible to fire.

## Blights

Awakened plants gifted with the powers of intelligence and mobility, blights plague lands contaminated by darkness. Drinking that darkness from the soil, a blight carries out the will of ancient evil and attempts to spread that evil wherever it can.

### Roots of the Gulthias Tree

Legends tell of a vampire named Gulthias who worked terrible magic and raised up an abominable tower called Nightfang Spire. Gulthias was undone when a hero plunged a wooden stake through his heart, but as the vampire was destroyed, his blood infused the stake with a dreadful power. In time, tendrils of new growth sprouted from the wood, growing into a sapling infused with the vampire's evil essence. It is said that a mad druid discovered the sapling, transplanting it to an underground grotto where it could grow. From this Gulthias tree came the seeds from which the first blights were sown.

### Dark Conquest

Wherever a tree or plant is contaminated by a fragment of an evil mind or power, a Gulthias tree can rise to infest and corrupt the surrounding forest. Its evil spreads through root and soil to other plants, which perish or transform into blights. As those blights spread, they poison and uproot healthy plants, replacing them with brambles, toxic weeds, and others of their kind. In time, an infestation of blights can turn any land or forest into a place of corruption.

In forests infested with blights, trees and plants grow with supernatural speed. Vines and undergrowth rapidly spread through buildings and overrun trails and roads. After blights have killed or driven off their inhabitants, whole villages can disappear in the space of days.

### Controlled by Evil

Blights are independent creatures, but most act under a Gulthias tree's control, often displaying the habits and traits of the life force or spirit that spawned them. By attacking their progenitor's old foes or seeking out treasures valuable to it, they carry on the legacy of long-lost evil.

> [!quote]  
> 
> Behold the legacy of Gulthias the vampire: plants with a taste for blood.


```statblock
"name": "Twig Blight"
"size": "Small"
"type": "plant"
"alignment": "Neutral Evil"
"ac": !!int "13"
"ac_class": "natural armor"
"hp": !!int "4"
"hit_dice": "1d6 + 1"
"modifier": !!int "1"
"stats":
  - !!int "6"
  - !!int "13"
  - !!int "12"
  - !!int "4"
  - !!int "8"
  - !!int "3"
"speed": "20 ft."
"skillsaves":
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+3"
"damage_vulnerabilities": "fire"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [deafened](/3-Mechanics/CLI/conditions.md#Deafened)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (blind beyond\
  \ this radius), passive Perception 9"
"languages": "understands Common but can't speak"
"cr": "1/8"
"traits":
  - "desc": "While the blight remains motionless, it is indistinguishable from a dead\
      \ shrub."
    "name": "False Appearance"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one target. *Hit:* 3 (1d4\
      \ + 1) piercing damage."
    "name": "Claws"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/plant/token/twig-blight.webp"
```
^statblock

## Environment

forest

```statblock
statblock: true
name: Zweigplage
image: [[TwigBlight.webp]]
source: Grundregelwerk
size: Klein
type: Pflanze
alignment: neutral böse
ac: 13
hp: 4
hit_dice: 1d6+1
speed: 6 Meter.
stats: [6, 13, 12, 4, 8, 3]
skillsaves:
  - Heimlichkeit: 3
damage_vulnerabilities: "Feuer"
damage_resistances: ""
damage_immunities: ""
condition_immunities: "Blind, Taub"
senses: Dunkelsicht 18 Meter (darüber hinaus blind), passive Wahrnehmung 9
languages: versteht Gemeinsprache, kann sie aber nicht sprechen
cr: 1/8
environment: Wälder
bestiary: true
traits:
  - name: Falsche Erscheinung
    desc: Solange die Plage unbeweglich bleibt, ist sie von einem toten Strauch nicht zu unterscheiden.
    attack_bonus: 0
actions:
  - name: Klauen
    desc: "Nahkampfangriff: +3 zum Treffen, Reichweite 1,5m, ein Ziel. Treffer: 3 (1W4 + 1) Stichschaden."
    attack_bonus: 3
    damage_dice: 1d4
    damage_bonus: 1
```

### Beschreibung

Die Zweigplage ist eine erwachte Pflanze, die einem holzigen Strauch ähnelt, der seine Wurzeln aus dem Boden ziehen kann. Ihre Zweige verflechten sich zu einem humanoid aussehenden Körper mit Kopf und Gliedmaßen.

![[TwigBlight.png|cover hsmall]]
[[TwigBlight.png|Show To Players]]

Die Zweigplage kann im Boden wurzeln, was sie tut, wenn es an lebenden Beutetieren mangelt. Solange sie verwurzelt sind, ähneln sie holzigen Sträuchern. Wenn sie ihre Wurzeln aus dem Boden zieht, um sich fortzubewegen, verdrehen sich die Zweige zu einem humanoid aussehenden Körper mit Kopf und Gliedmaßen.

Die Zweigplage sucht Lagerplätze und Wasserstellen auf und legt dort Hinterhalte für potenzielle Opfer, die zum Trinken oder Rasten kommen. In Gruppen zusammengekauert, fügen sich die Zweigplagen in die natürliche Vegetation eines Gebiets oder in Haufen von Schutt oder Brennholz ein.

Da sie sehr trocken sind, sind die Zweigplage besonders feuerempfindlich.