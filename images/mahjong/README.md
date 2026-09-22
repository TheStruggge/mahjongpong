# 图片资源替换指南

麻将、按钮、木槽和背景均支持图片资源。正式 PNG 放到 `public/images/mahjong/`，缺失时自动加载 `placeholders/` 中的 SVG。替换后刷新；部署版本需重新构建。

## 30 种麻将

完整命名见 [30 种麻将清单](TILES.md)。建议尺寸 62 × 80，可等比放大；透明 PNG 应包含完整牌身、牌面和侧边。

- `tile-characters-1.png` ～ `tile-characters-9.png`：一万至九万。
- `tile-dots-1.png` ～ `tile-dots-9.png`：一筒至九筒。
- `tile-bamboo-1.png` ～ `tile-bamboo-9.png`：一条至九条。
- `tile-dragon-red.png`：红中。
- `tile-dragon-green.png`：发财。
- `tile-dragon-white.png`：白板。

旧的水果、数字及西风素材仅保留作历史文件，不再用于新关卡。

## 游戏界面

| 文件名 | 用途 | 建议尺寸 |
| --- | --- | --- |
| tray.png | 四格木槽 | 205 × 74 |
| button-shuffle.png | 打乱 | 80 × 80 |
| button-hint.png | 提示 | 80 × 80 |
| button-undo.png | 后退 | 80 × 80 |
| button-settings.png | 设置 | 48 × 48 |

游戏背景直接使用 `placeholders/background.svg` 全屏铺满；底部横条由 CSS 绘制。首页的独立 PNG 在 `public/images/home/`，详见该目录 README。设置面板使用可缩放的 CSS 和 SVG。

`node scripts/generate-mahjong-tiles.mjs` 可重新生成 30 种标准占位牌。`node scripts/generate-placeholders.mjs` 可重新生成 UI 和标准麻将全部占位图。
