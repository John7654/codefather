
# 🧠 CODE FATHER

**Hyper-Thinking AI Developer Agent for Termux**

Build entire websites, PHP apps, Telegram bots, and single-file monsters — right from your terminal.

[![Version](https://img.shields.io/badge/version-2.0.0-blue.svg)](CHANGELOG.md)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Termux-orange.svg)](https://termux.dev)
[![Bash](https://img.shields.io/badge/language-Bash-89e051.svg)](https://www.gnu.org/software/bash/)
[![Telegram](https://img.shields.io/badge/Telegram-@tech__master__a2z-2CA5E0?logo=telegram)](https://t.me/tech_master_a2z)

**Developer:** [Tech Master](https://t.me/tech_master_a2z)

</div>

---

## ✨ Features

| Feature | Description |
|---|---|
| 🧠 **Hyper-Thinking Mode** | Plans the architecture first, then writes code |
| ♾️ **Long-Code Generator** | Up to 25 continuation chunks — writes massive single-file code |
| 🏗 **Builder Mode** | Guided wizard: name → stack → features → deploy → done |
| 🤖 **4 AI Models** | Claude Haiku 4.5 · Gemini · GPT-Logic · Cohere |
| 🐙 **GitHub Upload** | Auto-init, commit, create repo & push with a PAT |
| 🔁 **Auto-Retry** | 4 attempts with exponential backoff on API failures |
| 📎 **File Upload** | Attach any file to the AI prompt |
| 💾 **Shared Storage** | Saves to `/sdcard/CodeFather/` |
| 🗜 **ZIP Export** | One-click project archive |
| 🌐 **Localhost Preview** | Built-in `python -m http.server` / `php -S` |
| 🎨 **Modern UI** | Gradient ASCII banner, animated thinking, spinner |
| 🚫 **No-File API** | In-memory only — nothing persisted from API layer |

---

## 🚀 Installation

### One-line install (Termux)

```bash
pkg install git -y && \
git clone https://github.com/YOUR_USERNAME/codefather.git ~/codefather && \
cd ~/codefather && \
bash install.sh
