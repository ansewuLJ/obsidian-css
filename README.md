# Obsidian CSS Snippets

> Soft cards, lavender accents, and colorful folders for your Obsidian vault.

Nine drop-in CSS snippets that turn the default **Moonstone** light theme into a calm, editorial workspace — cream-paper cards, pill-shaped tabs, an 8-color file tree, Mac-style dark code blocks, full-width tables, and a Claudian chat panel that finally matches the rest of the UI.

**English** · [简体中文](README.zh-CN.md)

![Obsidian](https://img.shields.io/badge/Obsidian-1.14.5-8A5CF5?style=flat-square&logo=obsidian&logoColor=white)
![Theme](https://img.shields.io/badge/theme-light%20only-8A5CF5?style=flat-square)
![Snippets](https://img.shields.io/badge/snippets-9-8A5CF5?style=flat-square)
![Build](https://img.shields.io/badge/build-none-8A5CF5?style=flat-square)

**Zero-config.** Keep Obsidian's default theme as-is. There is no theme to install, no Style Settings to configure, and no build step — copy the snippets you want and enable only those. Every file is independent, so you can mix and match.

No theme install, no Style Settings, no build step — just nine plain CSS files.

## Highlights

- 🃏 **Card-based workspace** — the left sidebar, editor, and right sidebar become three floating cards with 12px radius, a 1px border, and a soft shadow.
- 🏷️ **Pill tabs** — a 44px tab bar with a clean active pill and a full-width purple underline.
- 🎨 **Colorful file tree** — folder icons cycle through eight colors, with open/closed SVG masks and tinted row hovers.
- 💻 **Mac-style code blocks** — dark `#282C34` blocks with traffic-light dots, a copy button, and horizontal scrolling in both reading view and live preview.
- 📊 **Full-width tables** — light gray headers and crisp 1px grids.
- 💬 **Claudian, styled** — matching user bubbles, dark code blocks, and one-click language labels.
- 🫥 **Auto-hiding chrome** — view header, ribbon, status bar, and vault profile stay out of the way until you need them.
- 🌗 **Light theme only** — every rule is scoped to `body.theme-light`; dark mode keeps Obsidian's defaults.

### Design philosophy

Calm surfaces, one accent color, and movement only when you ask for it.

## Quick start

1. Copy the nine `.css` files from [`snippets/`](snippets/) into your vault:

   ```text
   <vault>/.obsidian/snippets/
   ```

2. Open **Settings → Appearance → CSS snippets** and enable each file.
3. Recommended fonts:

   | Setting | Value |
   | --- | --- |
   | Interface font | Source Han Sans CN (思源黑体 CN) |
   | Text font | `Inter, "Source Han Sans CN"` |
   | Monospace font | JetBrains Mono |
   | Text font size | 16px |

   Install Inter, JetBrains Mono and Source Han Sans CN first.

4. Keep the default light theme (Moonstone). No theme installation is required; enable only the snippets you actually want.

## Files

| File | What it does |
| --- | --- |
| [`colors.css`](snippets/colors.css) | Every color variable. Edit colors here and nowhere else. |
| [`layout.css`](snippets/layout.css) | Three cards and spacing; auto-hide for view header, ribbon, status bar and vault profile; scrollbars and resize handles. |
| [`tabs.css`](snippets/tabs.css) | Tab bar height, active pill, purple underline, remove default separators. |
| [`file-tree.css`](snippets/file-tree.css) | 8-color folder icons via SVG masks, hover states, selected file text-only purple, recent files active item. |
| [`code.css`](snippets/code.css) | Reading/live-preview code blocks, dots, copy button, horizontal scrollbar, inline code, syntax highlighting. |
| [`table.css`](snippets/table.css) | Full-width tables, header background, cell grid. |
| [`claudian.css`](snippets/claudian.css) | Claudian user bubbles, code blocks, language label/copy button, inline code. |
| [`heading-level-hint.css`](snippets/heading-level-hint.css) | Show H1–H6 at the left of headings on hover in reading view. |
| [`titlebar-purple-gradient.css`](snippets/titlebar-purple-gradient.css) | Four-stop purple gradient title bar with light purple text. |

## Notes

- Scoped to `body.theme-light`; dark mode keeps Obsidian defaults.
- Tested on Obsidian **1.14.5** (desktop).
- Apart from `colors.css`, snippets only use variables — the title bar gradient and icon masks are the only literal colors.
- For a detailed, file-by-file reproduction guide, see the Chinese `CSS片段复现说明` in the vault.

## Repository structure

```text
obsidian-css/
├── README.md
├── README.zh-CN.md
└── snippets/
    ├── colors.css
    ├── layout.css
    ├── tabs.css
    ├── file-tree.css
    ├── code.css
    ├── table.css
    ├── claudian.css
    ├── heading-level-hint.css
    └── titlebar-purple-gradient.css
```
