# My VSCode + Neovim Setup

This repository documents my customized Visual Studio Code setup, tailored to bring a Neovim-like experience with enhanced usability and UI tweaks.

---

## Key Features

- **Vim keybindings** via [VSCodeVim](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
- Custom **leader key mappings** (`space` as leader) for common commands:
  - `space + f`: Quick file search in project (centered UI)
  - `space + h`: Toggle integrated terminal at bottom
  - `space + t` to return focus to the editor.
  - `ctrl + n`: Toggle Explorer sidebar (like NvChad)
- Minimal, clean UI with:
  - Hidden default status bar except showing current Vim mode at top-right
  - Centered Quick Open palette for file search
  - Custom colors and fonts (`Dank Mono`, Dracula Spirit theme)
  - Block-style cursor and blinking enabled for a Neovim feel
- Editor configured for smooth coding:
  - Relative line numbers
  - Large line height for readability
  - Disabled unnecessary UI elements (minimap, breadcrumbs, lightbulb, etc.)
 
## Usage

1. Install VSCode and [VSCodeVim extension](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim).
2. Apply custom keybindings from `keybindings.json` (e.g., leader shortcuts).
3. Apply custom settings from `settings.json`:
   - Font family and size
   - Cursor style and blinking
   - UI customizations with `custom-ui-style` extension for focused Vim mode indicator and clean layout.
4. Use `space` as your leader key for quick commands:
   - Press `space + f` to open file search centered on screen.
   - Press `space + h` to open/toggle terminal at the bottom.
   - Press `space + t` to return focus to the editor.
   - Press `ctrl + n` to toggle the explorer sidebar.
---
Side Note:
I recommend disabling the Vim extension or at least the Vim keybindings while typing in the integrated terminal. Otherwise, keys like space might trigger Vim commands instead of being passed to the terminal as normal input.

Gonna be adding more keybinds/configurations soon : )
