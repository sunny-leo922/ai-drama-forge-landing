# AI Drama Forge Landing Page

AI 短剧智能工厂 SaaS 落地页。纯静态 HTML，部署到 GitHub Pages。

## 部署步骤

### 1. 创建 GitHub 仓库

在 GitHub 创建新仓库 `drama-forge-landing`（或使用已有的 `sunny-leo922.github.io` 仓库）

### 2. 推送代码

```bash
cd drama-forge-landing
git init
git add .
git commit -m "AI Drama Forge landing page"
git remote add origin https://github.com/sunny-leo922/drama-forge-landing.git
git branch -M main
git push -u origin main
```

### 3. 启用 GitHub Pages

1. 进入仓库 Settings → Pages
2. Source 选择 "Deploy from a branch"
3. Branch 选择 `main`，目录选择 `/ (root)`
4. 点击 Save

### 4. 访问

等待 1-2 分钟部署完成后，访问：
- `https://sunny-leo922.github.io/drama-forge-landing/`

或者如果推送到 `sunny-leo922.github.io` 仓库的根目录，直接访问：
- `https://sunny-leo922.github.io/`

## 自定义域名（可选）

1. 在 Settings → Pages → Custom domain 填入你的域名
2. 在 DNS 服务商添加 CNAME 记录指向 `sunny-leo922.github.io`
3. 勾选 Enforce HTTPS

## 文件结构

```
drama-forge-landing/
├── index.html    # 单页落地页（完整内联 CSS/JS）
└── README.md     # 本文件
```
