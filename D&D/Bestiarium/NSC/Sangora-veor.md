---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Sangora
Kategorie: Untoter (Gestaltwandler)
Größe: Mittelgroß
HG: 13
Habitat: /
image: token/sangora-veor.webp
status: completed
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/13
  - Monster/Typ/Untote/shapechanger
  - Quelle/5e/veor
aliases:
  - Sangora
linter-yaml-title-alias: Sangora
---
# Sangora
*Quelle: Vecna: Vorabend der Verdammnis*  

```statblock
name: Sangora
image: token/sangora-veor.webp
source:
  - VEoR
size: Mittelgroß
type: Untot
subtype: Gestaltwandler
alignment: rechtschaffen böse
ac: 16
ac_class: natürliche Rüstung
hp: 144
hit_dice: 17d8 + 68
modifier: 4
stats:
  - 18
  - 18
  - 18
  - 17
  - 15
  - 18
speed: 9 m
saves:
  - Geschicklichkeit: 9
  - Weisheit: 7
  - Charisma: 9
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Heimlichkeit|Heimlichkeit<STATBLOCK-MARKDOWN-LINK>
    desc: "+9"
  - name: <STATBLOCK-MARKDOWN-LINK>Fertigkeiten-phb#Wahrnehmung|Wahrnehmung<STATBLOCK-MARKDOWN-LINK>
    desc: "+7"
damage_resistances: Nekrotisch; Wucht-, Stich- und Hiebschaden durch nichtmagische Angriffe
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 36 m, passive Wahrnehmung 17
languages: die Sprachen, die sie im Leben kannte
cr: "13"
traits:
  - name: Gestaltwandler
    desc: |-
      Wenn sich Sangora nicht im Sonnenlicht oder fließendem Wasser befindet, kann sie ihre Aktion verwenden, um sich in eine winzige Fledermaus oder eine mittelgroße Nebelwolke zu verwandeln oder wieder ihre wahre Gestalt anzunehmen.

      In Fledermausgestalt kann Sangora nicht sprechen, seine Bewegungsrate ist 1,5 m, und sie erhält eine Flug-Bewegungsrate von 9 m. Ihre Spielwerte, abgesehen von ihrer Größe und Bewegungsrate, bleiben unverändert. Alles, was sie am Körper trägt, verwandelt sich mit, doch nichts, was sie in der Hand hält, tut dies. Wenn sie stirbt, nimmt sie wieder ihre wahre Gestalt an.

      Solange sich Sangora in ihrer Nebelgestalt befindet, kann sie keine Aktionen ausführen, nicht sprechen und keine Gegenstände beeinflussen. Sie ist gewichtslos, hat eine Flug-Bewegungsrate von 6 m, kann schweben und kann den Bereich einer feindlichen Kreatur betreten und dort anhalten. Wenn außerdem Luft durch einen Bereich dringen kann, kann der Nebel dies auch, ohne sich quetschen zu müssen. Sie kann kein Wasser durchdringen. Sie hat einen Vorteil bei Rettungswürfen mit Stärke, Geschicklichkeit und Konstitution und ist immun gegen jeden nichtmagischen Schaden, abgesehen von dem Schaden, den sie durch Sonnenlicht erleidet.
  - name: Legendäre Resistenz (3/Tag)
    desc: Wenn Sangora einen Rettungswurf nicht schafft, kann sie sich stattdessen entscheiden, ihn zu schaffen.
  - name: Nebliges Entkommen
    desc: |-
      Wenn sie außerhalb ihrer Ruhestätte auf 0 Trefferpunkte fällt, verwandelt sich Sangora in eine Nebelwolke (wie beim Merkmal Gestaltwandler) anstatt das <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bewusstlos|Bewusstsein<STATBLOCK-MARKDOWN-LINK> zu verlieren, vorausgesetzt, sie ist weder im Sonnenlicht noch in fließendem Wasser. Wenn sie sich nicht verwandeln kann, wird sie zerstört.

      Solange sie in Nebelgestalt 0 Trefferpunkte besitzt, kann sie nicht ihre Vampirgestalt annehmen, und sie muss ihre Ruhestätte innerhalb von 2 Stunden erreichen, sonst wird sie zerstört. Sobald sie ihre Ruhestätte erreicht hat, nimmt sie wieder ihre Vampirgestalt an. Sie ist dann <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, bis sie mindestens 1 Trefferpunkt zurückerhält. Nachdem sie 1 Stunde mit 0 Trefferpunkten in ihrer Ruhestätte verbracht hat, erhält sie 1 Trefferpunkt zurück.
  - name: Regeneration
    desc: Sangora erhält zu Beginn ihres Zugs 20 Trefferpunkte zurück, wenn sie mindestens 1 Trefferpunkt besitzt und sich nicht im Sonnenlicht oder in fließendem Wasser befindet. Wenn Sangora gleißenden Schaden oder Schaden durch Weihwasser erleidet, funktioniert dieses Merkmal zu Beginn des nächsten Zugs Sangoras nicht.
  - name: Spinnenklettern
    desc: Sangora kann an schwierigen Oberflächen klettern, auch kopfüber an der Decke, ohne Attributswürfe ablegen zu müssen.
  - name: Vampirschwächens
    desc: |-
      Sangora hat die folgenden Nachteile:

      - **Verbot.** Sangora kann keinen Wohnsitz betreten, ohne eine Einladung von einem der Bewohner erhalten zu haben.  
      - **Verletzt durchfließendes Wasser.** Sangora erleidet 20 Säure schaden, wenn sie ihren Zug in fließendem Wasser beendet.  
      - **Pflock ins Herz.** Wenn eine Stichwaffe aus Holz ins Herz Sangoras getrieben wird, solange Sangora sich in ihrer Ruhestätte befindet und <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Kampfunfähig|kampfunfähig<STATBLOCK-MARKDOWN-LINK> ist, wird Sangora <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gelähmt|gelähmt<STATBLOCK-MARKDOWN-LINK>, bis der Pflock entfernt wird.  
      - **Hyperempfindlich gegenüber Sonnenlicht.** Sangora erleidet 20 gleißenden Schaden, wenn sie ihren Zug im Sonnenlicht beginnt. Solange sie sich im Sonnenlicht befindet, erleidet sie einen Nachteil auf Angriffswürfe und Attributswürfe.  
actions:
  - name: Mehrfachangriff (nur Vampirgestalt)
    desc: Sangora führt zwei Angriffe durch, von denen nur einer ein Biss-Angriff sein darf.
  - name: Waffenloser Angriff (nur Vampirgestalt)
    desc: "*Nahkampf-Waffenangriff:* +9 zum Treffen, Reichweite 1,5 m, eine Kreatur. *Treffer:* 8 (1d8 + 4) Wuchtschaden. Anstatt Schaden zu verursachen, kann Sangora das Ziel packen (SG zum Entkommen 18)."
  - name: Biss (Fledermaus- oder Vampirgestalt)
    desc: "*Nahkampf-Waffenangriff:* +9 zum Treffen, Reichweite 1,5 m, eine bereitwillige Kreatur oder eine Kreatur, die Sangora <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK> hat, die <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Kampfunfähig|kampfunfähig<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK>. *Treffer:* 7 (1d6 + 4) Stichschaden plus 10 (3d6) nekrotischer Schaden. Die maximalen Trefferpunkte des Ziels werden um den nekrotischen Schaden verringert, und Sangora erhält die gleiche Menge an Trefferpunkten zurück. Diese Verringerung hält an, bis das Ziel eine lange Rast abschließt. Das Ziel stirbt, wenn dieser Effekt es auf 0 maximale Trefferpunkte reduziert. Ein Humanoider, der auf diese Weise getötet und dann in der Erde begraben wird, erhebt sich in der folgenden Nacht als <STATBLOCK-MARKDOWN-LINK>Vampirbrut-mm|Vampirbrut<STATBLOCK-MARKDOWN-LINK> unter der Kontrolle Sangoras."
  - name: Bezaubern
    desc: |-
      Sangora wählt einen Humanoiden innerhalb von 9 m um sich aus, den sie sehen kann. Wenn das Ziel Sangora sehen kann, muss es gegen diese Magie einen Weisheitsrettungswurf gegen SG 17 ablegen, um nicht von Sangora <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|bezaubert<STATBLOCK-MARKDOWN-LINK> zu werden. Das <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Bezaubert|bezauberte<STATBLOCK-MARKDOWN-LINK> Ziel betrachtet Sangora als Freund, dem es vertraut, auf den es hören sollte und der beschützt werden muss. Auch wenn das Ziel nicht unter der Kontrolle Sangoras steht, deutet es die Forderungen und Taten Sangoras so wohlwollend wie es kann, und es ist ein bereitwilliges Ziel für den Biss-Angriff Sangoras.

      Immer wenn Sangora oder die Gefährten Sangoras etwas tun, das dem Ziel schadet, kann es den Rettungswurf wiederholen und den Effekt auf sich selbst bei einem Erfolg beenden. Ansonsten hält der Effekt für 24 Stunden an, oder bis Sangora zerstört wird, sich auf einer anderen Existenzebene als das Ziel befindet, oder eine Bonusaktion nutzt, um den Effekt zu beenden.
  - name: Kinder der Nacht (1/Tag)
    desc: Sangora ruft auf magische Art 2d4 Schwärme von <STATBLOCK-MARKDOWN-LINK>Schwarm_von_Fledermäusen-mm|Fledermäusen<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>Schwarm_von_Ratten-mm|Ratten<STATBLOCK-MARKDOWN-LINK>, vorausgesetzt die Sonne steht nicht am Himmel. Solange sich Sangora im Freien befindet, kann sie stattdessen 3d6 <STATBLOCK-MARKDOWN-LINK>Wolf-mm|Wölfe<STATBLOCK-MARKDOWN-LINK> rufen. Die gerufenen Kreaturen treffen innerhalb von 1d4 Runden ein, dienen als Verbündete Sangoras und gehorchen ihren gesprochenen Befehlen. Die Tiere bleiben für 1 Stunde, bis dSangora stirbt oder bis sie sie mit einer Bonusaktion entlässt.
legendary_description: "Sangora kann 3 legendäre Aktionen durchführen und aus den folgenden Optionen auswählen. Sie kann nur eine legendäre Aktionsoption auf einmal verwenden, und nur am Ende eines Zugs eines anderen Charakters. Sangora erhält verbrauchte legendäre Aktionen zu Beginn ihres Zuges zurück."
legendary_actions:
  - name: Bewegung
    desc: Sangora bewegt sich bis zu ihrer Bewegungsrate weit, ohne Gelegenheitsangriffe zu provozieren.
  - name: Waffenloser Angriff
    desc: Sangora führt einen Waffenlosen Angriff durch.
  - name: Biss (kostet 2 Aktionen)
    desc: Sangora führt einen Bissangriff durch.
```
^statblock