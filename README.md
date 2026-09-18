# 2005YOO · 中短线投资分析 — 静态宣传页

个人投资分析师宣传站，深色金融风格单页营销站点，可直接在 GitHub Pages 运行。

## 目录结构

```
docs/
├── index.html     # 单页站点（关于我 / 交易体系 / 服务 / 付费咨询 / 联系）
├── css/style.css  # 金融深色主题样式（藏蓝 + 金色）
├── js/main.js     # 交互：导航、滚动动画、数字滚动、进度条
├── .nojekyll      # 禁用 GitHub Pages 的 Jekyll 处理
└── assets/        # 预留静态资源目录
```

## 部署到 GitHub Pages

1. 将本仓库推送到 GitHub。
2. 进入仓库 **Settings → Pages**。
3. **Build and deployment → Source** 选择 `Deploy from a branch`。
4. **Branch** 选择 `main`，目录选择 `/docs`（GitHub Pages 仅支持 `/` 与 `/docs`），点击 Save。
5. 等待 1–2 分钟，访问 `https://<用户名>.github.io/<仓库名>/` 即可。

## 自定义

- 联系方式：站点内所有 X 链接统一指向 `https://x.com/2005yoo`，改品牌/文案直接编辑 `docs/index.html`。
- 配色主题：在 `docs/css/style.css` 顶部的 `:root` 变量中调整 `--gold`、`--bg` 等。
- 付费咨询定价：`docs/index.html` 中 `#pricing` 区块的三个方案。

> 风险提示：站点文案包含投资风险声明，请勿移除；内容不构成投资建议。
