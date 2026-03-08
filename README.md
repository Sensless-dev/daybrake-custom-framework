# 🌲 Daybrake Custom Framework

Welcome to the **Daybrake Custom Framework**, a high-performance, immersive survival framework for FiveM. Designed with a gritty, tactical aesthetic, Daybrake focuses on deep survival mechanics, high-stakes inventory management, and a clutter-free gameplay experience.

---

## 📦 Framework Architecture

The framework is composed of several modular resources designed to work together seamlessly:

### 1. 🏗️ Core Framework (`daybrake-core`)
The backbone of the entire ecosystem.
- **Player Management**: Custom player data handling, health/thirst/hunger systems, and persistent database storage.
- **Shared Database**: Centralized configuration for items, vehicles, and world settings.
- **Utility Library**: Shared functions for both client and server to ensure consistent behavior across all modules.
- **Database**: Optimized SQL structure for high-concurrency survival gameplay.

### 2. 🎒 Tactical Inventory (`daybrake-inventory`)
A robust, DayZ-inspired inventory system.
- **Grid-Based Storage**: Visual grid system for item management.
- **Specialized Slots**: Dedicated equipment slots (Headgear, Vest, Backpack, etc.).
- **Horizontal Weapons**: Side-by-side Primary, Secondary, and Melee weapon slots.
- **Survival Mechanics**: Dynamic weight penalties affecting movement and stamina.
- **Quickbar**: Integrated HUD element (press `Z`) for fast access to essential items.

### 3. 👥 Multicharacter System (`daybrake-multicharacter`)
Immersive character selection and creation.
- **Zombie Survival Theme**: Custom UI designed to fit the apocalypse aesthetic.
- **Character Persistence**: Deep integration with the core for seamless data loading.
- **Validation**: Built-in name validation and profanity filtering.

### 4. 🗺️ Spawn Selector (`daybrake-spawnselector`)
Control where your survival journey begins.
- **Tactical Spawning**: Allows players to choose their starting location based on the server's survival zones.
- **Integration**: Works directly with the multicharacter and core systems to ensure a smooth onboarding flow.

*Daybrake Framework — Built for Survivors.*
