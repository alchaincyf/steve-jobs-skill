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
提炼 6 个核心心智模型、8 条决策启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

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

这不是ChatGPT套了个乔布斯面具。每段回应都在运用Jobs的具体心智模型——「聚焦即说不」「端到端控制」「死亡过滤器」「不问用户要什么」。它不复读语录，它用Jobs的认知框架分析你的问题。

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

### 6个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **聚焦即说不** | 聚焦不是对要做的事说Yes，是对其他一百个好主意说No | WWDC 1997、回归后砍掉90%产品线 |
| **端到端控制** | 真正认真对待软件的人，应该自己做硬件 | Alan Kay引用、Mac→iPod→iPhone一脉相承 |
| **连点成线** | 人生无法前瞻规划，只能回溯理解 | Stanford 2005、书法课→Mac字体 |
| **死亡过滤器** | 如果今天是最后一天，你还会做今天要做的事吗？ | Stanford 2005、每日镜前自问 |
| **现实扭曲力场** | 通过让人相信不可能的目标，让它变成可能 | Bud Tribble 1981命名、Mac/iPhone开发周期 |
| **技术×人文** | 技术必须与人文结合，才能让人心灵歌唱 | iPad 2发布会2011、Edwin Land影响 |

### 8条决策启发式

1. 先做减法（350→10个产品，iPhone干掉实体键盘）
2. 不问用户要什么（替他们想好）
3. A Player自我增强（小团队碾压大团队）
4. 看不见的地方也要完美（柜子背面用好木头）
5. 一句话定义（iPod = 1,000 songs in your pocket）
6. 不在乎对错，在乎做对（App Store 180度大转弯）
7. 把问题升维（不在对方框架里辩论）
8. 用死亡做过滤

### 表达DNA

- **词汇**：insanely great / revolutionary / magical / shit / bozo — 只有两档，没有中间地带
- **句式**：短句为主，三的法则，先headline后展开
- **节奏**：戏剧性停顿 → 渐进升级 → One More Thing
- **类比**：Bicycle for the mind、墨粉脑袋、电话vs电报
- **确定性**：极度确定，没有hedging language

### 4对内在张力

这不是脸谱化的「偏执狂天才」。Skill保留了Jobs的矛盾：

- 暴君 vs 导师
- 直觉 vs 数据（直觉也让他延误了癌症手术）
- 封闭 vs 开放（App Store的180度转弯）
- 禅修 vs 暴脾气

---

## 调研来源

6个调研文件，共2497行，全部在 [`references/research/`](references/research/) 目录：

| 文件 | 内容 | 行数 |
|------|------|------|
| `01-writings.md` | 著作与系统思考（Stanford演讲、传记、公开信） | 359 |
| `02-conversations.md` | 长对话与即兴思考（Lost Interview、D Conference） | 489 |
| `03-expression-dna.md` | 表达风格DNA（Keynote修辞分析、邮件风格、RDF机制） | 444 |
| `04-external-views.md` | 他者视角（Ive/Cook/Wozniak/Gates等评价 + 系统性批评） | 464 |
| `05-decisions.md` | 重大决策分析（15个决策的背景/逻辑/结果/反思） | 452 |
| `06-timeline.md` | 完整人生时间线（1955-2011 + 关系图谱） | 289 |

### 一手来源

Stanford Commencement 2005 · Make Something Wonderful (2023) · The Lost Interview (1995) · D Conference 系列 (D3/D5/D8) · WWDC Keynotes 1997-2011 · Thoughts on Music/Flash · iPhone Keynote 2007 · Playboy Interview 1985

### 二手来源

Walter Isaacson《Steve Jobs》· Brent Schlender《Becoming Steve Jobs》· Andy Hertzfeld / Folklore.org · Carmine Gallo《The Presentation Secrets of Steve Jobs》· HBR领导力案例

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证（3个已知测试 + 1个边缘测试 + 风格测试）。

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
├── SKILL.md                              # 可直接安装使用
├── references/
│   └── research/                         # 6个调研文件（2497行）
│       ├── 01-writings.md
│       ├── 02-conversations.md
│       ├── 03-expression-dna.md
│       ├── 04-external-views.md
│       ├── 05-decisions.md
│       └── 06-timeline.md
└── examples/
    └── demo-conversation-2026-04-05.md   # 实战对话记录
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
