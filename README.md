# 保研自荐信写作 Skill

先帮助学生理清写信思路，再围绕选定导师，完成真实、具体、有联系依据的中文保研自荐信。

本 skill 面向不同学科、经历深浅和申请意向的学生，支持硕士、直博、跨方向申请，以及已有信件的修改。写作从本人的材料出发：选择值得展开的经历，讲清实际贡献，说明为什么联系这位老师，以及希望得到什么回应。

**[下载 skill 压缩包](baoyan-outreach-letter.zip) · [查看完整规则](baoyan-outreach-letter/SKILL.md) · [查看硕士自荐信参考模板](baoyan-outreach-letter/references/masters-letter-template.md)**

## 适合哪些情况

- 已有简历、完整项目整理或导师筛选报告，希望直接承接材料写信。
- 有科研、课程论文、竞赛、调查、设计、实习或阅读积累，需要帮助组织表达。
- 希望跨方向申请，需要说清已有训练可以迁移到哪里、还希望学习什么。
- 已有自荐信，希望调整导师段、研究经历、申请类型或整封信的组织。

没有正式科研项目、论文或量化成果，也可以从实际课程与学习经历开始。

## 怎样帮助你写信

推荐衔接顺序：**个人项目整理 → 根据学校筛选导师 → 针对选定导师制作自荐信。**

1. **先读取材料。** 已提供路径、附件或正文时直接读取；有完整项目整理就复用，不重新采访整个项目。
2. **明确本次申请。** 起草完整信件前确认申请硕士还是直博。已经明确的直接沿用，未知时先询问，不从旧信文件名或未来读博愿望推断。
3. **确定联系对象。** 有导师筛选报告时，读取选定导师的研究分析、已选论文、联系依据和未知项；尚未选择时先了解本次准备联系谁。
4. **展示写信主线。** 简短说明准备突出什么经历、与导师研究有什么具体联系、结尾提出什么请求。
5. **逐轮补齐缺口。** 每轮默认只问一个关键问题。资料足够时直接起草，只有使用者知道的事实、意愿和阅读情况才需要本人补充。
6. **成稿并核对。** 检查身份、贡献、结果条件、论文依据、申请类型、当前阶段与附件，按实际用途调整篇幅。

前两个 skill 的成果可以直接提供，也可使用自己整理的材料，无需先安装其他 skill。

## 安装与开始使用

这是一个由 `SKILL.md` 和参考资料组成的 Agent Skill，需要在支持技能的 AI 助手中使用。以下以 Codex 的本地使用方式为例。

### 方式一：通过 Skill Installer 安装

在 Codex 中输入：

```text
请使用 $skill-installer，从以下 GitHub 目录安装保研自荐信写作 skill：
https://github.com/dasdw-cyber/baoyan-outreach-letter/tree/main/baoyan-outreach-letter
```

### 方式二：下载后放入本地技能目录

1. 下载本仓库的 [baoyan-outreach-letter.zip](baoyan-outreach-letter.zip)。
2. 解压后，将完整的 `baoyan-outreach-letter` 文件夹放入本地用户技能目录 `~/.agents/skills/`。
3. 保持 `SKILL.md` 与 `references`、`assets`、`agents` 等文件的相对位置不变。

Windows 下，入口文件的位置可为：

```text
%USERPROFILE%\.agents\skills\baoyan-outreach-letter\SKILL.md
```

Codex 会自动识别新安装的技能；若未出现，可重启后再查看。安装位置与发现方式参见 [OpenAI 官方 Skills 文档](https://learn.chatgpt.com/docs/build-skills)。

## 开始对话的示例

安装后，可以这样发起请求，将〔〕内容替换为自己的情况：

```text
请使用 $baoyan-outreach-letter，帮我给〔学校〕的〔导师姓名〕老师写一封硕士申请自荐信。

我的材料在〔文件夹位置〕，已有〔简历／完整项目整理／导师筛选报告／旧信，按实际填写〕。
请先读取材料，帮我理清本封信的写作主线，再每轮只补问一个关键问题。
这次用于〔详细自荐材料／首次联系邮件正文〕。
```

没有现成文件时，也可以直接说明想申请的方向和记得的一段经历，助手会先整理，再逐步澄清。申请直博时说明本次直博意向；只需改某一段时，直接给出原文和修改范围。

## 会得到什么

- **一封符合本次用途的信件。** 首次联系邮件提供主题与正文；详细自荐材料保留相关经历的推进过程。
- **针对目标导师的联系理由。** 从实际研究证据与个人训练中选取具体连接点，区分已有能力、可迁移训练与学习兴趣。
- **按需修改的稿件。** 可以只调整用户指定的段落；需要 Word 文件时可提出排版要求，导出与预览依当前环境的工具完成。

仓库内附有 [硕士自荐信参考模板](baoyan-outreach-letter/references/masters-letter-template.md)，用于查看叙述结构。段落按材料合并、删减，起草个人信件时会替换为本人事实。

## 写作标准

- **用真实动作体现能力。** 写清问题、本人承担的工作、关键做法及结果依据，保留团队贡献与个人贡献、完成与计划等边界。
- **按学科选择内容。** 实验与工程、文献论证、调查分析、设计作品和课程阅读采用适合各自材料的叙述重点。
- **导师段有证据。** 使用论文时优先核对源 PDF 并阅读相关正文；只有摘要、题目或官网介绍时，按实际范围表达。
- **分清谁读过论文。** 助手阅读不等于学生本人阅读，个人理解与感受以本人确认的信息为准。
- **申请意愿来自本人。** 硕士、直博、继续读博、提前参与研究及附件安排，均按本次实际情况组织。
- **表达清楚、有分寸。** 用具体事实和联系理由支撑主线，篇幅随用途调整。

本 skill 负责写作与文件交付；发送邮件或联系导师由使用者自行安排。

## 仓库内容

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](baoyan-outreach-letter/SKILL.md) | 总体流程、材料衔接、事实边界和交付检查 |
| [guided-dialogue.md](baoyan-outreach-letter/references/guided-dialogue.md) | 材料优先、确认申请类型、逐轮引导 |
| [writing-guide.md](baoyan-outreach-letter/references/writing-guide.md) | 不同经历的组织、导师段、篇幅与措辞 |
| [paper-matching.md](baoyan-outreach-letter/references/paper-matching.md) | 研究材料阅读与具体连接的证据规则 |
| [masters-letter-template.md](baoyan-outreach-letter/references/masters-letter-template.md) | 已确认的详细硕士自荐信参考结构 |
| [docx-format.md](baoyan-outreach-letter/references/docx-format.md) | Word 正文排版与分页检查 |
| [student-profile.md](baoyan-outreach-letter/assets/student-profile.md) | 助手逐步维护的学生资料模板 |
| [mentor-profile.md](baoyan-outreach-letter/assets/mentor-profile.md) | 助手维护的导师资料与匹配依据模板 |
| [openai.yaml](baoyan-outreach-letter/agents/openai.yaml) | 展示名称、简介与默认提示词 |

两份资料模板用于助手整理工作记录，使用者无需一次填写整张表。个人材料保存在各自任务目录中。
