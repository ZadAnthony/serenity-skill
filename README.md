# Serenity 投资分析 Skill

把投资人 **Serenity（X / Twitter [@aleabitoreddit](https://x.com/aleabitoreddit)）** 的 **"供应链卡点逆向"投资逻辑和方法论操作化**的 [Claude Code](https://docs.claude.com/en/docs/claude-code) Skill —— 不是模仿他说话，而是用他**怎么提问、怎么排除、怎么把热闹拆成可验证环节**的方式，帮你分析一只票 / 一个板块 / 一个 thesis。

适用：美股 / AI 供应链 / 光模块（CPO·硅光·InP）/ 半导体 / 内存 / NeoCloud / 电力液冷 / 机器人等投资分析。

> An operationalized Claude Code Skill that turns the **"reverse-engineer the supply-chain bottleneck"** investing methodology of **Serenity ([@aleabitoreddit](https://x.com/aleabitoreddit))** into a repeatable analysis engine for US equities / the AI infrastructure supply chain. It models *how he frames questions and disqualifies ideas*, not his voice.

---

## ⚠️ 免责声明 / Disclaimer（先读这段）

- **不是投资建议（NOT investment advice）。** 本仓库仅用于学习、研究投资分析方法论。任何标的、信念分档、估值区间都不构成买卖建议；真金白银请自行 DYOR。
- **第三方独立提炼，非官方、未获授权背书。** 本 Skill 基于 [@aleabitoreddit](https://x.com/aleabitoreddit) 的**公开推文**自底向上系统化整理，**与本人没有任何关联，未经其授权或认可**。"Serenity" 名称仅用于标识所提炼方法论的来源。
- **内含分析性点评，均属第三方观点。** 文中对其持仓动机、战绩、已知偏差（如 "talking his book"、幸存者偏差等）的讨论，是为帮助使用者批判性看待信息源而做的**第三方分析与提醒**，不代表事实陈述，亦无意贬损。
- **他的战绩均为其本人自述、未经独立审计**，引用时务必带此限定。
- 投资有风险，决策风险与后果由使用者自行承担。

---

## 安装 / Install

这是一个**可移植的 Agent Skill**（开放的 `SKILL.md` 格式）——核心就是 `SKILL.md` + `methodology.md` 两个指令文件。**任何能加载 Agent Skill、或把指令作为上下文的 agent runtime 都能用**，[Claude Code](https://docs.claude.com/en/docs/claude-code) 只是其中一个 host（Claude Agent SDK、claude.ai、以及其它支持 Skills 格式的 agent 工具同样可用，安装与触发方式按各自约定）。

以 Claude Code 为例，克隆到它的 skills 目录即可：

```bash
# 用户级（所有项目可用）
git clone https://github.com/ZadAnthony/serenity-skill.git ~/.claude/skills/serenity

# 或项目级（仅当前项目）
git clone https://github.com/ZadAnthony/serenity-skill.git <你的项目>/.claude/skills/serenity
```

克隆后新开会话，输入 `/serenity` 即可调用（聊到相关板块也会自动触发）。**其它 runtime**：把这两个文件放进它的 skill 目录、或作为系统指令 / 上下文加载即可，触发方式按该 runtime 约定。

更新：`cd ~/.claude/skills/serenity && git pull`。

## 用法 / Usage

```
/serenity 分析一下 $CRDO 这只票值不值得
/serenity 帮我看 1.6T 光模块这条链现在还有没有没被定价的卡点
```

或直接聊到 AI 供应链 / 半导体 / 光通信等投资话题，Skill 会自动介入。它把分析做成一份**围着标的本身的专业投研报告**：先用大白话把这条链 / 这门生意讲清楚（照顾只听过名词的非专业读者），再把他的方法**内化**地跑一遍——沿供应链逆向找"卡点中的卡点"、逐个名字点明命中哪些卡点判据 / 踩哪些红旗、给 bear/base/bull 客观区间与买卖定档（🔥Fire Sale～Sell 五档）；可度量数字按一手源 / 管理层声称 / 推断 / 推测分级标注、并独立重核关键市值；最后派独立 reviewer 复核报告（无 sub-agent 环境则降级为显式标注的自查），防确认偏误与取数失真。**Serenity 本人的视角只在你要他的判断、或要据他战绩下注时才出现**，其余时候方法已内化在分析里。

## 文件结构

| 文件 | 作用 |
|---|---|
| `SKILL.md` | Skill 入口：核心立场、输出契约、分析流水线、各步判据 |
| `methodology.md` | 完整知识底座（9 节，由 2071 条公开推文自底向上提炼 + 反向校验加固） |

Skill 自包含，只依赖这两个文件、不捆绑任何数据集。两点 host 能力会影响完整度（都不是 Claude Code 专属）：① 要产出准确报告需 host 具备**联网 / 检索**能力（按取数纪律拉实时财务 / 市值）；② "最后一步独立复核"在支持**子 agent** 的 runtime 上跑独立 reviewer，不支持时按内置降级路径自查并显式标注。

## License

方法论提炼内容供个人学习 / 研究使用。底层投资观点版权归原作者所有；本仓库为第三方整理，请勿用于商业用途或冒充原作者。
