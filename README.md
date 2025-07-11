# 🛰️ SIGNAL 73 - Terminal Exploration Game

A **text-based, immersive sci-fi terminal game** set aboard a mysterious abandoned spacecraft. 

---
## Screenshot

![screenshot](https://github.com/user-attachments/assets/bbd0a768-3194-468f-88ad-39f2764c01e1)


## Live Preview : (https://signal-73-by-elvish.netlify.app)
---

## 🚀 Overview

You awaken with no memory.  
The crew is gone.  
Only a flickering terminal remains active...

**SIGNAL 73** is a story-driven exploration game played entirely through a retro terminal interface.  
Navigate the ship, read lost logs, decrypt signals, collect tools, solve puzzles — and uncover the truth.

---

## 🎮 How to Play

### 🧭 Commands

| Command | Description |
|--------|-------------|
| `help` | Show all available commands |
| `scan` | Examine the current room |
| `pickup [item]` | Collect an item in the room |
| `move [room_name]` | Navigate to another room |
| `read [log_id]` | Access a data log |
| `decode [signal_id]` | Decrypt a mysterious signal |
| `use [item] on [target]` | Use an item to unlock or activate |
| `solve [puzzle_id]` | Solve a puzzle in the current room |
| `inventory` | View your collected items |
| `save` / `load` | Save or load game progress |
| `shutdown` / `reboot` / `join signal` | Special endings (if conditions are met) |

💡 *Tip:* Every item, log, and signal could be a clue. Think, explore, and experiment.

---

## 🧱 Tech Stack

- HTML + CSS (Retro terminal interface)
- JavaScript (Dynamic game logic)
- JSON (Game data for rooms, items, logs, puzzles, signals)
- LocalStorage (Save/load progress)

---
## 📦 Features

- ✅ Immersive terminal UI
- ✅ Inventory system
- ✅ Unlockable rooms
- ✅ Puzzle-solving mechanics
- ✅ Multiple possible endings
- ✅ Save/Load functionality
- ✅ Responsive (mobile support)
- ✅ No external libraries — fully vanilla JS

---

## ✍️ Customization Tips

Want to add **new rooms**, **items**, or even **alternate endings**?  
Simply edit the corresponding JSON files located in the `/data` directory:

📁 /data/
├── rooms.json # Room definitions and descriptions
├── items.json # Collectible items and their behavior
├── logs.json # Discoverable logs and backstory content
├── puzzles.json # Puzzle mechanics and logic
└── signals.json # Decodable alien transmissions

You can enrich the game with your own:

- 🧩 Puzzles
- 📄 Logs
- 📡 Signals
- 🚪 Unlockable rooms
- 🧠 Endings

> 🛠 Pro Tip: Use consistent keys and update all references (like `exits`, `usableOn`, etc.) to ensure your additions function properly.

---
## 🛠️ Credits

Developed with ❤️ by **Elvish Patel**

Inspired by the minimalist and atmospheric game  
🎮 [*A Dark Room*](https://adarkroom.doublespeakgames.com/)

Built entirely using:

- ✅ Vanilla **HTML**
- ✅ Retro-themed **CSS**
- ✅ Functional **JavaScript**
- ❌ No frameworks or external libraries

---

## 🧾 License

**MIT License**  
You are free to:

- ✅ Use
- ✅ Modify
- ✅ Share
- ✅ Distribute

> Attribution is appreciated, but not required.  
If you enjoy the project, a ⭐ would mean a lot!

---


