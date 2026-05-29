---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Alustriel Silberhand
Kategorie: Humanoid
Größe: Mittelgroß
HG: 21
Habitat:
  - /
image: token/Alustriel-silverhand-veor.webp
status: WIP
linter-yaml-title-alias: Alustriel Silberhand
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/21
  - Monster/Typ/Humanoid/Magier
  - Monster/Typ/Humanoid/Mensch
  - Quelle/5e/veor
aliases:
  - Alustriel Silberhand
---
# Alustriel Silberhand
*Quelle: Vecna: Vorabend der Verdammnis S. 241*  

Alustriel Silberhand, die Strahlende Dame, ist schon seit Jahrhunderten eine einflussreiche Magiern und Verfechterin des Guten auf der Welt Toril. Sie ist eine der Sieben Schwestern - unsterbliche Töchter von Mystra, Göttin der Magie. Deren göttliche Energie trägt Alustriel in sich, was ihr erhebliche Macht über arkane Magie gewährt. 

Ihr jugendliches Erscheinungsbild als menschliche Frau mit silbernem Haar lässt in keiner Weise auf ihre übernatürlich lange Lebensspanne schließen. Meist trägt Alustriel lange Roben und führt einen Stab mit Einhornkopf - ihren _Stab von Silbrigmond_. 

## Persönlichkeit 

Alustriel möchte Freundlichkeit verbreiten, Tugend belohnen und im ganzen Multiversum eine Kultur des Mitgefühls etablieren. Sie ist gut darin, Allianzen zu schmieden und Bedrohungen der Kräfte des Guten zu eliminieren. Alustriel ist weit gereist und hat in allen Ebenen sichere Zufluchten geschaffen - zum Beispiel ihr Heiligtum in der Stadt Sigil. Persönlicher Ruhm und Reichtum interessieren sie nicht. Sie beeinflusst das Multiversum ruhig, aber stetig. 

## Geschichte

Wie andere Erwählte von Mystra ist auch Alustriel bestrebt, das Gewebe zu bewahren, die primäre Inkarnation der Magie, die Tori! durchdringt. Sie glaubt, dass das Gewebe jene begünstigt, die mit Gnade und Mitgefühl handeln und ein sicheres Leben für alle schaffen wollen, und dass es alle Anstrengungen stärkt, Unrecht zu beseitigen und das Böse zu bekämpfen. 

Nirgends sind Alustriel und ihre Taten besser bekannt als in den Silbermarschen und deren Hauptstadt Silbrigmond. Alustriel regiert seitJahrhunderten in Silbrigmond, einst getarnt als Magierin Elue Dualen, später in ihrer wahren Gestalt. Sie hat geholfen, Silbrigmonds berühmte Mondbrücke zu errichten, und hat die Schule der Herrin mitgegründet - die erste Schule Faeruns, an der Magier nicht als Lehrlinge, sondern als Studenten unterrichtet wurden. 

Alustriel ist vor über hundert Jahren von ihrem Amt als Hochmagierin Silbrigmonds zurückgetreten. Heute regiert ihr Sohn Methrammar Aerasume die Stadt und führt das Erbe seiner Mutter fort. 

Alustriel hat vor und nach ihrer Amtszeit als Silbrigmonds Hochmagierin zahllose Abenteuer bestanden. Sie ist mit berühmten Abenteurern wie Drizzt Do'Urden befreundet, hat mit bekannten Organisationen wie den Harfnern zusammengearbeitet und dem Bösen schon oft einen Strich durch die Rechnung gemacht. 

```statblock
name: Alustriel Silberhand
image: token/alustriel-silverhand-veor.webp
source:
  - VEoR
size: Mittelgroß
type: Humanoid
subtype: Mensch, Magier
alignment: Chaotisch Gut
ac: 15
ac_class: 18 mit <STATBLOCK-MARKDOWN-LINK>Magierrüstung-phb|Magierrüstung<STATBLOCK-MARKDOWN-LINK>
hp: 272
hit_dice: 32d8 + 128
modifier: 5
stats:
  - 12
  - 20
  - 18
  - 24
  - 23
  - 22
speed: 9 m
saves:
  - Konstitution: 11
  - Intelligenz: 14
  - Weisheit: 13
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Arkane%20Kunde|Arkane Kunde<STATBLOCK-MARKDOWN-LINK>
    desc: "+14"
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Geschichte|Geschichte<STATBLOCK-MARKDOWN-LINK>
    desc: "+14"
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Motiv%20erkennen|Motiv erkennen<STATBLOCK-MARKDOWN-LINK>
    desc: "+13"
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Religion|Religion<STATBLOCK-MARKDOWN-LINK>
    desc: "+14"
damage_resistances: Gleißend
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|Bezaubert<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Erschöpfung|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: passive Wahrnehmung 16
languages: Drakonisch, Elfisch, Gemeinsprache
cr: "21"
traits:
  - name: Besondere Ausrüstung
    desc: Alustriel trägt einen magischen Stab, der als Stab von Silbrigmond bekannt ist. In den Händen jeder anderen Person ist der Stab von Silbrigmond ein <STATBLOCK-MARKDOWN-LINK>Stab_der_Macht-dmg|Stab der Macht<STATBLOCK-MARKDOWN-LINK>.
  - name: Legendäre Resistenz (3-mal täglich)
    desc: Wenn ihr Rettungswurf scheitert, kann Alustriel den Wurf in einen Erfolg verwandeln.
  - name: Ohr der Erwählten
    desc: Wann immer eine Kreatur auf derselben Existenzebene wie Alustriel deren Namen ausspricht, hört Alustriel ihren Namen und die nächsten neun Worte, die die Kreatur spricht.
actions:
  - name: Mehrfachangriff
    desc: Alustriel führt drei Angriffe mit dem Stab von Silbrigmond oder zwei Rügender-Strahl-Angriffe aus.
  - name: Stab von Silbrigmond
    desc: "*Nahkampf-Waffenangriff:* +12 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 14 (2d8 + 5) Wuchtschaden plus 38 (7d10) gleißender Schaden."
  - name: Rügender Strahl
    desc: "*Fernkampf-Zauberangriff:* +14 zum Treffen, Reichweite 36 m, ein Ziel. *Treffer:* 65 (9d12 + 7) Energieschaden, und wenn das Ziel eine Kreatur ist, muss es einen SG-22-Charisma-Rettungswurf ausführen. Scheitert der Wurf, so ist das Ziel bis zum Beginn von Alustriels nächstem Zug <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Kampfunfähig|kampfunfähig<STATBLOCK-MARKDOWN-LINK>. Bei einem erfolgreichen Rettungswurf ist die Bewegungsrate des Ziels bis zum Beginn von Alustriels nächstem Zug um drei Meter verringert"
  - name: Silbernes Lodern (erfordert Silberfeuer)
    desc: Alustriel beschwört Silberfeuer in einem Kegel von 18 Metern. Jede Kreatur in diesem Bereich muss einen SG-22-Geschicklichkeits-Rettungswurf ausführen. Scheitert der Wurf, so erleidet sie 77 (14d10) gleißenden Schaden, anderenfalls die Hälfte. Außerdem erhält Alustriel oder eine Kreatur ihrer Wahl im Abstand von bis zu 18 Metern von ihr 10 (3d6) Trefferpunkte zurück.
  - name: Zauberwirken
    desc: |-
      Alustriel wirkt einen der folgenden Zauber mit Intelligenz als Attribut zum Zauberwirken (Zauberrettungswurf-SG 22):

      **Beliebig oft:** <STATBLOCK-MARKDOWN-LINK>Magie_entdecken-phb|Magie entdecken<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Magierhand-phb|Magierhand<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK><STATBLOCK-MARKDOWN-LINK> Detect Magic, Mage Armor (self only), Mage Hand

      **jeweils 2/Tag:** Detect Thoughts, Dispel Magic, Tongues

      **jeweils 1/Tag:** Telepathy, Teleport, Time Stop
bonus_actions:
  - name: Silberfeuer (2-mal täglich)
    desc: Strahlendes Silberfeuer umhüllt und ermächtigt Alustriel. Das Silberfeuer bleibt bestehen, bis eine Stunde vergangen ist, Alustriel kampfunfähig wird oder sie das Feuer mit einer weiteren Bonusaktion löscht. Solange Alustriel in Silberfeuer gehüllt ist, verfügt sie über Wahrer Blick im Abstand von bis zu neun Metern und kann ihre Silbernes-Lodern-Aktion verwenden. Außerdem ist sie vor Magie geschützt, die ihre Gesinnung, ihren Kreaturentyp, ihre Gedanken oder ihre Aufrichtigkeit erkunden würde.
reactions:
  - name: Strahlender Gegenzauber
    desc: Alustriel unterbricht eine Kreatur im Abstand von bis zu 18 Metern, die sie sehen kann und die einen Zauber wirkt. Wenn es sich um einen Zauber des höchstens 5. Grades handelt, schlägt er fehl und hat keine Wirkung. Bei einem Zauber ab dem 6. Grad führt Alustriel einen Intelligenzwurf (SG 10 plus Zaubergrad) aus. Bei einem Erfolg schlägt der Zauber fehl und hat keine Wirkung. Unabhängig vom Grad des Zaubers erleidet der Zauberwirker 11 (2d10) gleißenden Schaden, wenn der Zauber fehlschlägt.
```
^statblock