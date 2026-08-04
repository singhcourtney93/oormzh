蓝图娱乐测速【Q-——333307——】蓝图娱乐测速【 辋芷《888yx●vip》 】
蓝图娱乐测速【Q-——333307——】蓝图娱乐测速【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：Github Pages + Hexo 完整指南

> 还在为写技术文章找不到合适的平台发愁？Github Pages 免费、稳定、还能绑定自己的域名，搭配 Hexo 框架，30分钟就能拥有一个高逼格的个人技术博客。本文手把手教你从零开始搭建。

 为什么要用 Github Pages + Hexo？

对于技术写作者来说，Github Pages 提供了免费静态托管，不仅支持自定义域名和 HTTPS，而且完全掌控数据，不用担心平台限制。配合 Hexo 的极速渲染和丰富主题，让写作体验堪比 Medium，同时拥有完全的自主权。

 三步完成博客搭建

 第一步：初始化项目

```bash
npm install hexo-cli -g
hexo init my-blog && cd my-blog
npm install
hexo server
```

完成以上步骤，浏览器打开 http://localhost:4000 即可预览效果。

 第二步：关联 Github Pages

在 Github 创建 `你的用户名.github.io` 仓库，然后修改根目录 `_config.yml`：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: master
```

 第三步：一键部署

```bash
hexo clean && hexo generate && hexo deploy
```

访问 `https://你的用户名.github.io`，你的博客就已上线。

 进阶：提升博客逼格

- 绑定域名：购买域名后，在仓库 Settings → Pages 面板配置即可
- 深度自定义：博客根目录新建 `_posts` 文件夹，支持 Markdown 语法，写作体验拉满
- SEO 优化：安装 `hexo-generator-seo-friendly-sitemap` 插件，让 Google 更快收录文章

 开始你的技术写作之旅吧！

搭建完成后，重点还是专注内容创作。准备好后，先写一篇“Hello World”练手，遇到问题欢迎在评论区留言，或者通过 Github Issues 跟我交流，记得 Star 一下源码仓库支持我持续更新！

相关推荐：

https://github.com/rhodesandrea462/zjvmux/blob/main/2026%E7%AC%AC%E4%B8%80%E4%B8%A5%E9%80%89%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E5%BC%80%E6%88%B7_%E5%92%90%E6%B2%99%E5%A0%86%E8%80%98%E5%85%91WCJQR.md

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />

相关推荐：

https://github.com/rhodesandrea462/zjvmux/commit/9cc5e2bec3c7252cc30c64d5d9cc8a321e9dcac2

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E7%AC%AC%E4%B8%80%E6%80%BB%E7%BB%93%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E4%B8%BB%E7%AE%A1_%E6%94%BE%E8%8E%86%E9%97%B2%E8%8A%88%E5%A5%84CWJQQ.md

<img src="https://i.postimg.cc/ZnqdNVLn/lantu-00012.png" />
相关推荐：

https://github.com/martinezjessica6229/eyvqwl/commit/d2407fad0412f30da5f2d8e21bf18f92828beb56

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
