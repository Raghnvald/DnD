---
cssclasses:
  - json5e-monster
tags:
  - Quelle/5e/cos
  - Monster/HG/10
  - Monster/Größe/Mittelgroß
  - Monster/Typ/Humanoid/elf
statblock: inline
statblock-link: "#^statblock"
aliases:
  - Rahadin
---
# [Rahadin](3-Mechanics\CLI\bestiary\npc/rahadin-cos.md)
*Source: Curse of Strahd p. 237*  

Rahadin, the dusk elf chamberlain of Castle Ravenloft, has served Strahd's family faithfully for nearly five hundred years. He is Strahd's eternal servant, a longtime comrade-in-arms, and a ruthless warrior who has killed thousands in his lifetime.

## Exile

Rahadin was exiled for refusing to bow down to a dusk elf prince whom he considered weak and corrupt. When the dusk elves later declined to pay fealty to King Barov, Rahadin helped Barov conquer them. The elf kingdom's royal line was obliterated, the dusk elves hunted like rabbits. The few that survived were either subjugated or forced to live among the Vistani. So pleased was Barov with Rahadin that the king made the dusk elf an honorary member of his family.

## Chamberlain

After Barov died, Rahadin continued to fight as one of Strahd's generals. When the wars ended and Strahd turned his attention to building Castle Ravenloft, Rahadin saw to it that wizards and artisans were brought to Barovia. Years later, Strahd appointed Rahadin his castle chamberlain. Rahadin was pleased to do whatever Strahd asked of him, and he instilled terror in the castle staff by routinely flogging those who didn't perform their duties to his exacting standards.

When a dusk elf named Patrina Velikovna came knocking on Strahd's door, Rahadin could see that she intrigued Strahd, but Rahadin was suspicious of her motives. Patrina tried to seduce Strahd with the prospect of immortality - something Strahd desired above all. She told him of a vault of forbidden lore called the Amber Temple, where the secret of gaining immortality was hidden. While Strahd was off exploring the temple, Rahadin handled all of his master's affairs and began searching for a woman who could tear Strahd away from Patrina Velikovna. In this task, he failed. His goal was fulfilled, however, when Sergei, Strahd's brother, found Tatyana.

Tatyana was Strahd's type - a woman of exquisite beauty and gentle manner. When Strahd returned to Ravenloft, the young woman instantly caught his eye, and Rahadin had the pleasure of informing Patrina that her presence at the castle was no longer desired.

Rahadin's loyalty didn't waver after Tatyana died and Strahd became a vampire. Rahadin continued to do his master's bidding. Eager to put Tatyana out of his mind, Strahd lured more women to the castle, taking several of them as brides before draining their lives and turning them into vampire spawn. Rahadin would see to it that these women were lavished with jewels and fine clothes, and made comfortable during their stay in Ravenloft.

## Executioner

Patrina Velikovna and her people were living among the Vistani when they heard of Tatyana's death and Strahd's curse. The ageless Patrina returned to Ravenloft in the hope of winning Strahd's love. This time, it was clear that Patrina craved Strahd's power and that Strahd would never love her. Rahadin assumed that Patrina would suffer the same fate as those women who had come before her. He was proven wrong when Patrina's own people stoned her to death to keep Strahd from claiming her as his wife.

Strahd was upset that the dusk elves had taken Patrina from him. After securing her body and entombing it in the catacombs of Ravenloft, Strahd sent Rahadin to punish the dusk elves. Rahadin slew the female elves so that the males couldn't breed. He also sliced off the ears of Patrina's brother, Kasimir, who had orchestrated the stoning.

## Screams of the Dead

So dreadful a creature is Rahadin that anyone who stands within 10 feet of him can hear the howling screams of the countless men and women he has killed in his lifetime. Rahadin can't hear them, nor would he be haunted by them if he could. The only thing he cares about is Strahd von Zarovich, for whom he would gladly give his life.

## Rahadin's Traits

### Ideal

"Loyalty is everything."

### Bond

"I am a son of King Barov von Zarovich, and I will serve his son - my brother and lord - forever."

### Flaw

"I have slain thousands of men. I will slaughter thousands more to preserve the von Zarovich legacy."

```statblock
"name": "Rahadin (CoS)"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Lawful Evil"
"ac": !!int "18"
"ac_class": "[studded leather](/3-Mechanics/CLI/items/studded-leather-armor-xphb.md)"
"hp": !!int "135"
"hit_dice": "18d8 + 54"
"modifier": !!int "6"
"stats":
  - !!int "14"
  - !!int "22"
  - !!int "17"
  - !!int "15"
  - !!int "16"
  - !!int "18"
"speed": "35 ft."
"saves":
  - "constitution": !!int "7"
  - "wisdom": !!int "7"
"skillsaves":
  - "name": "[Deception](/3-Mechanics/CLI/skills.md#Deception)"
    "desc": "+8"
  - "name": "[Insight](/3-Mechanics/CLI/skills.md#Insight)"
    "desc": "+7"
  - "name": "[Intimidation](/3-Mechanics/CLI/skills.md#Intimidation)"
    "desc": "+12"
  - "name": "[Perception](/3-Mechanics/CLI/skills.md#Perception)"
    "desc": "+11"
  - "name": "[Stealth](/3-Mechanics/CLI/skills.md#Stealth)"
    "desc": "+14"
"senses": "[darkvision](/3-Mechanics/CLI/senses.md#Darkvision) 60 ft., passive Perception\
  \ 21"
"languages": "Common, Elvish"
"cr": "10"
"traits":
  - "desc": "Rahadin's innate spellcasting ability is Intelligence. He can innately\
      \ cast the following spells, requiring no components:\n\n**3/day:** [misty step](/3-Mechanics/CLI/spells/misty-step-xphb.md),\
      \ [phantom steed](/3-Mechanics/CLI/spells/phantom-steed-xphb.md)\n\n**1/day:**\
      \ [magic weapon](/3-Mechanics/CLI/spells/magic-weapon-xphb.md), [nondetection](/3-Mechanics/CLI/spells/nondetection-xphb.md)"
    "name": "Innate Spellcasting"
  - "desc": "Any creature within 10 feet of Rahadin that isn't protected by a [mind\
      \ blank](/3-Mechanics/CLI/spells/mind-blank-xphb.md) spell hears in its mind\
      \ the screams of the thousands of people Rahadin has killed. As a bonus action,\
      \ Rahadin can force all creatures that can hear the screams to make a DC 16\
      \ Wisdom saving throw. Each creature takes 16 (3d10) psychic damage on a failed\
      \ save, or half as much damage on a successful one."
    "name": "Deathly Choir"
  - "desc": "Rahadin has advantage on saving throws against being [charmed](/3-Mechanics/CLI/conditions.md#Charmed),\
      \ and magic can't put him to sleep."
    "name": "Fey Ancestry"
  - "desc": "Rahadin can attempt to hide even when he is only lightly obscured by\
      \ foliage, heavy rain, falling snow, mist, and other natural phenomena."
    "name": "Mask of the Wild"
"actions":
  - "desc": "Rahadin attacks three times with his scimitar, or twice with his [poisoned](/3-Mechanics/CLI/conditions.md#Poisoned)\
      \ darts."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 9\
      \ (1d6 + 6) slashing damage."
    "name": "Scimitar"
  - "desc": "*Ranged Weapon Attack:* +10 to hit, range 20/60 ft., one target. *Hit:*\
      \ 8 (1d4 + 6) piercing damage plus 5 (2d4) poison damage."
    "name": "Poisoned Dart"
"source":
  - "CoS"
"image": "/3-Mechanics/CLI/bestiary/npc/token/rahadin-cos.webp"
```
^statblock

---

# Rahadin
Rahadin, der Dämmerungselfen-Kammerherr von Schloss Ravenloft, hat Strahds Familie beinahe fünfhundertJahre lang treu gedient. Er ist Strahds ewiger Diener, ein langjähriger Waffengefährte und ein unbarmherziger Krieger, der im Laufe seines Lebens Tausende getötet hat.
$\quad$ **_Exilant_**. Rahadin wurde ins Exil geschickt, weil er sich geweigert hatte, sich vor einem Dämmerungselfenprinzen zu verneigen, den er für schwach und verdorben hielt. Als die Dämmerungselfen sich später weigerten, König Barov Lehenstreue zu erweisen, half Rahadin Barov dabei, sie zu erobern. Die königliche Linie des Elfenkönigreichs wurde ausgelöscht und die Dämmerungselfen wie Hasen gejagt. Die wenigen Überlebenden wurden entweder unterjocht oder gezwungen, unter den Vistani zu leben. Barov war so zufrieden mit Rahadin, dass der König den Dämmerungselfen zu einem Ehrenmitglied seiner Familie machte.
$\quad$ **_Kammerherr._** Nachdem Barov gestorben war, kämpfte Rahadin weiterhin als einer von Strahds Generälen. Als die Kriege endeten und Strahd seine Aufmerksamkeit auf den Bau von Schloss Ravenloft legte, sorgte Rahadin dafür, dass Magier und Kunsthandwerker nach Barovia gebracht wurden. Jahre später ernannte Strahd Rahadin zu seinem Schlosskammerherren. Rahadin war erfreut, alles zu tun, um das Strahd ihn bat, und er flößte dem Schlossgesinde Furcht ein, indem er regelmäßig diejenigen auspeitschen ließ, die ihre Pflichten nicht nach seinen präzisen Standards erfüllten.
$\quad$ Als eine Dämmerungselfe namens Patrina Welikowna an Strahds Tür klopfte, konnte Rahadin sehen, dass sie Strahd faszinierte, doch Rahadin war argwöhnisch gegenüber ihren Motiven. Patrina versuchte, Strahd mit der Aussicht auf Unsterblichkeit zu verführen - etwas, das Strahd vor allem anderen begehrte. Sie erzählte ihm von einem Gewölbe voller verbotenen alten Wissens, genannt der Bernsteintempel, wo das Geheimnis verborgen lag, Unsterblichkeit zu erhalten. Während Strahd unterwegs war, um den Tempel zu erkunden, kümmerte Rahadin sich um alle Angelegenheiten seines Herrn und begann nach einer Frau zu suchen, die Strahd von Patrina Welikowna wegreißen konnte. Bei dieser Aufgabe versagte er. Sein Ziel jedoch war erreicht, als Sergej, Strahds Bruder, Tatjana fand.
$\quad$ Tatjana war Strahds Typ - eine Frau von exquisiter Schönheit und sanftem Wesen. Als Strahd nach Ravenloft zurück- kehrte, stach ihm die junge Frau sofort ins Auge, und Rahadin hatte das Vergnügen, Patrina zu informieren, dass ihre Anwesenheit im Schloss nicht länger erwünscht war.
$\quad$ Rahadins Loyalität wankte auch nicht, nachdem Tatjana gestorben war und Strahd sich in einen Vampir verwandelt hatte. Rahadin folgte weiterhin Strahds Anweisungen. Begierig, Tatjana aus seinen Gedanken zu vertreiben, lockte Strahd weitere Frauen ins Schloss und nahm mehrere von ihnen zur Braut, bevor er ihr Leben aussaugte und sie in Vampirbrut verwandelte. Rahadin sorgte jeweils dafür, dass diese Frauen mit Juwelen und feinen Kleidern überhäuft wurden und es ihnen während ihres Aufenthalts in Ravenloft gut ging.
$\quad$ **_Henker._** Patrina Welikowna und ihr Volk lebten unter den Vistani, als sie von Tatjanas Tod und Strahds Fluch hörten. Die nicht alternde Patrina kehrte in der Hoffnung nach Ravenloft zurück, Strahds Liebe zu gewinnen. Dieses Mal war klar, dass Patrina Strahds Macht begehrte und dass Strahd sie niemals lieben würde. Rahadin nahm an, dass Patrina dasselbe Schicksal erleiden würde, wie die Frauen, die vor ihr kamen. Er wurde widerlegt, als Patrinas eigenes Volk sie zu Tode steinigte, um Strahd davon abzuhalten, sie als seine Braut zu beanspruchen.
$\quad$ Strahd war verärgert, dass die Dämmerungselfen ihm Patrina genommen hatten. Nachdem er ihre Leiche sichergestellt und sie in den Katakomben von Ravenloft bestattet hatte, sandte Strahd Rahadin aus, die Dämmerungselfen zu bestrafen. Rahadin erschlug die weiblichen Elfen, so dass die männlichen sich nicht fortpflanzen konnten. Er schnitt auch Patrinas Bruder Kasimir die Ohren ab, der die Steinigung geleitet hatte.
$\quad$ **_Schreie der Toten._** Rahadin ist eine so fürchterliche Kreatur, dass jeder, der in einem Umkreis von 3 Metern um ihn herum steht, die heulenden Schreie der zahllosen Männer und Frauen hören kann, die er während seines Lebens getötet hat. Rahdin kann sie weder hören, noch würde er sich von ihnen quälen lassen, wenn er es könnte. Das Einzige, das ihm etwas bedeutet, ist Strahd von Zarowitsch, für den er freudig sein Leben geben würde.

![](D&D/99-Setup/Archiv/DND/00.%20NPCs/pictures/rahadin.webp#token)

### Charakteristika von Rahadin
$\quad$ **_Ideal._** „Loyalität ist alles." 
$\quad$ **_Bindung._** „Ich bin ein Sohn von König Barov von Zarowitsch, und ich werde seinem Sohn - meinem Bruder und Herrn - auf immer dienen." 
$\quad$ **_Makel._** „Ich habe Tausende Männer erschlagen. Ich will Tausende mehr abschlachten, um das Vermächtnis der von Zarowitsch zu bewahren."

```statblock
statblock: true
name: Rahadin, Original
image: [[token/Rahadin.webp]]
source: Fluch des Strahd
size: Mittelgroß
type: Humanoid (Elf)
alignment: Rechtschaffen Böse
ac: 18
hp: 135
hit_dice: 18d8 + 54
speed: 10,5 Meter.
stats: [14, 22, 17, 15, 16, 18]
saves:
  - KON: +5
  - WEI: +7
skillsaves:
  - Einschüchtern: +12
  - Heimlichkeit: +14
  - Motiv-erkennen: +7
  - Täuschen: +8
  - Wahrnehmung: +11
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: ""
condition_immunities: ""
senses: Dunkelsicht 18 m, passive Wahrnehmung 21
languages: Elfisch, Gemeinsprache
cr: 10
bestiary: true
traits:
  - name: Angeborenes Zauberwirken.
    desc: "Das Attribut zum Wirken angeborener Zauber für Rahadin ist Intelligenz. Er kann von Natur aus die folgenden Zauber wirken, wobei er keine Komponenten benötigt:<br><br> 3/Tag: [Geisterross](Geisterross.md), [Nebelschritt](Nebelschritt.md) <br> 1/Tag: [Magische Waffe](Magische-Waffe.md), [Unauffindbarkeit](Unauffindbarkeit.md)"
  - name: Feenblut.
    desc: "Rahadin hat einen Vorteil bei Rettungswürfen wenn er bezaubert werden soll, und Magie kann ihn nicht einschläfern."
  - name: Maske der Wildnis.
    desc: "Rahadin kann sogar versuchen, sich zu verstecken, wenn er nur leicht verschleiert durch Blattwerk, starken Regen, Schneefall, Nebel oder andere Naturphänomene ist."
  - name: Tödlicher Chor.
    desc: "jede Kreatur innerhalb von 3 m um Rahadin, die nicht von dem Zauber Gedankenleere geschützt ist, hört in ihrem Geist die Schreie der Tausende Individuen, die Rah ad in getötet hat. Als eine Bonusaktion kann Rahadin alle Kreaturen, die die Schreie hören, dazu zwingen, einen Weisheitsrettungswurf gegen SG 16 abzulegen. jede Kreatur erleidet bei einem misslungenen Rettungswurf `16` (`3W10`) psychischen Schaden oder den halben Schaden bei einem gelungenen."
actions:
  - name: Mehrfachangriff
    desc: "Rahadin führt drei Angriffe mit seinem Krummsäbel oder zwei mit seinen Giftpfeilen aus."
  - name: Krummsäbel
    desc: "_Nahkampf-Waffenangriff_: +10 zum Treffen, Reichweite 1,50 m, ein Ziel. _Treffer_: 9 (`1W6 + 6`) Hiebschaden."
    attack_bonus: 10
    damage_dice: 1d6
    damage_bonus: 6
  - name: Giftpfeil
    desc: "_Fernkampf-Waffenangriff_: +10 zum Treffen, Reichweite 6/18 m, ein Ziel. _Treffer_: 8 (`1W4 + 6`) Stichschaden plus 5 (`2W4`) Giftschaden."
    attack_bonus: 10
    damage_dice: 1d4
    damage_bonus: 6
```