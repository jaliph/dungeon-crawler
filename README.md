# Dungeon Crawler

A simple roguelike dungeon crawler game written in Rust, using [bracket-lib](https://github.com/amethyst/bracket-lib) and [legion ECS](https://github.com/amethyst/legion).

## Features

- Procedurally generated dungeons with multiple generation algorithms (Drunkard's Walk, Rooms, Cellular Automata)
- Turn-based gameplay
- Monsters that chase and attack the player
- Field of view (FOV) and fog of war
- Item pickup and inventory system
- Usable items (potions, weapons, etc.)
- Health and combat system
- Win and game over states
- Camera that follows the player
- Keyboard controls (movement, pickup, use items, wait)
- HUD and tooltips
- Themed dungeon tiles (Forest and Dungeon themes)
- Prefab room support
- Multiple dungeon levels, each with unique layout and theme
- Amulet of Yala as the victory objective
- Restart option after death or victory

## Screenshots

![Gameplay 1](screenshots/screenshot1.png)
![Gameplay 2](screenshots/screenshot2.png)

## Getting Started

### Prerequisites

- [Rust](https://www.rust-lang.org/tools/install) (latest stable recommended)
- A terminal (macOS, Linux, or Windows)

### Clone the Repository

```sh
git clone https://github.com/jaliph/dungeon-crawler.git
cd dungeon-crawler
```

### Install Dependencies

All dependencies are managed by Cargo and will be installed automatically.

### Running the Game

```sh
cargo run
```

The game window should open. Use your keyboard to play.

### Controls

- **Arrow keys / WASD**: Move your character
- **1**: Restart after game over or victory

## Project Structure

- `src/main.rs`: Game entry point and main loop
- `src/map.rs`, `src/map_builder.rs`: Dungeon generation and map logic
- `src/systems/`: ECS systems (player, monster, chasing, etc.)
- `src/components.rs`: ECS components
- `resources/`: Game assets (fonts, tiles)

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

MIT

---

*Made with ❤️ in Rust!*