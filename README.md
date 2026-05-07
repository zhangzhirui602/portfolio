# Raelyn Zhang — Portfolio / 张芷睿 — 作品集

Personal portfolio site for Raelyn Zhang (张芷睿) — content creator and automation builder based in Lund, Sweden. Available in both English and Chinese.

张芷睿（Raelyn）的个人作品集网站 —— 内容创作者与自动化开发者，现居瑞典隆德。提供中英双语版本。

## Structure / 文件结构

- `index.html` — English version (entry page)
- `index-zh.html` — 中文版本
- Both files share the same layout, styles, and embedded screenshots. Navigation includes a top-right `EN` / `中` toggle to switch languages.
- 两个文件使用相同的布局、样式与嵌入的截图，导航栏右上角有 `EN` / `中` 切换按钮。

## Sections / 页面板块

1. **Hero / 首屏** — intro and availability / 自我介绍与合作开放状态
2. **TikTok Accounts / TikTok 账号** — account snapshots and growth timelines / 账号数据快照与增长时间线
3. **Automation Projects / 自动化项目** — workflow overviews and impact / 工作流概览与成效
4. **About / 关于我** — background and contact / 背景与联系方式

## Running locally / 本地运行

No build step required. The site is pure static HTML.

无需构建步骤，纯静态 HTML。

### Option 1 — Open the file directly / 直接打开文件

English version / 英文版：

```
start index.html
```

Chinese version / 中文版：

```
start index-zh.html
```

(On macOS use `open` instead of `start`. / macOS 系统请将 `start` 替换为 `open`。)

### Option 2 — Run a local static server / 启动本地静态服务器

```
python -m http.server 8000
```

Then visit / 然后访问：

- English: `http://localhost:8000/index.html`
- 中文: `http://localhost:8000/index-zh.html`

Once either page is open, use the `EN` / `中` link in the top-right of the navigation bar to switch between languages.

打开任意一个页面后，可通过导航栏右上角的 `EN` / `中` 链接在中英文之间切换。

## Tech / 技术栈

- HTML5
- CSS3 (custom properties, grid, flexbox)
- Google Fonts: Space Grotesk, Space Mono
