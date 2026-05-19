# 水母陪伴 · 用户端原型

桌面陪伴水母的交互原型（静态 HTML，可直接在浏览器中体验）。

## 在线预览

部署 GitHub Pages 后，分享链接形如：

`https://<你的用户名>.github.io/jellyfish-prototype/`

## 本地预览

直接用浏览器打开 `index.html` 即可。

## 部署到 GitHub Pages

1. 在 GitHub 新建仓库（例如 `jellyfish-prototype`），不要勾选 README
2. 在本目录执行：

```bash
git remote add origin https://github.com/<你的用户名>/jellyfish-prototype.git
git push -u origin main
```

3. 打开仓库 **Settings → Pages**
4. **Source** 选 `Deploy from a branch`，Branch 选 `main`，Folder 选 `/ (root)`
5. 保存后等待 1–2 分钟，访问 Pages 给出的 URL

## 文件说明

| 文件 | 说明 |
|------|------|
| `index.html` | 当前最新版（v2），用于 Pages 部署 |
| `jellyfish-user-prototype-v2.html` | v2 源文件 |
| `jellyfish-user-prototype.html` | v1 原型 |
| `jellyfish-prototype.html` | 早期原型 |
| `jellyfish-prd.md` | 产品说明 |
