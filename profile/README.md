# 🎮 ArchiSteamFarm (ASF) – Automated Steam Trading Card Farming Tool

**ArchiSteamFarm (ASF)** is a cross-platform, lightweight utility that automatically farms Steam trading cards, badges, and booster packs.  
It’s designed for advanced users and bot management, allowing you to efficiently manage multiple Steam accounts in a safe and automated way.

> ⚠️ A legitimate Steam account is required. ASF does **not bypass game ownership or Steam rules**.

---

# 🔗 Get the Latest Release

* [📦 View All Releases]()

---

# 🚀 Key Features

* ✅ Automatic farming of Steam trading cards from owned games  
* ✅ Supports multiple Steam accounts simultaneously  
* ✅ Automatic badge crafting and booster pack generation  
* ✅ Fully configurable via `ASF.json` and `BotName.json` files  
* ✅ Cross-platform: Windows, Linux, macOS, and Docker  
* ✅ Headless operation, ideal for servers or remote setups  
* ✅ Logging, statistics, and real-time notifications  

---

# 🧰 Requirements

Before running ASF, ensure you have:

* A **Steam account** (or multiple accounts for multi-bot setup)  
* **.NET 7 Runtime** or **.NET Core 3.1+** installed  
* Internet connection for Steam API  
* Steam Guard enabled for account security  
* Optional: Docker for containerized deployment  

---

# ⚡ Installation & Setup Guide

## 1️⃣ Download ASF

Download the latest release for your platform from the [Releases]() page.

## 2️⃣ Extract Files

Unpack the archive to your preferred folder. ASF is fully portable and does **not require installation**.

## 3️⃣ Configure Bot

* Rename `example-bot.json` to `BotName.json`  
* Edit login credentials, steamID, and farm settings  

## 4️⃣ Run ASF

Launch the executable:  

* Windows: double-click `ArchiSteamFarm.exe`  
* Linux/macOS: run `dotnet ArchiSteamFarm.dll`  
* Docker: `docker run --name asf -v /path/to/config:/app/config justarchinet/asf`

## 5️⃣ Monitor Farming

ASF runs in the background, farming trading cards automatically.  
Use the **web dashboard** (optional) for live statistics and bot control.

---

# 🔧 Troubleshooting

| Issue                               | Possible Fix                                                     |
| ----------------------------------- | ---------------------------------------------------------------- |
| Bot not logging in                    | Ensure Steam Guard is enabled and credentials are correct       |
| Cards not dropping                     | Make sure the game is owned and eligible for farming             |
| Badges not crafting                    | Check `BotName.json` badge settings and Steam API connection     |
| ASF crashes or freezes                 | Update .NET runtime and ASF to the latest release                |
| Docker issues                          | Map config folder correctly and ensure proper permissions       |

---

# 💡 Tips & Notes

* Always back up your `ASF.json` and bot config files  
* Supports multiple bots running simultaneously on the same machine  
* Web dashboard requires enabling `WebSocket` in config  
* Works with both official Steam builds and SteamCMD accounts  
* Re-run ASF after Steam updates to maintain farm efficiency  

---

# ⚠️ Disclaimer

ASF is intended strictly for **educational, research, and personal automation purposes**.  
Farming cards in violation of Steam’s Terms of Service can result in account restrictions.  
Use responsibly and only with accounts you legally own.

---

# 🐞 Bug Reports & Support

Found a bug or issue?

* Open a ticket on the ASF GitHub Issues page  
* Include ASF version, OS, logs, and bot configuration if possible  

---

# ⭐ Contributing

ASF welcomes contributions:

* Submit pull requests for bug fixes or features  
* Report broken game or card IDs  
* Improve documentation and setup guides  
* Suggest new features or enhancements  

---

# 📜 License

ASF is released under the **Apache License 2.0**.  
All contributions are subject to the same licensing terms.