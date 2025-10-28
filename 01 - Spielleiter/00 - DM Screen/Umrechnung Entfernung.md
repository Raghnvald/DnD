---
tags: [Quelle/5e/Dungeon_Masters_Guide]
Feet: 80
Meter: 0
---
| Type | Input                | Meter               |
| ---- | -------------------- | ------------------- |
| Feet | `INPUT[number:Feet]` | `VIEW[{Feet}/10*3]` |

| Meter | Feet |
| ----- | ---- |
| 1,5   | 5    |
| 3     | 10   |
| 4,5   | 15   |
| 6     | 20   |
| 7,5   | 25   |
| 9     | 30   |
| 10,5  | 35   |
| 12    | 40   |
| 13,5  | 45   |
| 15    | 50   |
| 16,5  | 55   |
| 18    | 60   |
| 19,5  | 65   |
| 21    | 70   |
| 22,5  | 75   |
| 24    | 80   |
| 25,5  | 85   |
| 27    | 90   |
| 28,5  | 95   |
| 30    | 100  |
| 36    | 120  |
| 72    | 240  |
| 96    | 320  |
| 108   | 360  |

m = (ft/10) * 3
“Meter erhälst du, wenn du den Feet-Wert durch 10 dividierst und mit drei multiplizierst”

Alternativ:
m = (ft/5) + (ft/5)/2
“Meter erhälst du, wenn du den Feet-Wert durch 5 dividierst und davon nochmal die Hälfte dazu addierst.”

ft = (m – m/3) * 5
“Feet erhälst du, wenn du vom Meter-Wert ein Drittel abziehst und das Ergebnis mit 5 multiplizierst.”