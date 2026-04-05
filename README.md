<div align="center">

# 心意祝福 · Love Blessings

**纯静态网页** — 沿心形依次弹出祝福小窗，再铺满全屏；可部署到任意服务器。

<br />

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![Deploy](https://img.shields.io/badge/Deploy-Static-9cf?style=flat-square)]()

<br />

</div>

---

## ✨ 效果一览

| 阶段 | 说明 |
|------|------|
| **心形弹窗** | 按参数方程排布，彩色小窗依次出现，每窗一句短祝福 |
| **铺满动画** | 全部出现后，小窗带弹性与错落延迟，移动到网格铺满可视区域 |
| **长文祝福** | 点击底部「打开祝福」打开大卡片，支持换一组文案（不自动弹出） |

---

## 🚀 快速开始

### 本地预览

用浏览器直接打开 `index.html`，或启一个静态服务：

```bash
npx --yes serve .
```

浏览器按终端提示访问（一般为 <http://localhost:3000>）；也可直接用浏览器打开 `index.html`，或使用 VS Code **Live Server** 等扩展。

### 部署到服务器

将 **`index.html`** 放到站点根目录（或任意路径），由 **Nginx / Apache / OSS / GitHub Pages / Netlify** 等托管即可，**无需后端**。

---

## 🎨 自定义

在 `index.html` 内可调整：

| 位置 | 作用 |
|------|------|
| `:root` → `--page-bg-photo` | 自有或已授权的背景图，如 `url("bg.jpg")`；开源默认 `none` |
| `POPUP_DELAY_MS` | 小窗依次出现的间隔（毫秒） |
| `WIN_BLESSINGS` | 小窗内循环使用的短祝福 |
| `BLESSING_SETS` | 大祝福弹层里的长段落（多组轮换） |

---

## 📁 项目结构

```
love/
├── index.html    # 主页面（单文件即可上线）
└── README.md
```

---

## 🖼️ 关于背景图

- 默认 **不包含** 任何第三方图片链接。
- 使用他人作品作背景前，请确保 **有权使用与分发**；开源仓库建议仅保留 `none`，在 README 中说明由部署者自行配置。

---

<div align="center">

<sub>若本项目对你有帮助，欢迎 Star ✨</sub>

</div>
