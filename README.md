# 太极币 项目展示站

这是根据 PPT 内容生成的静态展示站，使用简单的静态 HTML/CSS 进行构建，方便部署到 GitHub Pages。

快速开始

1. 在 GitHub 上创建一个新仓库（例如 `taichi-coin-site`）。
2. 将本地目录 `d:\TCCWebsite` 初始化为 git 仓库并推送：

```powershell
cd d:\TCCWebsite
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

3. 在仓库设置中启用 GitHub Pages（选择 `main` 分支的 `/ (root)`）。或者使用下面的 GitHub Actions 自动部署到 `gh-pages` 分支（已包含工作流文件）。

替换内容

- 将 PPT 原文件或导出的图片放入 `assets/` 目录并在 `index.html` 中替换引用。
- 如需我代为推送并配置仓库，请授权或提供仓库访问信息。

关于 GitHub Actions 自动部署

- 本仓库已添加 `.github/workflows/gh-pages.yml`，当你将代码推送到 `main` 分支时，Actions 会将仓库根目录内容发布到 `gh-pages` 分支。
- 你只需在仓库 Settings → Pages 中，将发布源选择为 `gh-pages` 分支即可，或保留使用 `main` 的 root（两种方式任选其一）。

如果你希望我替你完成推送并在 GitHub 上启用 Pages，请告诉我你的仓库地址，我可以协助完成（需要你在本地运行或提供一个有权限的 GitHub token）。
