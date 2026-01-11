
# 🎮 THE GAME STOPS LISTENING

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Godot](https://img.shields.io/badge/engine-Godot%204-3d9970)](https://godotengine.org)
[![Language](https://img.shields.io/badge/language-C%23-239120)](https://github.com)
![Status](https://img.shields.io/badge/status-In%20Development-orange.svg)
[
![Stars](https://img.shields.io/github/stars/echind4/THE-GAME-STOPS-LISTENING)](https://github.com/echind4/THE-GAME-STOPS-LISTENING/stargazers)

> You press a button.  
> The game hears you.  
> It just doesn’t answer right away.

---

## 📌 About

**The Game Stops Listening** is a short, conceptual and psychological game focused on a single idea:  
**what happens when the game slowly stops responding to you?**

You finish the game.  
It restarts.  
The input delay increases.  
Again.  
And again.

Eventually, control becomes unreliable.  
Not because of bugs.  
But because that’s the point.

---

## 🧩 This Repository

This repository contains the **open source version** of *The Game Stops Listening*.

- ❌ Does **not** include the original source code  
- ✅ Uses **Godot 4**, the same engine as the release version  
- ✅ Fully rewritten in **C#**  
- ⚙️ Heavily optimized  
- 🛠️ Designed for **modding, experimentation and future expansion**

---

## 🔍 Differences Between Versions

| Feature | ORIGINAL | OPEN SOURCE |
|------|---------|-------------|
| Engine | Godot 3.5 (pre-update) | Godot 4 |
| Language | GDScript | C# |
| Camera | Different behavior front/back | Unified camera, smoother movement |
| Effects | Simple camera overlays | Real effects via `Control` nodes |
| Progression | Same level repeated 3 times with more delay | 3 levels in sequence, then restart with higher delay |
| Console | None | Built-in console (expanding) |
| Proportion | 4:3 | 16:9 |

---

## 🕹️ Gameplay Concept

- The game has **3 stages**
- After finishing them, the game **restarts**
- Each restart increases **input delay**
- The delay affects all player actions
- Over time, the game stops obeying you

This is not a reaction test.  
This is a patience test.

---

## 🛣️ Roadmap

### ✔ Version 1.0 *(in progress)*

- Full **C# release**
- Focus on **stability**
- Minimal bugs

### 🔜 Version 1.1

- **Infinite Mode**
- Basic console

### 🔜 Version 1.2

- Additional **visual effects**
- Stronger atmosphere

### 🔜 Version 1.3

- **Multiplatform support**

### 🔜 Version 1.4 *(planned final)*

- Full console:
  - Physics modification  
  - Gameplay parameter control  
- **Level editor**  
- Level sharing:
  - `lvl_share` generates a hash  
  - `lvl_play` loads a level from the hash

### ❓ Version 1.5 *(maybe)*

- Functional **leaderboard**
- *(If possible)* Online mode





