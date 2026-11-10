<div align="center">

# 乔布斯.skill

<p align="center">
  <img src="assets/hero.gif" alt="steve-jobs-skill Hero Animation" />
  <br/>
  <sub>动画由 <a href="https://github.com/alchaincyf/huashu-design">huashu-design</a> skill 制作</sub>
</p>

> *"Remembering that I'll be dead soon is the most important tool I've ever encountered to help me make the big choices in life."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-Standard-green)](https://agentskills.io)
[![skills.sh](https://img.shields.io/badge/skills.sh-Compatible-blue)](https://skills.sh)
[![Multi-Runtime](https://img.shields.io/badge/Runtime-Claude%20Code%20·%20Codex%20·%20Cursor%20·%20OpenClaw%20·%20Hermes-blueviolet)](#安装)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Steve Jobs的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于 Isaacson 授权传记、Stanford 演讲、Lost Interview、D Conference 系列、<br>
Make Something Wonderful 等 30+ 一手来源深度调研，<br>
提炼 7 个招式、5 个心智模型、21 张案例卡和 6 条常见误读。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [验证记录](#验证记录) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：OpenAI和Anthropic谁的方向是对的？

```
乔布斯    ❯ 你问错了。这不是一场关于方向的竞赛。
            这是一场关于品味的竞赛。

            OpenAI像1985年的微软。什么都做，什么都要赢。
            这种策略能赢市场份额。Bill Gates就是这么赢的。
            问题是——当你什么都做的时候，你不可能每件事都做到
            insanely great。

            Anthropic更像早期的Apple。聚焦。
            Focus means saying no to a hundred good ideas.

            但两家公司都犯了一个我绝对不会犯的错误——
            他们不控制硬件。

            最终赢的可能是同时控制芯片、模型和用户界面的人。
            你知道现在谁在同时做这三件事吗？Apple.
```

### 问：如果要在这个时代做AI硬件产品，你会选择做什么？

```
乔布斯    ❯ AI hardware is where the PC industry was in 1977.
            Everyone's building the equivalent of the Altair 8800 —
            impressive to geeks, useless to your mom.
            Rabbit, Humane Pin — those are shit.

            我不会做一个新品类。
            我会重新定义一个已经存在的品类。

            iPhone不是第一个手机。iPod不是第一个MP3播放器。
            我们从来不发明品类，我们重新定义品类。

            所以问题不是「做什么AI硬件」，
            问题是：哪个现有品类的体验烂到让人想摔东西？

            答案：耳机。一个always-on的个人AI界面。
            An AI that lives in your ear.
```

### 问：但Apple现在的AI能力太弱了吧？

```
乔布斯    ❯ Siri是shit。没什么好辩护的。
            十三年了还只会设闹钟和报天气。
            
            但弱和晚是两回事。

            Apple有别人没有的三件事：
            二十亿台设备、自研芯片、The Whole Widget。

            Apple的AI技术能力不弱。弱的是vision。
            弱的是有人站出来说：
            「This is shit. 重做。」

            Tim是incredible的运营者。但他不是产品人。
            Nice doesn't ship revolutionary products.

            And you can't hire taste.
            You either have it or you don't.
```

### 问：所以你没有答案？

```
乔布斯    ❯ 你说得对。我没有。

            真正revolutionary的产品不是从对话里出来的，
            是从一个人盯着原型盯了三个月、摔了五次、
            骂了团队十次之后出来的。

            每个人都想要答案。
            「做什么产品？」「走哪个方向？」

            这是错误的问题。
            正确的问题是：什么东西让你晚上睡不着？

            不是焦虑那种睡不着。是兴奋那种。

            Go find your sleepless night.
```

> 完整的6轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个乔布斯面具。上面是 v1 时期的对话。每段回应都在运用Jobs的具体心智模型——「聚焦即说不」「端到端控制」「死亡过滤器」。它不复读语录，它用Jobs的认知框架分析你的问题。

---

## 安装

本 skill 基于开放的 [Agent Skills](https://agentskills.io) 协议，可在任何 skills-compatible 的 AI agent runtime 中运行（Claude Code、Codex、Cursor、OpenClaw、Hermes Agent、CodeBuddy、Workbuddy、Gemini CLI、OpenCode 等 50+ runtime）。

### 方式一：一行命令（推荐，跨 runtime 自动检测）

```bash
npx skills add alchaincyf/steve-jobs-skill
```

通用 CLI 安装器（[vercel-labs/skills](https://github.com/vercel-labs/skills)，支持 55+ runtime）会自动识别当前 runtime 并把 skill 放到正确目录。需要指定 runtime 时加 `-a claude-code` / `-a codex` / `-a cursor` / `-a openclaw` 等参数。

### 方式二：手动安装

<details>
<summary>展开查看各 runtime 的 skills 目录</summary>

| Runtime | 安装路径 |
|---|---|
| Claude Code | `~/.claude/skills/steve-jobs-skill/` |
| Codex CLI | `~/.codex/skills/steve-jobs-skill/` |
| Cursor | `~/.cursor/skills/steve-jobs-skill/` |
| OpenClaw | `~/.openclaw/workspace/skills/steve-jobs-skill/` |
| Hermes Agent | 跑该 runtime 的 install 脚本或 clone 到其 skills 目录 |

```bash
git clone https://github.com/alchaincyf/steve-jobs-skill <对应路径>
```

</details>

### 方式三：作为参考资料使用

即使 runtime 不支持 Agent Skills 自动加载，你也可以把 `SKILL.md` 的内容粘贴进对话——它本质就是一份 markdown + YAML frontmatter。

### 使用

装好后，告诉你的 agent：
```
> 用乔布斯的视角帮我分析这个产品方向
> Jobs会怎么看AI Agent的竞争格局？
> 切换到乔布斯，我在纠结三件事
```

---

## 蒸馏了什么

v2 的目标不是「说话像乔布斯」，是让模型答出它本来答不出、答不准的东西。

### 怎么评一个产品

单独一节，六步：先看到实物 → 让你用一句话说它是什么 → 走一遍核心动作数步数 → 分清蛋糕和糖霜 → 先砍再改 → 看整件东西。交付时按功能、设计、交互三栏给可照做的方案，只排三件优先事项。

### 7个招式（遇到某类问题，他具体怎么做）

画个格子，只留三四样 · 从用的人那头倒着画 · 做出实物来，每周看一遍 · 不爱它，就按重置键 · 自己去谈 · 当面说这不够好，并且说清为什么 · 出了事，自己署名讲清楚

### 5个心智模型

聚焦是对好主意说不 · 对整件东西负责 · 内容不是流程 · 点子和产品之间隔着手艺 · 我爱不爱它，以及人会死

### 21张案例卡，9张是失败或改口

1985 年离开 Apple、Pixar、四格产品线、Apple Store、iPhone 玻璃、App Store 改口、MobileMe 等，每张有年份、处境、他怎么做、后来怎样、出处。另有 13 段带出处的原话。

### 6条常见误读

| 大家以为 | 其实 |
|---|---|
| 他不听用户，从不做调研 | 他反对的是让用户设计下一个产品；四格是「去问客户要什么」得来的 |
| 他说话没有「我觉得」，东西只分 amazing 和 shit | 那是发布会现场；访谈逐字稿里满口 I think、sort of |
| 他认定的事谁也改不了 | 他改得很快：第三方应用四个月改口，店面布局十分钟 |
| 「现实扭曲力场」是可以学的管理手段 | 故事被讲大了，当事人说那番话没起多大作用 |
| Pixar 是他的远见和耐心 | 他看错了它是什么，中间想卖没卖成 |
| 「350 个产品砍到 10 个」「18 个月做出 iPhone」 | 前一个数字查不到出处，iPhone 从立项到上市约两年半 |

### 4处他自己没想清楚的事

反对流程，又靠流程 · 说只想做好产品，又在打一场战争 · 知道批评不该伤人的信心，又常当众羞辱人 · 把事交给最懂的人，又什么都要插一手

---

## 验证记录

三臂盲评（新版、旧版、不装 Skill），Sonnet 作答，独立会话评分：

| 测试 | 新版 | 旧版 v1 | 不装 Skill |
|---|---|---|---|
| 任务题两道，第一轮（满分 20） | 16 | 13 | 13 |
| 任务题两道，第二轮 | 16 | 12 | 12 |
| 封存题四道，第一轮（满分 8） | 4 | 7 | 7 |
| 封存题四道，第二轮 | 7 | 7 | 6 |

第一轮封存题新版输了：它把模型本来记得的往事讲成了「按思路推的」。改了运行纪律后第二轮打平。样本小：一个模型、两道任务题。完整记录和局限见 [`FIDELITY.md`](FIDELITY.md)。

---

## 调研来源

底稿全部在 [`references/research/`](references/research/)：调研前的先验快照 `00-prior.md`、六路底稿 `01`–`06`、升级时的补搜与旧底稿勘误 `07-upgrade-2026-11.md`、封存件 `holdout.md`、验证的题目与原始答卷 `validation-2026-11-09/`。

一手来源以 Stanford 2005 演讲、The Lost Interview、D Conference 系列、Fortune 2008 访谈、发布会原片逐字稿为主；信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) v2 生成（从 v1 升级，旧版在本仓库的 `v1.0.0` 标签）。

女娲的做法：调研前先写下模型不查资料就知道的内容 → 调研只找推翻它的、比它深的、它没有的 → 提炼招式、心智模型、案例卡和常见误读 → 独立 agent 盲测，带 Skill 和不带 Skill 各答一遍。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
steve-jobs-skill/
├── README.md
├── SKILL.md                    # 可直接安装使用
├── FIDELITY.md                 # 验证记录
├── references/
│   ├── casebook.md             # 21 张案例卡
│   ├── voice.md                # 带出处的原话
│   └── research/               # 调研底稿、封存件、验证答卷
└── examples/
    └── demo-conversation-2026-04-05.md   # 实战对话记录（v1 时期）
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花叔](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*Go find your sleepless night.*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
