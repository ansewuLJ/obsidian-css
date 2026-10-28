<h1 align="center">obsidian-css</h1>

<p align="center">为 Obsidian 默认主题准备的一套安静、卡片式工作区。</p>

<p align="center">
  <a href="https://github.com/ansewuLJ/obsidian-css/stargazers"><img src="https://img.shields.io/github/stars/ansewuLJ/obsidian-css?style=flat-square" alt="GitHub Stars"></a>
  <a href="https://github.com/ansewuLJ/obsidian-css/releases"><img src="https://img.shields.io/github/v/tag/ansewuLJ/obsidian-css?style=flat-square" alt="最新 Release"></a>
  <a href="https://github.com/ansewuLJ/obsidian-css/releases"><img src="https://img.shields.io/github/downloads/ansewuLJ/obsidian-css/total?style=flat-square" alt="下载量"></a>
  <a href="./LICENSE"><img src="https://img.shields.io/github/license/ansewuLJ/obsidian-css?style=flat-square" alt="许可证"></a>
</p>

<p align="center"><a href="README.md">English</a> | <strong>简体中文</strong></p>

https://github.com/user-attachments/assets/e3a76fb1-ee33-4fa0-971a-5b8935e2c16f

九个即插即用的 CSS 片段，把 Obsidian 默认主题变成一套安静、克制、适合长时间阅读的工作台：三块悬浮卡片、药丸标签、8 色文件树、阅读区的 macOS 风格深色代码块、通栏表格，以及和整体风格统一的 Claudian 面板。

不需要安装主题，不需要构建，也不需要插件配置。按需启用片段即可。

## 🌟 功能

- 🃏 **卡片式工作区** — 左栏、正文、右栏变成三块独立卡片，12px 圆角、1px 描边、柔和阴影。
- 🏷️ **药丸标签** — 44px 标签栏，激活标签是干净的圆角药丸 + 整条紫色下划线。
- 🎨 **彩色文件树** — 文件夹图标按 8 色循环，带展开/折叠两种 SVG 形状；悬停整行淡染，选中文件只变紫字。
- 💻 **阅读区 macOS 风格代码块** — `#282C34` 深色底、红黄绿三圆点、固定右上角复制按钮、系统原生细横向滚动条，支持语法高亮。实时预览保持 Obsidian 原生代码块，只加圆角和主题色光标。
- 📊 **通栏表格** — 浅灰表头、清晰的 1px 网格。
- 💬 **Claudian 同步风格** — 用户气泡、深色代码块、点击语言标签即复制。
- 👻 **自动隐藏** — 视图标题栏、Ribbon、状态栏、左下库信息栏和滚动条，需要时再出现。
- 🧩 **模块化** — 9 个独立文件，只启用你真正需要的片段。

---

## 📦 安装

### 1. 下载

下载 [最新 release](https://github.com/ansewuLJ/obsidian-css/releases/latest)，把 9 个 `.css` 文件解压到：

```text
<vault>/.obsidian/snippets/
```

或者克隆仓库后复制：

```bash
git clone https://github.com/ansewuLJ/obsidian-css.git
cp obsidian-css/snippets/*.css <vault>/.obsidian/snippets/
```

### 2. 推荐外观

在 **设置 → 外观** 中：

| 项目 | 值 |
| --- | --- |
| 基础颜色 | 浅色 |
| 主题色 | `#8A5CF5` |
| 主题 | 默认 |

### 3. 启用片段

打开 **设置 → 外观 → CSS 片段**，逐个启用你需要的文件。

### 4. 字体

| 项目 | 值 |
| --- | --- |
| 界面字体 | 思源黑体 CN |
| 文本字体 | `Inter, "思源黑体 CN"` |
| 等宽字体 | JetBrains Mono |
| 文本字体大小 | 16px |

需要先在系统中安装 Inter、JetBrains Mono、思源黑体 CN。

---

## 📁 文件

| 文件 | 功能 |
| --- | --- |
| [`colors.css`](snippets/colors.css) | 全部颜色变量；改色只改这个文件。 |
| [`layout.css`](snippets/layout.css) | 三块卡片与间距；视图标题栏、Ribbon、状态栏、左下库信息栏的自动隐藏；滚动条与分隔条。 |
| [`tabs.css`](snippets/tabs.css) | 标签栏高度、激活标签药丸、紫色下划线、去掉默认分隔线。 |
| [`file-tree.css`](snippets/file-tree.css) | 文件夹 8 色循环图标（SVG mask）、悬停状态、选中文件只变紫字、最近文件当前项。 |
| [`code.css`](snippets/code.css) | 阅读区 macOS 风格代码块、原生编辑模式代码块、原生滚动条、行内代码、语法高亮。 |
| [`table.css`](snippets/table.css) | 正文表格通栏、表头底色、单元格网格线。 |
| [`claudian.css`](snippets/claudian.css) | Claudian 用户气泡、代码块、语言标签与复制按钮、行内代码。 |
| [`heading-level-hint.css`](snippets/heading-level-hint.css) | 阅读视图鼠标悬停标题时，在左侧显示 H1–H6。 |
| [`titlebar-purple-gradient.css`](snippets/titlebar-purple-gradient.css) | 窗口标题栏四段紫色渐变与浅紫白文字。 |

## 📝 说明

- 每个片段相互独立，按需启用即可。
- 除 `colors.css` 外，片段只引用变量；标题栏渐变和图标 mask 是仅有的颜色字面量。
- 上面的推荐外观设置就是演示所用的完整配置。

## 📜 许可证

MIT © [ansewuLJ](https://github.com/ansewuLJ)
