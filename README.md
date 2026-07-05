# 超脑 × 小红书青少年 AI 活动｜微信分享页

这是一个可直接部署的静态网页项目，用于团队同步与微信分享。

## 文件结构

```txt
.
├── index.html
└── README.md
```

## 本地预览

直接双击 `index.html` 即可在浏览器中打开。

也可以用本地服务预览：

```bash
python3 -m http.server 8000
```

然后访问：

```txt
http://localhost:8000
```

## 部署方式

### 方式一：Vercel

1. 新建一个 GitHub 仓库
2. 上传本项目文件
3. 在 Vercel 中导入该仓库
4. Framework Preset 选择 `Other`
5. Deploy

### 方式二：Netlify

1. 打开 Netlify
2. 直接拖拽整个文件夹或 zip 包
3. 发布后获得可分享链接

### 方式三：GitHub Pages

1. 新建 GitHub 仓库
2. 上传 `index.html`
3. 打开 Settings → Pages
4. Source 选择 `Deploy from a branch`
5. Branch 选择 `main / root`
6. 保存后等待生成链接

## 适合发给 Codex 的任务说明

请将这个静态页面部署为一个可公开访问的网页，并保证：

- 入口文件为 `index.html`
- 保留移动端适配
- 不引入额外框架
- 不改动正文内容
- 可部署到 Vercel / Netlify / GitHub Pages 任一平台
