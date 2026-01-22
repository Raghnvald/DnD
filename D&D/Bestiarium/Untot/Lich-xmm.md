---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Lich
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Jedes
  - Monster/HG/21
  - Monster/Typ/Untote/wizard
  - Quelle/5e/xmm
aliases:
  - Lich
linter-yaml-title-alias: Lich
---
# [Lich](3-Mechanics\CLI\bestiary\undead/lich-xmm.md)
*Source: Monster Manual (2024) p. 196. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Lich

*Deathless Master of Magic*

- **Habitat.** Any  
- **Treasure.** [Arcana](/3-Mechanics/CLI/tables/random-magic-items-arcana.md)  

Some nefarious magic-users carry out forbidden necromantic rituals that sever their souls from their bodies to turn themselves into liches, masters of magic and undeath. With their souls preserved in hidden relics, liches puppet their own corpses as they pursue ambitions free from mortal bonds.

Liches possess exceptional cunning and magical prowess, and they use their unnatural immortality to pursue arcane secrets few could grasp in a single life. Uncanny agendas lead them to plumb the secrets of life, the multiverse, godhood, and less fathomable topics. Careless of mortal lives or desires, liches go to any lengths to achieve their goals.

A lich's age and origin influences its form. Older liches appear as little more than brittle skeletons clad in the rotten finery of forgotten empires, while younger liches more closely resemble living creatures and are clad in contemporary garb. Many cloak themselves in illusions of their idealized mortal forms.

Although liches don't fear death, they're not free from the ravages of time. Over ages, some liches lose their connection to time and the physical world, degenerating into demiliches.

### Lich Spirit Jars

The process of becoming a lich is involved, dangerous, and unique to each would-be lich. If the rite succeeds, the lich's soul is bound to a spirit jar, a specially prepared magical repository. This relic anchors the lich's spirit to the world and preserves it should the lich's body be destroyed. A lich can be slain only if its spirit jar is ruined. As such, a lich goes to great lengths to hide and protect its spirit jar.

Spirit jars are typically small, well-made objects that were meaningful to a lich in life. Roll on or choose a result from the Lich Spirit Jar table to inspire where a lich hides its soul.

**Lich Spirit Jars**

| dice: 1d8 | The Lich's Spirit Jar Is... |
|-----------|-----------------------------|
| 1 | A bottle or puzzle box inscribed with sigils. |
| 2 | A contract folded into a paper figure. |
| 3 | The first magic item the lich created. |
| 4 | A hollow figurine of a deity or monster. |
| 5 | An hourglass with its sands floating in stasis. |
| 6 | A locket or signet ring with a noble crest. |
| 7 | A rune-etched egg. |
| 8 | The skull of the lich's mentor. |
^lich-spirit-jars

### Lich Lairs

Liches create secluded libraries of magical lore and arcane laboratories hidden within extraplanar bastions, fortresses with cursed reputations, or other such deadly sanctuaries.

> [!quote] A quote from Rudolph van Richten  
> 
> Ambition can become an addiction of the mind and spirit. It builds beyond a driving flame into an insidious inferno that burns a mage hollow until only the desire for more magical power remains

```statblock
"name": "Lich (XMM)"
"size": "Medium"
"type": "undead"
"subtype": "wizard"
"alignment": "Neutral Evil"
"ac": !!int "20"
"hp": !!int "315"
"hit_dice": "42d8 + 126"
"modifier": !!int "17"
"stats":
  - !!int "11"
  - !!int "16"
  - !!int "16"
  - !!int "21"
  - !!int "14"
  - !!int "16"
"speed": "30 ft."
"saves":
  - "dexterity": !!int "10"
  - "constitution": !!int "10"
  - "intelligence": !!int "12"
  - "wisdom": !!int "9"
"skillsaves":
  - "name": "[Arcana](/3-Mechanics/CLI/skills.md#Arcana)"
    "desc": "+19"
  - "name": "[History](/3-Mechanics/CLI/skills.md#History)"
    "desc": "+12"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+9"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+9"
"damage_resistances": "cold, lightning"
"damage_immunities": "necrotic, poison"
"condition_immunities": "[charmed](/3-Mechanics/CLI/conditions.md#Charmed), [exhaustion](/3-Mechanics/CLI/conditions.md#Exhaustion),\
  \ [frightened](/3-Mechanics/CLI/conditions.md#Frightened), [paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed),\
  \ [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)"
"senses": "[truesight](/3-Mechanics/CLI/senses.md#Truesight) 120 ft., passive Perception\
  \ 19"
"languages": "all"
"cr": "21"
"traits":
  - "desc": "If the lich fails a saving throw, it can choose to succeed instead."
    "name": "Legendary Resistance (4/Day, or 5/Day in Lair)"
  - "desc": "If destroyed, the lich reforms in 1d10 days if it has a spirit jar, reviving\
      \ with all its [Hit Points](/3-Mechanics/CLI/variant-rules/hit-points-xphb.md).\
      \ The new body appears in an unoccupied space within the lich's lair."
    "name": "Spirit Jar"
"actions":
  - "desc": "The lich makes three attacks, using Eldritch Burst or Paralyzing Touch\
      \ in any combination."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +12, reach 5 ft. or range 120 ft. *Hit:*\
      \ 31 (4d12 + 5) Force damage."
    "name": "Eldritch Burst"
  - "desc": "*Melee Attack Roll:* +12, reach 5 ft. *Hit:* 15 (3d6 + 5) Cold damage,\
      \ and the target has the [Paralyzed](/3-Mechanics/CLI/conditions.md#Paralyzed)\
      \ condition until the start of the lich's next turn."
    "name": "Paralyzing Touch"
  - "desc": "The lich casts one of the following spells, using Intelligence as the\
      \ spellcasting ability (spell save DC 20):\n\n**At will:** [Detect Magic](/3-Mechanics/CLI/spells/detect-magic-xphb.md),\
      \ [Detect Thoughts](/3-Mechanics/CLI/spells/detect-thoughts-xphb.md), [Dispel\
      \ Magic](/3-Mechanics/CLI/spells/dispel-magic-xphb.md), [Fireball](/3-Mechanics/CLI/spells/fireball-xphb.md)\
      \ (level 5 version), [Invisibility](/3-Mechanics/CLI/spells/invisibility-xphb.md),\
      \ [Lightning Bolt](/3-Mechanics/CLI/spells/lightning-bolt-xphb.md) (level 5\
      \ version), [Mage Hand](/3-Mechanics/CLI/spells/mage-hand-xphb.md), [Prestidigitation](/3-Mechanics/CLI/spells/prestidigitation-xphb.md)\n\
      \n**2/day each:** [Animate Dead](/3-Mechanics/CLI/spells/animate-dead-xphb.md),\
      \ [Dimension Door](/3-Mechanics/CLI/spells/dimension-door-xphb.md), [Plane Shift](/3-Mechanics/CLI/spells/plane-shift-xphb.md)\n\
      \n**1/day each:** [Chain Lightning](/3-Mechanics/CLI/spells/chain-lightning-xphb.md),\
      \ [Finger of Death](/3-Mechanics/CLI/spells/finger-of-death-xphb.md), [Power\
      \ Word Kill](/3-Mechanics/CLI/spells/power-word-kill-xphb.md), [Scrying](/3-Mechanics/CLI/spells/scrying-xphb.md)"
    "name": "Spellcasting"
"reactions":
  - "desc": "The lich casts [Counterspell](/3-Mechanics/CLI/spells/counterspell-xphb.md)\
      \ or [Shield](/3-Mechanics/CLI/spells/shield-xphb.md) in response to the spell's\
      \ trigger, using the same spellcasting ability as Spellcasting.\n"
    "name": "Protective Magic"
"regional_effects":
  - "desc": "The region containing a lich's lair is warped by its presence, creating\
      \ the following effects:\n\n- **All-Seeing.** While in its lair, the lich can\
      \ cast [Clairvoyance](/3-Mechanics/CLI/spells/clairvoyance-xphb.md), requiring\
      \ no spell components and using the same spellcasting ability as its Spellcasting\
      \ action.  \n- **Inevitable Siphon.** Whenever a Humanoid dies within 1 mile\
      \ of the lair, its soul is immediately consumed by the lich. A Humanoid whose\
      \ soul is consumed in this way can be brought back to life only by a True Resurrection\
      \ or [Wish](/3-Mechanics/CLI/spells/wish-xphb.md) spell.  \n\nIf the lich is\
      \ destroyed or moves its lair elsewhere, these effects end immediately. These\
      \ effects resume if the lich gains a new body (see its Spirit Jar trait)."
    "name": ""
"legendary_description": "Legendary Action Uses: 3 (4 in Lair). Immediately after\
  \ another creature's turn, the lich can expend a use to take one of the following\
  \ actions. The lich regains all expended uses at the start of each of its turns."
"legendary_actions":
  - "desc": "The lich teleports up to 60 feet to an unoccupied space it can see, and\
      \ each creature within 10 feet of the space it left takes 11 (2d10) Necrotic\
      \ damage."
    "name": "Deathly Teleport"
  - "desc": "*Constitution Saving Throw:* DC 20, each creature that isn't an Undead\
      \ in a 20-foot [Emanation](/3-Mechanics/CLI/variant-rules/emanation-area-of-effect-xphb.md)\
      \ originating from the lich. *Failure:* 31 (9d6) Necrotic damage. *Success:*\
      \ Half damage. *Failure or Success:* The lich can't take this action again until\
      \ the start of its next turn."
    "name": "Disrupt Life"
  - "desc": "The lich casts [Fear](/3-Mechanics/CLI/spells/fear-xphb.md), using the\
      \ same spellcasting ability as Spellcasting. The lich can't take this action\
      \ again until the start of its next turn.\n"
    "name": "Frightening Gaze"
"source":
  - "XMM"
"image": "/3-Mechanics/CLI/bestiary/undead/token/lich-xmm.webp"
```
^statblock

## Environment

any

_Unsterbliche Meister der Magie_

>**Habitat:** Planar (Untere Ebenen)
>**Beute:** Arkanes

![](lich-2024.webp)

Einige ruchlose Magieanwender führen verbotene nekromantische Rituale durch, bei denen sie ihre Seelen von ihren Körpern trennen und sich in Lichs verwandeln, Meister der Magie und des Untodes. Mit ihren Seelen, die in verborgenen Reliquien aufbewahrt werden, sind Lichs Marionetten ihrer eigenen Leichen, während sie ihre Ambitionen frei von sterblichen Bindungen verfolgen.

Lichs verfügen über außergewöhnliche Gerissenheit und magische Fähigkeiten, und sie nutzen ihre unnatürliche Unsterblichkeit, um arkane Geheimnisse zu ergründen, die nur wenige in einem einzigen Leben begreifen könnten. Unheimliche Absichten führen sie dazu, die Geheimnisse des Lebens, des Multiversums, der Gottheit und weniger ergründbare Themen auszuloten. Ohne Rücksicht auf das Leben oder die Wünsche der Sterblichen gehen Lichs bis zum Äußersten, um ihre Ziele zu erreichen.

Das Alter und die Herkunft eines Lichs beeinflussen seine Form. Ältere Lichs sehen aus wie brüchige Skelette in den verrotteten Gewändern vergessener Reiche, während jüngere Lichs eher lebenden Kreaturen ähneln und in moderne Gewänder gekleidet sind. Viele hüllen sich in Illusionen ihrer idealisierten sterblichen Gestalt.

Obwohl Lichs den Tod nicht fürchten, sind sie nicht frei vom Zahn der Zeit. Im Laufe der Zeit verlieren einige Lichs ihre Verbindung zur Zeit und zur physischen Welt und degenerieren zu Demilichs.

>[!quote] Rudolph van Richten, <br>Van Richten's Leitfaden für Lichs
>Ehrgeiz kann zu einer Sucht des Geistes und der Seele werden. Er entwickelt sich über eine treibende Flamme hinaus zu einem heimtückischen Inferno, das einen Magier aushöhlt, bis nur noch das Verlangen nach mehr magischer Macht übrig bleibt.

## Lich-Geist-Gefäße
Der Prozess, ein Lich zu werden, ist kompliziert, gefährlich und für jeden angehenden Lich einzigartig. Wenn der Ritus erfolgreich ist, wird die Seele des Lichs an einen Geistkrug gebunden, einen speziell angefertigten magischen Behälter. Dieses Relikt verankert den Geist des Lichs in der Welt und bewahrt ihn, sollte der Körper des Lichs zerstört werden. Ein Lich kann nur getötet werden, wenn sein Geistergefäß zerstört ist. Aus diesem Grund tut ein Lich alles, um seinen Geistertopf zu verstecken und zu schützen.

Geistergefäße sind in der Regel kleine, gut gefertigte Gegenstände, die für den Lich zu Lebzeiten von Bedeutung waren. Würfle auf oder wähle ein Ergebnis aus der Tabelle Lich-Geistesgefäß, um zu erfahren, wo ein Lich seine Seele versteckt.

#### Lich-Geist-Gefäße

| 1d8 | Das Geist-Gefäß des Lichs ist...                              |
| --- | ------------------------------------------------------------- |
| 1   | Eine Flasche oder Rätselbox, die mit Siegeln beschriftet ist. |
| 2   | Ein Vertrag, der zu einer Papierfigur gefaltet ist.           |
| 3   | Der erste magische Gegenstand, den der Lich erschaffen hat.   |
| 4   | Eine hohle Figur einer Gottheit oder eines Monsters.          |
| 5   | Eine Sanduhr, deren Sand in der Stase schwebt.                |
| 6   | Ein Medaillon oder Siegelring mit einem edlen Wappen.         |
| 7   | Ein runengeätztes Ei.                                         |
| 8   | Der Schädel des Mentors des Lichs.                            |

## Lich-Verstecke
Lichs erschaffen abgelegene Bibliotheken magischer Überlieferungen und arkane Laboratorien, die in außerplanetarischen Bastionen, Festungen mit verfluchtem Ruf oder anderen tödlichen Heiligtümern versteckt sind.

Die Region, in der sich die Höhle eines Lichs befindet, wird durch seine Anwesenheit verzerrt, was die folgenden Effekte hervorruft:

**Alles sehend.** Während er sich in seiner Höhle aufhält, kann der Lich Hellsichtigkeit wirken, wofür er keine Zauberkomponenten benötigt und dieselbe Zauberfähigkeit wie seine Aktion Zaubern verwendet.

**Unvermeidlicher Siphon.** Immer wenn ein Humanoid im Umkreis von 1 Meile um die Höhle stirbt, wird seine Seele sofort von dem Lich verzehrt. Ein Humanoid, dessen Seele auf diese Weise verzehrt wird, kann nur durch einen Zauber [Wahre Auferstehung](Wahre-Auferstehung.md) oder [Wunsch](Wunsch.md) wieder zum Leben erweckt werden.

Wird der Lich zerstört oder verlegt er sein Versteck an einen anderen Ort, enden diese Effekte sofort. Diese Effekte werden wieder aufgenommen, wenn der Lich einen neuen Körper erhält (siehe seine Eigenschaft Geisterkrug).

```statblock
name: Lich (2024)
image: pictures/lich-2024.webp
source: Monsterhandbuch 2024
size: Mittelgroß
type: Untoter
subtype: (Magier)
alignment: Neutral Böse
ac: 20
hp: 315
hit_dice: 42d8 + 126
ini: +17 (27)
speed: 9 Meter
stats: [11, 16, 16, 21, 14, 16]
saves:
  - STR: +0
  - GES: +10
  - KON: +10
  - INT: +12
  - WEI: +9
  - CHA: +3
skillsaves:
  - Arkane Kunde: 19
  - Geschichte: 12  
  - Motiv erkennen: 9
  - Wahrnehmung: 9
damage_vulnerabilities: ""
damage_resistances: "Blitz, Kälte"
damage_immunities: "Gift, Nekrotisch"
condition_immunities: "[[Anhang PH-A#Bezaubert|Bezaubert]], [[Anhang PH-A#Erschöpfung|Erschöpfung]], [[Anhang PH-A#Gelähmt|Gelähmt]], [[Anhang PH-A#Verängstigt|Verängstigt]], [[Anhang PH-A#Vergiftet|Vergiftet]]"
gear: [Materialkomponentenbeutel](Materialkomponentenbeutel.md)
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Wahrer Blick|Wahrer Blick]] 36 Meter, passive Wahrnehmung 19
languages: Alle
cr: 21
bestiary: true
traits:
  - name: Legendäre Resistenz (4/Tag, oder 5/Tag im Versteck).
    desc: "Wenn der Rettungswurf des Lichs scheitert, kann dieser den Wurf in einen Erfolg verwandeln."
  - name: Seelengefäß.
    desc: "Wenn der Lich zerstört wird, jedoch über ein Seelengefäß verfügt, erhält er in 1W10 Tagen einen neuen Körper mit allen Trefferpunkten und wird wieder aktiv. Der neue Körper erscheint an einem freien Ort im Versteck des Lichs."
actions:
  - name: Mehrfachangriff.
    desc: "Der Lich führt drei Angriffe aus, wobei er Schauriger Strahl und Paralyzing Touch in beliebiger Kombination ausführt."
  - name: Schauriger Strahl.
    desc: "_Nahkampf- oder Fernkampfangriffswurf:_ +12, Reichweite 1,5m oder 36m  _Treffer:_ 31 (4d12 + 5) Energieschaden."
    attack_bonus: 12
    damage_dice: 4d12
    damage_bonus: 5
  - name: Lähmende Berührung.
    desc: "_Nahkampfangriffswurf:_ +12, Reichweite 1,5m _Treffer:_ 31 (4d12 + 5) Energieschaden."
    attack_bonus: 12
    damage_dice: 4d12
    damage_bonus: 5
  - name: Zauberwirken.
    desc: "Der Lich wirkt einen der folgenden Zauber. Seine Zauberfertigkeit ist Intelligenz (Zauber-Rettungswurf SG 20):"
  - name: Beliebig oft
    desc: "[Blitz](Blitz.md) (Zaubergrad 5), [Feuerball](Feuerball.md) (Zaubergrad 5), [Gedanken wahrnehmen](Gedanken-wahrnehmen.md), [Magie bannen](Magie-bannen.md), [Magie entdecken](Magie-entdecken.md), [Magierhand](Magierhand.md), [Taschenspielerei](Taschenspielerei.md), [Unsichtbarkeit](Unsichtbarkeit.md)"
  - name: je 2-mal täglich.
    desc: "[Dimensionstür](Dimensionstür.md), [Ebenenwechsel](Ebenenwechsel.md) [Tote beleben](Tote-beleben.md)"
  - name: je 1-mal täglich.
    desc: "[Ausspähung](Ausspähung.md), [Finger des Todes](Finger-des-Todes.md) [Kugelblitz](Kugelblitz.md), [Wort der Macht: Tod](Wort-der-Macht-Tod.md)"
reactions:
  - name: Schützende Magie
    desc: "Der Lich wirkt [Gegenzauber](Gegenzauber.md) oder [Schild](Zauber/Schild.md) als Reaktion auf den Auslöser des Zaubers und nutzt dabei dieselbe Zauberfertigkeit wie beim Zauberwirken."
legendary_description: "Der Lich kann drei legendäre Aktionen (4 in seinem Versteck) entsprechend den unten aufgeführten Optionen ausführen. Er kann jeweils nur eine legendäre Aktionsmöglichkeit und nur am Ende des Zugs einer anderen Kreatur ausführen. Der Lich erhält verbrauchte legendäre Aktionen am Anfang seines Zugs zurück."
legendary_actions:
  - name: Furchteinflößender Blick.
    desc: "Der Lich wirkt den Zauber [Furcht](Furcht.md), wobei er die gleiche Zauberfertigkeit wie beim Zauberwirken verwendet. Der Lich kann diese Aktion erst wieder zu Beginn seines nächsten Zuges ausführen."
  - name: Lebensunterbrechung.
    desc: "_Konstitutions-Rettungswurf_: SG 20, jede nicht-untote Kreatur in einem 6m Radius um den Lich herum. _Fehlschlag_: 31 (9d6) nekrotischer Schaden. _Erfolg_: Halber Schaden. _Fehlschlag oder Erfolg_: Der Lich kann diese Aktion bis zum Ende seiner nächsten Runde nicht erneut einsetzen."
  - name: Tödliche Teleportation.
    desc: "Der Lich teleportiert sich bis zu 18 Meter an einen unbesetzten Ort, den er sehen kann, und jede Kreatur im Umkreis von 3 Metern von dem Ort, den er verlassen hat, erleidet 11 (2d10) nekrotischen Schaden."
```