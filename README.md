# Kanagawa Like for Zed

A Kanagawa-inspired Zed theme tuned to feel closer to the darker VS Code and Neovim screenshots many people expect from Kanagawa.

Included themes:

- `Kanagawa Like Wave`
- `Kanagawa Like Dragon`

## Local install in Zed

1. Open Zed.
2. Run `zed: install dev extension` from the command palette.
3. Select this folder:

   `kanagawa-like-zed-theme`

4. Open `theme selector: toggle`.
5. Choose `Kanagawa Like Wave` or `Kanagawa Like Dragon`.

## Settings example

```json
{
  "theme": {
    "mode": "system",
    "light": "One Light",
    "dark": "Kanagawa Like Wave"
  }
}
```

## Publish to the Zed extension store

1. Put this extension in its own public GitHub repository.
2. Make sure the repository root contains:
   - `extension.toml`
   - `themes/`
   - `README.md`
   - a valid open-source license file
3. Open a PR against `zed-industries/extensions`.
4. In that PR:
   - add your repo as a Git submodule under `extensions/kanagawa-like`
   - add an entry for the extension in the top-level `extensions.toml`
   - run `pnpm sort-extensions`

Reference docs:

- https://zed.dev/docs/extensions/developing-extensions
- https://zed.dev/docs/extensions/themes
- https://github.com/zed-industries/extensions

## Notes

- Zed does not map syntax tokens exactly like VS Code or Neovim, so perfect parity is unrealistic.
- If you want it even closer to your screenshot, the next step is to tweak the theme in Zed Theme Builder and export updated JSON.
