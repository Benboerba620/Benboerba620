<div align="center">

# 奔波儿r / Benbor

**零代码股票研究员，把自己每天真实使用的 AI 投研工作流开源出来。**  
**Zero-code investment researcher building practical AI research systems.**

[![公众号](https://img.shields.io/badge/公众号-奔波儿r-07C160?logo=wechat&logoColor=white)](https://mp.weixin.qq.com/s/Ygatb842ew_JeN4LdcAbZg)
[![即刻](https://img.shields.io/badge/即刻-@奔波儿r-FFE411?logoColor=black)](https://okjk.co/mTVFAE)
[![GitHub followers](https://img.shields.io/github/followers/Benboerba620?style=social)](https://github.com/Benboerba620?tab=followers)

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Benboerba620&show_icons=true&theme=default&hide_title=true&hide_rank=true&include_all_commits=true" alt="GitHub Stats" />

</div>

---

我是研究员，不是程序员。做股票研究的日常就是这几件事：找 idea、收集资料、深入研究、写报告、做决策、跟踪复盘。我把这条工作流拆开，看每个环节 AI 能接多少，然后给接不好的地方写了小工具。

这些工具我自己每天在用。开源出来，是因为我觉得研究员的工作流大同小异——你拿去改改，大概率也能跑。

<details>
<summary>English</summary>

I'm a researcher, not a programmer. My daily job is stock research: sourcing ideas, collecting information, deep dives, writing reports, making decisions, and tracking follow-ups. I broke this workflow apart, figured out where AI can plug in at each stage, and built small tools for the gaps.

I use these tools every day. I open-sourced them because most researchers follow a similar workflow — clone it, tweak it, and it'll probably work for you too.

</details>

---

## Start here: my AI research stack

如果你也想搭一个"能每天用"的 AI 投研工作台，建议从这里开始：

<table>
  <tr>
    <td width="34%" valign="top">
      <h3>🌱 <a href="https://github.com/Benboerba620/ai-workspace-hub">ai-workspace-hub</a></h3>
      <p><b>先从这个开始。</b></p>
      <p>一个 Codex-first、Claude-compatible 的 AI 工作区模板：资料输入、知识库、输出、反馈和记忆都放进同一套结构里。</p>
      <p>适合想搭个人 AI 工作台、但不想先学一堆工程概念的人。</p>
      <p>
        <a href="https://github.com/Benboerba620/ai-workspace-hub"><img src="https://img.shields.io/github/stars/Benboerba620/ai-workspace-hub?style=social" alt="stars"></a>
        <a href="https://github.com/Benboerba620/ai-workspace-hub"><img src="https://img.shields.io/github/last-commit/Benboerba620/ai-workspace-hub?label=updated" alt="last commit"></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>📊 <a href="https://github.com/Benboerba620/daily-watchlist">daily-watchlist</a></h3>
      <p><b>让股票池每天自己跑起来。</b></p>
      <p>面向 Claude Code 的股票池 AI 监控工具：日报、观察列表、假设追踪、交易证据和复盘记录。</p>
      <p>核心不是"预测股价"，而是让研究过程更可追踪。</p>
      <p>
        <a href="https://github.com/Benboerba620/daily-watchlist"><img src="https://img.shields.io/github/stars/Benboerba620/daily-watchlist?style=social" alt="stars"></a>
        <a href="https://github.com/Benboerba620/daily-watchlist"><img src="https://img.shields.io/github/last-commit/Benboerba620/daily-watchlist?label=updated" alt="last commit"></a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>🎙️ <a href="https://github.com/Benboerba620/pod2wiki">pod2wiki</a></h3>
      <p><b>把长内容变成研究材料。</b></p>
      <p>把 YouTube / RSS / 播客自动转成中文摘要和英文原文存档，适合长期跟踪海外访谈、行业讨论和公司信息。</p>
      <p>Whisper + DeepSeek，一键安装，尽量照顾零代码用户。</p>
      <p>
        <a href="https://github.com/Benboerba620/pod2wiki"><img src="https://img.shields.io/github/stars/Benboerba620/pod2wiki?style=social" alt="stars"></a>
        <a href="https://github.com/Benboerba620/pod2wiki"><img src="https://img.shields.io/github/last-commit/Benboerba620/pod2wiki?label=updated" alt="last commit"></a>
      </p>
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
[![Last commit](https://img.shields.io/github/last-commit/Benboerba620/karpathy-claude-wiki?label=updated)](https://github.com/Benboerba620/karpathy-claude-wiki)

---

## What I care about

- **零代码 AI 工作流**：让不会写代码的人也能搭建、维护、迭代自己的 AI 系统。

- **投研过程工程化**：不是让 AI 替你拍脑袋，而是让资料、假设、证据、交易和复盘更可追踪。

- **个人知识库给 AI 读**：未来的知识库不只写给自己看，也要写给 AI agent 看。

- **公开可复制**：我更关心普通人能不能 clone 下来跑，而不是项目看起来有多"技术先进"。

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
