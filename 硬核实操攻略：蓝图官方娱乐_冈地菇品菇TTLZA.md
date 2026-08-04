蓝图官方娱乐【Q-——333307——】蓝图官方娱乐【 辋芷《888yx●vip》 】
蓝图官方娱乐【Q-——333307——】蓝图官方娱乐【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程

你是否想过拥有一个完全属于自己的技术博客？不需要购买服务器，不用折腾数据库，GitHub Pages + Hexo 组合让你免费、高效地搭建个人站点。今天这篇保姆级教程，手把手带你完成从环境配置到一键部署的全流程。

 为什么选择Hexo + GitHub Pages？

- 完全免费：托管在GitHub服务器，无需额外成本
- 极致速度：纯静态页面，CDN加速秒开
- SEO友好：生成标准化HTML，百度收录无压力
- 版本管理：文章用Markdown编写，天然支持Git版本控制

 第一步：环境准备

 1. 安装Node.js
访问[nodejs.org](https://nodejs.org)下载LTS版本，安装时保持默认配置。打开终端验证：
```bash
node -v && npm -v
```

 2. 安装Git
从[git-scm.com](https://git-scm.com)下载安装，Windows用户选择"Git Bash"组件。

 第二步：搭建Hexo框架

在终端执行以下命令：
```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
```

 快速测试
```bash
hexo server
```
浏览器访问 `http://localhost:4000`，看到默认页面即成功。

 第三步：配置GitHub仓库

 1. 新建仓库
登录GitHub，点击"New repository"，仓库名必须为：
```
你的用户名.github.io
```

 2. 安装部署插件
```bash
npm install hexo-deployer-git --save
```

 3. 修改配置文件
编辑 `_config.yml`，配置部署参数：
```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

 第四步：发布第一篇文章

在终端创建新
```bash
hexo new "我的第一篇博客"
```
用编辑器打开 `source/_posts/我的第一篇博客.md`，编写内容后执行：
```bash
hexo clean && hexo generate && hexo deploy
```
浏览器访问 `你的用户名.github.io`，祝贺你！博客已上线。

 进阶优化：加速百度收录

1. 站点地图：安装 `hexo-generator-sitemap` 插件
2. 主动提交：在[百度站长平台](https://ziyuan.baidu.com)添加站点属性并提交链接
3. 内链建设：合理使用标签和分类，增加页面间互链

---

互动环节：你在搭建过程中遇到最棘手的问题是什么？欢迎在评论区留言，我会逐一解答！如果这篇教程对你有帮助，请点个赞或收藏，让更多朋友看到。

想要获取完整的配置文件示例和主题美化技巧？关注我，下期为你揭秘Hexo高级玩法！

相关推荐：

https://github.com/brownbarbara40/yzuprm/blob/main/2026%E7%A7%91%E6%8A%80%E5%B9%B2%E8%B4%A7%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%B9%B3%E5%8F%B0_%E8%B0%86%E8%A7%85%E8%A1%AB%E6%BD%AE%E7%BB%95OOBPQ.md

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />

相关推荐：

https://github.com/brownbarbara40/yzuprm/commit/eed3486c832f22e503648c8f819abb1d3c1d76d0

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />
相关推荐：

https://github.com/singhcourtney93/oormzh/blob/main/2026%E6%9D%83%E5%A8%81%E8%AE%B2%E8%A7%A3%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%AE%98%E6%96%B9_%E8%80%98%E7%84%89%E7%94%AD%E7%9E%A5%E5%A7%A5TNTTA.md

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />
相关推荐：

https://github.com/singhcourtney93/oormzh/commit/5503ad82b9c56c684bc6f70f3b294d95a19ad666

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
