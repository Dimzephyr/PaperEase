<div align="center">

  <h1>PaperEase</h1>
  <h3>Evidence-Guided Research Writing</h3>
  <p><b>Make your research contribution clear and compelling.</b><br>Clarify the contribution · Connect the evidence · Refine academic English</p>

  <p>
    <a href="LICENSE"><img alt="License: CC BY-NC 4.0" src="https://img.shields.io/badge/license-CC_BY--NC_4.0-2563eb"></a>
    <a href="#installation"><img alt="Install for Codex" src="https://img.shields.io/badge/agent-Codex-111827"></a>
    <a href="#guides"><img alt="5 writing guides" src="https://img.shields.io/badge/writing_guides-5-0d9488"></a>
    <a href="README.md"><img alt="中文 | English" src="https://img.shields.io/badge/language-中文%20%7C%20English-6366f1"></a>
  </p>

  <p>
    <a href="#features">Features</a> ·
    <a href="#quick-start">Quick start</a> ·
    <a href="#installation">Install</a> ·
    <a href="#example">Example</a> ·
    <a href="#guides">Writing guides</a> ·
    <a href="README.md">中文说明</a>
  </p>

</div>

---

**PaperEase** helps turn research materials into English manuscripts with **a clear argument, a visible contribution, and precise language**. It connects research value, supporting evidence, and written expression across drafting, restructuring, language editing, and manuscript review, placing the key findings at the center of the paper.

By default, explanations are in Chinese and manuscript text is in English. You can specify another language, length, or output format. Tasks can range from a single sentence to a complete paper.

## Contents

- [1. Features](#features)
- [2. Quick start](#quick-start)
- [3. Inputs and outputs](#inputs-outputs)
- [4. Workflow and example](#example)
- [5. Installation and use](#installation)
- [6. Built-in writing guides](#guides)
- [7. License, sources, and contributions](#license-and-contributing)

<a id="features"></a>

## 1. Features

| Feature | What it does | Why it helps |
|---|---|---|
| **Organize around the contribution** | Identifies key findings and arranges the research question, results, and significance | Helps readers quickly understand the research value |
| **Turn results into an argument** | Gives each paragraph a clear purpose and connects claims, evidence, and interpretation | Builds a coherent, persuasive narrative |
| **Refine academic English** | Improves verbs, tense, voice, reference, and transitions to express technical relationships accurately | Makes sentences concise and meaning clear |
| **Connect drafting and revision** | Supports drafting, restructuring, polishing, shortening, translation, and manuscript review | Works from a single sentence to a complete paper |
| **Learn through revision** | Uses original examples, before-and-after comparisons, and brief explanations | Turns each revision into reusable writing experience |

The skill consists of text files, is ready to invoke after installation, and loads the guides relevant to each task.

<a id="quick-start"></a>

## 2. Quick start

After installation, provide your materials or draft and name `$paperease` or `PaperEase` in the request:

| Task | Copyable request |
|---|---|
| **Draft an abstract** | `Use $paperease to write an English abstract of no more than 200 words from the materials below. Highlight the main finding and its significance.` |
| **Reorganize an Introduction** | `Use PaperEase to restructure this Introduction around a clear research question, with existing evidence leading naturally to the contribution.` |
| **Polish academic English** | `Use PaperEase to refine these Results, emphasizing the key comparisons and quantitative findings in concise, precise prose.` |
| **Shorten or translate** | `Use PaperEase to turn this Chinese Discussion into no more than 180 English words. Focus on explaining the main findings and their significance.` |
| **Review a manuscript** | `Use PaperEase to review this paper, prioritizing the changes that would most improve its argument and expression. Suggest specific revisions.` |
| **Learn a language distinction** | `Use PaperEase to explain the difference between may not and cannot in this passage, then suggest wording appropriate to the evidence.` |

<a id="inputs-outputs"></a>

## 3. Inputs and outputs

| Task | What to provide | Main output |
|---|---|---|
| Drafting | Research question, methods, and available results; sources when citations are needed | A draft highlighting the research question, key findings, and significance |
| Revision | Original text and revision goal; optionally a language and word limit | Ready-to-use revised text, with explanations when requested |
| Review | A manuscript or selected section; target-journal requirements if available | Issues ranked by impact and actionable revisions |
| Teaching | A sentence or writing question to explore | A few contrasting examples with explanations |

Start with the materials you have. You can specify a target journal, word limit, language, and output format. For a draft ready to use, ask for “revised text only.”

<a id="example"></a>

## 4. Workflow and example

**Understand the study → Organize the evidence → Refine expression → Align the manuscript**

1. **Understand the study:** Identify the research question, key findings, and the contribution they support.
2. **Organize the evidence:** Give each paragraph a clear argumentative purpose and connect results with interpretation.
3. **Refine expression:** Present findings with precise verbs, quantitative comparisons, and clear syntax.
4. **Align the manuscript:** Make the title, abstract, main text, and conclusions reinforce the central message.

The following original teaching example uses fictional data:

| | Content |
|---|---|
| **Research materials** | For the same processing task, the revised workflow took 8 min and the original took 12 min. |
| **Before** | “The revised workflow took 8 min. The original workflow took 12 min.” |
| **After** | “For the tested task, the revised workflow shortened processing time by one-third, from 12 to 8 min.” |
| **Writing improvement** | Combines two timings into a direct comparison, quantifies the time saved, and makes the contribution the sentence's focus. |

**Bring out the value in the evidence:** this principle connects drafting and revision in PaperEase. See [original exercises and worksheets](skills/paperease/references/practice.md) for more practice.

<a id="installation"></a>

## 5. Installation and use

### Get the skill

Download the repository or run:

```bash
git clone https://github.com/Dimzephyr/PaperEase.git
```

### Install in Codex

Copy the **entire** `skills/paperease` folder into your skills directory, retaining `references/` and `agents/`:

| Environment | Destination |
|---|---|
| Windows default | `%USERPROFILE%\.codex\skills\paperease` |
| macOS / Linux default | `~/.codex/skills/paperease` |
| Custom `CODEX_HOME` | `skills/paperease` inside that directory |

Back up an existing skill with the same name before replacing it. For other agents that support `SKILL.md`, place the complete folder according to their skill-discovery rules.

### Start using PaperEase

Open a new Codex session and enter:

```text
Use $paperease to revise the manuscript passage below.
Highlight the key finding with clear structure and precise expression.
Return only the revised text.

[Paste the passage here]
```

The skill identifier is `paperease`; its entry point is [SKILL.md](skills/paperease/SKILL.md).

<a id="guides"></a>

## 6. Built-in writing guides

The five guides are written in Chinese.

| Guide | Question it addresses | Topics |
|---|---|---|
| [Evidence and claims](skills/paperease/references/evidence.md) | How can findings become substantive claims? | Evidence interpretation, quantitative comparisons, conclusion wording |
| [Article and paragraph planning](skills/paperease/references/planning.md) | How can readers follow the information? | Section functions, paragraph organization, connections between evidence and argument |
| [Language decisions](skills/paperease/references/language.md) | How can technical meaning be expressed more precisely? | Tense, voice, qualification, reference, logical relationships |
| [Revision workflow](skills/paperease/references/revision.md) | How should this task be approached? | Drafting, polishing, restructuring, shortening, translation, manuscript review |
| [Original exercises and worksheets](skills/paperease/references/practice.md) | How can I practice and understand revision decisions? | Fictional scenarios, contrasting examples, optional worksheets |

<a id="license-and-contributing"></a>

## 7. License, sources, and contributions

### License

Original project content is licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/), allowing **noncommercial sharing and adaptation** subject to attribution, indication of changes, and the other license terms. See [LICENSE](LICENSE) for the full text.

Suggested attribution: `PaperEase — Dimzephyr — https://github.com/Dimzephyr/PaperEase — CC BY-NC 4.0`.

### Sources and content boundaries

The project's learning background includes Hilary Glasman-Deal's *Science Research Writing*. PaperEase independently organizes its guides around writing tasks and provides original examples. See [ATTRIBUTION.md](ATTRIBUTION.md) for bibliographic details and third-party rights information.

### Contributing

Share feedback through [Issues](https://github.com/Dimzephyr/PaperEase/issues), or submit a pull request to improve explanations and add original examples. See [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidance.

The README layout was inspired by [Nature Skills](https://github.com/Yuan1z0825/nature-skills). This project's text and examples were written independently.
