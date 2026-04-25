# Linfeng Homepage Site

这个文件夹已经整理成可直接部署的独立静态网站项目。

包含内容：

- `index.html`
- `publications.html`
- `news.html`
- `honors.html`
- `services.html`
- `contact.html`
- `styles.css`
- `.github/workflows/deploy-pages.yml`
- `.nojekyll`
- `assets/icons/`
- `assets/img/`

推荐发布方式：

1. 新建一个独立仓库，例如 `linfeng-homepage-site`
2. 把这个文件夹里的全部内容上传到仓库根目录
3. 在 GitHub 仓库 `Settings > Pages` 中把 `Source` 设为 `GitHub Actions`
4. 推送到 `main` 后，站点会通过工作流自动部署

当前目录中的素材路径都已经改成站内相对路径，不再依赖旧项目或外部本地文件夹。

详细步骤见 [DEPLOY_TO_GITHUB_PAGES.md](./DEPLOY_TO_GITHUB_PAGES.md)。
