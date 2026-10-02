# Warm Toast for Zed

<img width="2672" height="1458" alt="Zed 2026-10-02 09 22 17" src="https://github.com/user-attachments/assets/fb5a46d9-3aba-4177-9dbc-14e9e865d0c2" />


Warm Toast is a theme I created to escape the gaudy, carnival-like colors of most editor themes. It's warm, easy
on the eyes, classy coloration, applied to relevant syntax.

Smells like toast!

This is the [Zed](https://zed.dev) port of the
[Warm Toast theme for Visual Studio Code](https://github.com/gpasq/VisualStudioCodeThemeWarmToast).

## Themes

- **Warm Toast** — the original dark theme.
- **Warm Toast Blurred** — the same colors over a translucent, blurred window background.

## Installing

### From the Zed extension registry

1. Open the extensions view (`zed: extensions` in the command palette).
2. Search for **Warm Toast** and click **Install**.
3. Run `theme selector: toggle` and pick **Warm Toast**.

### As a dev extension (local checkout)

1. Clone this repository.
2. In Zed, run `zed: install dev extension` and select the cloned folder.
3. Run `theme selector: toggle` and pick **Warm Toast**.

To make it the default, add this to your Zed `settings.json`:

```json
{
  "theme": "Warm Toast"
}
```

## Publishing a new version

1. Bump `version` in `extension.toml` and push to GitHub.
2. In a fork of [zed-industries/extensions](https://github.com/zed-industries/extensions), add or update this
   repository as a submodule under `extensions/warm-toast`, and set the matching `version` for
   `[warm-toast]` in `extensions.toml`.
3. Run `pnpm sort-extensions` and open a pull request.

## License

[MIT](LICENSE) © Greg Pasquariello / [Tecnicl.com](https://tecnicl.com)

**Enjoy!**
