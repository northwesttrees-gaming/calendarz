![Calendar](https://github.com/user-attachments/assets/6ff6fe73-e615-4aa8-9c56-0def3a64cec6)

# 📆 CALENDARZ
Adds calendars and customizable events to the game.

# 📌 USAGE
Requires both servers and players to have the mod installed for this mod to work.

## ⚖ LICENSE
This mod is property of NorthWestTrees (Kieran Martin) and marked as all right's reserved.
### ✔ What's Fine
- Use on servers, LAN or Single Player.
- Making mods addons for the mod using the events.json file.
- Making resource packs for this mod.
- Using this mod in mod packs as long as you provide a direct link to CurseForge.
### ❌ What's NOT Fine
- Distributing the modification without permission.
- Editing the jar file.
- Reverse engineering the modification.
- Using the mods assets for other mods or projects.
- Selling, trading, or profiting from the modification without permission.
- Anything not under the What's Fine list above.
## ✨ FEATURES:
### 🔑 ADMIN COMMANDS
- Server admins can modify the configuration file using the ``/calendaradmin`` command.
- The admin command allows adjusting the speed of the event index cycle.
- Admins can remove specific months, days, and events from the calendar.
- Events for a specified month or day can be retrieved, displaying an index number to facilitate targeted deletions.
- New events can be added, either by creating new months/days or adding to existing ones.
- Calendar events cycle through the event array indexes.
### 📌 PLAYER COMMANDS
- All players have access to the ``/calendar`` command, which opens the calendar interface.
### ⚙ CORE FEATURES
- Compatible with Single Player, LAN, and Multiplayer modes.
- Admins can add, edit, and remove events via the admin command.
- Events are fully customizable.
- Supports leap years.
- Days of the week are supported (Sun, Mon, Tue, Wed, Thu, Fri, and Sat).
- The calendar grid functions similarly to real-world months.
- Current day and event icons are overlaid on the calendar.
- Displays the current month and year at the top of the calendar.
- Admin commands and messages are logged to the server console.
- Players are kicked from the Calendar UI to enable real-time configuration changes by admins.
- Only the current month's calendar view is accessible.
### 🐞 KNOWN ISSUES
- Manually editing and saving changes to the ``events.json`` file while players are viewing the configuration will cause crashes.
  - Solution: Use the admin command to update the file in real time.
