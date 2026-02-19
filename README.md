🐾 AutoPurr for WotLK 3.3.5a
A lightweight, flavor-focused addon for Druids (Cat Form) and Shamans (Ghost Wolf). When someone pets you (/pet), your character automatically responds with a purr emote—but only if you are in your feral form!

📥 Actual Version: 1.1.0
Release Date: February 2026

Compatibility: WoW 3.3.5a (WotLK)

Locales: Supports English (enUS/enGB) and German (deDE).

✨ Features
Smart Form Detection: Only triggers if you are in Cat Form or Ghost Wolf.

Anti-Lag Combat Check: Automatically disables itself while UnitAffectingCombat is true to ensure maximum performance during encounters.

Slash Command: Toggle the addon on/off anytime with a simple command.

Multilingual: Automatically detects if your client is set to German or English for triggers and responses.

🛠 How to Use
Installation: Place the AutoPurr folder into your Interface/AddOns/ directory.

Toggle: Use the following command in-game:

/autopurr — Enables or disables the addon.

Macros: If you want to put the toggle on your action bar, the macro is well within the 255-character limit:

Lua
/autopurr
📝 Technical Details (The Code)
The addon monitors CHAT_MSG_TEXT_EMOTE. It uses a localized trigger string and validates your current buffs before sending a SendChatMessage response.

Note: This addon is specifically optimized for the 2010-era 3.3.5a API. It does not save the toggle state between sessions (resets to "Enabled" on login).
