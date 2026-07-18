---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Otyugh-Mutant
Kategorie: Aberration
Größe: Groß
HG: 6
Habitat:
  - /
Image: aberration/token/otyugh-mutate-pabtso.webp
Status: WIP
linter-yaml-title-alias: Otyugh-Mutant
tags:
  - Monster/Größe/Groß
  - Monster/HG/6
  - Monster/Typ/Aberration
  - Quelle/5e/pabtso
aliases:
  - Otyugh Mutate
  - Otyugh-Mutant
image: token/otyugh-mutate-pabtso.webp
status: completed
---
# Otyugh-Mutant
*Quelle: Die Tieffen von Phandelver: Der zersplitterte Obelisk S. 213*  

Ein Otyugh-Mutant kann aus Abfall- und Aashaufen entstehen, die der Energie des Femen Reichs ausgesetzt sind. Diese Mutanten entwickeln tiefschwarze Chitinpanzerplatten an ihren Gliedmaßen. Im Gegensatz zu den Panzerplatten sind die Muskeln glasig und fast geisterhaft. Durch diese grotesken Fenster ins Innere des Otyugh kann man einen grotesken Blick auf den giftigen Abfall erhaschen, den er gefressen hat.

## Mutanten

Wenn eine Kreatur der mysteriösen Energie des Fernen Reichs ausgesetzt ist, kann es zu Mutationen kommen. Wenn die Kräfte des Fernen Reichs die Grundbausteine einer solchen Kreatur umformen, beginnt eine Metamorphose.

$\quad$Jede beliebige Kreatur kann zum Mutanten werden und körperliche Merkmale entwickeln, die aus den Fernen Reich stammen. Manche Kreaturen werden zu Mutanten, wenn sie über längere Zeit der Energie des Fernen Reichs oder von dort stammender Magie ausgesetzt sind. Andere verändern sich willentlich - sie begrüßen und verehren die finsteren Mächte. Kreaturen, die zu Mutanten werden, kehren in vielen Fällen wieder zu ihrer ursprünglichen Form zurück, sobald der Einfluss des Fernen Reichs nachlässt.

$\quad$Unerklärlicherweise scheitern jegliche Versuche, Kreaturen zu solchen Transformationen zu zwingen - auch wenn böse Mächte wie das alte Imperium der Gedankenschinder diese Möglichkeit gründlich erforscht haben. Seit Jahrhunderten versuchen die Gedankenschinder, Mutantenarmeen zu erschaffen, um das Unterreich zu überrollen. Ihre Anstrengungen erwiesen sich jedoch immer als erfolglos, und irgendwann gaben die Gedankenschinder ihre Pläne auf.

$\quad$Es gibt mehrere verbreitete Mutantenarten. Die in diesem Abschnitt enthaltenen Wertekästen kommen im vorliegenden Abenteuer vor, es existieren jedoch auch andere Mutanten. Manche Kreaturen neigen eher dazu, zu Mutanten des Fernen Reichs zu werden. Das gilt zum Beispiel für den Mantler und den Otyugh auf den folgenden Seiten.

$\quad$Mutanten erlangen häufig psionische Fähigkeiten, Flügel, eine Hülle aus außerweltlichem Schleim oder andere verstörende Eigenschaften. Spezifisch mutierte Kreaturen werden in den folgenden Abschnitten näher beschrieben.

```statblock
name: Otyugh-Mutant
image: token/otyugh-mutate-pabtso.webp
source:
  - PaBTSO
size: Groß
type: Aberration
alignment: normalerweite neutral
ac: 16
ac_class: natürliche Rüstung
hp: 76
hit_dice: 8d10 + 32
modifier: 0
stats:
  - 19
  - 11
  - 18
  - 10
  - 15
  - 6
speed: 9 m
saves:
  - Stärke: 7
  - Konstitution: 7
damage_immunities: Gift
condition_immunities: <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>
senses: <STATBLOCK-MARKDOWN-LINK>Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 36 m, passive Wahrnehmung 12
languages: Otyugh, Telepathie auf 36 m
cr: "6"
traits:
  - name: Giftatem
    desc: "Aus dem Verdauungstrakt des Mutanten quellen giftige Gase hervor. Zu Beginn des Zugs des Mutanten muss jede Kreatur im Abstand von bis zu 1,5 Metern von ihm einen `SG-15-Konstitutionsrettungswurf` bestehen, oder sie erleidet 3 (1d6) Giftschaden."
actions:
  - name: Mehrfachangriff
    desc: Der Mutant führt zwei Biss- oder Tentakelangriffe aus. Er kann einen dieser Angriffe durch einen Chitinhieb ersetzen.
  - name: Biss
    desc: "*Nahkampf-Waffenangriff:* +7 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 13 (2d8 + 4) Stichschaden. Wenn das Ziel eine Kreatur ist, muss es einen `SG-15-Konstitutionsrettungswurf` bestehen, oder es ist <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>. Nach jeweils 24 Stunden muss das Ziel den Rettungswurf wiederholen. Scheitert der Wurf, wird sein Trefferpunktemaximum um 5 (1d10) verringert. Bei einem erfolgreichen Rettungswurf ist das Ziel nicht mehr <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK>. Diese Verringerung des Trefferpunktemaximums des Ziels hält an, bis es nicht mehr <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Vergiftet|vergiftet<STATBLOCK-MARKDOWN-LINK> ist."
  - name: Tentakel
    desc: "*Nahkampf-Waffenangriff:* +7 zum Treffen, Reichweite 3 m, ein Ziel. *Treffer:* 13 (2d8 + 4) Wuchtschaden. Wenn das Ziel eine höchstens mittelgroße Kreatur ist, wird es <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Gepackt|gepackt<STATBLOCK-MARKDOWN-LINK> (Rettungswurf-SG 15) und ist <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Festgesetzt|festgesetzt<STATBLOCK-MARKDOWN-LINK> bis es nicht mehr gepackt ist. Der Mutant hat zwei Tentakel, die jeweils ein Ziel packen können."
  - name: Chitinhieb
    desc: "Der Mutant zielt auf eine Kreatur, die er gepackt hat und schmettert sie gegen seine Chitinpanzerung. er gepackt hat und schmettert sie gegen seine Chitinpanzerung. Die Kreatur muss einen `SG-15-Konstitutionsrettungswurf` bestehen, oder sie erleidet 16 (3d10) Wuchtschaden und ist bis zum Ende des nächsten Zugs des Mutanten <STATBLOCK-MARKDOWN-LINK>Zustände-phb#Betäubt|betäubt<STATBLOCK-MARKDOWN-LINK>."
```
^statblock