<div align="center">

# 奔波儿r / Benbor

**零代码股票研究员，把自己每天真实使用的 AI 投研工作流开源出来。**  
**Zero-code investment researcher building practical AI research systems.**

[![公众号](https://img.shields.io/badge/公众号-奔波儿r-07C160?logo=wechat&logoColor=white)](https://mp.weixin.qq.com/s/Ygatb842ew_JeN4LdcAbZg)
[![即刻](https://img.shields.io/badge/即刻-@奔波儿r-FFE411?logoColor=black)](https://okjk.co/mTVFAE)
[![GitHub followers](https://img.shields.io/github/followers/Benboerba620?style=social)](https://github.com/Benboerba620?tab=followers)

</div>

---

我不是程序员，也不把这些项目当 demo。  
这些工具来自一个很具体的问题：

> 如果一个股票研究员不会写代码，但想让 AI 真正参与日常研究、资料整理、假设追踪和复盘，他需要一套什么样的工作台？

我的答案是：**少一点炫技，多一点可复制；少一点一次性 prompt，多一点长期运行的研究系统。**

<details>
<summary>English</summary>

I am not a programmer, and I do not treat these projects as demos.

They come from one practical question:

> If an investment researcher cannot code, but wants AI to actually help with daily research, source digestion, hypothesis tracking, and review, what kind of workspace does that person need?

My answer: **less prompt theater, more durable systems; less one-off magic, more repeatable workflows.**

</details>

---

## Start here: my AI research stack

如果你也想搭一个“能每天用”的 AI 投研工作台，建议从这里开始：

1. **输入资料**：用 [pod2wiki](https://github.com/Benboerba620/pod2wiki) 把播客、YouTube、RSS 和长内容变成可读、可沉淀的研究材料。

2. **搭工作区**：用 [ai-workspace-hub](https://github.com/Benboerba620/ai-workspace-hub) 把资料、知识库、输出、反馈和记忆放进同一套 AI 工作台。

3. **跑日常研究**：用 [daily-watchlist](https://github.com/Benboerba620/daily-watchlist) 做股票池日报、假设追踪、交易证据和复盘。

<table>
  <tr>
    <td width="34%" valign="top">
      <h3>🌱 <a href="https://github.com/Benboerba620/ai-workspace-hub">ai-workspace-hub</a></h3>
      <p><b>先从这个开始。</b></p>
      <p>一个 Codex-first、Claude-compatible 的 AI 工作区模板：资料输入、知识库、输出、反馈和记忆都放进同一套结构里。</p>
      <p>适合想搭个人 AI 工作台、但不想先学一堆工程概念的人。</p>
      <p><a href="https://github.com/Benboerba620/ai-workspace-hub"><img src="https://img.shields.io/github/stars/Benboerba620/ai-workspace-hub?style=social" alt="ai-workspace-hub stars"></a></p>
    </td>
    <td width="33%" valign="top">
      <h3>📊 <a href="https://github.com/Benboerba620/daily-watchlist">daily-watchlist</a></h3>
      <p><b>让股票池每天自己跑起来。</b></p>
      <p>面向 Claude Code 的股票池 AI 监控工具：日报、观察列表、假设追踪、交易证据和复盘记录。</p>
      <p>核心不是“预测股价”，而是让研究过程更可追踪。</p>
      <p><a href="https://github.com/Benboerba620/daily-watchlist"><img src="https://img.shields.io/github/stars/Benboerba620/daily-watchlist?style=social" alt="daily-watchlist stars"></a></p>
    </td>
    <td width="33%" valign="top">
      <h3>🎙️ <a href="https://github.com/Benboerba620/pod2wiki">pod2wiki</a></h3>
      <p><b>把长内容变成研究材料。</b></p>
      <p>把 YouTube / RSS / 播客自动转成中文摘要和英文原文存档，适合长期跟踪海外访谈、行业讨论和公司信息。</p>
      <p>Whisper + DeepSeek，一键安装，尽量照顾零代码用户。</p>
      <p><a href="https://github.com/Benboerba620/pod2wiki"><img src="https://img.shields.io/github/stars/Benboerba620/pod2wiki?style=social" alt="pod2wiki stars"></a></p>
    </td>
  </tr>
</table>

---

## Standalone knowledge base

### 🧠 [karpathy-claude-wiki](https://github.com/Benboerba620/karpathy-claude-wiki)

一个给 LLM 读写的个人 wiki 模板：纯 Markdown + frontmatter，**刻意不用向量库，也不做复杂 RAG**。

它解决的是另一个基础问题：  
**AI 不只是回答问题，它也需要一个能长期读写、能沉淀上下文的地方。**

[![karpathy-claude-wiki stars](https://img.shields.io/github/stars/Benboerba620/karpathy-claude-wiki?style=social)](https://github.com/Benboerba620/karpathy-claude-wiki)

---

## What I care about

- **零代码 AI 工作流**：让不会写代码的人也能搭建、维护、迭代自己的 AI 系统。

- **投研过程工程化**：不是让 AI 替你拍脑袋，而是让资料、假设、证据、交易和复盘更可追踪。

- **个人知识库给 AI 读**：未来的知识库不只写给自己看，也要写给 AI agent 看。

- **公开可复制**：我更关心普通人能不能 clone 下来跑，而不是项目看起来有多“技术先进”。

---

## Writing & updates

| 渠道 | 链接 | 主要内容 |
|---|---|---|
| 公众号「奔波儿r」 | [代表作一篇](https://mp.weixin.qq.com/s/Ygatb842ew_JeN4LdcAbZg) | 投资行业拆解、AI 投研实践、工具教程 |
| 即刻 | [@奔波儿r](https://okjk.co/mTVFAE) | 日常想法、项目更新、AI 使用观察 |
| GitHub | [Benboerba620](https://github.com/Benboerba620) | 开源工具、模板、研究工作流 |

---

## If this helps you

如果这些项目对你有用，欢迎：

- ⭐ 给你用得上的 repo 点一个 star，方便我判断哪些工具值得继续维护；

- 👀 follow 这个 profile，后面新的 AI 投研工具和教程会继续放在这里；

- 🧪 直接 fork / clone 试用，然后把你的使用问题提到 issue 里。

<sub>说明：这里的项目用于研究流程和知识管理，不构成投资建议。Profile picture is my cat 豆包 — chief approver.</sub>
