# Obsidian CSS Snippets / Obsidian CSS 片段

Light-theme-only CSS snippets for Obsidian 1.14.x, tested with the default Moonstone theme.
仅适配 Obsidian 亮色主题（默认 Moonstone）的 CSS 片段，已在 1.14.5 上验证。

[中文](#中文) · [English](#english)

---

## 中文

### 功能概览

- **卡片布局**：左栏、正文、右栏三块独立圆角卡片，12px 圆角、1px 描边、6px 阴影。
- **标签页**：44px 标签栏；激活标签为圆角药丸 + 3px 紫色下划线。
- **文件树**：文件夹图标按红橙黄绿青蓝紫粉 8 色循环，展开/折叠两种 SVG 形状；悬停整行淡染；选中文件只变紫字。
- **代码块**：深色底、10px 圆角、左上红黄绿圆点、右上复制按钮、内部横向滚动；阅读区与实时预览一致。
- **表格**：通栏、浅灰表头、1px 网格线。
- **Claudian**：用户消息气泡、深色代码块、语言标签点击复制。
- **自动隐藏**：视图标题栏、Ribbon、状态栏、左下库信息栏；鼠标移到对应区域才出现。
- **其他**：标题悬停显示 H1–H6、窗口标题栏紫韵渐变。
- 所有片段只作用于亮色主题，暗色保持 Obsidian 默认。

### 安装

1. 把 `snippets/` 下的 9 个 `.css` 文件复制到你的 vault：

   ```text
   <vault>/.obsidian/snippets/
   ```

2. 打开 Obsidian → 设置 → 外观 → CSS 片段，逐个启用。
3. 字体（推荐）：

   | 项目 | 值 |
   | --- | --- |
   | 界面字体 | 思源黑体 CN |
   | 文本字体 | `Inter, "思源黑体 CN"` |
   | 等宽字体 | JetBrains Mono |
   | 文本字体大小 | 16px |

   需要先在系统中安装 Inter、JetBrains Mono、思源黑体 CN。
4. 建议使用默认亮色主题（Moonstone），并关闭其他同类主题/片段。

### 文件说明

| 文件 | 功能 |
| --- | --- |
| `colors.css` | 全部颜色变量；改色只改这个文件。 |
| `layout.css` | 三块卡片与间距；视图标题栏、Ribbon、状态栏、左下库信息栏的自动隐藏；滚动条与分隔条。 |
| `tabs.css` | 标签栏高度、激活标签药丸、紫色下划线、去掉默认分隔线。 |
| `file-tree.css` | 文件夹 8 色循环图标（SVG mask）、悬停状态、选中文件只变紫字、最近文件当前项。 |
| `code.css` | 阅读区与实时预览代码块、三圆点、复制按钮、横向滚动条、行内代码、语法高亮。 |
| `table.css` | 正文表格通栏、表头底色、单元格网格线。 |
| `claudian.css` | Claudian 用户气泡、代码块、语言标签与复制按钮、行内代码。 |
| `heading-level-hint.css` | 阅读视图鼠标悬停标题时，在左侧显示 H1–H6。 |
| `titlebar-purple-gradient.css` | 窗口标题栏四段紫色渐变与浅紫白文字。 |

### 说明

- 只在 `body.theme-light` 下生效；暗色主题完全走 Obsidian 默认。
- 目标版本：Obsidian 1.14.5。
- 除 `colors.css` 外，片段只引用变量，不写颜色值（标题栏渐变与图标 mask 除外）。

---

## English

### Features

- **Card layout**: three independent rounded cards for the left sidebar, editor and right sidebar; 12px radius, 1px border, 6px shadow.
- **Tabs**: 44px tab bar; the active tab is a rounded pill with a 3px purple underline.
- **File tree**: 8-color folder icons (red, orange, yellow, green, cyan, blue, purple, pink) with open/closed SVG masks; full-row tint on hover; selected file turns purple text only.
- **Code blocks**: dark background, 10px radius, red/yellow/green dots, copy button, horizontal scrolling; consistent in reading view and live preview.
- **Tables**: full width, light gray header, 1px grid.
- **Claudian**: user message bubbles, dark code blocks, clickable language label to copy.
- **Auto-hide**: view header, ribbon, status bar and the bottom-left vault profile; reveal on hover.
- **Extras**: H1–H6 hint on heading hover, purple gradient title bar.
- Light theme only; dark theme keeps Obsidian defaults.

### Installation

1. Copy the nine `.css` files from `snippets/` into your vault:

   ```text
   <vault>/.obsidian/snippets/
   ```

2. Open Obsidian → Settings → Appearance → CSS snippets and enable each file.
3. Fonts (recommended):

   | Setting | Value |
   | --- | --- |
   | Interface font | Source Han Sans CN (思源黑体 CN) |
   | Text font | `Inter, "Source Han Sans CN"` |
   | Monospace font | JetBrains Mono |
   | Text font size | 16px |

   Install Inter, JetBrains Mono and Source Han Sans CN first.
4. Use the default light theme (Moonstone) and disable conflicting themes/snippets.

### Files

| File | Purpose |
| --- | --- |
| `colors.css` | All color variables; edit colors only here. |
| `layout.css` | Cards and spacing; auto-hide for view header, ribbon, status bar and vault profile; scrollbars and resize handles. |
| `tabs.css` | Tab bar height, active pill, purple underline, remove default separators. |
| `file-tree.css` | 8-color folder icons via SVG masks, hover states, selected file text-only purple, recent files active item. |
| `code.css` | Reading/live-preview code blocks, dots, copy button, horizontal scrollbar, inline code, syntax highlighting. |
| `table.css` | Full-width tables, header background, cell grid. |
| `claudian.css` | Claudian user bubbles, code blocks, language label/copy button, inline code. |
| `heading-level-hint.css` | Show H1–H6 at the left of headings on hover in reading view. |
| `titlebar-purple-gradient.css` | Four-stop purple gradient title bar with light purple text. |

### Notes

- Scoped to `body.theme-light`; dark mode keeps Obsidian defaults.
- Tested on Obsidian 1.14.5.
- Apart from `colors.css`, snippets only use variables (the title bar gradient and icon masks are the exceptions).

---

## Repository structure / 仓库结构

```text
obsidian-css/
├── README.md
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
