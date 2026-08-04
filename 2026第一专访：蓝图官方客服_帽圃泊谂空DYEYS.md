蓝图官方客服【Q-——333307——】蓝图官方客服【 辋芷《888yx●vip》 】
蓝图官方客服【Q-——333307——】蓝图官方客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：Github Pages + Hexo 完整教程（2025版）

你是不是也想拥有一个完全属于自己的博客？不需要买服务器，不用备案，免费且支持自定义域名——没错，这就是 Github Pages 的魅力。今天这篇教程，我将手把手带你用 Hexo 框架，在 Github 上搭建一个高颜值、可长期维护的个人站点。

 为什么选择 Hexo + Github Pages？

在开始之前，先解决“为什么”的问题。Github Pages 是 Github 提供的静态网站托管服务，完全免费，且访问速度在国内尚可。搭配 Hexo 这个老牌静态框架，你只需要用 Markdown 写文章，一条命令就能生成并部署到线上。相比 WordPress，它更轻量；相比 Vercel，它更稳定且不限制流量。

 第一步：环境准备与安装

前提条件：你已经注册了 Github 账号，并安装了 Node.js（建议版本 16+）和 Git。

打开终端，全局安装 Hexo 脚手架：

```bash
npm install -g hexo-cli
```

随后在本地新建一个文件夹（比如 `myblog`），初始化项目：

```bash
hexo init myblog
cd myblog
npm install
```

 第二步：配置站点信息

用任意编辑器打开项目根目录下的 `_config.yml`，这是 Hexo 的核心配置。找到 `Site` 区块，修改标题、作者、语言等关键信息：

```yaml
title: 你的博客名称
author: 你的名字
language: zh-CN
```

建议顺手把 `url` 改成你后续要绑定的自定义域名（如 `https://yourname.com`），避免后期迁移麻烦。

 第三步：连接 Github 仓库并部署

1. 在 Github 上新建一个仓库，命名为 `你的用户名.github.io`（注意：必须是这个格式，否则无法正常访问）。
2. 回到项目目录，安装自动部署插件：

```bash
npm install hexo-deployer-git --save
```

3. 修改 `_config.yml` 中的 `Deployment` 区块：

```yaml
deploy:
  type: git
  repo: 你的仓库地址（HTTPS或SSH）
  branch: main
```

4. 依次执行三条命令，完成生成、本地预览、上传部署：

```bash
hexo clean && hexo generate
hexo server    本地预览，浏览器访问 localhost:4000
hexo deploy    部署到 Github
```

 第四步：绑定自定义域名（可选但推荐）

如果不想用默认的 `xxx.github.io` 域名，可以购买一个自己的域名。在仓库的 `Settings -> Pages` 中填入你的域名，然后在域名服务商后台添加一条 CNAME 记录指向 `你的用户名.github.io`。最后在项目 `source` 文件夹下新建一个无扩展名的 `CNAME` 文件，内容写上你的域名。

 要不要做一下站内搜索？

看到这里的你，大概率已经是准备动手实操了。如果你在部署过程中遇到任何报错（比如 Node 版本不兼容、仓库分支名不对），欢迎在评论区留言你的具体报错信息，我会第一时间帮你定位问题。

 最后的话

搭建博客只是第一步，持续写作才是核心。Github Pages 的流量配额对于个人博客来说基本是无限的，放心使用。如果你觉得这篇教程对你有帮助，点赞或收藏一下，让更多朋友看到这份完整的踩坑指南。

---

延伸阅读：如果你想让博客支持评论系统，可以在主题配置中接入 Giscus（基于 Github Discussions）或 Waline（支持国内环境），之后我会出一篇详细的主题美化和插件配置指南，关注我不迷路。

相关推荐：

https://github.com/singhcourtney93/oormzh/blob/main/2026%E5%AE%98%E7%BD%91%E4%B8%93%E8%AE%BF%EF%BC%9A%E8%93%9D%E5%9B%BE%E6%B3%A8%E5%86%8C%E5%AE%98%E7%BD%91_%E7%85%A4%E7%BF%81%E8%AF%B5%E6%80%80%E6%8B%B7ZAHOW.md

<img src="https://i.postimg.cc/kGjWYk5W/lantu-00006.png" />

相关推荐：

https://github.com/singhcourtney93/oormzh/commit/15de3e969b0ebdcf50a6ca1aff3b605d7a50a735

<img src="https://i.postimg.cc/c4bQRyjk/lantu-00008.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/blob/main/2026%E7%AC%AC%E4%B8%80%E5%A4%8D%E7%9B%98%EF%BC%9A%E8%93%9D%E5%9B%BE%E6%B3%A8%E5%86%8C%E6%B5%8B%E9%80%9F_%E9%B9%8A%E8%83%96%E6%A0%8B%E8%B0%96%E6%83%ADHOHZL.md

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/commit/221fa5dd39e7a3afd601a591b0946b329bf50afb

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
