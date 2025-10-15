# Shoot The Balls

**Shoot The Balls** is a simple arcade game, developed with **Python** and the **Kivy** framework, where your main goal is to **hit the "balls"** falling from the top before they reach the bottom of the screen. Be quick, collect coins, and unlock new skins!

## Key Features

* **Classic Arcade Gameplay:** Hitting the falling balls destroys them, but you lose a life if a ball touches the bottom of the screen.
* **Score and Level System:** The score increases as you hit balls. Reaching score thresholds (multiples of **1000**) increases the game's **level and difficulty**.
* **Coins and Shop:** Collect special **coin balls** (`ShootTheBallsCoin.png`) and use the earned **Balance** in the **Shop Screen** (`ShopScreen`) to buy new enemy skins (e.g., `yellowBila.png` or `greenBila.png`).
* **Persistent Statistics:** The application uses an **SQLite3** database (`stb.sqlite3`) to permanently track your **Highscore** and the history of all games played, including the precise date and time.
* **Pixel Art Style:** The game features a straightforward, minimalist aesthetic with pixelated graphics and a custom **PixeboyFont.ttf** font.
* **Music/Sound:** Includes a looped background music track (`troll.ogg`) that can be toggled on or off.

---

## Technologies Used

* **Language:** Python 3
* **GUI Framework:** Kivy
* **Database:** SQLite3 (for game history, score, and datetime tracking)
* **Data Persistence:** `JsonStore` (for managing coin balance and skin ownership) and `csv` (for skin prices).
* **Time Management:** `pytz` and `datetime` (for correctly localizing and displaying game session times).
* **Mobile Compilation:** **Buildozer** (configured for Android builds with dependencies like `python3`, `kivy`, `sqlite3`, `datetime`, and `pytz`).
