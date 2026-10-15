# Owen Mao 个人网站

访问：https://owenmao-builder.github.io/

GitHub Pages 从 `main` 分支根目录发布这个静态站点。`.nojekyll` 让 Pages 按文件原样发布，不经过 Jekyll。

当前首页是个人空间，包含项目、文章、作品和联系方式。页面文件在仓库根目录：`index.html`、`style.css`、`main.js`、`fx.css` 和 `fx-*.js`。

`legacy/index.html` 是 2026-10-15 替换前的首页。它和当前首页共用根目录 `assets/`。旧图是 `om-titanium-hero.png` 与 `editorial-notebook.png`，新图是头像、图标和二维码，两边没有重名文件。旧首页中的图片地址写成 `../assets/`，从 `/legacy/` 打开时仍能加载这些图。

保留的其他入口：

- `admin/`：跳转到原管理后台
- `hai-gui-tang/`：海龟汤游戏入口

`/portfolio/`、`/expense-hearing/` 等地址由其他仓库的 GitHub Pages 提供，不在本仓库中。
