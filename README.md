# Cursor Dark for OpenCode

The Cursor editor dark theme (from the [cursor-dark](https://github.com/CedricVerlinden/cursor-dark) VS Code pack), ported to the OpenCode TUI.

Two variants:

- `cursor-dark` — background `#1a1a1a`
- `cursor-less-dark` — background `#242424`

## Install

```sh
mkdir -p ~/.config/opencode/themes
cp cursor-dark.json cursor-less-dark.json ~/.config/opencode/themes/
```

Restart OpenCode and run `/themes` to pick `cursor-dark` or `cursor-less-dark`, or set it in `~/.config/opencode/cli.json`:

```json
{ "$schema": "https://opencode.ai/v2/cli.json", "theme": { "name": "cursor-dark", "mode": "dark" } }
```

## Credits

Ported from [CedricVerlinden/cursor-dark](https://github.com/CedricVerlinden/cursor-dark) (MIT), which repackages the Cursor editor theme. MIT license.
