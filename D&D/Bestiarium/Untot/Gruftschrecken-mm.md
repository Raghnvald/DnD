---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Gruftschrecken
Kategorie: Untoter
Größe: Mittelgroß
HG: 2
Habitat:
  - Stadt
  - Sumpf
  - Unterreich
  - Wüste
image: token/wight.webp
status: completed
tags:
  - Monster/Größe/Mittelgroß
  - Monster/Habitat/Stadt
  - Monster/Habitat/Sumpf
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wüste
  - Monster/HG/3
  - Monster/Typ/Untote
  - Quelle/5e/mm
aliases:
  - Wight
linter-yaml-title-alias: Wight
---
# Gruftschrecken
*Quelle: Monsterhandbuch S. 153. Verfügbar im <span title='Systems Reference Document (5.1)'>SRD</span> und dem Grundregelwerk (2014)*  

Der Begriff „Gruftschrecken" bezeichnet böse Untote, die einst Sterbliche waren, die von dunklen Begierden und Eitelkeit angetrieben waren. Wenn der Tod das Herz einer solchen Kreatur zum Stillstehen bringt und ihren lebenden Atem raubt, stößt ihre Seele einen Ruf nach Gnade aus, den der Dämonenfürst Orcus oder ein anderer böser Gott der Unterwelt vernimmt. Die Kreatur bittet darum, ein Untoter zu werden, und führt dafür Krieg gegen die Lebenden. Wenn eine dunkle Macht auf den Ruf antwortet, wird dem Geist der Untod gewährt, damit er seine eigene bösartige Agenda weiter verfolgen kann

Gruftschrecken besitzen die Erinnerungen und Ziele ihres ehemaligen lebenden Selbst. Sie gehorchen dem Ruf der dunklen Wesenheit, die sie in Untote verwandelt hat, und schwören Eide, um ihren neuen Fürsten zu besänftigen und gleichzeitig ihre Selbstständigkeit zu wahren. Ein Gruftschrecken wird niemals müde und kann sein Ziel unerbittlich und ohne Ablenkung verfolgen.

## Lebensesser

Gruftschrecken sind weder tot noch lebendig, und existieren in einem Übergangsstatus zwischen einer Welt und der nächsten. Der helle Funken, den sie im Leben hatten, ist nicht mehr, und an seiner Stelle ist eine Sehnsucht getreten, den Funken des Lebens in allen lebenden Dingen zu verschlingen. Wenn ein Gruftschrecken angreift, leuchtet diese Lebensessenz für seine dunklen Augen wie weißglühende Kohlen, und die kalte Berührung des Gruftschrecken kann den Funken durch Fleisch, Kleidung und Rüstung heraus ziehen. 

## Schatten des Grabes

Gruftschrecken fliehen am Tage aus der Welt, weg vom Licht der Sonne, die sie hassen. Sie ziehen sich in Grabhügel, Krypten und Grüfte zurück, wo sie hausen. Ihre Behausungen sind stille, trostlose Orte, umgeben von toten Pflanzen, sichtlich geschwärzt und von Vögeln und Tieren gemieden.

Humanoide, die von einem Gruftschrecken erschlagen werden, können sich als Zombies unter seiner Kontrolle erheben. Motiviert vom Hunger nach lebenden Seelen und getrieben von der gleichen Gier nach Macht, die sie als Untote erweckt hat, dienen einige Gruftschrecken als Schocktruppen für böse Anführer, darunter auch Todesalben. Als Soldaten sind sie imstande zu planen, doch tun sie es selten, da sie sich auf ihren Hunger nach Zerstörung verlassen, um alle Kreaturen zu vernichten, die in ihrem Weg stehen. 

## Untote Natur

Ein Gruftschrecken braucht keine Luft, keine Nahrung, kein Wasser und keinen Schlaf. 

```statblock
name: Gruftschrecken
image: Untot/token/wight.webp
source:
  - MM
size: Mittelgroß
type: Untot
alignment: neutral böse
ac: 14
ac_class: <STATBLOCK-MARKDOWN-LINK>Gegenstände/Beschlagene_Lederrüstung-phb|Beschlagene Lederrüstung<STATBLOCK-MARKDOWN-LINK>
hp: 45
hit_dice: 6d8 + 18
modifier: 2
stats:
  - 15
  - 14
  - 16
  - 10
  - 13
  - 15
speed: 9 m
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Heimlichkeit|Heimlichkeit<STATBLOCK-MARKDOWN-LINK>
    desc: "+4"
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>
    desc: "+3"
damage_resistances: Nekrotisch; Wucht-, Stich- und Hiebschaden durch nichtmagische Angriffe, wenn die Waffe nicht versilbert ist.
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Erschöpfung|erschöpft<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 13
languages: die Sprachen, die er im Leben kannte 
cr: "3"
environment: Stadt, Sumpf, Unterreich, Wüste
traits:
  - name: Empfindlich gegenüber Sonnenlicht
    desc: Solange sich der Gruftschrecken im Sonnenlicht befindet, hat er einen Nachteil bei Angriffswürfen und Würfen auf Weisheit (<STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>) die Sicht verwenden.
actions:
  - name: Mehrfachangriff
    desc: Der Gruftschrecken führt zwei Langschwert-Angriffe oder zwei Langbogen-Angriffe durch. Er kann Lebensentzug anstelle eines Langschwert-Angriffs verwenden. 
  - name: Lebensentzug
    desc: |-
      *Nahkampf-Waffenangriff:* +4 zum Treffen, Reichweite 1,5 m, ein Ziel. Treffer: 5 (1W6 + 2) nekrotischer Schaden. Das Ziel muss einen Konstitutionsrettungswurf gegen SG 13 ablegen, sonst werden seine maximalen Trefferpunkte um den erlittenen Schaden verringert. Diese Verringerung hält an, bis das Ziel eine lange Rast durchführt. Das Ziel stirbt, wenn dieser Effekt es auf 0 maximale Trefferpunkte reduziert.

      Ein Humanoider, der von diesem Angriff getötet wird, erhebt sich 24 Stunden später als <STATBLOCK-MARKDOWN-LINK>Untot/Zombie-mm|Zombie<STATBLOCK-MARKDOWN-LINK> unter der Kontrolle des Gruftschrecken, es sei denn, der Humanoide wird zum Leben erweckt oder sein Körper zerstört. Der Gruftschrecken kann nicht mehr als zwölf Zombies auf einmal unter seiner Kontrolle haben.
  - name: Langschwert
    desc: "*Nahkampf-Waffenangriff:* +4 zum Treffen, Reichweite 1,5 m, ein Ziel. Treffer: 6 (1W8 + 2) Hiebschaden, oder 7 (2W10 +2) Hiebschaden, wenn die Waffe mit zwei Händen verwendet wird."
  - name: Langbogen
    desc: "*Fernkampf-Waffenangriff:* +4 zum Treffen, Reichweite 45/180 m, ein Ziel. Treffer: 6 (1W8 + 2) Stichschaden."
```
^statblock