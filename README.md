# Russian Snippets

Russian text snippets for [Zed](https://zed.dev): emails, meeting notes, and README templates.

## Installation

Install from the Zed extension registry: search for "Russian Snippets" in the Extensions panel.

Or install as a dev extension: clone this repository and use `zed: install dev extension`.

## Usage

Type the prefix and press Tab:

- `письмо` — Russian email template
- `заметка` — Meeting notes template
- `readme-ru` — README template

## Russian spell checking (grammar)

Install the `ltex` extension in Zed, then add to your `settings.json` (global `~/.config/zed/settings.json` or project `.zed/settings.json`):

```jsonc
{
  "lsp": {
    "ltex": {
      "settings": {
        "ltex": { "language": "ru-RU" }
      }
    }
  }
}
```

This enables Russian grammar and spell checking via LanguageTool. No separate plugin is needed.

## Russian UI

Zed has no official i18n API for extensions yet. For a Russian interface use the community builds: https://github.com/LI-NA/zed-i18n (includes `ru-RU`).

## License

MIT
