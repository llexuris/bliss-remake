# 🌿 Bliss SMP Plugin Remake

A modern reimplementation of the original Bliss SMP plugin, designed for the latest versions of [PaperMC](https://papermc.io/). This plugin brings customizable survival mechanics and perks tailored for engaging and balanced SMP gameplay.

---

## 🚀 Features

- ✨ **Custom Perks** – Unique passive abilities or buffs for players (configurable in future versions).
- ⚡ **Lightweight & Fast** – Optimized for minimal server impact.
- 🔁 **Hot Reload Support** – Reload changes without restarting the server (planned).

---

## 📥 Installation

1. Download the latest release from the [Releases](https://github.com/llexuris/bliss-remake/releases) page.
2. Place the `.jar` file into your server’s `/plugins` folder.
3. Restart your server.

---

## 🧪 Commands & Permissions

| Command | Description |
|--------|-------------|
| `/bliss` | Base command for the plugin |
| `/bliss info` | View plugin info and current version |
| `/bliss reload` | Reload plugin (if reloadable features are implemented) |

| Permission | Function |
|------------|----------|
| `bliss.admin` | Access to admin commands |
| `bliss.use` | Default permission for regular players |

---

## 🛠 Development

This plugin is open-source and contributions are welcome!

### Build from Source:
```bash
git clone https://github.com/yourusername/bliss-remake.git
cd bliss-remake
./gradlew build
