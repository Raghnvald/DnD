---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: "Ezmerelda d'Avenir"
Status: WIP
linter-yaml-title-alias: "Ezmerelda d'Avenir"
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/8
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/cos
aliases:
  - "Ezmerelda d'Avenir"
---
# [Ezmerelda d'Avenir](3-Mechanics\CLI\bestiary\npc/ezmerelda-davenir-cos.md)
*Source: Curse of Strahd p. 231*  

Ezmerelda d'Avenir, a Vistana, is the protégé of Rudolph van Richten - despite the fact that her first encounter with the vampire hunter was anything but pleasant.

## Witness to Tragedy

When Ezmerelda was a little girl, her family kidnapped van Richten's teenage son, Erasmus, and delivered him into the clutches of a vampire. Even today, years later, she can still hear Erasmus's pleas for mercy. That event haunted her childhood.

Van Richten tracked down Ezmerelda's family soon after the kidnapping, but not before the Vistani had sold the boy. Though van Richten could have done them harm, he instead interrogated Ezmerelda's mother and father on the whereabouts of his missing son. Satisfied with their answers, he spared their lives before departing with the information they had given him. Ezmerelda witnessed van Richten's act of mercy and was deeply moved by it.

## Van Richten's Tragic Tale

At the age of fifteen, Ezmerelda, still troubled by what her family had done to van Richten, ran away from home. After many harrowing adventures, she tracked down van Richten two years later. Thinking she was a Vistana assassin, he put a sword to her throat and threatened to spill her blood. Ezmerelda convinced him that she genuinely wanted to help him find his missing son, whereupon van Richten told her the saddest of tales. He had found his son, who had been transformed into a vampire spawn. When Erasmus pleaded to his father for salvation, van Richten granted his request by ending his existence.

## Farewell

Ezmerelda remained by van Richten's side for two years, helping him track down and slay many creatures of the night. But because van Richten could never bring himself to fully trust a Vistana, he kept secrets from her. The two vampire hunters got on each other's nerves, and their arguments became more frequent. At last, Ezmerelda suggested that they part company with some shred of their friendship still intact, and van Richten agreed.

## Ezmerelda's Secret

Since bidding farewell to van Richten, Ezmerelda has amassed a sizable personal fortune, some of which she used to buy a wagon to carry her vampire-slaying paraphernalia. On one of her less successful adventures, a werewolf bit off her right leg below the knee, and although she avoided being afflicted with lycanthropy, Ezmerelda was sidelined for months. She commissioned a master artisan to craft a prosthetic lower leg and foot. After several tries, he delivered a prosthesis that restored her mobility. She has since adapted well to the false appendage.

## The Great Vampire Hunt

While in the company of a Vistani caravan, Ezmerelda heard a rumor that Rudolph van Richten had gone to Barovia to slay the most powerful vampire of them all. She decided that he might need help and traveled for months to reach Strahd's domain. She rode her wagon to Vallaki and learned about an old tower that seemed the sort of place van Richten would use as a base. When she arrived there, she found some of van Richten's belongings, but of the vampire hunter there was no sign. Although she is anxious to learn the whereabouts of her mentor, she is also eager to earn his trust and respect. To that end, she has been poring over van Richten's research and learning about Strahd and Castle Ravenloft, with every intention of dispatching the vampire herself.

## Tarokka Deck

Ezmerelda keeps a [deck of tarokka cards](/3-Mechanics/CLI/decks/tarokka-deck-cos.md) in her wagon (chapter 11, area V1). Although the cards aren't magical, Ezmerelda can use them to perform a card reading for the characters (see chapter 1), like the one that can be performed by Madam Eva.

## Ezmerelda d'Avenir's Traits

### Ideal

"Evil that feeds on the innocent is the worst of all evils and must be destroyed."

### Bond

"My mentor and teacher, Dr. Rudolph van Richten, is like a father to me."

### Flaw

"I go where angels fear to tread."

```statblock
"name": "Ezmerelda d'Avenir (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "human"
"alignment": "Chaotic Good"
"ac": !!int "17"
"ac_class": "[+1 studded leather armor](/3-Mechanics/CLI/items/1-armor-xdmg.md)"
"hp": !!int "82"
"hit_dice": "11d8 + 33"
"modifier": !!int "4"
"stats":
  - !!int "14"
  - !!int "19"
  - !!int "16"
  - !!int "16"
  - !!int "11"
  - !!int "17"
"speed": "30 ft."
"saves":
  - "wisdom": !!int "3"
"skillsaves":
  - "name": "[Acrobatics](/3-Mechanics/CLI/skills.md#Acrobatics)"
    "desc": "+7"
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+9"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+3"
  - "name": "[Medicine](/3-Mechanics/CLI/skills.md#Medicine)"
    "desc": "+3"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+6"
  - "name": "[Performance](/3-Mechanics/CLI/skills.md#Performance)"
    "desc": "+6"
  - "name": "[Sleight of Hand](/3-Mechanics/CLI/skills.md#Sleight%20of%20Hand)"
    "desc": "+7"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+7"
  - "name": "[Survival](/3-Mechanics/CLI/skills.md#Survival)"
    "desc": "+6"
"senses": "passive Perception 16"
"languages": "Common, Elvish"
"cr": "8"
"traits":
  - "desc": "Ezmerelda is a 7th-level spellcaster. Her spellcasting ability is Intelligence\
      \ (spell save DC 14, +6 to hit with spell attacks). Ezmerelda has the following\
      \ wizard spells prepared:\n\n**Cantrips (at will):** [fire bolt](/3-Mechanics/CLI/spells/fire-bolt-xphb.md),\
      \ [light](/3-Mechanics/CLI/spells/light-xphb.md), [mage hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md),\
      \ [prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\n**1st\
      \ level (4 slots):** [protection from evil and good](/3-Mechanics/CLI/spells/protection-from-evil-and-good-xphb.md),\
      \ [magic missile](/3-Mechanics/CLI/spells/magic-missile-xphb.md), [shield](/3-Mechanics/CLI/spells/shield-xphb.md)\n\
      \n**2nd level (3 slots):** [darkvision](/3-Mechanics/CLI/spells/darkvision-xphb.md),\
      \ [knock](/3-Mechanics/CLI/spells/knock-xphb.md), [mirror image](/3-Mechanics/CLI/spells/mirror-image-xphb.md)\n\
      \n**3rd level (3 slots):** [clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md),\
      \ [lightning bolt](/3-Mechanics/CLI/spells/lightning-bolt-xphb.md), [magic circle](/3-Mechanics/CLI/spells/magic-circle-xphb.md)\n\
      \n**4th level (1 slots):** [greater invisibility](/3-Mechanics/CLI/spells/greater-invisibility-xphb.md)"
    "name": "Spellcasting"
  - "desc": "In addition to her magic armor and weapons, Ezmerelda has two [potions\
      \ of greater healing](/3-Mechanics/CLI/items/potion-of-greater-healing-xdmg.md),\
      \ six [vials of holy water](/3-Mechanics/CLI/items/holy-water-xphb.md), and\
      \ three wooden stakes."
    "name": "Special Equipment"
"actions":
  - "desc": "Ezmerelda makes three attacks: two with her +1 rapier and one with her\
      \ +1 handaxe or her silvered shortsword."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +8 to hit, reach 5 ft., one target. *Hit:* 9 (1d8\
      \ + 5) piercing damage."
    "name": "Rapier +1"
  - "desc": "*Melee  or Ranged Weapon Attack:* +6 to hit, reach 5 ft. or range 20/60\
      \ ft., one target. *Hit:* 6 (1d6 + 3) slashing damage."
    "name": "Handaxe +1"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 7 (1d6\
      \ + 4) piercing damage."
    "name": "Silvered Shortsword"
  - "desc": "Ezmerelda targets one creature that she can see within 30 feet of her.\
      \ The target must succeed on a DC 14 Wisdom saving throw or be cursed. While\
      \ cursed, the target has vulnerability to one type of damage of Ezmerelda's\
      \ choice. The curse lasts until ended with a [greater restoration](/3-Mechanics/CLI/spells/greater-restoration-xphb.md)\
      \ spell, a [remove curse](/3-Mechanics/CLI/spells/remove-curse-xphb.md) spell,\
      \ or similar magic. When the curse ends, Ezmerelda takes 3d6 psychic damage."
    "name": "Curse (Recharges after a Long Rest)"
  - "desc": "Ezmerelda targets one creature that she can see within 10 feet of her\
      \ and casts one of the following spells on the target (save DC 14), requiring\
      \ neither somatic nor material components to do so: animal friendship, charm\
      \ person, or hold person. If the target succeeds on the initial saving throw,\
      \ Ezmerelda is [blinded](/3-Mechanics/CLI/conditions.md#Blinded) until the end\
      \ of her next turn. Once a target succeeds on a saving throw against this effect,\
      \ it is immune to the Evil Eye power of all Vistani for 24 hours."
    "name": "Evil Eye (Recharges after a Short or Long Rest)"
"source":
  - "CoS"
"image": "ezmerelda-davenir-cos.webp"
```
^statblock

```statblock
statblock: true
name: Esmeralda d'Avenir
image: [[Esmeralda-d'Avenir.png]]
source: Fluch des Strahd
size: Mittelgroß
type: Humanoide
alignment: Chaotisch Gut
ac: 17
hp: 82
hit_dice: 11d8 + 33
speed: 9 Meter.
stats: [14, 19, 16, 16, 11, 17]
saves:
  - WEI: +3
skillsaves:
  - Akrobatik: +7
  - Arkane-Kunde: +6
  - Auftreten: +6
  - Fingerfertigkeit: +7
  - Heilkunde: +3
  - Heimlichkeit: +7
  - Motiv-erkennen: +3
  - Täuschen: +9
  - Überlebenskunst: +6
  - Wahrnehmung: +6
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: passive Wahrnehmung 16
languages: Gemeinsprache, Elfisch
cr: 8
bestiary: true
traits:
  - name: Besondere Ausrüstung
    desc: "Zusätzlich zu ihrer magischen Rüstung und Bewaffnung besitzt Esmerelda zwei [Tränke der mächtigen Heilung](Trank-der-mächtigen-Heilung.md), sechs Phiolen Weihwasser und drei Holzpflöcke"
    attack_bonus: 0
spells:
  - "Esmerelda ist eine Zauberwirkerin der 7. Stufe. Ihr Attribut zum Zauberwirken ist Intelligenz (Zauberrettungswurf-SG 14, +6 zum Treffen mit Zauberangriffen). Esmerelda hat die folgenden Magierzaubersprüche vorbereitet:"
  - Zaubertricks: Feuerpfeil, Licht, Magierhand, Taschenspielerei
  - Zaubergrad 1: [[Magisches Geschoss]], Schild, [Schutz vor Gut und Böse](Schutz-vor-Gut-und-Böse.md)
  - Zaubergrad 2: Dunkelheit, Klopfen, Spiegelbilder
  - Zaubergrad 3: Blitz, Hellsehen, Schutzkreis
  - Zaubergrad 4: Mächtige Unsichtbarkeit
actions:
  - name: Mehrfachangriff
    desc: "Esmerelda führt drei Angriffe aus: zwei mit ihrem [Rapier](Rapier.md) +1 und eine mit ihrem [Beil](Beil.md) +1 oder ihrem versilberten [Kurzschwert](Kurzschwert.md)."
  - name: Rapier +1
    desc: "_Nahkampf-Waffenangriff_: +8 zum Treffen, Reichweite 1,50 m, ein Ziel. Treffer: 9 (`1W8 + 5`) Stichschaden."
    attack_bonus: 8
    damage_dice: 1d8
    damage_bonus: 5
  - name: Beil +1
    desc: "_Nahkampf_- oder _Fernkampf-Waffenangriff_: +6 zum _Treffen_, Reichweite 1,50 m oder 6/18 m, ein Ziel. _Treffer_: 7 (`1W6 + 4`) Stichschaden"
    attack_bonus: 6
    damage_dice: 1d6
    damage_bonus: 4
  - name: Versilbertes Kurzschwert
    desc: "_Nahkampf-Waffenangriff_: +7 zum Treffen, Reichweite 1,50m, ein Ziel. _Treffer_: 7 (`1W6 + 4`) Stichschaden."
    attack_bonus: 7
    damage_dice: 1d6
    damage_bonus: 4
  - name: Fluch (Aufladung nach einer kurzen oder langen Rast)
    desc: "Esmerelda wählt eine Kreatur als Ziel, die sie innerhalb von 9 m um sich sehen kann. Dem Ziel muss ein Weisheits-Rettungswurf gegen SG 14 gelingen, oder es wird verflucht. Während der Fluch anhält, ist das Ziel verwundbar gegen eine Schadensart nach Esmereldas Wahl. Der Fluch hält an, bis er von einem Zauber [Fluch bannen](Fluch-brechen.md) oder ähnlicher Magie aufgehoben wird. Wenn der Fluch endet, erleidet Esmerelda `3W6` psychischen Schaden ."
  - name: Böser Blick (Aufladung nach einer kurzen oder langen Rast).
    desc: "Esmerelda wählt eine Kreatur als Ziel, die sie innerhalb von 3 m um sich sehen kann und wirkt einen der folgenden Zauber auf das Ziel (Rettungswurf-SG 14), sie benötigt weder körperliche noch Materialkomponenten dazu: [Tierfreundschaft](Tierfreundschaft.md), [Person bezaubern](Person-bezaubern.md) oder [Person festhalten](Person-festhalten). Wenn dem Ziel der erste Rettungswurf gelingt, ist Esmerelda bis zum Ende ihres nächsten Zugs blind. Sobald einem Ziel ein Rettungswurf gegen diesen Effekt gelingt, ist er für 24 Stunden gegen die Kraft Böser Blick aller Vistani immun."
```

$\quad$ **_Esmereldas Geheimnis._** Seit sie van Richten Lebewohl sagte, hat Esmerelda ein beträchtliches persönliches Vermögen angesammelt, von dem sie etwas zum Kauf eines Wohnwagens benutzte, um dort ihre Vampirtöter-Paraphernalien zu verstauen. Bei einem ihrer weniger erfolgreichen Abenteuer biss ein Werwolf ihr rechtes Bein unter dem Knie ab, und obwohl sie eine Ansteckung mit Lykanthropie vermeiden konnte, saß Esmerelda monatelang auf der Ersatzbank. Sie beauftragte einen Meisterhandwerker, um ihr eine Unterschenkel- und Fußprothese zu fertigen. Nach mehreren Versuchen lieferte er eine Prothese, die ihre Beweglichkeit wiederherstellte. Sie hat sich seitdem gut an die falsche Gliedmaße gewöhnt und gibt sich Mühe, sie nicht offen zu zeigen.
$\quad$ **_Die große Vampirjagd._** Während sie sich in der Gesellschaft einer Vistani-Karawane befand, hörte Esmerelda das Gerücht, dass Rudolph van Richten nach Barovia gegangen war, um den mächtigsten Vampir von allen zu erschlagen. Sie dachte, dass er vielleicht Hilfe brauchen könnte und reiste ihm nach, um nach Monaten endlich Strahds Domäne zu erreichen. Sie fuhr ihren Wagen nach Vallaki und erfuhr von einem alten Turm, der sie an van Richtens bevorzugte Lagerorte erinnerte. Als sie dort ankam, fand sie einige von van Richtens Habseligkeiten, aber von dem Vampirjäger selbst kein Zeichen. Obwohl sie nun bestrebt ist, den Aufenthaltsort ihres Mentors herauszufinden, ist sie auch begie rig, sein Vertrauen und seinen Respekt zu verdienen. Zu diesem Zweck brütete sie über van Richtens Nachforschungen und lernte alles über Strahd und Schloss Ravenloft, mit der Absicht, den Vampir selbst zu erledigen.
$\quad$ **_Tarokkablatt._** Esmerelda bewahrt einen Stapel Tarokkakarten in ihrem Wohnwagen auf (Kapitel 11, Bereich V1). Obwohl ihre Karten nicht magisch sind, kann Esmerelda sie benutzen, um die Karten für die Charaktere zu legen (siehe Kapitel 1), wie es Madame Eva tun kann.

## Charakteristika von Esmeralda d'Avenir
$\quad$ **_Ideal._** „Böses, das sich von den Unschuldigen nährt, ist das schlimmste von allen und muss vernichtet werden."
$\quad$ **_Bindung._** „Mein Mentor und Lehrer, Dr. Rudolph van Richten, ist wie ein Vater fü r mich."
$\quad$ **_Makel._** „Ich gehe dahin, wo Engel furchtsam weichen."
