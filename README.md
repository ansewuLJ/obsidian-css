<h1 align="center">obsidian-css</h1>

<p align="center">A calm, card-based workspace for Obsidian's default theme.</p>

<p align="center">
  <a href="https://github.com/ansewuLJ/obsidian-css/stargazers"><img src="https://img.shields.io/github/stars/ansewuLJ/obsidian-css?style=flat-square" alt="GitHub Stars"></a>
  <a href="https://github.com/ansewuLJ/obsidian-css/releases"><img src="https://img.shields.io/github/v/tag/ansewuLJ/obsidian-css?style=flat-square" alt="Latest Release"></a>
  <a href="https://github.com/ansewuLJ/obsidian-css/releases"><img src="https://img.shields.io/github/downloads/ansewuLJ/obsidian-css/total?style=flat-square" alt="Downloads"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/github/license/ansewuLJ/obsidian-css?style=flat-square" alt="License"></a>
</p>

<p align="center"><strong>English</strong> | <a href="README.zh-CN.md">简体中文</a></p>

https://github.com/user-attachments/assets/e3a76fb1-ee33-4fa0-971a-5b8935e2c16f

Nine drop-in CSS snippets that turn Obsidian's default theme into a calm, editorial workspace: floating cards, pill tabs, an 8-color file tree, Mac-style code blocks in reading view, full-width tables, and a Claudian chat panel that matches the rest of the UI.

No theme to install, no build step, and no plugin configuration. Enable only the snippets you need.

## 🌟 Features

- 🃏 **Card-based workspace** — the left sidebar, editor, and right sidebar become three floating cards with 12px radius, a 1px border, and a soft shadow.
- 🏷️ **Pill tabs** — a 44px tab bar with a clean active pill and a full-width purple underline.
- 🎨 **Colorful file tree** — folder icons cycle through eight colors, with open/closed SVG masks, tinted row hovers, and a text-only purple active file.
- 💻 **Mac-style code blocks in reading view** — dark `#282C34` blocks with traffic-light dots, a fixed copy button, a native thin horizontal scrollbar, and syntax highlighting. Live preview stays close to Obsidian's native block, with rounded corners and a visible theme-colored caret.
- 📊 **Full-width tables** — light gray headers and crisp 1px grids.
- 💬 **Claudian, styled** — matching user bubbles, dark code blocks, and one-click language labels.
- 👻 **Auto-hiding chrome** — view header, ribbon, status bar, vault profile, and scrollbar stay out of the way until you need them.
- 🧩 **Modular** — nine independent files; enable only the ones you want.

---

## 📦 Install

### 1. Download

Download the [latest release](https://github.com/ansewuLJ/obsidian-css/releases/latest) and extract the nine `.css` files into:

```text
<vault>/.obsidian/snippets/
```

Or clone the repository and copy them:

```bash
git clone https://github.com/ansewuLJ/obsidian-css.git
cp obsidian-css/snippets/*.css <vault>/.obsidian/snippets/
```

### 2. Recommended appearance

In **Settings → Appearance**:

| Setting | Value |
| --- | --- |
| Base color | Light |
| Accent color | `#8A5CF5` |
| Theme | Default |

### 3. Enable the snippets

Open **Settings → Appearance → CSS snippets** and enable the files you want.

### 4. Fonts

| Setting | Value |
| --- | --- |
| Interface font | Source Han Sans CN (思源黑体 CN) |
| Text font | `Inter, "Source Han Sans CN"` |
| Monospace font | JetBrains Mono |
| Text font size | 16px |

Install Inter, JetBrains Mono, and Source Han Sans CN first.

---

## 📁 Files

| File | What it does |
| --- | --- |
| [`colors.css`](snippets/colors.css) | Every color variable. Edit colors here and nowhere else. |
| [`layout.css`](snippets/layout.css) | Three cards and spacing; auto-hide for view header, ribbon, status bar and vault profile; scrollbars and resize handles. |
| [`tabs.css`](snippets/tabs.css) | Tab bar height, active pill, purple underline, remove default separators. |
| [`file-tree.css`](snippets/file-tree.css) | 8-color folder icons via SVG masks, hover states, selected file text-only purple, recent files active item. |
| [`code.css`](snippets/code.css) | Reading-view Mac-style code blocks, native-style edit-mode blocks, native scrollbar, inline code, syntax highlighting. |
| [`table.css`](snippets/table.css) | Full-width tables, header background, cell grid. |
| [`claudian.css`](snippets/claudian.css) | Claudian user bubbles, code blocks, language label/copy button, inline code. |
| [`heading-level-hint.css`](snippets/heading-level-hint.css) | Show H1–H6 at the left of headings on hover in reading view. |
| [`titlebar-purple-gradient.css`](snippets/titlebar-purple-gradient.css) | Four-stop purple gradient title bar with light purple text. |

## 📝 Notes

- Each snippet is independent — enable only what you need.
- Apart from `colors.css`, snippets only use variables; the title bar gradient and icon masks are the only literal colors.
- The recommended appearance settings above are the exact setup used in the demo.

## 📜 License

MIT © [ansewuLJ](https://github.com/ansewuLJ)
