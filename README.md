# Vanadium Nuker V2

![Version](https://img.shields.io/badge/version-2.0.0.33-blue)
![C#](https://img.shields.io/badge/language-C%23-green)
![Platform](https://img.shields.io/badge/platform-Windows-blue)

> **⚠️ Support for this project has been discontinued.**  
> There are no updates or support for the tool; it is outdated V2 Edition

**Vanadium Nuker V2** is a powerful Discord server nuker tool written in C#. It allows you to perform various destructive actions on a Discord server using HTTP requests only (no gateway needed). This tool is intended for **educational purposes only** and should only be used on servers you own or have explicit permission to test.

> Made by: RussianHarvey
> 
> GitHub: [github.com/RussiannHarvey](https://github.com/RussiannHarvey)
> 
> Discord Username: russianharvey 
---

## Features

- **Ban Members** – Ban all members in bulk (with optional member fetching).
- **Create Channels** – Mass create text or voice channels.
- **Delete Channels** – Delete all existing channels.
- **Create Roles** – Mass create roles with random colors.
- **Delete Roles** – Delete all existing roles.
- **Spam Channels** – Send a specified number of messages across all text channels (cyclic distribution).

---

## Requirements

- Windows 10/11 (64-bit recommended)
- A Discord bot token with the following permissions:
  - `Ban Members`
  - `Manage Channels`
  - `Manage Roles`
  - `Send Messages`
  - `Read Message History` (for spam)
- The bot must be added to the target server.

---

## Files Included

- `VanadiumNuker.exe` – The main executable.
- `README.md` – This file.

---

## Important Notes

- This tool uses **direct HTTP requests** for maximum speed. Concurrency is limited to 45 tasks at once to avoid hitting rate limits.
- Rate limits are handled with automatic retry.
- All actions are logged with timestamps and include the name/ID of the affected object (e.g., `2026-03-13 15:44:16 [INFO] Created channel general | 123456789012345678`).
- If the bot token or guild ID is invalid, you will be prompted to re-enter them.

---

## Is it safe? Is it a malware / logger?

**No, it's completely safe and contains no malware or loggers.**  
I do not add any malware or logger – I never included and never will include any backdoors, keyloggers, or data stealers. My only intention It was a perfect, simple tool; I didn't include any payloads or malware.

---

## Disclaimer

**This tool is for educational purposes only.** Misusing it on servers you do not own is against Discord's Terms of Service and may result in a permanent ban of your bot and account. The author is not responsible for any damage caused by this tool. Use at your own risk.

---

## Russian Harvey's belief

The reason I'm discontinuing support for the tool is the large number of trolls in the Nuke community. Some might tell me the tool is stolen and that I've included my copyright because of the similarity in design to existing tools. I created it myself and didn't steal any code, but this community's intelligence level doesn't exceed 1%. So fuck skidz

