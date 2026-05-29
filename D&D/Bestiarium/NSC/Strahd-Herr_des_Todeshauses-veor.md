---
statblock: inline
statblock-link: "#^statblock"
Bezeichnung: Strahd, Master of Death House
Kategorie: Untoter
Größe: Mittelgroß
HG: 15
Habitat:
  - /
image: token/strahd-master-of-death-house-veor.webp
status: WIP
linter-yaml-title-alias: Strahd, Master of Death House
tags:
  - Monster/Größe/Mittelgroß
  - Monster/HG/15
  - Monster/Typ/Untote/vampire
  - Monster/Typ/Untote/wizard
  - Quelle/5e/veor
aliases:
  - Strahd, Master of Death House
---
# Strahd, Master of Death House
*Quelle: Vecna: Vorabend der Verdammnis S. 250*  

Strahd von Zarowitsch ist der Dunkle Fürst von Barovia, einer Domäne des Schreckens. Ohne das Wissen des Dunklen Fürsten geschieht dort nur wenig, wobei Strahd nur selten Aufmerksamkeit für das übrig hat, was er als uninteressante Angelegenheiten niederer Wesen betrachtet.

## Geschichte

Zu seinen Lebzeiten war Strahd von Zarowitsch ein Prinz, ein Soldat und ein Eroberer. Doch seine Machtgier war unstillbar, und er schloss einen Pakt mit den Dunklen Mächten, um unsterblich zu werden. So vertiefte sich seine Bosheit, und in einem Anfall von Eifersucht ermordete er seinen Bruder Sergei. Sergeis Verlobte Tatyana sprang von einem Turm, um Strahd zu entkommen. Sie verschwand in jenen Nebeln, die sich um Barovia erhoben, als Strahd alle anderen in der Burg erschlug. Er wurde zum Vampir, und Barovia wurde eine Domäne des Schreckens. 

Nun halten die Dunklen Mächte Strahd in seinem Reich gefangen und quälen ihn damit, dass er es niemals wieder verlassen kann. Er verbringt seine Zeit damit, sich so gut wie möglich zu amüsieren, indem er die Bevölkerung von Barovia terrorisiert und die Angst und Anbetung genießt, über die er gebietet. 

```statblock
name: Strahd, Herr des Todeshauses
image: token/strahd-master-of-death-house-veor.webp
source:
  - VEoR
size: Mittelgroß
type: Untot
subtype: Vampire, Magier
alignment: Rechtschaffen Böse
ac: 16
ac_class: natürliche Rüstung
hp: 136
hit_dice: 16d8 + 64
modifier: 4
stats:
  - 18
  - 18
  - 18
  - 20
  - 15
  - 18
speed: 30 ft.
saves:
  - dexterity: 9
  - wisdom: 7
  - charisma: 9
skillsaves:
  - name: Arcana
    desc: "+15"
  - name: Perception
    desc: "+12"
  - name: Religion
    desc: "+10"
  - name: Stealth
    desc: "+14"
damage_resistances: necrotic; bludgeoning, piercing, slashing from nonmagical attacks
senses: darkvision 120 ft., passive Perception 22
languages: Abyssal, Common, Draconic, Elvish, Giant, Infernal
cr: "15"
traits:
  - desc: If Strahd fails a saving throw, he can choose to succeed instead.
    name: Legendary Resistance (3/Day)
  - desc: When Strahd is reduced to 0 hit points, he dissolves into mist and immediately teleports to his lair in Castle Ravenloft. After 1d4 hours, Strahd re-forms in a random unoccupied space within his lair, regaining all his hit points.
    name: Master of the House
  - desc: Strahd regains 20 hit points at the start of his turn if he has at least 1 hit point. If he takes radiant damage, this trait doesn't function at the start of his next turn.
    name: Regeneration
  - desc: Strahd can climb difficult surfaces, including upside down on ceilings, without needing to make an ability check.
    name: Spider Climb
  - desc: |-
      Strahd has the following flaws:

      - **Harmed by Running Water.** While in running water, Strahd takes 20 acid damage if he ends his turn there, and he can't use his Change Shape.  
      - **Sunlight Hypersensitivity.** While in sunlight, Strahd takes 20 radiant damage at the start of his turn, has disadvantage on attack rolls and ability checks, and can't use his Change Shape bonus action.  
    name: Vampire Weaknesses
actions:
  - desc: Strahd makes two Death Strike attacks. He can replace one of these attacks with Blighted Fire if available.
    name: Multiattack
  - desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one target. *Hit:* 8 (1d8 + 4) slashing damage plus 14 (4d6) necrotic damage. If the target is a creature, Strahd can forgo dealing slashing damage; the target then has the grappled condition (escape DC 18) instead. Strahd can grapple only one creature at a time."
    name: Death Strike
  - desc: Strahd summons shadowy, necrotic fire that fills a 20-foot-radius sphere centered on a point he can see within 90 feet of himself. Each creature in that area must make a DC 18 Dexterity saving throw, taking 14 (4d6) fire damage plus 14 (4d6) necrotic damage on a failed save or half as much damage on a successful one.
    name: Blighted Fire (Recharge 5-6)
  - desc: |-
      Strahd targets one Humanoid he can see within 30 feet of himself. The target must succeed on a DC 17 Wisdom saving throw or have the charmed condition. The charmed target regards Strahd as a trusted friend to be heeded and protected. The target isn't under Strahd's control, but it takes Strahd's requests and actions in the most favorable way.

      Each time Strahd or his companions deal damage to the target, it can repeat the saving throw, ending the effect on itself on a success. Otherwise, the effect lasts 24 hours or until Strahd is reduced to 0 hit points, is on a different plane of existence than the target, or uses a bonus action to end the effect.
    name: Charm
  - desc: |-
      Strahd casts one of the following spells, using Intelligence as the spellcasting ability (spell save DC 18):

      **At will:** Detect Thoughts, Fog Cloud, Mage Hand

      **2/day each:** Animate Dead (as an action), Gust of Wind, Mirror Image, Nondetection

      **1/day each:** Greater Invisibility, Polymorph, Scrying (as an action)
    name: Spellcasting
bonus_actions:
  - desc: "*Melee Weapon Attack:* +9 to hit, reach 5 ft., one creature that has the charmed or grappled condition. *Hit:* 7 (1d6 + 4) piercing damage plus 10 (3d6) necrotic damage. The target's hit point maximum is reduced by an amount equal to the necrotic damage taken, and Strahd regains a number of hit points equal to that amount. The reduction lasts until the target finishes a long rest. The target dies if its hit point maximum is reduced to 0. A Humanoid slain in this way and then buried rises the following night as a vampire spawn under Strahd's control."
    name: Bite
  - desc: "Strahd transforms into a new form or back into his true form. Anything he is wearing transforms with him, but nothing he is carrying does. He reverts to his true form if he dies. When transforming into a new form, Strahd chooses one of the following options:"
    name: Change Shape
  - desc: Strahd transforms into a Tiny bat (flying speed 30 ft.) or a Medium wolf (speed 40 ft.). While in that form, he can't speak, and he retains his game statistics other than his size and speed.
    name: Beast Form
  - desc: Strahd transforms into a Medium cloud of mist. While in this form, Strahd has a flying speed of 20 feet, can hover, and can enter a hostile creature's space and stop there. While in mist form, Strahd can pass through a space without squeezing as long as air can pass through that space, but he can't pass through water. Strahd has advantage on Strength, Dexterity, and Constitution saving throws, and he is immune to all nonmagical damage except the damage he takes as part of his Vampire Weaknesses trait. While in mist form, Strahd can't take any actions, speak, or manipulate objects.
    name: Mist Form
legendary_description: "Legendary Action Uses: 3. Immediately after another creature's turn, Strahd can expend a use to take one of the following actions. Strahd regains all expended uses at the start of each of their turns."
legendary_actions:
  - desc: Strahd moves up to his speed without provoking opportunity attacks.
    name: Cunning Escape
  - desc: Strahd makes one Death Strike attack.
    name: Strike (Costs 2 Actions)
```
^statblock