[![Repo Size](https://img.shields.io/github/repo-size/USMCsky/7DTD_Trap_Buff?style=for-the-badge)](https://github.com/USMCsky/7DTD_Trap_Buff)
[![Last Commit](https://img.shields.io/github/last-commit/USMCsky/7DTD_Trap_Buff?style=for-the-badge)](https://github.com/USMCsky/7DTD_Trap_Buff/commits)
[![Language](https://img.shields.io/badge/language-XML-blue?style=for-the-badge)](https://github.com/USMCsky/7DTD_Trap_Buff)
[![Version](https://img.shields.io/badge/version-3.0-brightgreen?style=for-the-badge)](https://github.com/USMCsky/7DTD_Trap_Buff)

# 7DTD INDESTRUCTIBLE TRAPS

This project is a server-side mod for **7 Days to Die V3.0** that makes **Electric Fences** and **Blade Traps** effectively indestructible.
The mod uses XML patches only, so clients do not need to install anything.

## 🌟 Features
*   **Electric Fence Buff:** Sets `electricfencepost` to take no incoming damage and raises its durability ceiling.
*   **Blade Trap Buff:** Sets `bladeTrap` to take no incoming damage.
*   **Blade Trap Material Buff:** Raises `MmetalBladeTrap` durability so blade traps no longer break under normal use.
*   **Server-Side Only:** No UI, loot, or client asset changes.

## 📁 Project Structure
<code>
The project follows a modular structure, with configuration files separated by concern:
└── Mods
    └── IndestructibleTraps
        ├── ModInfo.xml
        └── Config
            ├── blocks.xml
            └── materials.xml
</code>

### Installation
1.  Place the `IndestructibleTraps` folder into your server's `Mods` directory.
2.  Remove any older duplicate copy from `%AppData%\7DaysToDie\Mods` or the game can load that version first.
3.  Restart the server so the XML patches load.
