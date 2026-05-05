# Kanagawa Like for Zed

A Kanagawa-inspired theme for Zed, tuned to feel closer to the darker VS Code and Neovim variants many people expect from Kanagawa.

## Included themes

- `Kanagawa Like Wave`
- `Kanagawa Like Dragon`

## Installation

### Local install in Zed

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

## Notes

- Zed does not map syntax tokens exactly like VS Code or Neovim, so exact visual parity is not always possible.
- This theme aims to capture a similar feel rather than act as a strict 1:1 port.
- Some colors were intentionally adjusted to better match real-world Kanagawa screenshots.

## Development

This repository contains a standalone Zed theme extension.

Main files:

- `extension.toml`
- `themes/`
- `README.md`
- `LICENSE`

## Publishing to the Zed extension store

1. Keep the extension in its own public GitHub repository.
2. Ensure the repository root contains:
   - `extension.toml`
   - `themes/`
   - `README.md`
   - `LICENSE`
3. Open a pull request against [`zed-industries/extensions`](https://github.com/zed-industries/extensions).
4. In that pull request:
   - add the repository as a submodule under `extensions/`
   - add the extension entry to the top-level `extensions.toml`
   - run `pnpm sort-extensions`

## References

- [Developing Extensions](https://zed.dev/docs/extensions/developing-extensions)
- [Themes](https://zed.dev/docs/extensions/themes)
- [zed-industries/extensions](https://github.com/zed-industries/extensions)

## License

MIT
