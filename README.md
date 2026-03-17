# Ghostty Configuration — iTerm2 Dark Theme

Personal [Ghostty](https://ghostty.org/) terminal configuration aligned with the iTerm2 Default Dark color scheme.

## Color Scheme

The palette mirrors iTerm2's default dark theme:

| Color   | Normal    | Bright    |
|---------|-----------|-----------|
| Black   | `#000000` | `#676767` |
| Red     | `#c91b00` | `#ff6d67` |
| Green   | `#00c200` | `#5ff967` |
| Yellow  | `#c7c400` | `#fefb67` |
| Blue    | `#00c5c7` | `#5ffdff` |
| Magenta | `#c930c7` | `#ff76ff` |
| Cyan    | `#00c5c7` | `#5ffdff` |
| White   | `#c7c7c7` | `#feffff` |

- **Background:** `#1d1d1d`
- **Foreground:** `#ffffff`
- **Cursor:** `#ffffff`

## Keybindings

- `Cmd+Shift+[` / `Cmd+Shift+]` — Navigate between tabs (matches iTerm2 defaults)
- `Shift+Enter` — Insert literal newline

## Other Settings

- `bold-is-bright = true` — Bold text uses bright color variants
- `confirm-close-surface = false` — Close tabs/windows without confirmation

## Usage

Place the `config` file at `~/.config/ghostty/config` (the default Ghostty config path).
