# Dungeon Crawler

A simple roguelike dungeon crawler game written in Rust, using [bracket-lib](https://github.com/amethyst/bracket-lib) and [legion ECS](https://github.com/amethyst/legion).

## Features

- Procedurally generated dungeons
- Turn-based gameplay
- Monsters that chase the player
- Win and game over states

## Screenshots

*WIP*

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