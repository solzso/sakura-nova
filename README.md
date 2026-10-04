<div align="center">

<img src="https://raw.githubusercontent.com/shahinso/sakura-nova/main/images/logo.png" alt="Sakura Nova" width="180" />

# Sakura Nova

**A cosmic cherry-blossom theme for Visual Studio Code.**

Five hand-tuned variants — four dark, one light — built around a single sakura-pink accent,
with full semantic highlighting and a matching terminal palette.

[![Version](https://img.shields.io/badge/version-0.0.1-FF5DA2?labelColor=100E23&style=for-the-badge)](https://marketplace.visualstudio.com/items?itemName=zsn-Rose.sakura-nova-new)
[![Downloads](https://vsmarketplacebadges.dev/downloads/zsn-Rose.sakura-nova-new.svg?style=for-the-badge&colorA=100E23&colorB=91DDFF)](https://marketplace.visualstudio.com/items?itemName=zsn-Rose.sakura-nova-new)
[![License](https://img.shields.io/badge/license-MIT-A1EFD3?labelColor=100E23&style=for-the-badge)](LICENSE)

<sub>Published on the Marketplace as <b>Sakura Nova New</b> — extension ID <code>zsn-Rose.sakura-nova-new</code>.</sub>

</div>

---

## Contents

- [Install](#install)
- [Variants](#variants)
- [Preview](#preview)
- [Color palette](#color-palette)
- [Recommended settings](#recommended-settings)
- [Customizing](#customizing)
- [Language coverage](#language-coverage)
- [Contributing](#contributing)
- [Changelog](#changelog)
- [License](#license)

---

## Install

**From the Marketplace** — open the Extensions view (`Ctrl+Shift+X` / `Cmd+Shift+X`), search for **Sakura Nova New**, and hit **Install**. A few similarly-named sakura themes exist on the Marketplace, so if you want to be certain, the exact extension ID is `zsn-Rose.sakura-nova-new`.

**From Quick Open** — press `Ctrl+P` / `Cmd+P`, then:

```
ext install zsn-Rose.sakura-nova-new
```

**From the CLI:**

```bash
code --install-extension zsn-Rose.sakura-nova-new
```

**Then pick a variant** with `Ctrl+K Ctrl+T` / `Cmd+K Cmd+T`, or run **Preferences: Color Theme** from the Command Palette.

> **Requirements** — VS Code `1.77.0` or later. Works out of the box in restricted/untrusted workspaces and virtual workspaces such as vscode.dev and github.dev, since a color theme is just data.

---

## Variants

| Theme | Base | Editor background | Best for |
| :--- | :--- | :--- | :--- |
| **Sakura Nova Dark** | `vs-dark` | `#100E23` | The default. Violet keywords, mint strings, deep midnight canvas. |
| **Sakura Nova Dark Pro** | `vs-dark` | `#100E23` | Higher-contrast take — pink keywords, cooler variables, extra UI polish. |
| **Sakura Nova Warm** | `vs-dark` | `#231A2D` | Softer plum background that takes the blue edge off long sessions. |
| **Sakura Nova Dark Red** | `vs-dark` | `#100E23` | Rose-forward accents with italic variables. |
| **Sakura Nova Light** | `vs` | `#F8F8F2` | Daylight variant, tuned for contrast rather than washed-out pastels. |

---

## Preview

### Sakura Nova Dark

![#100E23](https://placehold.co/16x16/100E23/100E23.png) ![#AD50EC](https://placehold.co/16x16/AD50EC/AD50EC.png) ![#A1EFD3](https://placehold.co/16x16/A1EFD3/A1EFD3.png) ![#FFC0CB](https://placehold.co/16x16/FFC0CB/FFC0CB.png) <sub>background · keyword · string · cursor</sub>

![Sakura Nova Dark](https://raw.githubusercontent.com/shahinso/sakura-nova/main/images/Sakura-Nova-Dark.png)

### Sakura Nova Dark Pro

![#100E23](https://placehold.co/16x16/100E23/100E23.png) ![#FF75C3](https://placehold.co/16x16/FF75C3/FF75C3.png) ![#ADE292](https://placehold.co/16x16/ADE292/ADE292.png) ![#FFC0CB](https://placehold.co/16x16/FFC0CB/FFC0CB.png) <sub>background · keyword · string · cursor</sub>

![Sakura Nova Dark Pro](https://raw.githubusercontent.com/shahinso/sakura-nova/main/images/Sakura-Nova-Dark-Pro.png)

### Sakura Nova Warm

![#231A2D](https://placehold.co/16x16/231A2D/231A2D.png) ![#FF75C3](https://placehold.co/16x16/FF75C3/FF75C3.png) ![#ADE292](https://placehold.co/16x16/ADE292/ADE292.png) ![#FFC0CB](https://placehold.co/16x16/FFC0CB/FFC0CB.png) <sub>background · keyword · string · cursor</sub>

![Sakura Nova Warm](https://raw.githubusercontent.com/shahinso/sakura-nova/main/images/Sakura-Nova-Warm.png)

### Sakura Nova Dark Red

![#100E23](https://placehold.co/16x16/100E23/100E23.png) ![#F2608F](https://placehold.co/16x16/F2608F/F2608F.png) ![#A1EFD3](https://placehold.co/16x16/A1EFD3/A1EFD3.png) ![#FF5DA2](https://placehold.co/16x16/FF5DA2/FF5DA2.png) <sub>background · keyword · string · cursor</sub>

![Sakura Nova Dark Red](https://raw.githubusercontent.com/shahinso/sakura-nova/main/images/Sakura-Nova-Red.png)

### Sakura Nova Light

![#F8F8F2](https://placehold.co/16x16/F8F8F2/F8F8F2.png) ![#FF00BB](https://placehold.co/16x16/FF00BB/FF00BB.png) ![#40A02B](https://placehold.co/16x16/40A02B/40A02B.png) ![#FF5DA2](https://placehold.co/16x16/FF5DA2/FF5DA2.png) <sub>background · keyword · string · cursor</sub>

![Sakura Nova Light](https://raw.githubusercontent.com/shahinso/sakura-nova/main/images/Sakura-Nova-Light.png)

---

## Color palette

Every variant is built from the same underlying palette — only which UI role gets which color changes. Everything below is read directly from the theme JSON, not eyeballed off a screenshot.

### Brand core

The accent is shared across all five variants, so switching between them never changes the feel of the UI chrome.

| | Name | Hex | Role |
| :--- | :--- | :--- | :--- |
| ![#FF75C3](https://placehold.co/16x16/FF75C3/FF75C3.png) | Blossom | `#FF75C3` | Keywords & headings in Pro / Warm |
| ![#FF5DA2](https://placehold.co/16x16/FF5DA2/FF5DA2.png) | Sakura | `#FF5DA2` | focus border, badges, active line number, tab indicator |
| ![#F02E6E](https://placehold.co/16x16/F02E6E/F02E6E.png) | Rose | `#F02E6E` | Errors, deleted-file indicator & Warm's buttons |
| ![#2CE592](https://placehold.co/16x16/2CE592/2CE592.png) | Nova Green | `#2CE592` | Added-file indicator & terminal green (four dark variants) |
| ![#1DA0E2](https://placehold.co/16x16/1DA0E2/1DA0E2.png) | Comet | `#1DA0E2` | Modified-file indicator & terminal blue (four dark variants) |
| ![#FFC0CB](https://placehold.co/16x16/FFC0CB/FFC0CB.png) | Petal | `#FFC0CB` | Cursor in Dark, Dark Pro & Warm |
| ![#AD50EC](https://placehold.co/16x16/AD50EC/AD50EC.png) | Nova Violet | `#AD50EC` | Keywords in Dark |
| ![#D4BFFF](https://placehold.co/16x16/D4BFFF/D4BFFF.png) | Lavender | `#D4BFFF` | Numbers, constants, types |
| ![#91DDFF](https://placehold.co/16x16/91DDFF/91DDFF.png) | Nova Blue | `#91DDFF` | Functions |
| ![#63F2F1](https://placehold.co/16x16/63F2F1/63F2F1.png) | Aqua | `#63F2F1` | Attributes |
| ![#A1EFD3](https://placehold.co/16x16/A1EFD3/A1EFD3.png) | Mint | `#A1EFD3` | Strings |
| ![#FFB378](https://placehold.co/16x16/FFB378/FFB378.png) | Amber | `#FFB378` | Terminal yellow; bracket accents in some dark variants |
| ![#FFE6B3](https://placehold.co/16x16/FFE6B3/FFE6B3.png) | Honey | `#FFE6B3` | Warnings, conflicts & bright terminal yellow (four dark variants) |
| ![#7F789F](https://placehold.co/16x16/7F789F/7F789F.png) | Dusk | `#7F789F` | Comments, line numbers, muted UI |
| ![#F8F8F2](https://placehold.co/16x16/F8F8F2/F8F8F2.png) | Moonlight | `#F8F8F2` | Foreground |
| ![#100E23](https://placehold.co/16x16/100E23/100E23.png) | Midnight | `#100E23` | Editor background |
| ![#1E1C31](https://placehold.co/16x16/1E1C31/1E1C31.png) | Nebula | `#1E1C31` | Elevated surfaces, line highlight |

### Interface

| Theme | Editor | Chrome | Foreground | Accent | Cursor | Selection |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Dark | `#100E23` | `#16112A` | `#F8F8F2` | `#FF5DA2` | `#FFC0CB` | `#FF5DA2` @ 32% |
| Dark Pro | `#100E23` | `#16112A` | `#F8F8F2` | `#FF5DA2` | `#FFC0CB` | `#FF5DA2` @ 32% |
| Warm | `#231A2D` | `#140D1F` | `#F8F8F2` | `#FF5DA2` | `#FFC0CB` | `#FF5DA2` @ 32% |
| Dark Red | `#100E23` | `#1E1C31` | `#F8F8F2` | `#FF5DA2` | `#FF5DA2` | `#FF5DA2` @ 32% |
| Light | `#F8F8F2` | `#E4EFED` | `#1E1C31` | `#FF5DA2` | `#FF5DA2` | `#FF5DA2` @ 32% |

### Syntax

| Token | Dark | Dark Pro | Warm | Dark Red | Light |
| :--- | :--- | :--- | :--- | :--- | :--- |
| Comment *(italic)* | `#7F789F` | `#7F789F` | `#7F789F` | `#7F789F` | `#9A91A0` |
| Keyword | `#AD50EC` | `#FF75C3` | `#FF75C3` | `#F2608F` | `#FF00BB` |
| String | `#A1EFD3` | `#ADE292` | `#ADE292` | `#A1EFD3` | `#40A02B` |
| Number / constant | `#D4BFFF` | `#D4BFFF` | `#D4BFFF` | `#D4BFFF` | `#8839EF` |
| Function | `#91DDFF` | `#91DDFF` | `#91DDFF` | `#91DDFF` | `#FE640B` |
| Class / type | `#D4BFFF` | `#D4BFFF` | `#D4BFFF` | `#D4BFFF` | `#8839EF` |
| Variable / property | `#F5C2E7` | `#CFEFFF` | `#F5C2E7` | `#F5C2E7` *(italic)* | `#5B5F97` |
| Operator | `#F8F8F2` | `#F8F8F2` | `#F8F8F2` | `#F8F8F2` | `#1E1C31` |
| Tag | `#FF5F94` | `#FF5F94` | `#FF5F94` | `#FF5F94` | `#F02E6E` |
| Attribute | `#63F2F1` | `#63F2F1` | `#63F2F1` | `#63F2F1` | `#1E66F5` |
| Bracket pair 1 / 2 / 3 | `#AD50EC` `#91DDFF` `#FFE6B3` | `#FF75C3` `#91DDFF` `#F4D0D0` | `#FF75C3` `#91DDFF` `#FFE6B3` | `#F2608F` `#91DDFF` `#FFB378` | `#8A38C4` `#0E76B1` `#B25A17` |

<details>
<summary><b>Terminal (ANSI) palette</b></summary>

<br>

**Sakura Nova Dark**

| | Black | Red | Green | Yellow | Blue | Magenta | Cyan | White |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Normal | `#383648` | `#FF5F94` | `#2CE592` | `#FFB378` | `#1DA0E2` | `#AD50EC` | `#87DFEB` | `#8D91A8` |
| Bright | `#7F789F` | `#F2608F` | `#A1EFD3` | `#FFE6B3` | `#91DDFF` | `#FF5DA2` | `#63F2F1` | `#F8F8F2` |

**Sakura Nova Dark Pro**

| | Black | Red | Green | Yellow | Blue | Magenta | Cyan | White |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Normal | `#383648` | `#F02E6E` | `#2CE592` | `#FFB378` | `#1DA0E2` | `#FF75C3` | `#87DFEB` | `#8D91A8` |
| Bright | `#7F789F` | `#F2608F` | `#A1EFD3` | `#FFE6B3` | `#91DDFF` | `#FF5DA2` | `#63F2F1` | `#F8F8F2` |

**Sakura Nova Warm**

| | Black | Red | Green | Yellow | Blue | Magenta | Cyan | White |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Normal | `#383648` | `#F02E6E` | `#2CE592` | `#FFB378` | `#1DA0E2` | `#FF75C3` | `#87DFEB` | `#8D91A8` |
| Bright | `#7F789F` | `#F2608F` | `#A1EFD3` | `#FFE6B3` | `#91DDFF` | `#FF5DA2` | `#63F2F1` | `#F8F8F2` |

**Sakura Nova Dark Red**

| | Black | Red | Green | Yellow | Blue | Magenta | Cyan | White |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Normal | `#383648` | `#F02E6E` | `#2CE592` | `#FFB378` | `#1DA0E2` | `#F2608F` | `#87DFEB` | `#8D91A8` |
| Bright | `#7F789F` | `#F2608F` | `#A1EFD3` | `#FFE6B3` | `#91DDFF` | `#FF5DA2` | `#63F2F1` | `#F8F8F2` |

**Sakura Nova Light**

| | Black | Red | Green | Yellow | Blue | Magenta | Cyan | White |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Normal | `#1E1C31` | `#E01055` | `#40A02B` | `#B25A17` | `#0E76B1` | `#8A38C4` | `#0B7E7E` | `#807F88` |
| Bright | `#6B708D` | `#F02E6E` | `#1CA373` | `#C28200` | `#0096D8` | `#FF4393` | `#0D9F9E` | `#1E1C31` |

</details>

---

## Recommended settings

Sakura Nova ships semantic highlighting and bracket-pair colors, so both are worth leaving on. Drop this into your `settings.json`:

```jsonc
{
  "workbench.colorTheme": "Sakura Nova Dark",

  // Semantic tokens are defined for all five variants
  "editor.semanticHighlighting.enabled": true,

  // Bracket pair colors are theme-defined (3 levels + unexpected)
  "editor.bracketPairColorization.enabled": true,
  "editor.guides.bracketPairs": "active",

  // Pairs well with the theme's italics
  "editor.fontFamily": "'JetBrains Mono', 'Fira Code', 'Cascadia Code', monospace",
  "editor.fontLigatures": true,
  "editor.fontSize": 14,
  "editor.lineHeight": 1.6,

  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": "on",
  "terminal.integrated.fontFamily": "'JetBrains Mono', monospace"
}
```

> **Note on italics** — comments are italic in every variant. Dark Red goes further and italicizes variables and properties throughout; Dark Pro and Warm add a subtle italic to semantic parameters only, visible once `editor.semanticHighlighting.enabled` is on as recommended above. If your font has no true italic, pick one that does (JetBrains Mono, Cascadia Code, Fira Code, Victor Mono) or turn italics off in [Customizing](#customizing) below.

---

## Customizing

Scope your overrides to a single variant so they don't leak into other themes.

```jsonc
{
  "workbench.colorCustomizations": {
    "[Sakura Nova Dark]": {
      "editor.background": "#0B0A1A",
      "editorCursor.foreground": "#FF5DA2",
      "sideBar.background": "#0B0A1A"
    }
  },

  "editor.tokenColorCustomizations": {
    "[Sakura Nova Dark]": {
      // Turn off italic comments
      "comments": { "fontStyle": "" },
      "textMateRules": [
        {
          "scope": "keyword.control",
          "settings": { "foreground": "#FF5DA2" }
        }
      ]
    }
  }
}
```

To find the scope under your cursor, run **Developer: Inspect Editor Tokens and Scopes** from the Command Palette.

---

## Language coverage

Token rules are tuned and visually checked against:

`JavaScript` · `TypeScript` · `JSX / TSX` · `HTML` · `CSS / SCSS` · `Python` · `C` · `C++` · `Rust` · `Go` · `Java` · `Ruby` · `PHP` · `Swift` · `Markdown` · `JSON / JSONC` · `YAML` · `TOML` · `Shell`

Anything not in that list still renders correctly through the base scopes and semantic tokens — open an issue if a language looks off and it'll get a dedicated pass.

---


## Contributing

Issues and pull requests are welcome at [shahinso/sakura-nova](https://github.com/shahinso/sakura-nova/issues).

- Formatting follows the repo's [`.editorconfig`](.editorconfig) — 2-space indents, LF line endings, UTF-8, and a final newline. Markdown files are exempt from trailing-whitespace trimming, since a trailing double-space is a valid Markdown line break.
- Before opening a PR that touches a theme file, run `npm run validate`. It's the same check the release workflow runs, so a label typo or a missing color fails fast either way.
- New or adjusted token rules should be checked against the languages in [Language coverage](#language-coverage). If a language you use looks off, open an issue instead of guessing at a scope.
- Screenshots in [Preview](#preview) are taken from the same **Extension: Preview Sakura Nova** Extension Development Host — keep new ones at a similar window size and zoom level so the set stays consistent.

---

## Changelog

All notable changes are recorded in [CHANGELOG.md](CHANGELOG.md), which follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/) and [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---

## License

[MIT](LICENSE) © [zso](https://github.com/shahinso)

<div align="center">

**If Sakura Nova makes your editor a nicer place to sit, a ⭐ on the repo or a review on the Marketplace goes a long way.**

</div>
