---
cssclasses: dnd5e-only-statblock
prefer-view: edit-source read
Bezeichnung: Aboleth
Typ: Aberration
Größe: Groß
HG: 10
status:
order:
parent:
image: token/Aboleth.webp
tags:
- Quelle/5e/Monster_Manual
- Typ/Aberration
- Größe/Groß
- Habitat/Unterreich
aliases:
- Aboleth
---
```statblock
statblock: true
name: Aboleth
image: [[Aboleth.png]]
source: Grundregelwerk
size: Groß
type: Aberation
alignment: Rechtschaffen Böse
ac: 17
hp: 135
hit_dice: 18d10 + 36
speed: 3 Meter, schwimmend 12 Meter.
stats: [21, 9, 15, 18, 15, 18]
saves:
  - KON: +6
  - INT: +8
  - WEI: +6
skillsaves:
  - Geschichte: +12
  - Wahrnehmung: +10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 36 Meter, passive Wahrnehmung 20
languages: Tiefensprache, Telepathie 36 Meter
cr: 10
environment: Tiefenreich
bestiary: true
traits:
  - name: Amphibious
    desc: "The aboleth can breathe air and water."
    attack_bonus: 0
  - name: Mucous Cloud
    desc: "While underwater, the aboleth is surrounded by transformative mucus. A creature that touches the aboleth or that hits it with a melee attack while within 5 feet of it must make a DC 14 Constitution saving throw. On a failure, the creature is diseased for `1d4` hours. The diseased creature can breathe only underwater."
    attack_bonus: 0
  - name: Probing Telepathy
    desc: "If a creature communicates telepathically with the aboleth, the aboleth learns the creature's greatest desires if the aboleth can see the creature."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The aboleth makes three tentacle attacks."
  - name: Tentacle
    desc: "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 12 (`2d6 + 5`) bludgeoning damage. If the target is a creature, it must succeed on a DC 14 Constitution saving throw or become diseased. The disease has no effect for 1 minute and can be removed by any magic that cures disease. After 1 minute, the diseased creature's skin becomes translucent and slimy, the creature can't regain hit points unless it is underwater, and the disease can be removed only by [heal](compendium/spells/heal.md) or another disease-curing spell of 6th level or higher. When the creature is outside a body of water, it takes 6 (`1d12`) acid damage every 10 minutes unless moisture is applied to the skin before 10 minutes have passed."
    attack_bonus: 9
    damage_dice: 2d6
    damage_bonus: 5
  - name: Tail
    desc: "*Melee Weapon Attack:* +9 to hit, reach 10 ft., one target. *Hit:* 15 (`3d6 + 5`) bludgeoning damage."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Enslave (3/Day)
    desc: "The aboleth targets one creature it can see within 30 feet of it. The target must succeed on a DC 14 Wisdom saving throw or be magically [charmed](rules/conditions.md#charmed) by the aboleth until the aboleth dies or until it is on a different plane of existence from the target. The [charmed](rules/conditions.md#charmed) target is under the aboleth's control and can't take reactions, and the aboleth and the target can communicate telepathically with each other over any distance.<br> Whenever the [charmed](rules/conditions.md#charmed) target takes damage, the target can repeat the saving throw. On a success, the effect ends. No more than once every 24 hours, the target can also repeat the saving throw when it is at least 1 mile away from the aboleth."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
legendary_description: "The aboleth can take 3 legendary actions, choosing from the options below. Only one legendary action option can be used at a time and only at the end of another creature’s turn. The aboleth regains spent legendary actions at the start of its turn."
legendary_actions:
  - name: Detect
    desc: The aboleth makes a Wisdom (Perception) check.  
  - name: Tail Swipe
    desc: The aboleth makes one tail attack.
  - name: Psychic Drain (Costs 2 Actions)
    desc: One creature [charmed] by the aboleth takes 10 (3d6) psychic damage, and the aboleth regains hit points equal to the damage the creature takes.
```

```statblock
statblock: true
name: Aboleth
image: [[Aboleth.png]]
source: Grundregelwerk
size: Groß
type: Aberration
alignment: Rechtschaffen Böse
ac: 17
hp: 135
hit_dice: 18d10 + 36
speed: 3 Meter, schwimmend 12 Meter.
stats: [21, 9, 15, 18, 15, 18]
saves:
  - KON: +6
  - INT: +8
  - WEI: +6
skillsaves:
  - Geschichte: +12
  - Wahrnehmung: +10
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 36 Meter, passive Wahrnehmung 20
languages: Tiefensprache, Telepathie 36 Meter
cr: 10
environment: Tiefenreich
bestiary: true
traits:
  - name: Amphibisch
    desc: "Der Aboleth kann Luft und Wasser atmen."
    attack_bonus: 0
  - name: Schleimiger Nebel
    desc: "Während er sich unter Wasser befindet, ist der Aboleth von einem transformativen Schleim umgeben. Eine Kreatur, die den Aboleth berührt oder ihn im Nahkampf innerhalb von 5 ft. trifft, muss einen Rettungswurf auf Konstitution (SG 14) bestehen. Bei einem Fehlschlag ist die Kreatur für `1d4` Stunden erkrankt. Die erkrankte Kreatur kann nur unter Wasser atmen."
    attack_bonus: 0
  - name: Forschende Telepathie
    desc: "Wenn eine Kreatur telepathisch mit dem Aboleth kommuniziert, erfährt der Aboleth die größten Wünsche dieser Kreatur, sofern er sie sehen kann."
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Aboleth führt drei Tentakelangriffe aus."
  - name: Tentakel
    desc: "*Nahkampfangriff:* +9 zum Treffen, Reichweite 10 ft., ein Ziel. *Treffer:* 12 (`2d6 + 5`) Wucht-Schaden. Trifft das Ziel eine Kreatur, muss diese einen Rettungswurf auf Konstitution (SG 14) bestehen oder erkranken. Der Krankheitszustand hat für 1 Minute keine Wirkung und kann durch jede Magie, die Krankheiten heilt, entfernt werden. Nach 1 Minute wird die Haut des Erkrankten durchsichtig und schleimig, die Kreatur kann keine Trefferpunkte zurückgewinnen, solange sie nicht im Wasser ist, und die Krankheit kann nur durch *Heilung* (Kompendium/Zauber/heal.md) oder einen anderen krankheitsheilenden Zauber der Stufe 6 oder höher entfernt werden. Befindet sich die Kreatur außerhalb eines Gewässers, erleidet sie alle 10 Minuten 6 (`1d12`) Säure-Schaden, sofern die Haut nicht vorher befeuchtet wurde."
    attack_bonus: 9
    damage_dice: 2d6
    damage_bonus: 5
  - name: Schwanz
    desc: "*Nahkampfangriff:* +9 zum Treffen, Reichweite 10 ft., ein Ziel. *Treffer:* 15 (`3d6 + 5`) Wucht-Schaden."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
  - name: Versklaven (3/Tag)
    desc: "Der Aboleth zielt auf eine Kreatur, die er innerhalb von 30 ft. sehen kann. Das Ziel muss einen Rettungswurf auf Weisheit (SG 14) bestehen, sonst wird es bis zum Tod des Aboleths oder bis es sich in einer anderen Dimension befindet, magisch [verzaubert](rules/conditions.md#charmed) vom Aboleth. Das verzauberte Ziel kann keine Reaktionen ausführen, und der Aboleth sowie das Ziel können über beliebige Entfernungen telepathisch miteinander kommunizieren. Immer wenn das verzauberte Ziel Schaden erleidet, kann es den Rettungswurf wiederholen; bei Erfolg endet der Effekt. Höchstens einmal pro 24 Stunden kann das Ziel den Rettungswurf auch wiederholen, wenn es mindestens 1 Meile vom Aboleth entfernt ist."
    attack_bonus: 4
    damage_dice: 1d6
    damage_bonus: 2
legendary_description: "Der Aboleth kann 3 legendäre Aktionen einsetzen, wobei er jeweils eine der untenstehenden Optionen wählt. Nur eine legendäre Aktion kann gleichzeitig verwendet werden und nur am Ende des Zuges einer anderen Kreatur. Der Aboleth erhält verbrauchte legendäre Aktionen zu Beginn seines Zuges zurück."
legendary_actions:
  - name: Wahrnehmen
    desc: Der Aboleth macht eine Weisheits-(Wahrnehmungs-)Probe.
  - name: Schwanzschlag
    desc: Der Aboleth führt einen Schwanzangriff aus.
  - name: Psychischer Sog (Kosten 2 Aktionen)
    desc: Eine vom Aboleth verzauberte Kreatur erleidet 10 (`3d6`) psychischen Schaden, und der Aboleth erhält Trefferpunkte in Höhe des verursachten Schadens zurück.
lair_actions:
  - name: Phantasmale Kraft wirken
    desc: Der Aboleth wirkt *Phantasmale Kraft* (keine Komponenten erforderlich) auf beliebig viele Kreaturen, die er innerhalb von 60 ft. sehen kann. Solange er die Konzentration auf diesen Effekt hält, kann er keine weiteren Lair-Aktionen ausführen. Gelingt einem Ziel der Rettungswurf oder endet der Effekt für das Ziel, ist das Ziel für die nächsten 24 Stunden immun gegen die Lair‑Aktion *Phantasmale Kraft* des Aboleths, kann jedoch erneut gewählt werden.
  - name: Griffende Flut
    desc: Wassermengen im Umkreis von 90 ft. des Aboleths strömen nach außen wie eine tückische Flut. Jede Kreatur, die sich auf dem Boden innerhalb von 20 ft. einer solchen Wasserfläche befindet, muss einen Rettungswurf auf Stärke (SG 14) bestehen oder wird bis zu 20 ft. ins Wasser gezogen und fällt *liegend* (prone). Der Aboleth kann diese Lair‑Aktion erst wieder nutzen, nachdem er eine andere eingesetzt hat.
  - name: Rausch des Wassers
    desc: Das Wasser im Lair wird zu einem Kanal für die Wut der Kreaturen. Der Aboleth kann beliebig viele Kreaturen, die er im Wasser innerhalb von 90 ft. sehen kann, anvisieren. Jede Zielkreatur muss einen Rettungswurf auf Weisheit (SG 14) bestehen, sonst erleidet sie 7 (`2d6`) psychischen Schaden. Der Aboleth kann diese Lair‑Aktion erst wieder nutzen, nachdem er eine andere eingesetzt hat.
regional_effects:
  - name: Schlammiges Terrain
    desc: Unterirdische Oberflächen im Umkreis von 1 Meile um das Lair des Aboleths sind schlammig und nass und gelten als schwieriges Gelände.
  - name: Verseuchtes Wasser
    desc: Wasserquellen im Umkreis von 1 Meile des Lairs sind übernatürlich befleckt. Feinde des Aboleths, die solches Wasser trinken, erbrechen es innerhalb von Minuten.
  - name: Illusorisches Abbild
    desc: Als Aktion kann der Aboleth ein illusorisches Bild seiner selbst im Umkreis von 1 Meile um das Lair erschaffen. Das Abbild kann an jedem Ort erscheinen, den der Aboleth zuvor gesehen hat, oder an einem Ort, den eine vom Aboleth verzauberte Kreatur gerade sehen kann. Sobald das Bild entsteht, hält es so lange an, wie der Aboleth die Konzentration darauf aufrechterhält, als würde er einen Zauber wirken. Das Bild ist immateriell, sieht aber aus, klingt und bewegt sich wie der echte Aboleth. Der Aboleth kann vom Bild aus sehen, sprechen und telepathisch kommunizieren, als wäre er dort. Wird das Bild beschädigt, verschwindet es sofort.
```

Aboleths lair in subterranean lakes or the rocky depths of the ocean, often surrounded by the ruins of an ancient, fallen aboleth city. An aboleth spends most of its existence underwater, surfacing occasionally to treat with visitors or worshipers.

![](Aboleth.webp#token)

#### Lair Actions

When fighting inside its lair, an aboleth can invoke the ambient magic to take lair actions. On initiative count 20 (losing initiative ties), the aboleth takes a lair action to cause one of the following effects:

- The aboleth casts [phantasmal force](https://www.dndbeyond.com/spells/2332-phantasmal-force) (no components required) on any number of creatures it can see within 60 feet of it. While maintaining concentration on this effect, the aboleth can’t take other lair actions. If a target succeeds on the saving throw or if the effect ends for it, the target is immune to the aboleth’s [phantasmal force](https://www.dndbeyond.com/spells/2332-phantasmal-force) lair action for the next 24 hours, although such a creature can choose to be affected.
- Pools of water within 90 feet of the aboleth surge outward in a grasping tide. Any creature on the ground within 20 feet of such a pool must succeed on a DC 14 Strength saving throw or be pulled up to 20 feet into the water and knocked [prone](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#ProneCondition). The aboleth can’t use this lair action again until it has used a different one.
- Water in the aboleth’s lair magically becomes a conduit for the creature’s rage. The aboleth can target any number of creatures it can see in such water within 90 feet of it. A target must succeed on a DC 14 Wisdom saving throw or take 7 (2d6) psychic damage. The aboleth can’t use this lair action again until it has used a different one.

#### Regional Effects

The region containing an aboleth’s lair is warped by the creature’s presence, which creates one or more of the following effects:

- Underground surfaces within 1 mile of the aboleth’s lair are slimy and wet and are difficult terrain.
- Water sources within 1 mile of the lair are supernaturally fouled. Enemies of the aboleth that drink such water vomit it within minutes.
- As an action, the aboleth can create an illusory image of itself within 1 mile of the lair. The copy can appear at any location the aboleth has seen before or in any location a creature [charmed](https://www.dndbeyond.com/sources/dnd/free-rules/rules-glossary#CharmedCondition) by the aboleth can currently see. Once created, the image lasts for as long as the aboleth maintains concentration, as if concentrating on a spell. Although the image is intangible, it looks, sounds, and can move like the aboleth. The aboleth can sense, speak, and use telepathy from the image’s position as if present at that position. If the image takes any damage, it disappears.

If the aboleth dies, the first two effects fade over the course of 3d10 days.

---

Before the coming of the gods, aboleths lurked in primordial oceans and underground lakes. They reached out with their minds and seized control of the burgeoning life-forms of the mortal realm. Their dominance made them like gods. Then the true gods appeared, smashing the aboleths’ empire.

Aboleths have never forgotten.

_**Eternal Memories**_. Aboleths have flawless memories. They pass on their knowledge and experience from generation to generation. Thus, the injury of their defeat by the gods remains perfectly preserved in their minds.

Aboleths’ minds are treasure troves of ancient lore, recalling moments from prehistory with perfect clarity. They plot patiently and intricately across eons. Few creatures can conceive of the extent of an aboleth’s plan.

_**Gods in the Lake.**_ Aboleths dwell in watery environments, including ocean abysses, deep lakes, and the Elemental Plane of Water. In these domains and the lands that adjoin them, aboleths are like gods, demanding worship and obedience from their subjects. When they consume other creatures, aboleths add the knowledge and experiences of their prey to their eternal memories.

Aboleths use their telepathic powers to read the minds of creatures and know their desires. An aboleth uses this knowledge to gain a creature’s loyalty, promising to fulfill such wants in exchange for obedience. Within its lair, the aboleth can further use its powers to override senses, granting creatures, such as its followers, the illusion of promised rewards.

_**Enemies of the Gods.**_ The aboleths’ fall from power is written in stark clarity on their flawless memories, for aboleths never truly die. If an aboleth’s body is destroyed, its spirit returns to the Elemental Plane of Water, where a new body coalesces for it over days or months.

Ultimately, aboleths dream of overthrowing the gods and regaining control of the world. Aboleths have had untold eons to plot and to prepare their plans for perfect execution.