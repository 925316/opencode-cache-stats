<div align="center">
<strong>
    <h1>OpenCode Visual Cache</h1>
    Real-time Token Cache Hit Rate · TUI Sidebar Visualization<br>
    Adaptive Theme Colors · Auto-desaturated · Chinese / English
</strong>
<br>

[![Stars](https://img.shields.io/github/stars/Hotakus/opencode-visual-cache?style=flat-square)](https://github.com/Hotakus/opencode-visual-cache/stargazers)
[![License](https://img.shields.io/github/license/Hotakus/opencode-visual-cache?style=flat-square)](LICENSE)
[![中文](https://img.shields.io/badge/中文-README-red?style=flat-square)](README.md)

</div>

---

## Screenshots

<div align="center">
<strong>Collapsed 👇</strong> <br>
<img src="./assets/example2.png"></img>
</div>
<div align="center">
<strong>Expanded 👇</strong> <br>
<img src="./assets/example1.png"></img>
</div>

---

## Features

- **Cache Hit Rate**: Real-time `cache_read / total_input × 100%` with adaptive-width progress bar
- **Token Breakdown**: Cache Read / Write / Miss / Output, left-aligned labels, right-aligned values
- **Cost & Savings**: Session cost + cache savings (input_rate − cache_read_rate) × cache_read
- **Model Pricing**: Current model's input / cache-read rates (from provider config)
- **Collapsible**: Click title to fold into one line
- **Adaptive Colors**: ≥85% green · ≥70% orange · <70% red, auto-desaturated from theme
- **Language**: Auto-detects system locale, switches between Chinese and English

---

## Installation

> [!NOTE]
> Installation method TBD — will be updated after publishing.

```jsonc
// TODO: install steps
```

---

## Debug

Force English:

```powershell
# Windows PowerShell
$env:CACHE_TUI_LANG="en"; opencode
```

```bash
# macOS / Linux
CACHE_TUI_LANG=en opencode
```

---

## Compatibility

Model-agnostic — works with all OpenCode-compatible AI models (DeepSeek / Claude / GPT etc.).
Token data and pricing are read via OpenCode SDK standard interfaces.

---

## License

MIT
