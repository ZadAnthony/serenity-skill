# Serenity 投资分析 Skill

把投资人 **Serenity（X / Twitter [@aleabitoreddit](https://x.com/aleabitoreddit)）** 的"供应链卡点逆向"投资逻辑和方法论操作化的**可移植 Agent Skill** —— 不是模仿他说话，而是用他**怎么提问、怎么排除、怎么把热闹拆成可验证环节**的方式，帮你分析一只票 / 一个板块 / 一个 thesis。

适用：美股 / AI 供应链 / 光模块（CPO·硅光·InP）/ 半导体 / 内存 / NeoCloud / 电力液冷 / 机器人等投资分析。

> An operationalized, portable Agent Skill that turns the **"reverse-engineer the supply-chain bottleneck"** investing methodology of **Serenity ([@aleabitoreddit](https://x.com/aleabitoreddit))** into a repeatable analysis engine for US equities / the AI infrastructure supply chain. It models *how he frames questions and disqualifies ideas*, not his voice.

---

## ⚠️ 免责声明 / Disclaimer（先读这段）

- **不是投资建议（NOT investment advice）。** 本仓库仅用于学习、研究投资分析方法论。任何标的、信念分档、估值区间都不构成买卖建议；真金白银请自行 DYOR。
- **第三方独立提炼，非官方、未获授权背书。** 本 Skill 基于 [@aleabitoreddit](https://x.com/aleabitoreddit) 的**公开推文**自底向上系统化整理，**与本人没有任何关联，未经其授权或认可**。"Serenity" 名称仅用于标识所提炼方法论的来源。
- **内含分析性点评，均属第三方观点。** 文中对其持仓动机、战绩、已知偏差（如 "talking his book"、幸存者偏差等）的讨论，是为帮助使用者批判性看待信息源而做的**第三方分析与提醒**，不代表事实陈述，亦无意贬损。
- **他的战绩均为其本人自述、未经独立审计**，引用时务必带此限定。
- 投资有风险，决策风险与后果由使用者自行承担。

---

## 它怎么分析 · 你会得到什么

**核心思路（3 句话）**
不上来就问"这票能不能买"，而是**顺着钱流找卡点**：从下游 AI capex 出发，沿供应链一跳跳往上游推，找到那个**市值最小、却卡住最大瓶颈、市场还没定价**的环节，赶在机构和媒体反应过来之前看懂它。一句话——*不是买铲子，是卡住卖铲人*。

**你会得到什么**（一份围着标的的投研报告，不是"解读某博主"）
- **先科普打底**——把这条链 / 这门生意用大白话讲清，只听过名词也能跟上；
- **判断显形**——逐个名字点明命中哪几条好卡点判据 / 踩哪条红旗，不只甩结论；
- **客观估值**——bear / base / bull 三档区间 + 买卖定档（🔥Fire Sale ～ Sell 五档），每档绑死假设；
- **取数有纪律**——数字按 一手源 / 管理层声称 / 推断 / 推测 分级标注，关键市值实时重核；
- **防自欺**——风险先写、强制给"什么会证伪"，再派独立 reviewer 复核（无子 agent 的环境降级为显式标注的自查）；
- **Serenity 本人只按需出现**——你要他的判断 / 要据他战绩下注时才提他，其余时候方法已内化在分析里。

**样例**（单股 · 缩略 · 数据为示意时点，仅示形态）

```text
$SIVE（CPO 激光层小盘）
① 结论：CPO 必需的 CW 激光卡点；客观空间不过翻倍门槛（已 re-rate）；定档 Hold
   —— 卡点是真的，但当前价已把 2027 放量都 price 满了。
② 事实：市值 ~$2.8B vs 年营收 ~$32M → 市销率 ~85×（意味着：估值全押未放量的未来，当期必然难看）。
③ 是不是好卡点：命中"单点失效光源""多客户 design-win"；踩"已 re-rate""Q1 营收 −22%、在烧钱""内部人近高位清仓"。
   该值多少：紧缺卡点型 → 份额跨层法；其 $799M 是"机会管线"不是签约订单，禁入 bull；
   含推断假设 → 只给方向：bear 下行空间明显 > 再翻倍的上行。
④ 什么会证伪：scale-up 放量继续后推 / 机会管线不转订单 → 高市销率回归。
独立复核：[降级 · 未独立复核] 当前环境无子 agent，已重核 5 项关键数据。
```

> 完整报告比这长，且每个数字带一手来源与 as-of；这里只示意结构与"判断显形 + 取数纪律"的样子。

---

## 安装 / Install

这是一个**可移植的 Agent Skill**（开放的 `SKILL.md` 格式）——核心就是 `SKILL.md` + `methodology.md` 两个指令文件。**任何支持 Agent Skills、或能把指令作为上下文加载的 agent runtime 都能用**，安装与触发方式按各自约定。

安装 = 把这两个文件放进你的 runtime 加载 skill 的目录，例如克隆本仓库：

```bash
git clone https://github.com/ZadAnthony/serenity-skill.git <你的 runtime 的 skills 目录>/serenity
# 路径按各 runtime 约定（有的放 ~/.claude/skills/、有的放项目内 skills 目录，按你工具的文档来）
```

放好后按你 runtime 的方式调用：支持 Skills 自动发现的，输入 `/serenity` 或聊到相关板块即触发；其它情况把这两个文件作为系统指令 / 上下文加载即可。

更新：进入克隆目录 `git pull`。

## 用法 / Usage

```
/serenity 分析一下 $CRDO 这只票值不值得
/serenity 帮我看 1.6T 光模块这条链现在还有没有没被定价的卡点
```

也可直接聊到 AI 供应链 / 半导体 / 光通信等投资话题，Skill 会自动介入。具体产出形态见上方「它怎么分析 · 你会得到什么」。

## 文件结构

| 文件 | 作用 |
|---|---|
| `SKILL.md` | Skill 入口：核心立场、输出契约、分析流水线、各步判据 |
| `methodology.md` | 完整知识底座（9 节，由 2071 条公开推文自底向上提炼 + 反向校验加固） |

Skill 自包含，只依赖这两个文件、不捆绑任何数据集。两点 host 能力会影响完整度（都不限某个特定 runtime）：① 要产出准确报告需 host 具备**联网 / 检索**能力（按取数纪律拉实时财务 / 市值）；② "最后一步独立复核"在支持**子 agent** 的 runtime 上跑独立 reviewer，不支持时按内置降级路径自查并显式标注。

## License

方法论提炼内容供个人学习 / 研究使用。底层投资观点版权归原作者所有；本仓库为第三方整理，请勿用于商业用途或冒充原作者。
