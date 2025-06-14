# ⚙️ Discord Moderation Bot

A feature-rich Discord moderation bot designed for server security, automation, and user management. Built with modular commands, event handling, and smart automod tools — perfect for any Discord community or RP server.

---

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Status](https://img.shields.io/badge/status-active-success)
[![Join our Discord](https://img.shields.io/discord/1336789892180738162?style=flat-square&logo=discord)](https://discord.gg/pHsTfwAXbF)
[![Support me on Patreon](https://img.shields.io/badge/Patreon-FF424D?style=flat&logo=patreon&logoColor=white)](https://www.patreon.com/c/smocdevelopment/membership)





## 📦 Features

### 🔧 Moderation & Utility Commands

All commands are modular and located in the `commands/` directory:

| Command        | Description                                       |
|----------------|---------------------------------------------------|
| `assignrole.js` | Assigns a role to a user                         |
| `ban.js`        | Bans a user from the server and creates a thread for proof in the log channel!                     |
| `dmuser.js`     | You can dm a user but stay anonymous!            |
| `kick.js`       | Kicks a user from the server                     |
| `mute.js`       | Mutes a user                                     |
| `ping.js`       | Checks the bot's latency                         |
| `purge.js`      | Deletes multiple messages                        |
| `removerole.js` | Removes a role from a user                       |
| `report.js`     | Reports a user or issue to staff                 |
| `roleembed.js`  | Sends an embed with self-role buttons            |
| `serverinfo.js` | Shows server details and stats                   |
| `slowmode.js`   | Sets slowmode duration in a channel              |
| `striproles.js` | Removes all roles from a user                    |
| `unban.js`      | Unbans a user by ID                              |
| `userinfo.js`   | Displays user information                        |
| `warn.js`       | Issues a warning to a user                       |

---

### 📡 Event Handlers

Located in the `events/` directory:

- **Welcome System** — Sends a welcome message when a user joins to a channel and DMS.
- **Guild Activity Logger** — Logs joins, leaves, bans, role changes, and more.
- **Account Age Alerts** — Alerts staff if a new user joins with:
  - Less than 2 weeks account age
  - No verified email

---

### 🚨 Automoderation

Built-in automod system includes:

- 🔗 **Link Filter** — Deletes messages with unwanted or suspicious links.
- 🧼 **Word Filter** — Automatically deletes offensive or blacklisted words.
- 👤 **Role Whitelisting** — Bypasses filters for trusted roles.

---

# ⚙️ Setup Instructions

1. **Get the Bot Code**  
   You can either clone the repository or download it as a ZIP file:  
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git


2. **Configure the Bot**
- Gather a Discord Bot Token from the [developer portal](https://discord.com/developers/applications) 
- Please open the configuration file (config.js, .env) included in the folder and fill in all necessary information and requirements.
  
> [!IMPORTANT]  
> Please visit the Discord Developer Portal, navigate to the **Bot** tab, and enable all **Privileged Gateway Intents**:  
> - Presence Intent  
> - Server Members Intent  
> - Message Content Intent

> [!WARNING]  
> The report channel configuration is **not** in the config file. Instead, it’s set in the `commands/report.js` file, within lines 1–5.

## Dedicated Hosting  
You can purchase a hosting service and transfer all your bot files to the server via SFTP.

## Local System Hosting  
Open your command prompt, navigate to your bot’s folder using `cd C:\FilePath`, then start the bot by running `node index.js`.
> [!IMPORTANT]  
> Ensure that you have NODE.JS installed and up to date. https://nodejs.org/en






Join my discord! - https://discord.gg/pHsTfwAXbF I OFFER SUPPORT!


