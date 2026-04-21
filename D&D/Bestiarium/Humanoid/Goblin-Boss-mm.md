---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Goblin Boss
tags:
  - Monster/Größe/Klein
  - Monster/Habitat/Grasland
  - Monster/Habitat/Hügel
  - Monster/Habitat/Unterreich
  - Monster/Habitat/Wald
  - Monster/HG/1
  - Monster/Typ/Humanoid/goblinoid
  - Quelle/5e/mm
aliases:
  - Goblin Boss
---
# Goblin Boss
*Quelle: Monsterhandbuch S. 142*  

Goblins sind kleine, verkommene, egoistische Humanoide, die in Höhlen, verlassenen Minen, ausgeplünderten Gewölben und anderen elenden Orten hausen. Goblins sind für sich genommen schwach, versammeln sich aber in großer - oft überwältigender - Zahl. Sie gieren nach Macht und missbrauchen oft die Autorität, die sie erhalten.

## Goblinoids

Goblins gehören zu einer Kreaturenfamilie, die Goblinoide genannt wird. Ihre größeren Vettern, Grottenschrate und Hobgoblins, mögen es, Goblins bis zur absoluten Unterwürfigkeit einzuschüchtern. Goblins sind faul und undiszipliniert, was sie zu schlechten Dienern, Arbeitern und Wachen macht.

## Bösartige Freude

Goblins sind von Gier und Bosheit angetrieben und können nicht anders, als die wenigen Male zu feiern, die sie die Oberhand haben. Sie tanzen und springen vor schierer Freude, wenn sie gewonnen haben. Sobald ihre Freude endet, erfreuen sich Goblins daran, andere Kreaturen zu quälen, und genießen verschiedene Formen der Bösartigkeit.

## Anführer und Gefolgsleute

Goblins werde von den Stärksten oder Schlausten unter ihnen beherrscht. Ein Goblin-Boss könnte einen einzelnen Bau beherrschen, während ein Goblinkönig oder eine Goblinkönigin (was nicht mehr ist als ein glorifizierter Goblinboss) Hunderte von Goblins regieren könnte, die auf mehrere Bauten verteilt sind, um das Überleben des Stammes zu garantieren. Goblin-Bosse sind schnell gestürzt, und viele Goblinstämme werden von Hobgoblin-Kriegsherren oder Grottenschrat-Häuptlingen übernommen.

## Herausfordernde Behausungen

Goblins sichern ihre Behausungen mit Alarmsystemen, die vor der Ankunft von Eindringlingen warnen sollen. Diese Behausungen sind durchzogen von engen Tunneln und Fluchtlöchern, die menschengroße Wesen nicht nutzen können, durch die Goblins aber ohne große Schwierigkeiten kriechen können. So können sie entkommen oder ihre Gegner von hinten überraschen.

## Rattenhalter und Wolfsreiter

Goblins haben eine Affinität für Ratten und Wölfe und züchten sie als Gefährten und Reittiere. Wie Ratten meiden Goblins das Sonnenlicht und schlafen während des Tages unter der Erde. Wie Wölfe sind sie Rudeljäger, die durch Überzahl mutiger werden. Wenn sie vom Rücken ihrer Wölfe aus jagen, verwenden Goblins Überfalltaktiken.

## Anhänger von Maglubiyet

Maglubiyet, der Mächtige, der Fürst der Tiefe und Dunkelheit, ist der höchste Gott der Goblinoiden. Die meisten Gobtins stellen ihn sich als fast vier Meter großen, von Kampfnarben bedeckten Goblin mit schwarzer Haut vor, aus dessen Augen Flammen lodern. Er wird nicht aus Respekt angebetet, sondern aus Furcht. Goblins glauben, dass ihre Seelen, wenn sie im Kampf sterben, sich den Reihen von Maglubiyets Armee auf der Ebene Acheron anschließen. Dies ist ein „Privileg", das die meisten Goblins fürchten, da sie die ewige Tyrannei des Mächtigen sogar noch mehr fürchten als den Tod.

> [!quote] Stalman Kilm, Sklaventreiber
> 
> Wenn du Soldaten oder Schläger willst, werbe Hobgoblins an. Wenn du willst, dass jemand im Schlaf zu Tode geprügelt wird, nimm Grottenschrate. Wenn du fiese kleine Narren willst, dann nimm Goblins.

> [!quote] Goblinisch für "Wir kapitulieren!" (sagen sie zumindest)  
> 
> **Bree-Yark!**

```statblock
name: Goblin-Boss
size: Klein
type: Humanoid
subtype: Goblinoid
alignment: Neutral Böse
ac: 17
ac_class: <STATBLOCK-MARKDOWN-LINK>Gegenstände/Kettenhemd|Kettenhemd-phb<STATBLOCK-MARKDOWN-LINK>, <STATBLOCK-MARKDOWN-LINK>Gegenstände/Schild-phb|Schild<STATBLOCK-MARKDOWN-LINK>
hp: 21
hit_dice: 6d6
modifier: 2
stats:
  - 10
  - 14
  - 10
  - 10
  - 8
  - 10
speed: 9 m
skillsaves:
  - name: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Fertigkeiten-phb#Heimlichkeit|Heimlichkeit<STATBLOCK-MARKDOWN-LINK>
    desc: "+6"
senses: <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Sinne-phb#Dunkelsicht|Dunkelsicht<STATBLOCK-MARKDOWN-LINK> 18 m, passive Wahrnehmung 9
languages: Gemeinsprache, Goblininisch
cr: "1"
traits:
  - desc: Der Goblin kann in jedem seiner Züge die Aktion <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Aktionen-phb#Rückzug|Rückzug<STATBLOCK-MARKDOWN-LINK> oder <STATBLOCK-MARKDOWN-LINK>01-Spielleiter/Aktionen-phb#Verstecken|Verstecken<STATBLOCK-MARKDOWN-LINK> als Bonusaktion verwenden.
    name: Behändes Entkommen
actions:
  - desc: Der Goblin führt zwei Angriffe mit seinem Krummsäbel aus. Er hat einen Nachteil bei seinem zweiten Angriff.
    name: Mehrfachangriff
  - desc: "*Nahkampf-Waffenangriff:* +4 zum Treffen, Reichweite 1,5 m, ein Ziel. *Treffer:* 5 (1d6 +2) Hiebschaden."
    name: Krummsäbel
  - desc: "*Nahkampf- oder Fernkampf-Waffenangriff:* +2 zum Treffen, Reichweite 1,5 m (Nahkampf), 9/36 m, ein Ziel. *Treffer:* 3 (1d6) Stichschaden."
    name: Wurfspeer
reactions:
  - desc: Wenn eine Kreatur, die der Goblin sehen kann, ihn mit einem Angriff trifft, kann er einen anderen Goblin im Umkreis von 1,5 m um sich auswählen. Die beiden Goblins tauschen ihren Platz und der ausgewählte Goblin wird Ziel des Angriffs.
    name: Angriff umlenken
source:
  - MM
image: Bestiarium/Humanoid/token/goblin-boss.webp
path: Bestiarium/Humanoid/Goblin-Boss-mm.md

```
^statblock

## Vorkommen

Grasland, Hügel, Unterreich, Wald