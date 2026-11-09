# Awesome EasonL

我自己的精选清单。不是「收藏夹」，是**用过之后留下来**的东西。

收藏夹的问题是会无限膨胀，最后谁也不看。所以这里每条都要回答一句话：**为什么留着它**。答不上来的，删掉。

## 收录标准

1. **我真的用过**，不是「据说很好」。
2. **能说清它解决哪个具体问题**，一句话讲不明白的不收。
3. **半年内还在更新**。开源项目尤其苛刻，停更超过半年的要单独标注。

第 3 条不是歧视，是省时间。一个两年没动的项目，跑起来大概率卡在依赖上。

## 目录

- [AI 与提示词](#ai-与提示词)
- [学习资源](#学习资源)
- [写作与发布](#写作与发布)
- [本机环境](#本机环境)
- [读书笔记](notes/)
- [提示词库](prompts/)

---

## AI 与提示词

- [Prompt Engineering Guide](https://github.com/dair-ai/Prompt-Engineering-Guide) — 提示词方法论最全的一份，从怎么提问到让模型调用工具、连续完成复杂任务都有案例。约 8 万 star，长期维护。
- [LobeChat](https://github.com/lobehub/lobe-chat) — 开源的 AI 聊天前端，能同时接 ChatGPT、Claude、DeepSeek、Ollama。界面干净，支持插件。**注意**：它的 License 在 GitHub 上显示 `NOASSERTION`，商用前必须自己读 LICENSE 文件。
- [沉浸式翻译](https://immersivetranslate.com/) — 浏览器插件，中英对照翻译整页。看英文文档和 GitHub README 的性价比之王。
- [Codex](https://openai.com/codex/) — 用自然语言驱动代码修改的 Agent。今天这篇博客的 git 操作思路就来自它，但我实际用的是 LobsterAI 里的助手。

## 学习资源

- [free-programming-books](https://github.com/EbookFoundation/free-programming-books) — 免费编程书和课程合集，40 万 star 级别。按语言和主题分类，找入门材料不用再到处搜。
- [Markdown Guide](https://www.markdownguide.org/) — Markdown 语法速查。写博客、写笔记、写 README 都用得上，比记语法表靠谱。
- [GitHub Trending](https://github.com/trending) — 按天/周/月看热门项目。新 AI 工具通常比自媒体介绍早几天到几周出现在这里，这是时间差。

## 写作与发布

- [我的博客](https://xinshify001.github.io/) — 就是你现在看这个清单的主人写长文的地方。GitHub Pages 托管，纯 Markdown，零成本。
- [GitHub Pages](https://pages.github.com/) — 静态站托管。适合博客、作品集、产品介绍页。不需要买服务器，不需要备案。
- [Vercel](https://vercel.com/) — 应用型项目的部署平台，个人免费额度够用。和 GitHub 账号绑定后推送即部署。

## 本机环境

- [Git](https://git-scm.com/) — 版本管理。装好就行，日常命令交给 AI 敲，我只记三个概念：Commit 是存档，Branch 是平行试验田，Push 是同步到云端。
- [VS Code](https://code.visualstudio.com/) — 编辑器。Cursor、Trae 这些 AI 编程工具都是基于它的开源版本魔改的。
- [Python](https://www.python.org/) — 脚本和自动化。这个博客的生成器就是纯 Python 标准库写的，不用装任何第三方包。

---

## 怎么往里加东西

在对应分类下加一行，格式是：

```markdown
- [名称](链接) — 一句话说清它解决什么问题，以及我为什么留着它。
```

加完提交推送就行。说不清「为什么留着」的，说明它还没资格进来。
