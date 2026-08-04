蓝图地址平台【Q-——333307——】蓝图地址平台【 辋芷《888yx●vip》 】
蓝图地址平台【Q-——333307——】蓝图地址平台【 辋芷《888yx●vip》 】

 从零搭建个人技术博客：GitHub Pages + Hexo 实战教程

还在羡慕别人的技术博客？其实用 GitHub Pages 和 Hexo，半小时就能搭建一个免费、高速、支持 HTTPS 的个人站点。今天手把手教你从零开始，无需购买服务器，只需一个 GitHub 账号。

 为什么选择 Hexo + GitHub Pages？

- 完全免费，全球 CDN 加速访问
- 支持 Markdown 写作，专注内容而非排版
- 部署仅需 git push，自动发布更新
- 插件生态丰富，SEO 友好易收录

 快速上手指南

 第一步：准备环境
本地安装 Node.js 和 Git，Mac 用户可用 Homebrew 安装，Windows 用户直接下载安装包。

 第二步：安装 Hexo 并初始化
```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog && npm install
```

 第三步：连接 GitHub
创建 `<用户名>.github.io` 仓库，然后修改 `_config.yml` 中的 deploy 配置：
```yaml
deploy:
  type: git
  repo: https://github.com/用户名/用户名.github.io.git
```

 第四步：写文章并发布
```bash
hexo new post "我的第一篇博客"
hexo g -d    生成并部署
```

 进阶优化建议

1. 绑定自定义域名：在仓库设置中配置 CNAME 文件，即可使用自己的域名
2. 添加评论系统：集成 giscus 或 utterances，基于 GitHub Discussions
3. SEO 优化：安装 `hexo-seo-autonickname` 等插件，自动生成关键词和描述

遇到问题？最常见的是 SSH 密钥未配置，执行 `ssh-keygen` 并添加到 GitHub 即可解决。

搭建完成后，你的个人博客就拥有了和 Vercel、Netlify 同级别的托管质量。想进一步了解主题美化或性能优化技巧？点赞 + 关注，评论区告诉我你的 Hexo 版本，下期为你定制专属教程。

相关推荐：

https://github.com/benderjessica393/clipwq/blob/main/%E6%B5%81%E7%A8%8B%E5%AE%9E%E6%93%8D%E6%8C%87%E5%8D%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%AE%98%E6%96%B9%E4%B8%8B%E8%BD%BD_%E5%83%9A%E9%A6%97%E9%9D%A5%E6%9D%96%E5%AA%92JPPJQ.md

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />

相关推荐：

https://github.com/benderjessica393/clipwq/commit/a9a1e78c3191803550b874d5785bf63bc65c1091

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/blob/main/2026%E7%AC%AC%E4%B8%80%E6%B1%87%E6%80%BB%EF%BC%9A%E8%93%9D%E5%9B%BE%E6%B3%A8%E5%86%8C%E4%BB%A3%E7%90%86_%E6%82%A3%E9%94%A4%E5%91%98%E5%91%98%E8%87%83MNAHH.md

<img src="https://i.postimg.cc/50y4qGDp/lantu-00014.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/commit/49e674f28ea5bbc78a7992a79fbd34cae6a238bb

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
