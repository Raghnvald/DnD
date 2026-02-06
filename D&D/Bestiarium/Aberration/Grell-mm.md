---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Grell
Kategorie: Aberration
Größe: Mittelgroß
HG: 3
status:
image: token/Grell.webp
tags:
  - Quelle/5e/mm
  - Monster/HG/3
  - Monster/Habitat/Unterreich
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Aberration
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Grell
---
# [Grell](3-Mechanics\CLI\bestiary\aberration/grell.md)
*Source: Monster Manual p. 172*  

A grell resembles a bulbous floating brain with a wide, sharp beak. Its ten long tentacles are made of hundreds of ring-shaped muscles sheathed in tough fibrous hide. Sharp barbs line the tip each tentacle and inject paralytic venom. The grell can partially retract its barbs into its tentacles to handle or manipulate objects it doesn't want to pierce or tear.

Grells have no eyes and floats by means of a sort of levitation. They have keen hearing, however, and their skin is sensitive to vibrations and electrical fields, allowing them to detect the presence of creatures and objects in their immediate vicinity. The creature's ability to manipulate electricity to sense and move also allow it to absorb lightning without harm.

Although solitary by nature, grells sometimes gather in small groups called covens.

## Floating Ambushers

A grell prefers to ambush lone creatures or stragglers, hovering silently near the ceiling of a passage or cavern until a suitable target passes below, whereupon it descends quickly and wraps its tentacles around its prey. It then floats away to its lair with the [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed) creature in its clutches.

## Alien Devourers

Grell are alien predators that group other creatures into three categories: edibles, inedibles, and Great Eaters (those rare creatures that might prey on a grell). Grells have no compunction about attacking creatures they classify as edible, including humanoids. They tend to avoid bigger creatures that they have little hope of carrying away.

A grell will sometimes allow adventurers to wage war on the other monstrous inhabitants of the dungeon complex it calls home, staying out of the adventurers' way as they dispose of larger threats while waiting for the right time to strike.

> [!quote] A quote from An adventurer's account of a grell attack in Khyber, published in The Korranberg Chronicle  
> 
> Our intrepid rogue climbed up the shaft to secure a rope. There was a gasp, and the rope fell. We never saw her again.


```statblock
"name": "Grell"
"size": "Medium"
"type": "aberration"
"alignment": "Neutral Evil"
"ac": !!int "12"
"hp": !!int "55"
"hit_dice": "10d8 + 10"
"modifier": !!int "2"
"stats":
  - !!int "15"
  - !!int "14"
  - !!int "13"
  - !!int "12"
  - !!int "11"
  - !!int "9"
"speed": "10 ft., fly 30 ft. (hover)"
"skillsaves":
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+4"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+6"
"damage_immunities": "lightning"
"condition_immunities": "[blinded](/3-Mechanics/CLI/conditions.md#Blinded), [prone](/3-Mechanics/CLI/conditions.md#Prone)"
"senses": "[blindsight](/3-Mechanics/CLI/senses.md#Blindsight) 60 ft. (blind beyond\
  \ this radius), passive Perception 14"
"languages": "Grell"
"cr": "3"
"actions":
  - "desc": "The grell makes two attacks: one with its tentacles and one with its\
      \ beak."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 10 ft., one creature. *Hit:*\
      \ 7 (1d10 + 2) piercing damage, and the target must succeed on a DC 11 Constitution\
      \ saving throw or be [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) for\
      \ 1 minute. The [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned) target is\
      \ [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed), and it can repeat the\
      \ saving throw at the end of each of its turns, ending the effect on a success.\n\
      \nThe target is also [grappled](/3-Mechanics/CLI/conditions.md#Grappled) (escape\
      \ DC 15). If the target is Medium or smaller, it is also [restrained](/3-Mechanics/CLI/conditions.md#Restrained)\
      \ until this grapple ends. While grappling the target, the grell has advantage\
      \ on attack rolls against it and can 't use this attack against other targets.\
      \ When the grell moves, any Medium or smaller target it is grappling moves with\
      \ it."
    "name": "Tentacles"
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 7 (2d4\
      \ + 2) piercing damage."
    "name": "Beak"
"source":
  - "MM"
"image": "/3-Mechanics/CLI/bestiary/aberration/token/grell.webp"
```
^statblock

## Environment

underdark

```statblock
statblock: true
name: Grell
image: [[Grell.webp]]
source: Grundregelwerk
size: Mittelgroß
type: Aberration
alignment: neutral böse
ac: 12
hp: 55
hit_dice: 10d8+10
speed: 3 Meter, fliegend 9 Meter (schwebend).
stats: [8, 14, 10, 10, 8, 8]
skillsaves:
  - Wahrnehmung: 4
  - Heimlichkeit: 6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Blitz"
condition_immunities: "Blind, Liegend"
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 9
languages: Grell
cr: 3
environment: Unterreich
bestiary: true
actions:
  - name: Mehrfachangriff
    desc: "Der Grell macht zwei Angriffe: einen mit seinen Tentakeln und einen mit seinem Schnabel."
    attack_bonus: 0
  - name: Tentakel
    desc: "Nahkampfangriff: +4 zum Treffen, Reichweite 3m, ein Ziel. Treffer: 7 (`1W10` + 2) Stichschaden. Das Ziel muss einen Konstitutions-Rettungswurf SG 11 bestehen oder wird 1 Minute lang vergiftet. Das vergiftete Ziel ist gelähmt und kann den Rettungswurf am Ende jeder seiner Runden wiederholen, wobei der Effekt bei einem Erfolg beendet wird. Das Ziel wird außerdem gepackt (Befreiung SG 15). Wenn das Ziel mittelgroß oder kleiner ist, wird es ebenfalls gefesselt, bis dieser Griff endet. Während der Grell das Ziel packt, hat er einen Vorteil bei Angriffswürfen gegen das Ziel und kann diesen Angriff nicht gegen andere Ziele einsetzen. Wenn sich der Grell bewegt, bewegt sich jedes Ziel mittlerer Größe oder kleiner, das er im Griff hat, mit ihm."
    attack_bonus: 4
    damage_dice: 1d10
    damage_bonus: 2
```

### Beschreibung

Ein Grell ähnelt einem bauchigen schwimmenden Gehirn mit einem breiten, scharfen Schnabel. Ihre zehn langen Tentakel bestehen aus Hunderten von ringförmigen Muskeln, die von einer zähen Faserhaut umhüllt sind. An der Spitze jedes Tentakels befinden sich scharfe Widerhaken, die ein lähmendes Gift injizieren. Der Grell kann seine Widerhaken teilweise in seine Tentakel einziehen, um Objekte zu handhaben, die er nicht durchbohren oder zerreißen will.

![](D&D/05%20-%20Wikipedia/Bestiarium/00-pictures/Grell.webp#token)

Grells haben keine Augen und schweben mit Hilfe einer Art Schwebezustand. Sie haben jedoch ein scharfes Gehör und ihre Haut ist empfindlich für Vibrationen und elektrische Felder, so dass sie die Anwesenheit von Kreaturen und Gegenständen in ihrer unmittelbaren Umgebung wahrnehmen können. Die Fähigkeit der Kreatur, Elektrizität zu manipulieren, um zu spüren und sich zu bewegen, erlaubt es ihr auch, Blitze zu absorbieren, ohne Schaden zu nehmen.

Obwohl sie von Natur aus Einzelgänger sind, versammeln sich Grells manchmal in kleinen Gruppen, die Covens genannt werden.

**Schwebende Angreifer.** Ein Grell zieht es vor, einsamen Kreaturen oder Nachzüglern aufzulauern, indem er lautlos in der Nähe der Decke eines Ganges oder einer Höhle schwebt, bis ein geeignetes Ziel vorbeikommt, woraufhin er schnell herabsteigt und seine Tentakel um seine Beute schlingt. Dann schwebt es mit der gelähmten Kreatur in seinen Fängen in sein Versteck.

**Außerirdische Fresser.** Grell sind außerirdische Raubtiere, die andere Kreaturen in drei Kategorien einteilen: essbare, ungenießbare und große Fresser (die seltenen Kreaturen, die einen Grell fressen könnten). Grells haben keine Skrupel, Kreaturen anzugreifen, die sie als essbar einstufen, einschließlich Humanoiden. Sie neigen dazu, größere Kreaturen zu meiden, bei denen sie wenig Hoffnung haben, sie zu erbeuten.

Ein Grell erlaubt es Abenteurern manchmal, die anderen monströsen Bewohner des Kerkerkomplexes, den er sein Zuhause nennt, zu bekämpfen, indem er den Abenteurern aus dem Weg geht, während sie sich größerer Bedrohungen entledigen und auf den richtigen Zeitpunkt zum Zuschlagen warten.