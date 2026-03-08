# daybrake-custom-framework
daybrake custom framework for zombie like five m framework



# 🌲 Daybrake Custom Framework

Welcome to the **Daybrake Custom Framework**, a high-performance, immersive survival framework for FiveM. Designed with a gritty, tactical aesthetic, Daybrake focuses on deep survival mechanics, high-stakes inventory management, and a clutter-free gameplay experience.

---

## 🎒 Key Features

### 1. Tactical Inventory System (`daybrake-inventory`)
- **DayZ Style Layout**: Grid-based inventory with dedicated equipment slots for headgear, masks, vests, backpacks, and more.
- **Side-by-Side Weapon Slots**: Quick access to Primary, Secondary, and Melee weapons in a streamlined horizontal layout.
- **Dynamic Weight System**: Carrying too much gear will realistically affect your character's movement speed and ability to sprint.
- **Interactive Quickbar**: Toggleable HUD element (press `Z`) for fast item usage, integrated directly into the bottom of the inventory UI.
- **Ground Loot & Proximity**: Dropped items appear in the "Ground" panel when nearby, allowing for seamless scavenging.
- **Disabled Weapon Wheel**: The standard GTA weapon wheel is disabled, forcing players to use their inventory for a more immersive experience.

### 2. Core Framework (`daybrake-core`)
- **Shared Item Database**: A centralized [items.lua](file:///d:/server/txData/FiveMBasicServerCFXDefault_AD5DB5.base/resources/%5Bdaybrake%5D/daybrake-core/shared/items.lua) containing definitions for food, medical supplies, weapons, tools, and clothing.
- **Consumable Logic**: Integrated handling for eating, drinking, and using medical items like bandages and morphine.
- **Item Metadata**: Support for durability, stack sizes, and custom item descriptions.

---

## ⌨️ Controls

| Key | Action |
|-----|--------|
| **TAB** | Open / Close Inventory |
| **ESC** | Close Inventory |
| **Z** | Toggle Quickbar Visibility |
| **1 - 0** | Use Quickbar Slots |
| **Right Click** | Item Context Menu (Use, Split, Drop) |

---

## 🛠️ Admin Commands

Administrators can use the following commands (requires `inventory.admin` ACE permission):

- `/giveitem <playerID> <itemName> <amount>` - Grant items from the core database.
- `/clearinv <playerID>` - Completely wipe a player's inventory.
- `/openinventory <playerID>` - Remotely view and manage a player's gear.

### ACE Setup
Add this to your `server.cfg`:
```bash
add_ace group.admin command.giveitem allow
add_ace group.admin command.clearinv allow
add_ace group.admin command.openinventory allow
```

---

## 🚀 Installation & Development

### Requirements
- FiveM Server (latest artifacts recommended)
- `daybrake-core` (must start before other modules)

### Starting Resources
```bash
ensure daybrake-core
ensure daybrake-inventory
```

---

*Daybrake Framework — Built for Survivors.*
