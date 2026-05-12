---
obsidianUIMode: preview
cssclasses:
- json5e-vehicle
tags:
- ttrpg-cli/compendium/src/5e/aag
- ttrpg-cli/vehicle/terrain/space
- ttrpg-cli/vehicle/type/spelljammer
aliases:
- "Nautiloid"
---
# Nautiloid
*Source: Astral Adventurer's Guide p. 38*  

Built and used by mind flayers, nautiloids are designed exclusively for space travel. They can't float on water, nor can they land safely on the ground.

As an action, a creature attuned to a nautiloid's [spelljamming helm](3-Mechanics/CLI/items/spelljamming-helm-aag.md) and in physical contact with the ship can transport the nautiloid and all creatures and objects aboard it to a different plane of existence, at or near a destination envisioned by the spelljammer (or to a random location on the plane if no destination is envisioned). This property is a feature of the ship, not the [spelljamming helm](3-Mechanics/CLI/items/spelljamming-helm-aag.md). Each time this property is used, roll a `d6`. On a 5–6, the property recharges after 1 minute; otherwise, it can't be used again for 24 hours.

```ad-statblock
title: Nautiloid
![](3-Mechanics/CLI/vehicles/token/nautiloid-aag.webp#token)
*Spelljammer (180 ft. by 30 ft.); space*

- **Armor Class** 15
- **Hit Points** 400
- **Damage Threshold** 15
- **Speed** fly 40 ft. (fly 4½ mph ^[108.0 miles per day])
- **Cargo** 17 tons tons
- **Crew** 20 crew
- **Keel/Beam** 180 ft. by 30 ft.
- **Cost** 50.000 gp

## Weapon: 4 Ballistae (Crew: 3 each)

- **Armor Class** 15
- **Hit Points** 50
- **Cost** 50 gp (ballista), 5 gp (bolt)

It takes 1 action to load a ballista, 1 action to aim it, and 1 action to fire it.

**Bolt.** *Ranged Weapon Attack:* `+6` to hit, range 120/480 ft., one target. *Hit:* 16 (`3d10`) piercing damage.

## Weapon: Mangonel (Crew: 5)

- **Armor Class** 15
- **Hit Points** 100
- **Cost** 100 gp (mangonel), ⏤ (stone)

It takes 2 actions to load the mangonel, 2 actions to aim it, and 1 action to fire it.

**Mangonel Stone.** *Ranged Weapon Attack:* `+5` to hit, range 200/800 ft. (can't hit targets within 60 feet of it), one target. *Hit:* 27 (`5d10`) bludgeoning damage.

## Weapon: Tentacles

- **Cost** ⏤ (included in ship cost)

As an action, the ship's spelljammer can make one of the following attacks with the ship's tentacles.

**Grappling Tentacles.** *Melee Weapon Attack:* `+8` to hit, reach 30 ft., one Huge or Gargantuan target. *Hit:* 22 (`4d10`) bludgeoning damage, and the nautiloid's speed becomes 0 until its spelljammer uses an action to release the target. If the target is a creature, it is grappled (escape DC 16). If the target is another ship, the target's speed becomes 0 until the nautiloid releases it, or until the target or the nautiloid drops to 0 hit points.

**Teleport.** *Melee Spell Attack:* `+8` to hit, reach 30 ft., one creature. *Hit:* The target must succeed on a DC 15 Constitution saving throw or be teleported to an unoccupied space aboard the nautiloid that the nautiloid's spelljammer can see.
```
^statblock