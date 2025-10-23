---
obsidianUIMode: preview
cssclasses: json5e-monster
tags:
- DnD/Kompendium/Quelle/5e/MM 2014
- DnD/Kompendium/Quelle/5e/MM 2024
- Habitat/Jedes
- Größe/Groß
- Typ/Konstrukt
aliases:
- Stone Golem
---
# Stone Golem (2014)
*Source: SRD / Basic Rules*  

> [!statblock] Stone Golem
> ![](compendium/bestiary/construct/token/stone-golem.png#token)
> *Large construct, Unaligned*
> 
> - **Armor Class** 17  (natural armor)
> - **Hit Points** 178 (`17d10 + 85`)
> - **Speed** 30 ft.
> 
> |STR|DEX|CON|INT|WIS|CHA|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> |22 (+6)| 9 (-1)|20 (+5)| 3 (-4)|11 (+0)| 1 (-5)|
> 
> - **Proficiency Bonus** +4
> - **Saving Throws** ⏤
> - **Skills** ⏤
> - **Senses** darkvision 120 ft., passive Perception 10
> - **Damage Immunities** poison; psychic; bludgeoning, piercing, slashing from nonmagical attacks that aren't adamantine
> - **Condition Immunities** charmed, exhaustion, frightened, paralyzed, petrified, poisoned
> - **Languages** understands the languages of its creator but can't speak
> - **Challenge** 10
> 
> ## Traits
> 
> ***Immutable Form.*** The golem is immune to any spell or effect that would alter its form.
> 
> ***Magic Resistance.*** The golem has advantage on saving throws against spells and other magical effects.
> 
> ***Magic Weapons.*** The golem's weapon attacks are magical.
> 
> ## Actions
> 
> ***Multiattack.*** The golem makes two slam attacks.
> 
> ***Slam.*** *Melee Weapon Attack:* +10 to hit, reach 5 ft., one target. *Hit:* 19 (`3d8 + 6`) bludgeoning damage.
> 
> ***Slow (Recharge 5-6).*** The golem targets one or more creatures it can see within 10 feet of it. Each target must make a DC 17 Wisdom saving throw against this magic. On a failed save, a target can't use reactions, its speed is halved, and it can't make more than one attack on its turn. In addition, the target can take either an action or a bonus action on its turn, not both. These effects last for 1 minute. A target can repeat the saving throw at the end of each of its turns, ending the effect on itself on a success.

^statblock

# Steingolem (2024)
_Hüter der Geschichte und des Heiligen_

>**Habitat:** Jedes
>**Beute:** Nichts

![](19-031.stone-golem.webp)

Steingolems nehmen verschiedene Formen an, wie zum Beispiel verwitterte Schnitzereien alter Gottheiten, lebensechte Skulpturen von Helden oder jede andere Form, die sich ihre Schöpfer vorstellen. Unabhängig von ihrem Design oder dem Gestein, aus dem sie gefertigt sind, werden diese Golems durch die Magie, die sie belebt, gestärkt und können die Befehle ihrer Schöpfer über Jahrhunderte hinweg befolgen.

Steingolems werden in der Regel erschaffen, um Orte zu schützen, die für eine Gruppe von Bedeutung sind, wie zum Beispiel ein Denkmal für ein wichtiges Ereignis, das Grab eines Anführers oder das Heiligtum eines Glaubens. Würfle auf oder wähle ein Ergebnis aus der Tabelle Steingolem-Befehle, um die Befehle zu inspirieren, denen ein Steingolem folgt.

### Steingolem-Befehle
| 1d6 | Der Steingolem befolgt Befehle, um...                                                                       |
| --- | ----------------------------------------------------------------------------------------------------------- |
| 1   | Erlaube nur denjenigen, die rituelle Gewänder tragen, den Durchgang.                                        |
| 2   | Verlangsamen Sie jeden, der ein wertvolles Relikt der Stadt berührt, und helfen Sie ihm, ihn zu fassen.     |
| 3   | Zerstöre einen Damm oder eine Brücke auf den Befehl eines Herrschers, der das Medaillon seines Amtes trägt. |
| 4   | Gehorche demjenigen, der ein fehlendes Wappen in seine Truhe legt, und deaktiviere es dann für ein Jahr.    |
| 5   | Enthülle einen verborgenen Durchgang für diejenigen, die die letzten Worte eines Anführers aufsagen.        |
| 6   | Halte Ausschau nach dem Monster, das den Helden, dem es ähnelt, getötet hat, und kämpfe mit ihm.            |

>[!quote] Handbuch der Stein-Golems
>Wähle das Aussehen deines Golems mit Bedacht, denn deine Kreation wird ihr Vorbild wahrscheinlich lange überleben.

```statblock
name: Steingolem (2024)
image: pictures/19-031.stone-golem.webp
size: Groß
type: Konstrukt
alignment: Keine Gesinnung
ac: 18
hp: 220
hit_dice: 21d10 + 105
ini: +3 (13)
speed: 9 Meter
stats: [22, 9, 20, 3, 11, 1]
saves:
  - STR: +6
  - GES: -1
  - KON: +5
  - INT: -4
  - WEI: +0
  - CHA: -5
damage_vulnerabilities: ""
damage_resistances: ""
damage_immunities: "Gift, Psychisch"
condition_immunities: "Charmed, Exhaustion, Frightened, Paralyzed, Pertrified, Poisoned"
gear: ""
senses: [[Regularien/2014/Grundregelwerk/08-Abenteuersuche#Dunkelsicht|Dunkelsicht]] 36 Meter, passive Wahrnehmung 10
languages: Versteht Gemeinsprache plus zwei weitere Sprachen, kann aber nicht sprechen
cr: 10
bestiary: true
traits:
  - name: Magische Resistenz.
    desc: "Der Golem ist bei Rettungswürfen gegen Zauber und andere magische Effekte im Vorteil."
  - name: Unveränderliche Form..
    desc: "Der Golem kann seine Form nicht verändern."
actions:
  - name: Mehrfachangriff.
    desc: "Der Golem führt zwei Angriffe aus, wobei er entweder Schmettern oder Energiebolzen in beliebiger Kombination einsetzt."
  - name: Schmettern.
    desc: "_Nahkampfangriffswurf:_ +10, Reichweite 1,5m. _Treffer:_ 15 (2d8 + 5) Wuchtschaden plus 9 (2d8) Energieschaden."
    attack_bonus: 10
    damage_dice: 2d8
    damage_bonus: 5
  - name: Energiebolzen.
    desc: "_Fernkampfangriffswurf:_ +9, Reichweite 36m. _Treffer:_ 22 (4d10) Energieschaden."
bonus_actions:
  - name: Verlangsamung.
    desc: "Der Golem wirkt Zauber [Verlangsamung](Verlangsamung.md), ohne Komponenten zu benötigen. Seine Zauberfertigkeit ist Konstitution (Zauber-Rettungswurf SG 17)"
```