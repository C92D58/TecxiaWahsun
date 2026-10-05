# TECXIA × WAHSUN — 品牌包 v1.0

TECXIA 与 WAHSUN 联署的完整品牌资产：标志、交记记号、色彩与字体令牌、应用模板与品牌规范手册。

> **铁律：「×」不是字母 x。**
> 组合中的连接符是一枚设计记号（两笔斜划相交、四端各戴横杠），或文字环境中的乘号「×」（U+00D7）。**任何情况下不得用字母 x 替代** —— 详细信息见[规范手册](https://brand.tecxia.com)第 02 节。

## 目录

```
TecxiaWahsun/
├── index.html                  # 品牌规范手册（单文件站点，零依赖）
├── assets/
│   ├── logo-horizontal.svg     # 横版（墨）
│   ├── logo-horizontal-reversed.svg  # 横版（反白）
│   ├── logo-vertical.svg       # 竖版（墨）
│   ├── logo-vertical-reversed.svg    # 竖版（反白）
│   ├── logo-badge.svg          # 徽标（深底组合）
│   ├── logo-monogram.svg       # 徽记（深底）
│   ├── logo-monogram-paper.svg # 徽记（纸底）
│   ├── mark-cross.svg          # 交记记号（墨）
│   ├── mark-cross-paper.svg    # 交记记号（纸）
│   ├── favicon.svg             # 站点图标（16px 优化）
│   ├── pattern-cross.svg       # 辅助纹样（交记底纹）
│   └── png/                    # 高分辨率 PNG（透明底）
├── tokens/
│   ├── tokens.css              # CSS 变量（--tw-*）
│   └── tokens.json             # 设计令牌（机器可读）
├── applications/
│   ├── business-card-front.svg # 名片正面（90×54mm 模板）
│   ├── business-card-back.svg  # 名片背面
│   └── email-signature.html    # 邮件签名模板
└── README.md
```

## 使用

**网页 / 产品**：直接引用 SVG（矢量、无障碍标签已内置）：

```html
<img src="assets/logo-horizontal.svg" alt="TECXIA × WAHSUN" width="320">
<link rel="icon" href="assets/favicon.svg" type="image/svg+xml">
```

**颜色与字体令牌**：引入 `tokens/tokens.css`，使用 `--tw-*` 变量；构建工具链读取 `tokens/tokens.json`。

**印刷 / 办公**：使用 `assets/png/` 高分辨率版本（2560px 级），或直接将 SVG 交付印厂（字标转外框后输出）。

**名片与邮件**：`applications/` 内为 300dpi 级 SVG 模板与签名 HTML 源码，按注释替换个人信息即可。

## 核心规格

| 项 | 值 |
|---|---|
| 墨 Ink | `#1A1510` |
| 纸 Paper | `#F7F2E9` |
| 赤陶 Signal | `#C25A2E` |
| 夜 Night | `#151009` |
| 西文字体 | -apple-system / SF Pro / Inter |
| 中文 | 苹方 / Noto Sans SC |
| 微文案等宽 | SF Mono / Menlo |
| 标题字距 | 0.18em |
| 字标最小尺寸 | 15px（字标大写高度）；更小仅用徽记 |
| 安全区 | 四周留白 ≥ 记号高度的 ½ |

## 版权

© 2026 **TECXIA × WAHSUN** · 保留所有权利

---

*TECXIA × WAHSUN — brand package v1.0. The conjunction is the hand-drawn cross-mark glyph or "×" (U+00D7); never the letter x. Live handbook: https://brand.tecxia.com*
