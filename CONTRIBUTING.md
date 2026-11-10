# 贡献指南

# Contributing

感谢参与《世界公民基本法》草案的共创。请先阅读 [README.md](README.md) 中的撰写目标和 [docs/PURPOSE.md](docs/PURPOSE.md)，并遵守 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 与 [TERMS.md](TERMS.md)。

## 原则

1. **默认分支只放已确认的工作正文。** 正在讨论的修改在分支或分叉上进行，经拉取请求合并。
2. **一议题一建议。** 每个议题只处理一项明确请求，说明理由，并尽可能附上拟议的中文和英文条文。
3. **先议题，后改稿。** 拉取请求应关联已有议题，或在说明中写清目的。不要直接在默认分支上修改正文。
4. **正文、评注、译文分开。** 不要在同一文件里把这三者混在一起而不加标注。正式条文只进入 `text/` 中的正文文件。
5. **编号保持稳定。** 不重编第1–144条及已有扩展编号。需要在两条之间插入时，使用扩展编号（例如第12-1条）。
6. **修订必附对照。** 说明中写明：条文号、旧文、新文、简要理由。不要只提交“润色后的全文”而不标出改动点。
7. **合并前审查。** 凡改动条文、定义、例外、程序或中英对应关系的，合并前须做一致性审查：定义是否同一含义、权利是否被其他条文悄然抵消、例外是否宽于规则、程序是否有着落、互引是否仍然有效、中英是否同一规则。
8. **未经确认不得合并到默认分支。** 由项目发起人或其指定的维护者接受正式措辞。平行草稿须收口为同一份正文。
9. **合并后更新 [CHANGELOG.md](CHANGELOG.md）。** 写明日期、版本或拉取请求编号，以及一句话摘要。
10. **不得擅自把未合并文本当作正式文本对外发布。**

## 建议议题时

请写明：

- 涉及的条文号（如为新条，建议的扩展编号和插入位置）；
- 问题是什么（缺漏、冲突、中英不一致，或可核验的文书对照问题）；
- 拟议新文（中文和英文）；
- 简要理由；如引用条约或宣言，须给出可核验的官方出处，不得编造。

维护者可以关闭或合并重复议题，也可以拒绝夹带个人数据、威胁，或其他不应进入正式记录的内容，并说明理由。

## 提交拉取请求时

- 从默认分支拉出专题分支，分支名简短说明改动（例如 `amend-art-23`）。
- 只改与该议题有关的文件。
- 若改动正文，同步更新修订说明和 `CHANGELOG.md`。
- 自检：中英是否对应；是否误改未涉及的条文；是否把评注写进了条文。

## English summary

The default branch holds confirmed working text only. Propose one request per issue, with a short rationale and bilingual wording where possible. Work on a branch or fork, link the pull request to an issue, and do not mix official text, commentary and translation in one file without labels. Keep article numbers stable; use extension numbers for insertions. Each revision must state the article number, old wording, new wording and a short rationale. Changes to articles or definitions require a consistency review. Do not merge to the default branch without approval by the project initiator or a named maintainer. After a merge, update the changelog. Do not publish unmerged text as if it were the official wording.
