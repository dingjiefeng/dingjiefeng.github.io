# dingjiefeng.github.io

个人技术博客，采用无依赖的单文件静态结构，可直接部署到 GitHub Pages。

## 发布

在仓库的 **Settings → Pages** 中选择：

- Source: `Deploy from a branch`
- Branch: `main`
- Folder: `/ (root)`

保存后，站点将发布到 <https://dingjiefeng.github.io>。

## 更新文章

目前首页文章位于 `index.html` 中的 `<section id="notes">`。复制其中的 `<article class="note">` 区块即可添加文章。文章数量增多后，可无损迁移到 Hugo 或 Eleventy；域名和现有链接无需改变。
