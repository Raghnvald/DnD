---
Bezeichnung: Bolzen des Kataklysmus
Kategorie: Munition
Eigenschaften:
  - Munition
Kst.: /
Gew.: 0,0375 kg
status: WIP
linter-yaml-title-alias: Bolzen des Kataklysmus
tags:
  - Gegenstand/Ausrüstung/ammunition
  - Gegenstand/Seltenheit/sehr_selten
  - Quelle/5e/tdcsr
aliases:
  - Bolzen des Kataklysmus
---
# Bolzen des Kataklysmus
*Ammunition, very rare*  

- **Weight**: 0.075 lbs.

These steel [crossbow bolts](/3-Mechanics/CLI/items/bolt-xphb.md) were first created by the Jaggenstrike Clan during the "Scattered War", and the secret to crafting them remains well guarded by the "Houses of Kraghammer". Cataclysm bolts are usually kept in sets of ten, though anyone who holds even one can feel it thrumming with magical power. When you hit with an attack using a cataclysm bolt, the attack deals normal damage. Then roll a `dice:d6|noform|noparens|avg` (`d6`) on the following table to determine its additional effect.

**Cataclysm Bolt Effects**

`dice: [](cataclysm-bolts-tdcsr.md#^cataclysm-bolt-effects)`

| dice: d6 | Effect |
|----------|--------|
| 1-2 | The bolt explodes in a blast of fire, dealing `dice:3d8\|noform\|noparens\|avg` (`3d8`) fire damage to the target and each creature within 5 feet of it. |
| 3-4 | The bolt freezes the air around the target into jagged ice. The target and each creature within 5 feet of it must succeed on a DC 17 Dexterity saving throw or take `dice:1d10\|noform\|noparens\|avg` (`1d10`) cold damage and be [restrained](/3-Mechanics/CLI/conditions.md#Restrained) until the end of your next turn. |
| 5 | The bolt releases a pulse of necrotic energy. The target takes `dice:2d6\|noform\|noparens\|avg` (`2d6`) necrotic damage and must succeed on a DC 16 Strength saving throw or be [stunned](/3-Mechanics/CLI/conditions.md#Stunned) until the end of your next turn. |
| 6 | The bolt shatters to unleash a burst of shrapnel. Make six additional ranged attacks against the target, each of which has a `dice:1d20+7\|noform\|noparens\|text(+7)` attack bonus and deals `dice:1d6\|noform\|noparens\|avg` (`1d6`) piercing damage on a hit. |
^cataclysm-bolt-effects

Once the bolt hits, the enchantment ends and it becomes a normal piece of ammunition.

*Source: Tal'Dorei Campaign Setting Reborn p. 194*