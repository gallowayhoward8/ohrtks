VS官网网址【Q-——333307——】VS官网网址【 辋芷《888yx●vip》 】
VS官网网址【Q-——333307——】VS官网网址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

> 还在羡慕别人酷炫的技术博客？其实你用 GitHub Pages 加 Hexo，半小时就能搭建一个属于自己的免费博客。本文手把手带你完成从环境配置到一键部署的全流程。

 为什么选择 GitHub Pages 作为博客平台？

对于开发者而言，GitHub Pages 拥有三个无法抗拒的优势——完全免费、支持自定义域名、静态页面加载极快。配合 Hexo 框架，Markdown 写作体验极佳，且天然适配搜索引擎收录。

 第一步：环境准备（Node.js 与 Git）

在开始前，请确认你的电脑已安装以下工具：

- Node.js（建议使用 LTS 版本，下载地址见官网）
- Git（用于版本管理与代码推送）
- GitHub 账号（没有的话先去注册）

安装完成后，打开终端（Mac 用 Terminal，Windows 用 PowerShell），依次输入 `node -v` 和 `git --version` 验证环境是否就绪。

 第二步：安装 Hexo 并初始化项目

在终端执行以下命令，全局安装 Hexo 命令行工具：

```bash
npm install -g hexo-cli
```

接着，创建一个新的博客目录并初始化：

```bash
hexo init my-blog
cd my-blog
npm install
```

此时本地博客框架已搭好。执行 `hexo s` 启动本地服务，浏览器访问 `http://localhost:4000` 即可看到默认页面。

 第三步：将博客部署到 GitHub Pages

这一步是关键。我们需要创建一个名为 `用户名.github.io` 的仓库（记得将“用户名”替换成你的 GitHub 昵称）。然后安装部署插件：

```bash
npm install hexo-deployer-git --save
```

修改博客根目录下的 `_config.yml` 文件，在末尾加入：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

最后依次执行：

```bash
hexo clean && hexo generate
hexo deploy
```

静候半分钟，访问 `https://你的用户名.github.io`，你的博客就已正式上线了！

 进阶：绑定自定义域名与 SEO 优化

为了让百度和 Google 更好收录你的文章，建议在 `_config.yml` 中修改 `title`、`keywords` 和 `description` 字段。同时安装 SEO 插件 `hexo-generator-seo-friendly-sitemap`，自动生成站点地图，方便搜索引擎爬取。

 遇到问题？看看这里

- 部署无反应：检查仓库名称是否与用户名完全一致，并确认 `branch` 是否为 `main` 或 `master`
- 样式丢失：在 `_config.yml` 中将 `url` 改为你的正式地址，然后重新部署
- 页面 404：GitHub 仓库的 `Settings` > `Pages` 中确认 Source 已选择 `main` 分支

 结语

现在你已经拥有一个独立、免费且可自定义的博客啦！下一步就是开始写作——好的技术博客，坚持比技巧更重要。如果这篇文章帮到你，点个 Star 支持一下，或者把它转发给身边同样想搭博客的朋友吧！

评论区告诉我：你的博客第一篇文章准备写什么主题？我们互相交流学习。

相关推荐：

https://github.com/hamiltonlinda25/thgubw/blob/main/2026%E6%9D%83%E5%A8%81%E6%95%99%E7%A8%8B%EF%BC%9AV8%E5%9C%B0%E5%9D%80%E6%B3%A8%E5%86%8C_%E8%80%81%E6%B2%9F%E6%80%A5%E7%BA%B9%E9%A6%81SZNUC.md

<img src="https://i.postimg.cc/c4YqSXdK/V8-00012.png" />

相关推荐：

https://github.com/hamiltonlinda25/thgubw/commit/eaec00bd75148d54591f3e7b7acfd50cde68785a

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/blob/main/%E6%96%87%E5%A8%B1%E8%A1%8C%E4%B8%9A%E5%8A%A8%E6%80%81%EF%BC%9AV8%E5%9C%B0%E5%9D%80%E5%BC%80%E6%88%B7_%E5%A2%93%E8%BD%A6%E6%BB%A9%E5%94%A4%E5%96%9COUVQX.md

<img src="https://i.postimg.cc/d05pBf9J/V8-00019.png" />
相关推荐：

https://github.com/hamiltonlinda25/thgubw/commit/0fa17579f1000d3dc6e1e5e1d34e911d72c3cd6d

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
