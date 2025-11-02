---
cssclasses: json5e-monster
tags:
  - Quelle/5e/Monster_Manual
  - Habitat/Unterreich
  - Größe/Groß
  - Typ/Aberration
aliases:
  - Cloaker
---
```statblock
statblock: true
name: Mantler
image: [[Cloaker.png]]
source: Grundregelwerk
size: Groß
type: Aberation
alignment: Chaotisch Neutral
ac: 14
hp: 78
hit_dice: 12d10 + 12
speed: 9 Meter, fliegend 12 Meter.
stats: [17, 15, 12, 13, 12, 14]
skillsaves:
  - Heimlichkeit: +5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 11
languages: Tiefensprache, Undercommon
cr: 8
environment: Tiefenreich
bestiary: true
traits:
  - name: Damage Transfer
    desc: "While attached to a creature, the cloaker takes only half the damage dealt to it (rounded down), and that creature takes the other half."
  - name: False Appearance
    desc: "While the cloaker remains motionless without its underside exposed, it is indistinguishable from a dark leather cloak."
  - name: Light Sensitivity
    desc: "While in bright light, the cloaker has disadvantage on attack rolls and Wisdom ([Perception]) checks that rely on sight."
    attack_bonus: 0
actions:
  - name: Multiattack
    desc: "The cloaker makes two attacks: one with its bite and one with its tail."
  - name: Bite
    desc: "_Melee Weapon Attack:_ +6 to hit, reach 5 ft., one creature. _Hit:_ 10 (2d6 + 3) piercing damage, and if the target is Large or smaller, the cloaker attaches to it. If the cloaker has advantage against the target, the cloaker attaches to the target's head, and the target is [blinded] and unable to breathe while the cloaker is attached. While attached, the cloaker can make this attack only against the target and has advantage on the attack roll. The cloaker can detach itself by spending 5 feet of its movement. A creature, including the target, can take its action to detach the cloaker by succeeding on a DC 16 Strength check."
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 3
  - name: Tail
    desc: "_Melee Weapon Attack:_ +6 to hit, reach 10 ft., one creature. _Hit:_ 7 (1d8 + 3) slashing damage."
    attack_bonus: 6
    damage_dice: 1d8
    damage_bonus: 3
  - name: Moan
    desc: "Each creature within 60 feet of the cloaker that can hear its moan and that isn't an aberration must succeed on a DC 13 Wisdom saving throw or become [frightened] until the end of the cloaker's next turn. If a creature's saving throw is successful, the creature is immune to the cloaker's moan for the next 24 hours."
  - name: Phantasms (Recharges after a Short or Long Rest)
    desc: "The cloaker magically creates three illusory duplicates of itself if it isn't in bright light. The duplicates move with it and mimic its actions, shifting position so as to make it impossible to track which cloaker is the real one. If the cloaker is ever in an area of bright light, the duplicates disappear. <br> Whenever any creature targets the cloaker with an attack or a harmful spell while a duplicate remains, that creature rolls randomly to determine whether it targets the cloaker or one of the duplicates. A creature is unaffected by this magical effect if it can't see or if it relies on senses other than sight. <br>  A duplicate has the cloaker's AC and uses its saving throws. If an attack hits a duplicate, or if a duplicate fails a saving throw against an effect that deals damage, the duplicate disappears."
```

```statblock
statblock: true
name: Mantler
image: [[Cloaker.png]]
source: Grundregelwerk
size: Groß
type: Aberration
alignment: Chaotisch Neutral
ac: 14
hp: 78
hit_dice: 12d10 + 12
speed: 9 Meter, fliegend 12 Meter.
stats: [17, 15, 12, 13, 12, 14]
skillsaves:
  - Heimlichkeit: +5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 Meter, passive Wahrnehmung 11
languages: Tiefensprache, Undercommon
cr: 8
environment: Tiefenreich
bestiary: true
traits:
  - name: Schadensübertragung
    desc: "Während er an einer Kreatur befestigt ist, erleidet der Mantler nur die Hälfte des ihm zugefügten Schadens (abgerundet); die andere Hälfte geht auf die befestigte Kreatur über."
  - name: Täuschendes Aussehen
    desc: "Solange der Mantler unbeweglich bleibt und seine Unterseite nicht sichtbar ist, ist er nicht von einem dunklen Lederumhang zu unterscheiden."
  - name: Lichtempfindlichkeit
    desc: "Im hellen Licht hat der Mantler Nachteil bei Angriffswürfen und Weisheits‑(Wahrnehmungs‑)Proben, die das Sehen erfordern."
    attack_bonus: 0
actions:
  - name: Mehrfachangriff
    desc: "Der Mantler führt zwei Angriffe aus: einen Biss und einen Schwanzangriff."
  - name: Biss
    desc: "_Nahkampfangriff:_ +6 zum Treffen, Reichweite 5 ft., ein Ziel. _Treffer:_ 10 (2d6 + 3) Stichschaden, und wenn das Ziel groß oder kleiner ist, haftet der Mantler daran. Hat der Mantler Vorteil gegenüber dem Ziel, haftet er am Kopf des Ziels; das Ziel ist dann **blind** und kann nicht atmen, solange der Mantler befestigt ist. Während er befestigt ist, kann er diesen Angriff nur gegen das Ziel einsetzen und hat Vorteil beim Angriffswurf. Der Mantler kann sich lösen, indem er 5 ft. seiner Bewegung ausgibt. Eine Kreatur, einschließlich des Ziels, kann seine Aktion nutzen, um den Mantler zu lösen, indem sie einen Stärke‑Check (SG 16) besteht."
    attack_bonus: 6
    damage_dice: 2d6
    damage_bonus: 3
  - name: Schwanz
    desc: "_Nahkampfangriff:_ +6 zum Treffen, Reichweite 10 ft., ein Ziel. _Treffer:_ 7 (1d8 + 3) Hiebschaden."
    attack_bonus: 6
    damage_dice: 1d8
    damage_bonus: 3
  - name: Stöhnen
    desc: "Jede Kreatur im Umkreis von 60 ft., die das Stöhnen hören kann und keine Aberration ist, muss einen Rettungswurf auf Weisheit (SG 13) bestehen, sonst wird sie **verängstigt**, bis zum Ende des nächsten Zuges des Mantlers. Bei einem erfolgreichen Rettungswurf ist die Kreatur für die nächsten 24 Stunden immun gegen das Stöhnen des Mantlers."
  - name: Phantome (Erholt sich nach kurzer oder langer Rast)
    desc: "Der Mantler erschafft magisch drei illusorische Duplikate von sich, solange er sich nicht in hellem Licht befindet. Die Duplikate bewegen sich mit ihm und ahmen seine Aktionen nach, sodass es unmöglich ist, das wahre Exemplar zu bestimmen. Befindet sich der Mantler jemals in hellem Licht, verschwinden die Duplikate. Immer wenn eine Kreatur den Mantler mit einem Angriff oder einem schädlichen Zauber ins Visier nimmt, während ein Duplikat existiert, würfelt die Kreatur zufällig, ob sie das Original oder ein Duplikat trifft. Eine Kreatur ist von diesem Effekt unbeeinflusst, wenn sie nicht sehen kann oder andere Sinne nutzt. Ein Duplikat hat dieselbe RK wie der Mantler und nutzt dessen Rettungswürfe. Trifft ein Angriff ein Duplikat oder scheitert ein Duplikat bei einem Rettungswurf gegen einen schädlichen Effekt, verschwindet das Duplikat."
```

Cloakers earned their names for the resemblance they bear to dark leathery cloaks. Lurking in remote dungeons and caves, these stealthy predators wait to slay lone or injured prey stumbling through the darkness.

![](Cloaker.webp#token)

_**Camouflaged Lurkers.**_ Like a stingray, a cloaker’s body is composed of cartilage and muscle. With its tail and fins unfurled, it flies through darkness and lurks among the shadows of caverns the same way a stingray glides through water and hides on the ocean floor. Parallel rows of round, black eyespots run along its back like buttons, and the ivory-colored claws on its cowl resemble bone clasps.

When a cloaker unfurls and moves to attack, it reveals its pale underside and makes its true nature evident. Red eyes glow above rows of sharp teeth, and a long pendulous tail whips behind it.

_**Opportunistic Predators.**_ When hunting, cloakers glide through the shadows at a safe distance behind groups of other creatures traversing the Underdark. They follow parties of humanoids to prey on the wounded after a battle, or pursue herds of Underdark beasts, attacking the sick, the weak, or the straggling.

Cloakers strike quickly and consume their meals as swiftly as possible, enveloping and devouring their victims. While it feeds, a cloaker uses its swift, whiplike tail for defense, although it rarely takes a stand against dangerous foes or groups of creatures. As an added defense, cloakers can create illusory duplicates of themselves.

_**Haunting Moan.**_ Cloakers’ thoughts are alien to other life-forms, and they communicate with one another through subsonic moans inaudible to most creatures. At higher intensities, a cloaker’s haunting moan becomes audible, evoking sensations of doom and dread in creatures that hear it.

_**Cloaker Conclaves.**_ Cloakers prefer isolation, but they sometimes convene with other cloakers for defense or to exchange information about new dangers, suitable hunting grounds, or developments that might affect their habitats. When this convergence is complete, the cloakers separate again.