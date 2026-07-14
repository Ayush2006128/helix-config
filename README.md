# My Helix Config

This config is fine-tuned for my personal use with the help of AI. 
You can use it if you share similar workflow preferences and want a clean, fast setup out of the box.

Currently, it has built-in support for **Rust, Python, Ruby**, and **Web Development** (HTML, CSS, JS/TS, Tailwind CSS) alongside some essential custom keymaps.

## 🚀 Features
- **Auto-formatting** on save enabled for most languages.
- **Bufferline** enabled (displays open buffers as tabs).
- **Current Line Highlight** to always know where your cursor is.

## ⌨️ Keymaps

- `Ctrl+s` - Saves the file (returns to normal mode if in insert mode).
- `Ctrl+n` - Opens file picker (only in normal mode).
- `Ctrl+Alt+r` - Reloads the Helix configuration (only in normal mode).
- `ga` - Opens code actions.

## 📦 Requirements

To get the most out of the language server configurations, you need to install the following dependencies:

### Rust
- **Rust Analyzer**: `rustup component add rust-analyzer`

### Python
- **Ruff** (LSP & Formatter): `uv tool install ruff`
- **Pyright** (Types & Autocomplete): `uv tool install pyright`

### Ruby
- **Solargraph** (LSP for Ruby): `gem install solargraph`
- **Ruby-LSP** (Linting & Formatting): `gem install ruby-lsp`

### Web Development
- **HTML, CSS, TS/JS, & Tailwind**:
  ```bash
  npm install -g vscode-langservers-extracted typescript typescript-language-server @tailwindcss/language-server
  ```

### Fonts
- A **Nerd Font** installed (_I use JetBrainsMono_).

---

That's it! Enjoy your new editor setup.
