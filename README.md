# 💤 NeoVim Configuration

🗓️ **Updated on:** _November, 2025_

A custom **NeoVim configuration** designed for personal use — focused on speed, simplicity, and extensibility.

This setup is based on the popular [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) configuration, with personal tweaks and improvements for a cleaner development workflow.

---

## 🚀 Installation

### For Windows
1. Copy the `nvim` directory to:
   ```
   C:\Users\%User_Name%\AppData\Local
   ```

### For Linux
1. Copy the `nvim` directory to:
   ```
   ~/.config
   ```

---

## 🧩 Features

- Based on **kickstart.nvim** for modular and maintainable structure.
- Lightweight and fast — optimized for modern Neovim.
- Preconfigured plugins for:
  - Syntax highlighting and LSP
  - Git integration
  - Autocompletion
  - File explorer and fuzzy finder
- Easy to extend and customize.

---

## ⚙️ Requirements

- **Neovim 0.9+**
- **Git**
- A modern terminal with TrueColor support.

---

## 🛠️ Usage

1. Launch NeoVim:
   ```bash
   nvim
   ```
2. Plugins will automatically install on the first launch.
3. Restart NeoVim after installation is complete.

---

## 🧑‍💻 Customization

You can easily modify or extend the configuration:
- Add or remove plugins in the `lua/plugins` directory.
- Adjust keymaps and settings in `lua/config`.
- Modify themes and visuals as desired.

---

## 🧠 Credits

- [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim) – Base configuration template.
- [Neovim](https://neovim.io/) – The modern Vim editor.
