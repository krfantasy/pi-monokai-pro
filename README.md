# pi-monokai-pro

[Monokai Pro (CE)](https://monokai.pro/contribute) theme for the [pi coding agent](https://pi.dev).

Uses the official Monokai Pro palette (default filter): `#FF6188` keyword, `#FC9867` argument, `#FFD866` string, `#A9DC76` function, `#78DCE8` class, `#AB9DF2` constant, with the `#2D2A2E` / `#221F22` / `#19181A` background ladder.

## Install

```bash
# from this repo
pi install ./path/to/pi-monokai-pro

# or from git
pi install git:github.com/krfantasy/pi-monokai-pro

# or via npm
pi install npm:@krfantasy/pi-monokai-pro
```

For a project-local install, add `-l`.

## Activate

Run `/settings` in pi and select **Monokai Pro (CE)**, or set it directly in `settings.json`:

```json
{
  "theme": "Monokai Pro (CE)"
}
```

**Tip:** for the full look, set your terminal background to `#19181A` and enable truecolor (`COLORTERM=truecolor`).

**Hot reload:** edit `themes/monokai-pro.json` while the theme is active and pi applies changes immediately.

## Layout

```text
themes/monokai-pro.json   # the theme (51 tokens, official palette)
package.json              # pi package manifest (pi.themes)
```

## License

MIT. Monokai Pro is a copyrighted color scheme by [Monokai](https://monokai.pro); this package follows the
[Community Edition rules](https://monokai.pro/contribute): default filter only, free and open source,
named "Monokai Pro (CE)".
