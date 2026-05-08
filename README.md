# Lance Create · 云澜数创科技

AI 产品设计与开发 — 双语官网（中文 / English）

## 部署

静态站点，部署在 Vercel。

- 主入口：`index.html`
- 配置：`vercel.json`

## 本地预览

任意一种方式：

```bash
# Python
python3 -m http.server 8000

# Node (npx)
npx serve .
```

然后打开 http://localhost:8000

## 技术

- 纯 HTML / CSS / JS（无需构建）
- Google Fonts: Syne, Instrument Sans
- 双语切换（localStorage 持久化）
