# 🎰 Python Slot Machine Game

This is a simple terminal-based Slot Machine game written in Python. The player can deposit money, place bets on up to 3 lines, and spin to try their luck. The game rewards the player based on matched symbols across the selected lines.

---

## 📂 Project Structure

- `main.py` — Contains all game logic and functions.
- No external libraries required (uses only Python's built-in `random` module).

---

## 🧠 Game Rules

- You can bet on **1 to 3 horizontal lines** (top, middle, bottom).
- You place a **bet per line** (between `$1` and `$100`).
- The slot machine has a **3x3 grid** of symbols (`A`, `B`, `C`, `D`) chosen based on weighted frequencies.
- You **win** if all three symbols in a selected line match.
- Each symbol has a different payout value:

| Symbol | Frequency | Value |
|--------|-----------|-------|
| A      | 2         | 5x    |
| B      | 4         | 4x    |
| C      | 6         | 3x    |
| D      | 8         | 2x    |

---

## 🚀 How to Run

1. Make sure you have Python installed (`Python 3.x`).
2. Download or clone this repository.
3. Run the script:

```bash
python main.py
