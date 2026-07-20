![Version](https://img.shields.io/badge/Version-3.0-blue?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/USMCsky/7DTD_Indestructible_Traps?style=for-the-badge)
![Language](https://img.shields.io/badge/Language-XML-orange?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-USMCsky-blue?style=for-the-badge)

# 7DTD Indestructible Traps

A lightweight **server-side XML mod** for **7 Days to Die V3.0** that makes **Electric Fences** and **Blade Traps** effectively indestructible.

Because this mod uses XML patches only, **clients do not need to install anything**.

## 🌟 Features
- **Electric Fence Buff**
  - Sets `electricfencepost` to take no incoming damage.
  - Raises electric fence durability ceiling.

- **Blade Trap Buff**
  - Sets `bladeTrap` to take no incoming damage.

- **Blade Trap Material Buff**
  - Raises `MmetalBladeTrap` durability so blade traps no longer break under normal use.

- **Server-Side Only**
  - No UI, loot, or client asset changes.

## 📁 Project Structure
The project follows a modular structure, with configuration files separated by concern:

```text
Mods/
└── IndestructibleTraps/
    ├── ModInfo.xml
    └── Config/
        ├── blocks.xml
        └── materials.xml
```

## 🛠 Installation
1. Place the `IndestructibleTraps` folder into your server's `Mods` directory.
2. Remove any older duplicate copy from `%AppData%\7DaysToDie\Mods` or the game can load that version first.
3. Restart the server so the XML patches load.

## ✅ Compatibility
- Target game version: **7 Days to Die V3.0**
- Server-side modlet format (XML patch only)
