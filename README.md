# My Helix config

This config is fine-tuned for my use with the help of AI.
You can use it if you are same as me and have less expectations.

Currently it has support for Rust, Python and Ruby and basic keymaps.

## Keymaps:
- `Ctrl+s` saved the file and if in insert mode then goes to normal mode
- `Ctrl+n` opens file picker (only in normal mode)
- `Ctrl+Alt+r` reloads config (only in normal mode)
- `ga` code actions

It also enables tabline (bufferline in this case) and highlights current line

## Requirements:
- *Ruff (LSP & FormatterPython)* `uv tool install ruff`
- *Pyright (LSP for Python)* `uv tool install pyright`
- *Rust analyser* `rustup component add rust-analyzer`
- *Solargraph (LSP for Ruby)* `gem install solargraph`
- A *Nerd Font* installed _I use JetBrainsMono_

That's it! Enjoy your new editor.
