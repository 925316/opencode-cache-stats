<div align="center">
<strong>
    <h1>OpenCode Visual Cache</h1>
    实时 Token 缓存命中率 · TUI 侧边栏可视化<br>
    自适应主题色 · 自动低饱和设计语言 · 支持中/英双语
</strong>
<br>

[![Stars](https://img.shields.io/github/stars/Hotakus/opencode-visual-cache?style=flat-square)](https://github.com/Hotakus/opencode-visual-cache/stargazers)
[![License](https://img.shields.io/github/license/Hotakus/opencode-visual-cache?style=flat-square)](LICENSE)
[![English](https://img.shields.io/badge/English-README-blue?style=flat-square)](README_EN.md)

</div>

---

## 图片展示

<div align="center"> 
<strong>支持折叠，节省侧边栏占用👇</strong> <br>
<img src="./assets/example2.png"></img>
</div>
<div align="center"> 
<strong>展开👇</strong> <br>
<img src="./assets/example1.png"></img>
</div>

---
## 功能

- **缓存命中率**：实时计算并显示缓存命中率，自适应宽度进度条
- **Token 明细**：缓存读 / 缓存写 / 未命中 / 输出，标签左对齐 · 数据右对齐
- **费用与节省**：Session 累计费用 + 缓存命中带来的费用节省
- **模型定价**：显示当前模型的输入 / 缓存读单价（从 provider 配置动态读取）
- **折叠面板**：点击标题折叠为一行，节省侧边栏空间
- **颜色自适应**：命中率 ≥85% 绿 · ≥70% 橙 · <70% 红，颜色从主题色自动去饱和
- **语言适配**：自动检测系统语言

---

## 安装

> [!NOTE]
> 安装方式待定 —— 本喵还在研究如何发布喵~
> 发布后将更新此部分。

```jsonc
// TODO: 安装步骤
```

---

## 调试

强制英文（Windows PowerShell）：

```powershell
$env:CACHE_TUI_LANG="en"; opencode
```

---

## 兼容性

代码完全模型无关，支持所有 OpenCode 兼容的 AI 模型（DeepSeek / Claude / GPT 等）。
Token 数据和定价信息均通过 OpenCode SDK 标准接口获取。

---

## License

MIT
