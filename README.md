# WAIC 2026 超脑青少年 AI 特别展｜公开分享页

这是一个可直接发布的静态网页，用于公开分享「WAIC 2026 超脑青少年 AI 特别展」与小红书传播合作方向。

## 文件结构

```txt
.
├── index.html
├── assets/
│   └── youth-ai-showcase-hero.jpg
└── README.md
```

## 本地预览

直接双击 `index.html` 即可打开。

也可以在当前文件夹启动本地预览：

```bash
python3 -m http.server 8000
```

然后访问：

```txt
http://localhost:8000
```

## 发布方式

### Netlify

直接把整个文件夹拖到 Netlify 的部署页面即可。

### Vercel

把整个文件夹上传到 GitHub 仓库，在 Vercel 导入该仓库，Framework Preset 选择 `Other`。

### GitHub Pages

把 `index.html`、`assets/` 和 `.nojekyll` 放在仓库根目录，在 Settings -> Pages 中选择 `main / root`。

## 发布前检查

- 入口文件是 `index.html`。
- 页面不依赖 React、Vue 或外部 CDN。
- 首屏图已放在 `assets/` 中，部署时不要漏掉。
- 小红书合作口径保持为传播支持与内容共创方向，具体资源以双方确认和正式公告为准。
