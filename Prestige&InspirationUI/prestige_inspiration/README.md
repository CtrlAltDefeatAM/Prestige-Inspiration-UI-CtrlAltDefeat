Prestige & Inspiration UI
Created by CtrlAltDefeat

A sleek, lightweight, and highly customizable Meta Currency Manager for Foundry VTT. Originally designed to support standard D&D 5e Inspiration alongside specialized homebrew mechanics like Pirate Prestige and Crew Reputation (perfect for One Piece D&D campaigns), this module provides a unified, synced interface for your entire table.

✨ Key Features
🎲 Meta-Currency Tracking
Inspiration & Prestige: Easily add or remove Inspiration and Prestige points with a single click.

Character Sheet Integration: Automatically generates passive rulebook features on player character sheets so they always know what their points do without cluttering their uses trackers.

Automatic Roll Reminders: The system watches player rolls and periodically whispers a friendly reminder if they are sitting on unspent Inspiration or Prestige.

🏴‍☠️ Crew Reputation Engine
Visual Slider: A built-in, thematic gold-fill slider to track your crew's reputation on their current island.

GM Controlled, Player Visible: The GM sets the maximum reputation based on the island size (Diminutive to Colossal) and controls the slider. Players can view the bar updating in real-time as they complete quests.

⚔️ Tactical Action HUD
Instant Combat Reference: Players and GMs can generate a "Tactical HUD" chat card detailing available Actions, Bonus Actions, Reactions, Free Actions, and Movement rules.

Smart Whispering: When players click the HUD button, it whispers privately to them to prevent chat bloat. When the GM clicks it, it broadcasts publicly to the table.

🔊 Flawless Audio Sync (Chat-Socket Bypass)
Zero Permission Errors: Bypasses standard Foundry player audio restrictions by embedding sound data directly into chat packets.

Table-Wide Sync: When a player uses a point, the sound plays exactly once, perfectly synchronized for every connected client at the table.

Custom SFX: GMs can assign unique .ogg or .wav files for adding and removing points via the built-in Foundry FilePicker.

⚙️ GM Settings & Quality of Life
Persistent Data: All settings, maximum caps, and custom sounds are saved to Foundry's core game.settings database, making them 100% immune to accidental macro flag wipes.

Global Hotkey: Press Ctrl+1 at any time to instantly toggle the UI open or closed.

Auto-Boot: The UI automatically pops up for all players and the GM the moment they log into the session.

Customization: Every player can adjust their own UI scale and select a custom hex theme color for their personal window.

🚀 Usage
Launch: The UI will automatically appear when you load into the world.

Toggle: Press Ctrl+1 to open or minimize the window.

GM Settings: Click the Gear/Cog icon in the bottom right of the UI to set Max Inspiration, Max Prestige, Max Island Reputation, master volume, and custom sound effects.

Sheet Access: Click any character portrait in the UI to instantly pull up their Foundry character sheet.

🤝 Support & Community
If you enjoy this module and want to support the creation of more Foundry VTT tools, macros, and content:

---

## Install via Manifest (recommended)

1. Foundry → **Add-on Modules** → **Install Module**
2. Paste this **Manifest URL**:
   ```
   https://github.com/CtrlAltDefeatAM/Prestige-Inspiration-UI-CtrlAltDefeat/releases/latest/download/module.json
   ```
3. Install → enable **Prestige & Inspiration CtrlAltDefeat** in **Settings → Manage Modules**

## Manual Install

1. Download the ZIP from the GitHub Release.
2. Unzip into:
   ```
   FoundryVTT/Data/modules/prestige_inspiration/
   ```
3. Restart Foundry (or refresh) and enable the module.

## Use

- The UI auto-launches on world load.
- Press **Ctrl+1** to toggle the UI.
- The compendium includes a macro: **Prestige & Inspiration CtrlAltDefeat**.

## Links

- Patreon: https://www.patreon.com/Ctrl_Alt_Defeat
- Discord: https://discord.gg/fBf7xw2bmB
