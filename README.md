<div align="center">

  <h1>PaperEase</h1>
  <h3>证据驱动的科研写作助手</h3>
  <p><b>让研究贡献清晰、有力地呈现。</b><br>提炼核心贡献 · 串联研究证据 · 精修学术英语</p>

  <p>
    <a href="LICENSE"><img alt="License: CC BY-NC 4.0" src="https://img.shields.io/badge/license-CC_BY--NC_4.0-2563eb"></a>
    <a href="#installation"><img alt="Install for Codex" src="https://img.shields.io/badge/agent-Codex-111827"></a>
    <a href="#guides"><img alt="5 writing guides" src="https://img.shields.io/badge/writing_guides-5-0d9488"></a>
    <a href="README_EN.md"><img alt="中文 | English" src="https://img.shields.io/badge/language-中文%20%7C%20English-6366f1"></a>
  </p>

  <p>
    <a href="#features">核心特点</a> ·
    <a href="#quick-start">快速开始</a> ·
    <a href="#installation">安装</a> ·
    <a href="#example">效果示例</a> ·
    <a href="#guides">写作指南</a> ·
    <a href="README_EN.md">English</a>
  </p>

</div>

---

**PaperEase** 帮助你把研究材料组织成**主线清楚、贡献突出、语言准确**的英文论文。它围绕“研究价值—支撑证据—论文表达”，串联起草、结构重组、语言精修和全文审查，让关键发现成为文章的中心。

默认用中文解释、用英文交付稿件；可按请求切换语言、篇幅和输出形式。适用于从一句话到完整论文的写作任务。

## 目录

- [1. 核心特点](#features)
- [2. 快速开始](#quick-start)
- [3. 你提供什么，会得到什么](#inputs-outputs)
- [4. 工作方式与效果示例](#example)
- [5. 安装与调用](#installation)
- [6. 内置写作指南](#guides)
- [7. 许可、来源与贡献](#license-and-contributing)

<a id="features"></a>

## 1. 核心特点

| 特点 | 具体做什么 | 对写作的帮助 |
|---|---|---|
| **围绕贡献组织全文** | 从材料中提炼关键发现，安排研究问题、结果和意义的呈现顺序 | 让读者迅速理解研究价值 |
| **把结果写成论证** | 为每段确定明确任务，连接主张、证据和解释 | 形成连贯、有说服力的论文主线 |
| **精修学术英语** | 打磨动词、时态、语态、指代和句间衔接，准确表达技术关系 | 句子更简洁，含义更清楚 |
| **贯通起草与修订** | 按任务处理起草、重组、润色、压缩、翻译与全文审查 | 从一个句子到完整论文都能调用 |
| **在改写中学习** | 用原创示例、改前改后对照和简短理由解释写作选择 | 把一次修改转化为可复用的写作经验 |

技能采用文本文件组织，安装后即可调用，并按任务加载对应指南。

<a id="quick-start"></a>

## 2. 快速开始

安装后，把材料或原稿交给 Agent，并在请求中写明 `$paperease` 或 `PaperEase`：

| 想做什么 | 可以直接复制的请求 |
|---|---|
| **从材料起草摘要** | `使用 $paperease，根据以下研究材料写一段 200 词以内的英文摘要，突出核心发现与研究意义。` |
| **梳理 Introduction** | `使用 PaperEase 重组这段 Introduction，建立清楚的问题主线，让已有证据自然引出本文贡献。` |
| **精修学术英语** | `使用 PaperEase 精修下面的 Results，突出关键比较与定量结果，让句子简洁、准确、有力。` |
| **压缩或翻译** | `使用 PaperEase 将这段中文 Discussion 写成 180 词以内的英文，集中解释主要发现及其意义。` |
| **检查整篇论文** | `使用 PaperEase 审查这篇论文，优先找出最能提升论证与表达的修改，并给出具体改法。` |
| **学习表达差异** | `使用 PaperEase 解释这段话中 may not 与 cannot 的含义差别，并给出适合当前证据的改写。` |

<a id="inputs-outputs"></a>

## 3. 你提供什么，会得到什么

| 任务 | 提供的材料 | 主要产出 |
|---|---|---|
| 起草 | 研究问题、方法与已有结果；需要引用时附来源 | 突出研究问题、关键发现与意义的草稿 |
| 修订 | 待改原文、修改目标；可指定语言和字数 | 可直接使用的修改稿；按需附修改理由 |
| 审查 | 稿件或指定章节；如有目标期刊，可附其要求 | 按影响排序的问题清单与可执行改法 |
| 教学 | 想理解的句子或写作问题 | 少量对照示例与理由 |

从手头已有材料开始即可。你可以指定目标期刊、字数、语言和输出形式；需要直接使用稿件时，写明“只输出修改稿”。

<a id="example"></a>

## 4. 工作方式与效果示例

**理解研究 → 组织证据 → 打磨表达 → 贯通全文**

1. **理解研究：** 识别研究问题、关键结果及其支持的贡献。
2. **组织证据：** 给每段明确的论证任务，让结果与解释紧密衔接。
3. **打磨表达：** 用准确的动词、定量比较和清楚的句法呈现发现。
4. **贯通全文：** 让标题、摘要、正文和结论共同强化文章的核心信息。

下面是原创教学示例，数据为虚构：

| | 内容 |
|---|---|
| **研究材料** | 同一处理任务中，新流程用时 8 min，原流程用时 12 min。 |
| **修改前** | “The revised workflow took 8 min. The original workflow took 12 min.” |
| **修改后** | “For the tested task, the revised workflow shortened processing time by one-third, from 12 to 8 min.” |
| **写作提升** | 把两项用时整合为直接比较，量化省时幅度，让研究贡献成为句子的重点。 |

**把证据中的价值写出来**，是 PaperEase 贯穿起草与修订的写作思路。更多练习见[原创练习与工作表](skills/paperease/references/practice.md)。

<a id="installation"></a>

## 5. 安装与调用

### 获取技能

下载仓库，或执行：

```bash
git clone https://github.com/Dimzephyr/PaperEase.git
```

### 安装到 Codex

将 `skills/paperease` **整个文件夹**复制到技能目录，保留其中的 `references/` 和 `agents/`：

| 环境 | 放置位置 |
|---|---|
| Windows 默认目录 | `%USERPROFILE%\.codex\skills\paperease` |
| macOS / Linux 默认目录 | `~/.codex/skills/paperease` |
| 设置了 `CODEX_HOME` | 该目录下的 `skills/paperease` |

已有同名技能时先备份，再替换目录。其他支持 `SKILL.md` 的 Agent 可按其技能发现规则放置完整文件夹。

### 开始使用

打开新的 Codex 会话，输入：

```text
使用 $paperease，帮我修改下面的论文段落。
目标：突出关键发现，让结构清楚、表达准确。只输出修改稿。

[在这里粘贴原文]
```

技术标识为 `paperease`，入口文件是 [SKILL.md](skills/paperease/SKILL.md)。

<a id="guides"></a>

## 6. 内置写作指南

| 指南 | 回答的问题 | 主要内容 |
|---|---|---|
| [证据与主张](skills/paperease/references/evidence.md) | 怎样把研究结果转化为有分量的主张？ | 证据解释、定量比较、结论表述 |
| [文章与段落规划](skills/paperease/references/planning.md) | 怎样安排信息，读者才跟得上？ | 章节任务、段落组织、证据衔接 |
| [语言判断](skills/paperease/references/language.md) | 怎样把技术含义表达得更准确？ | 时态、语态、限定、指代与逻辑关系 |
| [修订流程](skills/paperease/references/revision.md) | 当前任务应该怎样改？ | 起草、润色、重组、压缩、翻译与全文审查 |
| [原创练习与工作表](skills/paperease/references/practice.md) | 怎样练习并理解修改理由？ | 虚构情境、对照示例、可选工作表 |

<a id="license-and-contributing"></a>

## 7. 许可、来源与贡献

### 使用许可

项目原创内容采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)，允许在署名、注明修改等许可条件下进行**非商业分享与改编**。完整条款见 [LICENSE](LICENSE)。

建议署名：`PaperEase — Dimzephyr — https://github.com/Dimzephyr/PaperEase — CC BY-NC 4.0`。

### 来源与内容边界

项目的学习背景包括 Hilary Glasman-Deal 的 *Science Research Writing*。PaperEase 按写作任务独立组织指南并编写示例；书目信息及第三方权利说明见 [ATTRIBUTION.md](ATTRIBUTION.md)。

### 参与改进

欢迎通过 [Issues](https://github.com/Dimzephyr/PaperEase/issues) 分享使用反馈，或通过 Pull Request 改进表达、补充原创示例。贡献方式见 [CONTRIBUTING.md](CONTRIBUTING.md)。

README 的展示结构参考了 [Nature Skills](https://github.com/Yuan1z0825/nature-skills)，文字与示例由本项目独立编写。
