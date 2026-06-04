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

需要 [Claude Code](https://docs.claude.com/en/docs/claude-code)。把本仓库克隆到 Claude Code 的 skills 目录即可：

```bash
# 用户级（所有项目可用）
git clone https://github.com/ZadAnthony/serenity-skill.git ~/.claude/skills/serenity

# 或项目级（仅当前项目）
git clone https://github.com/ZadAnthony/serenity-skill.git <你的项目>/.claude/skills/serenity
```

克隆后新开一个 Claude Code 会话，输入 `/serenity` 即可调用（聊到相关板块也会自动触发）。

更新：`cd ~/.claude/skills/serenity && git pull`。

## 用法 / Usage

```
/serenity 分析一下 $CRDO 这只票值不值得
/serenity 帮我看 1.6T 光模块这条链现在还有没有没被定价的卡点
```

或直接聊到 AI 供应链 / 半导体 / 光通信等投资话题，Skill 会自动介入。它会：先建 thesis 再谈标的、沿供应链逆向找"卡点中的卡点"、把可度量数字按一手源 / 推断 / 推测分级标注、最后派独立 reviewer 复核报告（防确认偏误与取数失真）。

## 文件结构

| 文件 | 作用 |
|---|---|
| `SKILL.md` | Skill 入口：核心立场、输出契约、分析流水线、各步判据 |
| `methodology.md` | 完整知识底座（9 节，由 2071 条公开推文自底向上提炼 + 反向校验加固） |

Skill 自包含，运行只依赖这两个文件，不读取任何外部数据。

## License

方法论提炼内容供个人学习 / 研究使用。底层投资观点版权归原作者所有；本仓库为第三方整理，请勿用于商业用途或冒充原作者。
