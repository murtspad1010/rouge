# Depths of Dread

A browser-based roguelike dungeon crawler. Descend 5 floors and escape with your life.

No build step, no dependencies — just open `index.html`.

## Controls

| Key | Action |
|-----|--------|
| `W A S D` or Arrow keys | Move |
| `H J K L` | Move (vim-style) |
| `Space` or `.` | Wait a turn |
| `R` | Restart |

## How to play

- Bump into enemies to attack them
- Walk over items to pick them up automatically
- Reach the `>` stairs to go deeper
- Kill enemies to gain XP and level up
- Survive all 5 floors to win

## Enemies

| Glyph | Name   | Notes               |
|-------|--------|---------------------|
| `g`   | Goblin | Weak, common        |
| `o`   | Orc    | Appears on floor 2+ |
| `T`   | Troll  | Tough, floor 3+     |
| `D`   | Demon  | Dangerous, floor 4+ |

## Items

| Glyph | Item         | Effect          |
|-------|--------------|-----------------|
| `!`   | Health Potion | Restores 20 HP |
| `/`   | Iron Sword   | +3 attack       |
| `$`   | Gold Coins   | +15 gold        |

## Tips

- Dark tiles are areas you've explored but can't currently see — enemies can lurk there
- If your HP is flashing red, find a potion fast
- Tougher enemies drop more XP — sometimes worth the risk
