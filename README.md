# myshell-starship

Traditional Chinese (TC) localized Starship prompt presets.

## Presets

- `starship-kali.toml` — Kali-style two-line frame (`┌──(user㉿host)-[dir]` / `└─$`), inspired by the Kali Linux zsh prompt.
- `starship-tokyo-night.toml` — Powerline-style segments with Tokyo Night-inspired colors (cool blues and purples).

## Features

- **Traditional Chinese (TC) Labels** (e.g., `於` for `at`, `先` for `ahead`).
- **Nerd Font Glyphs** for OS, Git, and language segments.
- **Comprehensive Segment Support** (Git, Node.js, Rust, Docker, etc.).

## Installation

1. Install [Starship](https://starship.rs/).
1. Download the preset you want (`starship-kali.toml` or `starship-tokyo-night.toml`) from this repository.
1. Move it to your configuration directory as:
   - `~/.config/starship.toml`

## Required Font

Requires a [Nerd Font](https://www.nerdfonts.com/) for the symbols to render correctly.

For the best experience with Traditional Chinese (TC) characters and Nerd Font symbols, it is highly recommended to use the **[ENS Font](https://ens.tw/font)**. It combines *Meslo LGSDZ Nerd Font* with *LXGW WenKai TC*, ensuring consistent and beautiful rendering for this preset.
