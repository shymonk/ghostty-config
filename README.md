# Ghostty Configuration

This is my Ghostty terminal configuration, matching the Solarized Dark theme from macOS Terminal.

## Theme Configuration

- **Color Scheme**: Solarized Dark
- **Font**: Menlo Regular 14pt
- **Cursor**: White block cursor
- **Bold Text**: Use bright colors (`bold-is-bright = true`)
- **Background**: 100% opacity

## Keybindings

### Emacs-style Split Management

- `Ctrl+x 2` - Split horizontally (new pane below)
- `Ctrl+x 3` - Split vertically (new pane to the right)
- `Ctrl+x 0` - Close current pane
- `Ctrl+x 1` - Toggle maximize/restore current pane
- `Ctrl+x o` - Switch to next pane
- `Ctrl+x ↑` - Focus pane above
- `Ctrl+x ↓` - Focus pane below
- `Ctrl+x ←` - Focus pane on the left
- `Ctrl+x →` - Focus pane on the right

### Tab Navigation

- `Shift+Command+←` - Previous tab
- `Shift+Command+→` - Next tab

### Quick Terminal

- `Ctrl+\`` - Toggle quick terminal

## Zsh Configuration

To ensure zsh-autosuggestion displays properly in Ghostty, the following is configured in `.zshrc`:

```zsh
export ZSH_AUTOSUGGEST_HIGHLIGHT_STYLE="fg=#586e75"
```

Suggestion text will appear in gray with good contrast against the Solarized Dark background.

## Reload Configuration

After modifying the configuration, you can reload by:
- Using Ghostty's built-in reload function
- Or restarting the Ghostty application

## File Locations

- Configuration file: `~/.config/ghostty/config`
- Zsh configuration: `~/.zshrc`
- This README: `~/.config/ghostty/README.md`
