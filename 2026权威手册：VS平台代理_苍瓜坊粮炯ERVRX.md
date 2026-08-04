VS平台代理【Q-——333307——】VS平台代理【 辋芷《888yx●vip》 】
VS平台代理【Q-——333307——】VS平台代理【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

还在羡慕别人的技术博客？其实你也能在 30分钟 内拥有一个完全属于自己的博客站点。本文手把手教你用 GitHub Pages 和 Hexo 免费搭建个人博客，无需服务器，无需数据库，连域名钱都省了。

 为什么选 GitHub Pages + Hexo？

- 零成本：托管免费，静态站点加载快
- 高度可定制：主题丰富，支持自定义样式
- SEO友好：静态HTML天然利于搜索引擎收录
- 版本管理：所有文章都在Git里，不怕丢失

 第一步：准备环境

确保本地已安装 Node.js 和 Git。在终端输入以下命令验证：

```bash
node -v && git --version
```

 第二步：安装Hexo并初始化

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

初始化完成后，目录结构清晰，`source/_posts` 就是你的文章仓库。

 第三步：写文章并本地预览

```bash
hexo new "我的第一篇博客"
```

编辑器打开 `source/_posts/` 下生成的 `.md` 文件，写入内容后：

```bash
hexo s    本地预览，访问 localhost:4000
```

 第四步：部署到GitHub

1. 新建仓库：`你的用户名.github.io`
2. 安装部署插件：

```bash
npm install hexo-deployer-git --save
```

3. 修改站点配置 `_config.yml`：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

4. 一键部署：

```bash
hexo clean && hexo g && hexo d
```

浏览器访问 `https://你的用户名.github.io`，你的博客已上线！

 免费给博客加个自定义域名

购买域名后，在仓库 `Settings → Pages` 中填写自定义域名，并在域名服务商处添加一条CNAME记录指向你的博客地址即可。

---

你已经成功迈出技术写作的第一步！

在评论区聊聊：你准备用博客记录什么内容？是踩坑日记、学习笔记，还是日常思考？如果这篇文章对你有帮助，请点赞支持，我会继续输出更多搭建教程和效率工具分享。

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/blob/main/%E5%BD%B1%E8%A7%86%E5%9C%88%E6%96%B0%E5%8A%A8%E5%90%91%EF%BC%9AVSapp_%E6%B1%A0%E8%AA%93%E8%9C%97%E5%BD%95%E5%81%BBIOHOV.md

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />

相关推荐：

https://github.com/underwoodcassidy5/coqdxx/commit/291d86d7d8f736587e050803b1b2c851320950e8

<img src="https://i.postimg.cc/90Rpy8Ls/V8-00008.png" />
相关推荐：

https://github.com/noblekarla5/poxesn/blob/main/2026%E7%AC%AC%E4%B8%80%E7%88%86%E7%82%B9%EF%BC%9AVS%E4%B8%BB%E7%AE%A1_%E6%92%AC%E5%8F%B7%E8%B0%9C%E8%A1%AC%E5%8E%A6PIIWH.md

<img src="https://i.postimg.cc/90Rpy8Ls/V8-00008.png" />
相关推荐：

https://github.com/noblekarla5/poxesn/commit/4d8464d72308e368b12779a90b683be23cc623ec

<img src="https://i.postimg.cc/SKg3rPf5/V8-00018.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
