# 论文 · Academic Writing Workflow

一个面向 Codex 的中文学术写作协作 skill。适用于课程论文、反思报告和个人发展计划：从理解要求到核实事实、建立论证、按评分细则修改，再到语言润色、中文核对和文档交付。

**先建立可靠内容，再改语言。** 从已有进度继续；只在关键事实、立场或方向不明确时提问。

## 工作流程

1. 阅读作业说明、rubric、模板和 AI 使用规则，区分课程要求、用户要求与建议。
2. 确定目标，把评分描述转成具体写作要求。
3. 整理事实与证据，区分已确认信息、推断、未来计划和待确认事项。
4. 有针对性地补齐材料；反思类采集实际经历，研究类核实来源。
5. 明确中心论点、结构、证据用途与字数分配。
6. 完成初稿，连接证据与分析，保留局限和反面证据。
7. 对照 rubric 找出具体缺口并修改正文。
8. 在内容稳定后润色表达，检查文字异常，保留事实和必要披露。
9. 提供忠实的中文译文核对，同步处理事实或立场修正。
10. 排版并核验最终文件，交付版本清楚的成果。

单独翻译或局部审阅时只处理相应范围，不重新启动完整流程。中文原稿无需重复翻译。

## 安装

将仓库作为 skill 安装到个人 Codex skills 目录，文件夹名为 `academic-writing-workflow`。

在支持 skill-installer 的 Codex 会话中，可以直接提供本仓库链接并说：

> 请将这个仓库安装为个人 skill，名称为 academic-writing-workflow。

手动安装时，将仓库文件放到 `~/.codex/skills/academic-writing-workflow/`。如果设置了 `CODEX_HOME`，则使用其 `skills/academic-writing-workflow/` 目录。不要覆盖已有定制版本；安装后在新一轮会话中调用。

## 使用

显示名称：**论文**。内部名称：`academic-writing-workflow`。

```text
使用 $academic-writing-workflow，先阅读作业说明和评分细则，按论文流程帮我完成这份作业。
```

也可以说：

```text
按论文流程帮我检查这篇初稿，重点核对证据是否支持结论。
```

用户提供材料和真实观点；助手负责组织、研究、起草和核验。根据实际进度进入对应阶段，避免重复询问已经回答的问题。

## 配套技能

本仓库只包含工作流，没有独立的改写引擎，也不捆绑其他技能代码。

- [blader/humanizer](https://github.com/blader/humanizer)：在最终编辑阶段检查模板化表达。
- `clean-user-facing-text`：可选的文字清理和写作模式检查技能；需要另行提供，此仓库未包含。
- documents、pdf、presentations：按材料格式使用当前环境提供的相应技能；具体名称和能力取决于安装环境。

缺少配套技能时，应说明限制并继续可完成的部分，不擅自下载安装、不上传文稿、不声称执行了不存在的检查。文字检查结果不代表作者身份或任何检测器的结论。

## 事实、隐私和 AI 披露

- 不编造经历、数据、文献、引文、心理动机或项目成果。
- 遵守课程对 AI 使用的限制，并保留准确的工具使用声明。
- 不保证成绩，不宣称通过 AI 检测或不可检测。
- 作业写作授权不等于代交、公开资料或联系第三方的授权。
- 本仓库不包含学生作业、个人经历资料、学号、成绩或私密附件。

## English overview

A Chinese-first Codex skill for coursework essays, reflective reports and personal development plans. It covers assignment interpretation, evidence tracking, argument development, rubric-based revision, final prose editing, Chinese meaning checks and document verification.

The workflow preserves factual boundaries and AI disclosures. It does not fabricate citations, promise grades, certify human authorship or submit assignments on the user's behalf. Optional companion skills are not bundled.

Invoke it with `$academic-writing-workflow`. The display name is **论文**.

## License

MIT. See [LICENSE](LICENSE). Companion projects retain their own licenses.
