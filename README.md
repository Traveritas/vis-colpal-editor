# kimi-code-theme-editor

Kimi Code CLI TUI 的可视化配色工具——单文件网页，零依赖，双击即用。

实时预览配色效果，一键导出 Kimi Code 自定义主题 JSON。

## 使用

1. 用浏览器打开 `index.html`（无需安装任何东西，也无需联网） 或 访问[在线页面](https://traveritas.github.io/kimi-code-theme-editor/)
2. 点击左侧色块打开取色器调整颜色，或直接从「预设」下拉框套用经典配色
3. 右侧实时预览 Kimi TUI 的模拟界面（消息、Markdown、diff、审批面板、状态栏等）
4. 点「下载 .json」，保存为 `~/.kimi-code/themes/<主题名>.json`
5. 在 kimi 里运行 `/theme` 选择 `Custom: <主题名>`；若修改的是当前正在使用的主题，运行 `/reload-tui` 重新加载

## 功能

- 覆盖 Kimi Code 全部 19 个颜色 token，支持 dark / light 基础色板继承
- 自定义取色面板：饱和度/明度面板、色相滑条、hex 输入、当前主题色快捷复用
- 模拟终端预览，可自定义预览背景色
- 导入已有主题 JSON 继续编辑
- 预设配色：Catppuccin (Mocha/Latte)、Gruvbox (Dark/Light)、Nord、Tokyo Night、Dracula

## 截图

<img width="1950" height="1199" alt="image" src="https://github.com/user-attachments/assets/5d397532-bf89-45c6-9534-6e8c541a6d3f" />


## 预设色板来源

| 预设 | 来源 | 许可证 |
| --- | --- | --- |
| Catppuccin | [catppuccin/palette](https://github.com/catppuccin/palette) | MIT |
| Gruvbox | [morhetz/gruvbox](https://github.com/morhetz/gruvbox) | MIT/X11 |
| Nord | [nordtheme.com](https://www.nordtheme.com/docs/colors-and-palettes) | MIT |
| Tokyo Night | [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim) | Apache-2.0 |
| Dracula | [draculatheme.com](https://draculatheme.com/contribute) | MIT |

颜色 token 定义来自 [Kimi Code 官方文档](https://www.kimi.com/code/docs/en/kimi-code-cli/customization/themes.html)。

## License

MIT
