# Stardew Valley Clone

A 2D farming simulator inspired by *Stardew Valley*, built in Java with [libGDX](https://libgdx.com/) as a team project for the Advanced Programming course.

![Gameplay](docs/Screenshot%202026-11-06%20152329.png)

## Features

- **Accounts & profiles:** register/login, avatar selection, and editable username, nickname, email, and password
- **Multiplayer:** up to 3 players per game, with a choice of map
- **Farming:** plant, water, and harvest crops and trees; forage for wild items
- **Tools & skills:** watering can, scythe, pickaxe, axe, and more, with upgrades and skill levels
- **Fishing & animals:** catch fish, build barns and coops, raise farm animals
- **Crafting & cooking:** recipes and artisan machines (keg, loom, bee house, and more)
- **Economy:** shops such as JojaMart and player-to-player trading
- **Social:** NPCs (e.g. Robin) with quests and rewards, gifts, friendship levels, and marriage
- **World simulation:** day/night cycle, seasons, weather, and an energy system

## Screenshots

| | |
|---|---|
| ![Title screen](docs/Screenshot%202026-11-06%20152001.png) | ![Main menu](docs/Screenshot%202026-11-06%20152056.png) |
| ![Profile](docs/Screenshot%202026-11-06%20152103.png) | ![New game](docs/Screenshot%202026-11-06%20152227.png) |
| ![Store](docs/Screenshot%202026-11-06%20152408.png) | ![NPC quests](docs/Screenshot%202026-11-06%20152329.png) |
| ![Social menu](docs/Screenshot%202026-11-06%20152419.png) | ![Inventory](docs/Screenshot%202026-11-06%20152445.png) |
| ![Tools menu](docs/Screenshot%202026-11-06%20152439.png) | ![Gameplay](docs/Screenshot%202026-11-06%20152322.png) |

## Tech Stack

Java · libGDX · Gradle (LWJGL3 desktop backend)

## Getting Started

**Requirements:** JDK 23

Run the following commands in your terminal:

git clone [https://github.com/shayan24soley85/adv-programming-stardew-valley.git](https://github.com/shayan24soley85/adv-programming-stardew-valley.git)
cd adv-programming-stardew-valley
./gradlew lwjgl3:run

On Windows, use `gradlew.bat lwjgl3:run`.

### Useful Gradle tasks

- `lwjgl3:run`: starts the game
- `lwjgl3:jar`: builds a runnable JAR in `lwjgl3/build/libs`
- `build`: builds sources and archives of every module
- `clean`: removes `build` folders
- `test`: runs unit tests

## Project Structure

- `core/`: main module with the game logic shared by all platforms
- `lwjgl3/`: desktop launcher (LWJGL3)
- `assets/`: textures, fonts, and other resources

The project was generated with [gdx-liftoff](https://github.com/libgdx/gdx-liftoff).

## Team

Developed by Amirshayan Soleimani Nia, Sina Aghaee Hakak, and Arshia Arab Behjat.
**My contribution:** Lead graphics developer; migrated the game from a terminal-based interface to a fully graphical 2D experience using libGDX, including UI rendering, sprites, and visual systems.
