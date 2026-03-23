# Match-3 Game

![C#](https://img.shields.io/badge/language-C%23-239120) ![Unity](https://img.shields.io/badge/engine-Unity-000000?logo=unity) ![Firebase](https://img.shields.io/badge/backend-Firebase-FFCA28?logo=firebase)

A Candy Crush-style match-3 puzzle game built in Unity. Swap adjacent tiles to form matches of three or more, clear the board, and climb the leaderboard. Integrated with Firebase for persistent score tracking.

## Features

- **Match Detection** — Horizontal and vertical match-3 (and longer) detection
- **Tile Swap** — Swipe/click-to-swap with animated tile movement
- **Cascade System** — Gravity-based tile drop and refill after matches
- **Score System** — Points per match, combo multipliers
- **Firebase Integration** — Leaderboard and score persistence via Firebase Realtime Database
- **Level Progression** — Multiple levels with varying board layouts and objectives

## Tech Stack

| Layer | Technology |
|---|---|
| Engine | Unity (2021.x+) |
| Language | C# |
| Backend | Firebase Realtime Database |

## Project Structure

```
Assets/
├── Scripts/
│   ├── Board/          # Board logic, tile management, match detection
│   ├── Tiles/          # Tile types and behaviours
│   ├── UI/             # Score, level UI controllers
│   └── Firebase/       # Leaderboard / data persistence
├── Prefabs/
├── Scenes/
└── Art/
```

## Getting Started

**Prerequisites**
- Unity 2021.3 LTS or newer
- Firebase Unity SDK (add via Package Manager or download from Firebase console)
- A Firebase project with Realtime Database enabled

**Running the project**
1. Clone the repository
   ```bash
   git clone https://github.com/Oppenheimr/Match-3-Game.git
   ```
2. Open with Unity Hub → **Add project from disk**
3. Add your `google-services.json` (Android) or `GoogleService-Info.plist` (iOS) to the `Assets/` folder
4. Open `MainScene` and press **Play**

## Author

**Umutcan Bağcı** — [github.com/Oppenheimr](https://github.com/Oppenheimr)

## License

This project is licensed under the [MIT License](LICENSE).
