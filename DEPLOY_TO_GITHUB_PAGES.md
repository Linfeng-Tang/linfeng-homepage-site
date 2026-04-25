# 发布到 GitHub Pages

这套主页已经整理成独立静态站点项目，并且已经附带了 GitHub Pages 自动部署工作流。

## 推荐仓库名

- 推荐新建仓库：`linfeng-homepage-site`
- 如果你想保留为独立项目页，发布地址通常会是：
  `https://linfeng-tang.github.io/linfeng-homepage-site/`

## 最短发布流程

1. 在 GitHub 上新建一个空仓库，例如 `linfeng-homepage-site`
2. 把当前文件夹里的全部内容上传到仓库根目录
3. 确保默认分支为 `main`
4. 打开 GitHub 仓库 `Settings > Pages`
5. 在 `Build and deployment` 中把 `Source` 设为 `GitHub Actions`
6. 推送完成后，等待 `Actions` 里的 `Deploy Static Site to GitHub Pages` 跑完
7. 部署成功后，访问 Pages 地址

## 当前项目已准备好的内容

- 独立页面结构
- 独立素材目录 `assets/`
- 自动部署工作流 `.github/workflows/deploy-pages.yml`
- `.nojekyll`

## 注意

- 这是项目页方案，不会覆盖你当前 `Linfeng-Tang.github.io` 的主站
- 如果你以后想绑定自定义域名，可以再补一个 `CNAME` 文件
- 如果你希望它直接成为根域名主页，需要把仓库改成 `Linfeng-Tang.github.io`
