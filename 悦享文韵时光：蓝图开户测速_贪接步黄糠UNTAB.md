蓝图开户测速【Q-——333307——】蓝图开户测速【 辋芷《888yx●vip》 】
蓝图开户测速【Q-——333307——】蓝图开户测速【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是不是也想拥有一个属于自己的技术博客，却又觉得买服务器、配数据库太麻烦？

其实，用 GitHub Pages 免费托管 + Hexo 静态生成，10分钟就能上线一个高颜值、可自定义的个人网站。本文按实战顺序拆解，文末附常见报错排查，建议先点赞收藏再慢慢看。

 一、为什么选择 GitHub Pages + Hexo？

- 免费且稳定：无需购买服务器，GitHub 全球 CDN 加速，国内访问速度尚可。
- 写作体验极佳：支持 Markdown 语法，专注内容无需关心后端。
- SEO 友好：纯静态 HTML，搜索引擎收录快，利于个人品牌曝光。

 二、环境准备（Windows/macOS 通用）

1. 安装 Node.js（建议 LTS 版本）和 Git。
2. 注册 GitHub 账号，并新建一个仓库，命名为 `你的用户名.github.io`（必须是这个格式）。
3. 本地创建项目目录，打开终端执行：
   ```bash
   npm install -g hexo-cli
   hexo init my-blog && cd my-blog
   npm install
   ```
   这样你就得到了一个最基础的 Hexo 站点骨架。

 三、关联 GitHub 并一键部署

1. 修改站点根目录 `_config.yml` 中的 `deploy` 配置：
   ```yaml
   deploy:
     type: git
     repo: https://github.com/你的用户名/你的用户名.github.io.git
     branch: main
   ```
2. 安装部署插件：
   ```bash
   npm install hexo-deployer-git --save
   ```
3. 依次执行：
   ```bash
   hexo clean && hexo generate
   hexo deploy
   ```
   浏览器访问 `https://你的用户名.github.io`，就能看到你的第一个博客了。

 四、自定义主题与优化收录

Hexo 默认主题较朴素。你可以去 [Hexo Themes](https://hexo.io/themes/) 挑选一个喜欢的主题（如 Next、Fluid）。下载后放入 `themes` 目录，并修改 `_config.yml` 里的 `theme` 字段即可。

SEO 优化建议：安装 `hexo-generator-seo-friendly-sitemap` 插件生成 sitemap，并在 GitHub 仓库的 Settings > Pages 里启用 HTTPS。这样百度等搜索引擎能更快抓取你的文章。

 五、常见问题排查

- 部署报错 401：检查仓库地址是否正确，或 SSH Key 是否已配置。
- 样式丢失：确认 `_config.yml` 中的 `url` 为 `https://你的用户名.github.io`。
- 图片不显示：使用相对路径或先上传到仓库再引用链接。

---

如果你在搭建过程中遇到任何报错，欢迎在评论区留言，我会逐一回复。觉得有用的话，点个赞让更多朋友看到，也方便你下次查找。

---

（文章内含适量关键词：GitHub Pages、Hexo博客搭建、静态博客SEO、个人网站部署、免费技术博客）

相关推荐：

https://github.com/orozcogregory68/fxoxig/blob/main/%E6%96%87%E5%A8%B1%E8%A1%8C%E4%B8%9A%E5%BF%AB%E8%AE%AF%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%A8%B1%E4%B9%90%E5%9C%B0%E5%9D%80_%E5%B9%BC%E4%B9%88%E9%B8%B5%E8%AF%9A%E7%A3%95JCKDS.md

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />

相关推荐：

https://github.com/orozcogregory68/fxoxig/commit/61c4c7fb725e14aae9ea9e3d6a57f180aeca512f

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />
相关推荐：

https://github.com/klinegina28/bhjqeg/blob/main/2026%E6%9D%83%E5%A8%81%E6%80%BB%E7%BB%93%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95_%E4%BE%B5%E5%9C%9F%E6%8B%B1%E5%92%8F%E5%94%A4TTMSZ.md

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />
相关推荐：

https://github.com/klinegina28/bhjqeg/commit/c08a0d6a6ff8317f5b7d0fc3d2a717e68b5aff31

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
