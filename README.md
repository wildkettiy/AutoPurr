<h1>🐾 AutoPurr for WotLK 3.3.5a</h1>
A lightweight, flavor-focused addon for Druids (Cat Form) and Shamans (Ghost Wolf). When someone pets you (/pet), your character automatically responds with a purr emote—but only if you are in your feral form!

<h1>📥 Actual Version: 1.1.0</h1>
Release Date: February 2026

<b>Compatibility:</b> WoW 3.3.5a (WotLK)

<b>Locales:</b> Supports English (enUS/enGB) and German (deDE).

<h1>✨ Features</h1>
<b>Smart Form Detection:</b> Only triggers if you are in Cat Form or Ghost Wolf.

<b>Anti-Lag Combat Check:</b> Automatically disables itself while UnitAffectingCombat is true to ensure maximum performance during encounters.

<b>Slash Command:</b> Toggle the addon on/off anytime with a simple command.

<b>Multilingual:</b> Automatically detects if your client is set to German or English for triggers and responses.

<h1>🛠 How to Use</h1>
<b>Installation:</b> Place the AutoPurr folder into your Interface/AddOns/ directory.

Toggle:</b> Use the following command in-game:

/autopurr — Enables or disables the addon.

<h1>📝 Technical Details</h1>
The addon monitors CHAT_MSG_TEXT_EMOTE. It uses a localized trigger string and validates your current buffs before sending a SendChatMessage response.

<b>Note: This addon is specifically optimized for the 2010-era 3.3.5a API. It does not save the toggle state between sessions (resets to "Enabled" on login).</b>
