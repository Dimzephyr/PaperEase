# PaperEase · 公开学习版

**帮助学习英文科研写作，把研究材料组织成清楚、准确的论文。**

PaperEase is an academic writing skill for noncommercial learning and research. This public learning edition contains an independently written workflow, general writing guidance, and original examples, with Chinese explanations and English manuscript output by default.

## 功能

- 起草、修改和检查科研论文的结构与学术英语。
- 区分研究事实、解释、假说与未来应用，保持数值及证据边界。
- 根据任务选择文章规划、语言判断、局部润色或全文审查流程。
- 通过原创示例练习段落组织、比较表达、时态和模态判断。

本公开版按写作任务组织内容，不提供教材的逐章复述、练习答案、完整词表、原书案例或页码映射。使用无需原书PDF、Python、网络或其他技能。

## 安装

下载仓库，或执行：

```sh
git clone https://github.com/Dimzephyr/PaperEase.git
```

将 `skills/paperease` 整个目录复制到 Codex 的技能目录：

- 默认位置：`~/.codex/skills/paperease`
- 设置了 `CODEX_HOME`：`$CODEX_HOME/skills/paperease`

已有同名技能时请先备份。打开新会话，在请求中使用 `$paperease` 或 PaperEase。入口为 [SKILL.md](skills/paperease/SKILL.md)。其他支持 `SKILL.md` 的代理可按其技能发现路径使用本目录。

## 使用示例

```text
使用 $paperease 修改下面的 Introduction，保留研究事实，重点检查问题、证据与贡献是否衔接。
```

```text
使用 PaperEase 将这些材料写成200词以内的英文摘要，只输出稿件。
```

```text
使用 PaperEase 检查这篇论文，按影响排序列出问题和具体改法。
```

```text
使用 PaperEase 解释这段文字中 may not 和 cannot 的含义差别。
```

可在请求中指定目标期刊、语言、字数和输出形式。示例中的虚构数据仅用于练习，不能移入真实论文。

## 内容导航

|文件|用途|
|---|---|
|[证据与主张](skills/paperease/references/evidence.md)|控制主张范围、数量比较与不确定性|
|[文章与段落规划](skills/paperease/references/planning.md)|安排读者需要的信息和论证顺序|
|[语言判断](skills/paperease/references/language.md)|检查语法改动是否改变含义|
|[修订流程](skills/paperease/references/revision.md)|执行起草、润色、压缩与审查|
|[原创练习](skills/paperease/references/practice.md)|学习示例与可选工作表|

## 许可

项目原创内容采用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)：允许在署名、注明修改等许可条件下进行非商业分享与改编。完整条款见 [LICENSE](LICENSE)。本项目面向非商业学习与研究；具体权利和条件以许可证为准。

建议署名：`PaperEase — Dimzephyr — https://github.com/Dimzephyr/PaperEase — CC BY-NC 4.0`。

## 致谢与内容边界

项目的学习背景包括 Hilary Glasman-Deal 的 *Science Research Writing*（第二版，World Scientific）。书目信息见 [ATTRIBUTION.md](ATTRIBUTION.md)。PaperEase与作者、出版社无隶属或背书关系。

仓库不分发原书PDF、全文抽取、出版物图像、逐章转述资料或教材答案。项目许可不授予对原书及其他第三方材料的任何权利。“学习用途”声明和非商业许可本身不构成对第三方内容的授权；贡献者只应提交可授权的原创内容或已获许可的材料。

如认为仓库内容涉及权利问题，可通过 [Issues](https://github.com/Dimzephyr/PaperEase/issues) 提供具体文件位置和说明；请勿在Issue中上传原书或私人稿件。贡献要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。
