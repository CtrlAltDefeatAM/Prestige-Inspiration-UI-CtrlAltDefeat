# Prestige & Inspiration UI
> **Created by CtrlAltDefeat**[cite: 1]

A sleek, lightweight, and highly customizable Meta Currency Manager for Foundry VTT[cite: 1]. Originally designed to support standard D&D 5e Inspiration alongside specialized homebrew mechanics like Pirate Prestige and Crew Reputation (perfect for One Piece D&D campaigns), this module provides a unified, synced interface for your entire table[cite: 1].

---

## ✨ Key Features

### 🎲 Meta-Currency Tracking
* **Inspiration & Prestige:** Easily add or remove Inspiration and Prestige points with a single click[cite: 1].
* **Character Sheet Integration:** Automatically generates passive rulebook features on player character sheets so they always know what their points do without cluttering their uses trackers[cite: 1].
* **Automated Feature Cleanup:** Automatically cleans up residual or legacy feat items on character sheets to prevent duplicate entries[cite: 3].
* **Dual-Write Compatibility:** Safely reads and writes to legacy flags (`curseMeta` and `bruiserData`) to ensure older modules like DevilFruit2 and Curse Stage continue to work perfectly[cite: 3].
* **Smart Reminders:** The system watches player rolls and periodically whispers a friendly reminder if they are sitting on unspent Inspiration or Prestige (triggers every 6 rolls)[cite: 3]. It also fires a welcome message reminding players of their meta currency upon logging in[cite: 3].

### 🏴‍☠️ Crew Reputation & Bounty System
* **Crew Reputation Engine:** Features a built-in, thematic gold-fill slider to track your crew's reputation on their current island[cite: 1]. The GM sets the maximum reputation based on the island size (Diminutive to Colossal) and controls the slider, while players view real-time updates as they complete quests[cite: 1].
* **Animated Wanted Posters:** Displays player bounties with animated "WANTED" styles[cite: 3]. Players can choose from Default Gold, Neon Snap, Tumbler, Cyber Glitch, Redact, or set it to randomly rotate[cite: 3].
* **Dead or Alive Multipliers:** The GM can configure optional percentage multipliers to automatically adjust the displayed bounty value when a character's status changes to "DEAD" or "ALIVE"[cite: 3].

### ⚔️ Tactical Action HUD & Integrations
* **Instant Combat Reference:** Players and GMs can generate a "Tactical HUD" chat card detailing available Actions, Bonus Actions, Reactions, Free Actions, and Movement rules[cite: 1].
* **Smart Whispering:** Clicking the HUD button whispers privately to players to prevent chat bloat, but broadcasts publicly when clicked by the GM[cite: 1].
* **Devil Fruit & Curse Detection:** The HUD automatically detects if a character has Devil Fruit charges or an active Curse Stage, generating dedicated quick-launch macro buttons directly in the interface to open their respective controllers[cite: 3].
* **House Rule Integration:** Includes a custom action button on the HUD to share a GIF and automatically roll a 1d4 bonus with GM approval[cite: 3].
* **Willpower & Haki Engine:** Calculates a character's Willpower and Haki DC behind the scenes based on their level or the number of Haki category items they possess[cite: 3].

### 🔊 Flawless Audio Sync (Chat-Socket Bypass)
* **Zero Permission Errors:** Bypasses standard Foundry player audio restrictions by embedding sound data directly into chat packets[cite: 1].
* **Table-Wide Sync:** When a player uses a point, the sound plays exactly once, perfectly synchronized for every connected client at the table[cite: 1].
* **Custom SFX & Volume:** GMs can assign unique `.ogg` or `.wav` files for adding and removing points via the built-in Foundry FilePicker, as well as control the master volume for these alerts[cite: 1, 3].

### ⚙️ UI, Settings & Quality of Life
* **D&D5e V2 Sheet Integration:** Injects a glowing diamond quick-launch button directly into the V2 character sheet sidebar for seamless access[cite: 3].
* **Global Hotkeys:** Press `Alt+Q` or `Alt+P` at any time to instantly toggle the UI open or closed[cite: 3].
* **Auto-Boot:** The UI automatically pops up for all players and the GM the moment they log into the session[cite: 1].
* **Persistent Data:** All settings, maximum caps, and custom sounds are saved to Foundry's core game settings database, making them 100% immune to accidental macro flag wipes[cite: 1].
* **High Customizability:** Every player can adjust their own UI scale, select a custom hex theme color, disable random bounty animations, or completely hide the HUD tab[cite: 1, 3]. GMs have additional toggles to hide tooltips, wanted values, and the reputation bar[cite: 3].

---

## 🚀 Usage

* **Launch:** The UI will automatically appear when you load into the world[cite: 1].
* **Toggle:** Press `Alt+Q` or `Alt+P` to open or minimize the window[cite: 3]. Alternatively, click the glowing diamond icon injected into the D&D5e V2 character sheet[cite: 3].
* **GM Settings:** Click the Gear/Cog icon in the bottom right of the UI to set Max Inspiration, Max Prestige, Max Island Reputation, master volume, and custom sound effects[cite: 1].
* **Sheet Access:** Click any character portrait in the UI to instantly pull up their Foundry character sheet[cite: 1].

---

## 🤝 Support & Community

If you enjoy this module and want to support the creation of more Foundry VTT tools, macros, and content:
* [Join the Developer Discord!](https://discord.gg/fBf7xw2bmB)[cite: 3]
* [Support the Creator on Patreon!](https://www.patreon.com/Ctrl_Alt_Defeat)[cite: 3]
