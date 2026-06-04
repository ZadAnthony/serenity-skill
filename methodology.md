# Serenity 投资方法论知识库（统一版）

> 来源：@aleabitoreddit 全语料（2071 条推文，2025-07→2026-06）按 6 维度自底向上提炼后收敛。
> 用途：供 `/serenity` 分析 skill 调用——帮人**照着分析股票**：怎么分析、往哪一层挖、如何判断值不值得投。
> **统一免责**：本人所有战绩/回报/市值/客户映射均**[自述未验证]**，无第三方审计；他自己也承认踩错短线（$TOWA / $VPG ASP / $POET 单一客户）。任何标的「结果」只作方法论先验，不作业绩或事实依据。

**章节索引**（SKILL.md 引用对照）：
§1 核心哲学 · **§2 选股框架（操作引擎，最详）** · §3 估值 · §4 催化剂 · §5 决策/仓位/离场 · §6 风控&宏观 · **§7 AI 板块地图 + 卡点案例库** · §8 已知偏差与局限 · **§9 分析任意标的的 SOP**。
（注：旧 SKILL.md 提到「§6 板块地图 / §9 偏差」，本版已重排为 §7 板块地图 / §8 偏差 / §9 SOP；语气话术并入 §8 末尾「招牌术语」。）

---

## 0. 人物速写

自定位 **trader 而非 deep investor**：「有深度投资者，也有像我这样的 trader——investor 错过的恰恰是『什么让一只股票涨』」(id=2037050804591583421)。自述异常财务记忆（归因为某种 disorder，"can't recall things in real life"，却能记任何财务事实 id=2007752385599270959），这是多跳供应链映射的底层能力；自建"Citadel-like 数据管线"(id=2010049741460218026)，盯衍生品/现货先行信号。价值观：正和游戏 + 免费分享，反 paywall（"收 $200/$2000 的人是因为 idea 不够好，否则会自己重仓退休" id=2050302664031039691），"put my money where my mouth is"——甚至直接收购 $SIVE 股份(id=2037503648520179834)。这条「免费/利他」叙事同时也消解了他 **talking his book** 的事实（见 §8）。

---

## 1. 核心哲学 & Alpha 来源

### 1.1 根信念：alpha = 信息合成/发现的时间差（最高中心性）
> "The alpha is knowing what types of contracts lead to isolation from current fears and where there's mispricing on individual components" (id=1998933069307470323)
> "I identify the biggest chokepoints in hyperscaler supply chains before anyone else. Then go long" (id=2036089423990042630)

alpha **不来自"选好公司"**，来自做别人没做的**多跳供应链综合**：在 AI capex 大叙事里向上游逐跳映射，找到一个**被错误定价的卡点**，抢在算法/被动资金/卖方/媒体反应过来前逆向建仓，等"信息被发现"重定价。"I democratize information discovery/synthesis for regular retail investors"(id=2047485717341987232)。

### 1.2 市场观：长期有效、短期严重无效
- 短期无效（多跳供应链 + 衍生品定价）："If you ask an AI: Is AXT part of Google TPU supply chains — It will say no due to obscured multi-hop"(id=2026755002514157818)；"$VLN was the perfect example of markets not being efficient"（算法照错数据做空 id=2009672143999787356）。
- 长期有效（错的只是时间差）："Markets are the final arbiter... [bad theses] age like milk"(id=2026500828606116348)。
- **自洽**：alpha 活在"短期无效→长期裁决"之间的缝隙。

### 1.3 卡点定价是非线性博弈，不是 P/E
> "Stop trying to model bottlenecks with P/S or P/E"(id=2036638807496499687)；"it's not linear. It's a game theory supply bottleneck"(id=2009198276235448369)

标志案例 $AXTI："company this small ($700M) that controlled a critical bottleneck for a multi-trillion dollar industry"(id=2005654662616387783)。

### 1.4 两道自我证伪闸（避免把"卡点"当万能）
1. **Chokepoints can be designed out**（卡点可能被架构设计掉）
2. **可能 material 不足**（卡不住到能转成收入）——复盘 $HIMX 时点破(id=2037698708612210693)
> "Not the best idea to FOMO the new bottleneck every news cycle"(id=2047426124586893566)——他自己也警告别每个新闻周期追新瓶颈。

### 1.5 对手盘（在演变）
早期对抗**零售情绪**（"/r/wallstreetbets is a great bottom signal for $NBIS" id=1980801533198627336）；中后期机构化——对抗**算法/被动资金/做市商/媒体**："profiting off Jane Street algos weekly"(id=2026341976942195152)；自封 Level 5 "making market makers cry"(id=2024705125298929819)；媒体误读当机会（$CRDO "purple cable"，"markets trade off Kindergarten logic" id=2010255341196628117）。**演变方向：对手越来越技术化，他们看不到多跳关系——这既是流动性也是 alpha 来源。**

### 1.6 对 AI / 宏观大叙事的分层判断（非无脑多头）
- **(a) AI capex 结构性非泡沫**："Capex is ramping exponentially"；区分自有现金 vs 债务 capex（"Google using their OWN $180B operating cash flow is positive" id=2019216672004141282）；take-or-pay 合同 = de-risked。
- **(b) 精确指认泡沫位置 = OpenAI 及其纯依赖方**（反两个极端）："The main fear in 'AI Bubble' is OpenAI and their $1T capex promises. That is a clear bubble... Most other things, no"(id=1993332726020423755)；"OpenAI is the tech equivalent of Iran"(id=2039359732457357453)。
- **(c) AI = 国安 + 阶层固化史观**（后期底色）："AI is the largest national security issue in history"（近似原话 id=1978247373089358249，措辞略异）；"escape the permanent underclass... by owning compute and infrastructure"(id=2048479754672844939)；"every supply chain is being weaponized... US enemies own most chokepoints"(id=2035739495031792031)。
- **(d) 宏观是放大器非主线**："this is now a stock picker's market"(id=2036016177940680819)，但承认"macro > individual fundamentals 短期"(id=2038635697603826096)。

### 1.7 演变时间线（载体迁移 / 对手盘迁移）
| 时期 | alpha 主形态 |
|---|---|
| 2025-07~09 | 泛 catalyst + 短挤（$HIMS 42%SI）+ 价值修复（$UPWK 7.5PE）+ 逆向情绪 |
| 2025-09~11 | 过渡：单一高信念逆向 + Mag7→Neocloud 资金漏斗（$NBIS sum-of-parts）|
| 2025-12~2026-01 | **框架结晶：bottleneck/chokepoint = 唯一 alpha 母题**（$AXTI/InP 转折）|
| 2026-02~04 | 方法工业化 + 衍生品错定价套利（$EWY IV）；自我神化达峰 |
| 2026-04~06 | 同框架转向国际小盘 + CPO 单一超级周期（$SIVE 取代 $AXTI 头号）|

**不变的根信念**：信息合成时间差、向上游找卡点、frontrun、逆向恐慌、正和免费、AI capex 结构多头。
**变的**：载体（短挤 → neocloud → InP → CPO）、对手盘（零售 → 算法/做市商/媒体）、地域（美国大盘 → 台/日/韩/欧小盘）。

---

## 2. 选股框架（操作引擎 —— 最详，核心）

> 一句话（他自己的话）："从 capex 顺着钱往下游/上游推，找到供应链里那个**最小市值、控制最大份额、设计已锁定但营收还没体现**的卡点，在市场发现之前重仓。" 自命名 **supply chain investing**(id=2005972815493885957)。
> 能力门槛自述："如果你不能把整个光通信产业链脱口而出，从上游 InP 衬底一路到光模块成品制造商……说明你读我写的还不够多"(id=2059073941734662551)。

### 2.1 发现路径（5 步）

**步骤 0 — 先锁主题/超级周期，不追每日新闻卡点。**
卡点轮转链："GPUs→Memory→Power→EMLs→Memory→GPUs→transceivers→Packaging→Transformers→CPUs"(id=2047426124586893566)。锁定结构性 supercycle（CPO = "my #1 thematic long" id=2054412992000012555）；判早晚看主题处周期哪段——"middle for memory, start for photonics"(id=2026125089255866749)。**别 FOMO 单日新瓶颈。**

**步骤 1 — 从下游需求/capex 起步（follow the money flow，核心起手式）。**
起点 = 确凿下游数字（hyperscaler capex 具体额、CEO 财报点名瓶颈）。
> "$GOOGL capex→Follow the money flow down to: $AVGO/$TSM (design/foundry) — SK hynix/Samsung/$MU/$SNDK (memory) — $ANET/$LITE/$COHR/$VRT"(id=2019181182026686661)
> "entered $ALAB/$NBIS/$TSM/$LITE because of Mag7 funneling revenue"(id=1999240464420250042)

**步骤 2 — 多跳往上游推（multi-hop mapping，技术核心）。**
- **(a) 沿已知供货关系逐跳推到最上游**。招牌链：$LITE 是 $GOOGL 已知供应商 → $IQE 是 $LITE 已知供应商 → $AXTI 是 $IQE 已知供应商。"BOM 机密但能从 relationship mapping 猜"(id=2026663975145164937)。**BOM 机密 → 用已知供货关系反推，不需官方确认。**
- **(b) speculative mapping / OSINT 推断未公开供货关系**——见 §2.2 线索清单。
- **(c) 找"到处冒头"的公司**："$COHR shows up everywhere on future bottlenecks... I like to invest in ones that pop up multiple places"(id=2015167262727299369)；$AEHR = "toll booth for hbm4, SiC, photonics"。**在多条链里反复出现 = 加分。**

**步骤 3 — 定位"卡点中的卡点"（往最底层材料/单点钻）。**
$AXTI 双层卡点教科书："two bottlenecks. InP Feedstock-Duopoly (China 78-80%) + InP Substrates-Monopoly"(id=2009446195933139114；他说 78-80%，权威源约 70%)。主题："copper→photonics 制造 structural single point of failure"(id=2004622136837898647)。**substrate → feedstock → 原料现货，一路往下钻。**

**步骤 4 — 用实时衍生信号验证卡点正在发生（不等财报）。**
> "If you wait for actual earnings you're late. Signals are from derivatives like 7n indium prices on SMM for $AXTI, alpha in news, or correlated earnings from other companies"(id=2026595168179404907)

用过：原料现货价突破（7N Indium ATH）、同链相邻公司财报交叉（IntelliEPI CEO 确认 InP 短缺、$LITE 电话会承认外购 CW laser）、贸易/出口管制（中国对日 InP 管制 → $AXTI 独家）。根因优先于价格（$AXTI 财报 AH -29% 不动摇，"immaterial to the bottleneck"）。

### 2.2 OSINT 线索清单（推断未公开供货关系，可复用）
| 线索 | 例子 | id |
|---|---|---|
| 官网供应商列表增删 | "$LITE/$MTSI silently removed from Ayar's website" → 推 $SIVE 顶替 | 2046696582696083634 |
| CFO/CEO 访谈失言 | "$POET CFO confirming direct supplier to $MRVL... upstream laser hint: $SIVE" | 2046879187076817237 |
| 生态/会议 PPT 配图 | "$SIVE 1 of 2 public laser suppliers in $GFS ecosystem image" | 2051432439432740931 |
| RFQ/采购协议/认股权证 | $AMZN purchase agreement/warrants(id=2047209727738957983)；Apple "Fortune 100, RFQ for 50 MILLION units"(id=2048680795586568237) | 2048680795586568237 |
| 投资 deck + 融资历史 | "from old investor deck + fundraising: Celestial direct customers of $SIVE" | 2049761085872570864 |
| 被收购方客户继承 | ALLSPACE 被 $YSS 收购 → $SIVE 接入 Golden Dome/DoD | — |
| 众包/粉丝 DM 线索 | 粉丝提供产业内部线索 | — |
| 汇总映射网 | $SIVE→$JBL 1.6T/Lightmatter/Ayar/$MRVL Celestial/$POET/$GFS/$AMD CPO/$AAPL SiPh/$YSS | 2051566667009073315 |

### 2.3 "卡点中的卡点"判别逻辑
推到上游后**继续往最底层钻**：成品 → 模组 → 器件/激光 → 外延片 → 衬底 → feedstock/原料现货。越往下越可能是"single point of failure"。叠加**地缘单卡**（中国控约 70% 铟，他常称 78-80%）= 材料 + 地缘双卡，最强。
> **同一成品可能是多原料双卡点，往 molecular/前驱体级钻时要逐一原料拆**：InP 衬底既要铟（中国控约 70%，地缘单卡）又要高纯磷前驱体（Nippon Chemical/NCI 4092 [垄断系其 OSINT 推断·无第三方份额证据]，"$169m 收购 NCI 就能掐死西方算力扩张" id=2043906518026989817）——两条独立垄断链各自是 single point of failure。"Thought $AXTI was a bottleneck? NCI is the bottleneck of the bottleneck." 别只盯一种原料。

### 2.4 好卡点判据（值不值得重仓全清单，1-6 为核心）
| # | 判据 | 例子 | id |
|---|---|---|---|
| 1 | **垄断/双寡头/极高份额（量价双控最佳）** | $AXTI "controls both quantity & price"(id=2009436652184457529)；"40%+ of InP supply chain" | 2049985874193195425 |
| 2 | **极小市值 vs 巨大下游 TAM（核心不对称）** | "$700M company controlling a multi-trillion industry"($AXTI) | 2005654662616387783 |
| 3 | **BOM 占比相对市值巨大 + designed-in** | $LITE "8-12% BOM of every Google TPU v7"[推断·BOM 机密无公开源]，$26B MC（已过时） | 2003024646367740327 |
| 4 | **designed-in + 多客户（避单一依赖）** | $SIVE 进 $AAPL/$JBL/$MRVL/Ayar/Lightmatter 多线 | 2051566667009073315 |
| 5 | **认证/资格周期长、未反映当期营收** | $AEHR/$LPK "earnings call volume ramp indicators are what matter"(id=2049876593674440706) | 2049737227677421908 |
| 6 | **未来（2027-28）爆发营收，当期财务无所谓** | "all 2027 hyperbolic forward growth: Nobody should care about current financials"($AAOI) | 2052485912714752144 |
| 7 | 资产负债表能撑过爬坡 | $OSS "$40m cash, 45% 毛利"；$POET 跌46%仍有 $420m cash | 2008932076264046635 |
| 8 | demand far outstrips supply（产出全被买光）| $SIVE "We do not look at competitors when demand far outstrips supply" + "60% gross margins future" | 2060273330804969764 |
| 9 | 大客户把上游产能全包 → 制造卡点 | $NVDA "ate up all capacity with $COHR/$LITE after $2B spree" | 2050833230736269767 |
| 10 | 国家安全/CHIPS Act/政府介入（护城河+催化）| $SIVE "US gov doesn't give funding to random $1B Swedish companies" | 2049386026460942645 |
| 11 | Made in America / 本土化 = 护城河 | "'Made in America' is the greatest moat $MU and $INTC have"(id=2016126247869546583)；$AAOI "Optical $INTC" | 2052799637669769363 |
| 12 | 信息不对称/定价错误（pure alpha）| $VLN ticker collision 错算；涨势中机构还劝别买 | 2010016015330291787 |
| 13 | 极少数玩家（世界没几家能做）| laser 历史 $LITE $3B→$15B→$80B；$AAOI $770M→$15B | 2054470106244350122 |
| 14 | 多年营收可见性 / 大额 backlog 已 de-risk | $FLNC "$5.6B backlog derisks growth" + 2 hyperscaler 合同 | 2052435712126161008 |

> **判据 1-14 是把"卡点"过滤成"好投资"的筛子。** "there's a difference between 'bottleneck' and good investment"——$WOLF 是卡点但负债噩梦，不买(id=2015153348287381771)。

### 2.5 红旗排除（坚决不碰 / 命中即降级或否决）
| 红旗 | 例子 | id | 强度 |
|---|---|---|---|
| **无限 ATM / 增发稀释机器** | $IREN "endless dilution machine... 6B ATM"；$SLNH/$BKKT | 2053928672202268993 | **硬否决** |
| **单一客户集中风险** | $POET 被 $MRVL 砍单 -46% | 2048785899610427809 | 高 |
| 资产负债表 toxic（撑不过爬坡）| $WOLF "toxic at $15"(id=2059275827024728219)；$CRWV "$14B debt nightmare" | 1992360259634303347 | 高 |
| 零收入纯炒作/债务驱动靠 backlog | $CRWV "casino"；$ORCL 靠没钱的 OpenAI 建产能 | 2016361080117961170 | 高 |
| **中国敞口（原则性排除，即使公司好）** | "stay away from Chinese companies like $XPEV out of principle"（承认 $XPEV/$BYD 是好公司）| 2002985501293428827 | 原则性 |
| 技术太远/科学项目（2028+ 不碰）| MicroLED "volume H2 2028 / H1 2029 if it even takes off" | 2054858304107745356 | 中 |
| 纯软件/SaaS（被 AI 颠覆且无硬卡点）| 嘲讽 software bros；唯一例外 $RDDT（错杀，70%增长/91%毛利 id=2021359576575246505，未被 AI 颠覆）| 2052760996784349455 | 中 |
| 价值/红利陷阱 | $PYPL/$FISV/$NVO "dividend/value investors went extinct" | 2052974730429501586 | 中 |
| 大市值已无不对称 | "10x chance increases the smaller marketcap (Sub $2B)" | 2002402259683192895 | 降级 |
| brand/risk-free convertible 假合作 | $IREN-$NVDA "just brand agreement giving NVDA risk-free convertible notes" | 2052494142765441301 | 高 |

> **稀释的好坏看条款**（关键反例）："已 priced in"或"换来 forward rev"的稀释是利好——$NBIS MSFT 合约稀释 "ALREADY PRICED IN"；$SIVE 2.5% 稀释 "extremely positive"（助力 Nasdaq 上市）。**战略投资/可转债 = 绿旗；无条件 ATM = 红旗。**

### 2.6 卡点排序（多候选时优先级）
核心 = **不对称性最大者优先**（最小市值 × 最上游/最难替代 × 离放量越近）。
- 光子学示例排序："$AXTI my favorite for strategic value... $LITE runner up... $COHR #3, $AAOI #4"(id=2026169893289345285)——越上游/越卡点/市值越小 = 越前。
- **动态轮动**：已 10x 的踢出，换尚未被发现的小市值——"$AXTI already 10x'd, different lineup now: $SIVE $2B, FOCI $2.8B, Shunsin $2B best risk/reward"(id=2060536520952754374)。

**排序权衡 6 维度**：
1. 市值/下游 TAM 不对称比（越极端越前）
2. 离 volume ramp 时间（2027 内 > 2028+ 科学项目）
3. 上游程度/可替代性（feedstock/substrate > 模块成品）
4. **是否已被机构发现**（未发现 alpha > 已 re-rate；机构发帖后 4-6 周才进）
5. 多年可见性 vs 纯动量
6. 回报潜力 vs 已知度

---

## 3. 估值方法（三套尺子 + 硬阈值）

### 3.1 核心哲学：用 Forward 不用 Current，错配 = 机会（最高频·主轴）
> "Who cares about revenue growth when they can scale operating margins?"($UPWK id=1947215927462027284)
> "Nobody should care about current financials"（源仅 $AAOI id=2052485912714752144；泛指所有 2027 超成长公司，$AEHR/$LPK 属类比外推）

**演变**：2025 下半年用于软件/超成长，2026 平移到半导体瓶颈股（forward P/E + capacity=revenue），底层逻辑不变只换行业。

### 3.2 三套尺子（先判类型，再套尺子）
| 类型 | 尺子 | 关键判据 / 例子 |
|---|---|---|
| **一 超成长/NeoCloud** | forward revenue/ARR vs 市值 + 倍数推演 | $NBIS "$24B MC doing $8B forward ARR"；分析师模型反推"$7-9B ARR → ~$355/share" |
| **二 紧缺卡点/瓶颈股** | **拒绝传统 P/S P/E**，用垄断地位 × 供需缺口 | (a) 同层同行**可比倍数差**："$SIVE: $MTSI $17B, $LITE $52B → 应 $2-3B"(id=2036108082531664159)；(b) **历史卡点价格曲线**（Dysprosium ~2300%；"$LITE $3B→$15B→$80B 两年" id=2054470106244350122）；(c) **capacity ≈ revenue**（产能全被 hyperscaler 包圆）|
| **三 深度价值** | 传统数字：P/E · EV/FCF · 净现金占比 · book | $UPWK "7.5 P/E, 78% 毛利, $622M 现金"；$ETOR "~3.9x EV/FCF vs 别人 10-15x"；$VLN "资产≈市值"；Yamamura "付 $240M 买 $500M 销售 + $360M book = 免费买公司" |

> **[取数硬约束 · Phase B 实测]** 做"同层同行倍数差"对比时，两端 fwd P/E / 价格 / EPS 必须**同 as-of 日 + 同数据源**，否则结论作废；近一年涨幅 >300% 的标的尤其现取现比。§2.3 给的是静态市值对比（$MTSI $17B/$LITE $52B→$SIVE $2-3B），但倍数对比极易拿旧倍数比新价造出伪溢价（WDC 案例：用 Seagate 两个月前旧倍数对当前价，凭空造出"贵 65%"）。

> **解消"鄙视 P/E vs 用 forward P/E"的冲突——他是双轨，从未明说**：超增长卡点用 TAM/game-theory/产能（类型一二）；成熟记忆/软件/价值股才用 forward P/E（类型三 + memory 股）。**判断标的属于哪一类，再决定用哪套尺子。**

### 3.3 数字化硬阈值
- **单位数 forward P/E = 极便宜**（memory）：$MU "~8.2-8.5 fwd P/E @ 77% 毛利"；SK Hynix "~4.3x"；Samsung "~5.1x"。
- **反向锚 $WMT 40 P/E = 贵到荒谬的标尺**："$MU 11.6 fwd P/E +133% Y/Y vs $WMT 40 P/E +4.9%"(id=2014285507270963425)。
- **机构持股 < 40% = 还会涨**（把机构吸筹空间当上行依据）：$NBIS "38% 不正常，好公司通常 60-80%"(id=1980786077003833508)。
  - **[按市值分档护栏 · Phase B 实测]** 此阈值原语境是 **sub-$2B 小盘**的机构吸筹空间；市值 >$5-10B 或已是 Strong Buy 共识时该信号**失效甚至反向**（大盘机构持股低更可能是质量存疑，非上行）。别机械套到大盘（MOD $15B 差点机械误用：实测 32.8% 反被读成"上行"，与"已耗尽"判断自相矛盾）。
- **净现金 ≈ 市值 = 下行保护**；**capacity = revenue**（瓶颈股核心假设）：$AAOI "1.97B capacity EOY2027 基本=revenue"。
- **鄙视纯 TA**："TA and Charting alone is pure astrology and snake oil"(id=2029675551980679177)。（注：他自己仍用支撑位/setup，见 §8 矛盾。）

### 3.4 估值流程（可还原）
1. 选 sector/瓶颈 → 沿供应链向上游 map
2. 判类型（超成长 / 卡点 / 深价值）→ 套对应尺子
3. 算 forward 收入/ARR/capacity
4. 找同层同行倍数差 或 历史卡点价格曲线
5. 查下行保护（净现金/book/有无稀释 ATM overhang）
6. 机构持股低 + 信息未定价 = 上行空间

### 3.5 预期空间(自算,decision-neutral,skill 显式输出)
把上面的估值做成一个**与"买/不买判定"分开的客观回报区间**,交给用户决策(他的 Hold ≠ 用户不能买):
- 按类型选尺子(卡点/超成长 → forward 营收·产能 ÷ 市值 + **对标龙头同层倍数**;成熟/价值 → P/E·EV/FCF)——**自算,不抄分析师目标价**。
- 给 **bear / base / bull 三档**,每档绑死假设(对标谁、几倍、哪年营收/产能 → 隐含市值与回报%);输入标 `已证实/声称/推断/推测`;倍数两端同源同日。
- 分析师共识 PT 仅作 positioning 旁证(判是否已被定价),不当上行真值。
- 无可信对标/太不确定 → 标"区间太宽,不给假精确"。整块走独立复核,防对标挑肥拣瘦/凑回报。

---

## 4. 催化剂识别（先行/衍生信号，不等财报）

### 4.1 [铁律·最高中心性] 不等正式财报，用先行/衍生指标抢跑
> "If you wait for actual earnings you're a little late. All the signals are from derivatives like 7n indium prices on SMM for $AXTI, alpha in news, or correlated earnings from other companies"(id=2026595168179404907)
> "Nvidia earnings is a partially lagging indicator... #1 thing is hyperscaler capex projections and $TSM"(id=2027052811318693995)

### 4.2 他实际盯的先行/衍生指标（按频率）
1. **上游原料现货价（最独特招牌）**：7N 高纯铟 on SMM（中国现货）= $AXTI 实时领先信号(id=2017278999727378786)；Germanium→$LPTH；Tungsten +557%→$ALM。
2. **相关公司财报/电话会逐字稿 cross-read**（不等本票财报）：$ORCL 14% HPC 毛利 → 反推 NBIS 71% 是护城河；$LITE CEO "keeps me up at night: Substrates" → 验证 $AXTI；Samsung "NAND 涨价 100%" → memory 全链。
3. **行业会议/大厂资本动作当定时催化**：围绕 NVDA GTC + OFC 择时建 $SIVE；"$NVDA invested $2B each into $LITE+$COHR（合计 $4B，该笔不含 $MRVL）... same playbook" → 上游卡点必涨；大厂收购/入股（$MTSI 投 $IQE）。
4. **政策/法案/出口管制**：SPEED Act "better than 3x rate cut"；中国对日 InP 出口管制（Jan6）→ $AXTI 变垄断（全程最大催化）；CHIPS / EU CHIPS Act 2。
5. **指数纳入/被动流**：NBIS MSCI inflow；$SIVE MSCI Small Cap 纳入（5/29 rebalance）；$HOOD 进 S&P500。
6. **宏观/事件驱动**：降息、政府关门（Polymarket 已定价 → 恐慌建仓）、地缘（"How do I profit off this" 模板）。
7. **终端囤货/库存堆积信号**：小市值 niche 元件被大客户（$NVDA/$MSFT）突然扫货囤库存 = 营收上修先行指标，分析师建模通常滞后（$SNDK SSD 囤货"likely triples revenue estimates" id=2022923880575455472；$RPI 14%→48-55% 后券商上修到 $511M id=2038913900582998087）。特别适合 sub-$1B niche 的非对称 re-rating（2000%+ vs 大盘 DC 的 2-3x）。

### 4.3 短期催化交易节奏
- 恐慌/无消息下跌 DCA："No news dips are a nice gift"。
- **区分重大消息 vs 噪音判可买**：$HIMS "strongly worded letter = immaterial" 可买 vs $RKLB "$750M 公开市场卖" 恢复慢；$CRDO "Amazon 只改电缆颜色 = 误读，买 25% 跌幅"。
- 抢跑自述："frontran institutions... 4-6 周后机构才进场"(id=2052662451418861957)。
- 量产拐点（qualification → volume ramp）当催化：$AEHR/$LPK/$AAOI。

### 4.4 催化分层 & 信号解读规则
- 评级帖用 emoji：catalyst 🐈 / swing 🛝 / 长期 conviction。
- 短挤信号：SI% > 40% + 盈利 + 增长（非 0 收入）——$HIMS/$GME/$OPEN 模板。
- **NVDA 财报 = 滞后指标**（数字 lagging），但 **NVDA 投资动作 = 强领先催化**（资本动作 leading）。
- **Insider selling = 噪音不当催化；ATM/大额稀释 = 真实结构利空**。
- 催化分两层：**"会不会发生" vs "何时发生"**——他承认 timing 会错（$NBIS/$TOWA），但"方向对 + 给够时间会兑现"。

---

## 5. 决策 / 仓位 / 信念分档 / 离场（thesis 状态机）

> **总纲（load-bearing）**：「卖点 = thesis 状态机的状态翻转，而非价格触发器。」
> "If something bad changes to the fundamentals, I'm not afraid to sell. But so far I've only seen positive changes"(id=1997341675753189423)

### 5.1 建仓：极端恐惧/错杀当天接刀 + DCA 分批
- 错杀当天买："Fire sale today... Bought $SG $13.8 on the 6% drop"(id=1942222651151548657)；"bought $100k $SG on the drop to $8.22. No news, down 8.2%"(id=1965084810982064626)。
- **判断跌因是否 material 是接刀前提**："diff vs $HIMS drop is one was a strongly worded letter with no material affect. The other is selling $750M on open market"(id=1968012441838817569)。
- DCA 分层：首仓 ~30%，价格分层往下加（"buy 30% of position after the 18.75% drop, then cost average down"）。
- 越跌越买当信念试金石："$NBIS 30%+ drop $140→$97... if you understand the fundamentals, this is a gift"(id=1981009544546591207)。

### 5.2 信念分档（从"评级清单"到"chokepoint 一票否决"）
- **早期显式评级帖**（周末收盘模板）：Extremely Strong Buy / Buy / Hold / Sell(id=1972769926302855553)，叠加符号 🛝swing / 🐈catalyst / 🔥Fire Sale（最高强度买入 = 极端错杀）。
- **"high conviction" 是稀缺标签**："I rarely have high-conviction stocks. But NBIS is one"(id=1970880728994107816)。
- **后期锚点切到 chokepoint**："$AXTI is effectively a monopoly for InP, single point of failure"(id=2009176232416669998)；多链交叉 = 加分。
- **永久黑名单 = 反复稀释股**：$BKKT/$IREN/$CRWV（"F tier... balance sheet nightmare"）。

### 5.3 PT + 时间框架（早期精确，后期模糊）
- 早期：精确 PT + 月数，随催化剂滚动上调（"$NBIS $225 PT, 1 year" → $400 → $450）。
- 后期：用"该值多少市值/对标谁"代替精确 PT（"$SIVE $320m MC... $MTSI $17B, $LITE $52B → should trade $2-3B" id=2036108082531664159）。
- 短挤明确无 PT："no price target for short squeezes. Sell on sudden volume increase and spike"。
> **注意**：PT 精度退化 = 可证伪性下降；且 **PT 只升不降**（见 §8）。

### 5.4 离场（本框架最关键也最薄弱）
- **thesis 仓基本面不变就不卖**："even if $NBIS were $160 I wouldn't sell it"；"I haven't sold a single share"($SIVE)。
- **唯一卖出条件 = 论点破裂**（基本面/单一客户/稀释变坏）："$TSLA design out risk made me cut concentration [$VPG]"；$POET 被砍单 -46% 减仓。
- 反对为落袋而卖，**trim 触发税 > 多数回调**(id=2055200705334395161)。
- **swing/catalyst 仓有明确卖点且会卖**："I have exit strategies for swing trading. For investing I hold for years"；挤压必兑现（"$OPEN squeezed but people didn't sell, that's why they lost 40%"）。
- 真实卖错反思："sold $HIMS early"；"biggest sin was not taking STCG on $SMCI"。

### 5.5 仓位管理（集中、分层、显式权重表）
- 高度集中单一最高信念："$750K+ in $NBIS, scaling to $1M+"；"50% of portfolio into Bitcoin around $73K"。
- 显式 % 权重表（按 supercycle 分桶）：2026-02 "35% Memory Supercycle (10% Samsung/10% SK Hynix/10% $MU/5% $SNDK) / 25% Digital Asset / 15% Fintech"(id=2020258804953411966)。
- 分散 = 防看走眼：核心集中 1-2 标的（30-50%），卫星分散；留非对称对冲位（$VIRT/$VIX）。
- 小仓试水高赔率小盘："$OSS is wait and see for a 1000%+"。
- **仓位匹配波动承受力 = 核心风控原则**："if it's hard to stomach volatility with high beta names like $AXTI, maybe your portfolio weighting is wrong"(id=2024653987224702986)。

> **解消"别 full port vs 极度集中"的冲突——嘴上/行为分裂**：他口头反复警告别人 "wouldn't recommend full porting anything"(id=1972147593741586777)，但行为是清空其他 neocloud 全押 $NBIS $2M+、50% BTC、单标的 30-50%。**这是真实张力（动机 + 行为不一致），引用时必须点破：别照抄他的集中度，照抄他的"仓位匹配波动承受力"原则。**

### 5.6 工具：正股 vs 期权/Leaps/卖权
- 基础几乎只买正股；calls 留给"极度超卖"或"低 IV"（"i don't leverage unless something is extremely oversold"）。
- Leaps 用于高信念错杀（"$300K in call leaps, December ITM 2026"），换月抗波动。
- **卖 put / covered call 做现金流**：被 assign = 折价被动建仓（"take assignment since you'd want to buy those stocks anyway"）；涨太猛停卖 CC。
- 后期新主线：**OTM Leaps 吃 IV/Vega 错配**（"2028 OTM leaps benefit from once-a-generation IV mispricing"，$EWY IV 32%→44.7%）。

### 5.7 持有周期三档
1 年（$NBIS）/ 5 年（$RKLB/$TSM/$HOOD/$BTC）/ few-week swing。真正多年持有极挑剔："I don't long term invest unless it's $RKLB（国安+护城河+#2 to SpaceX）"。

### 5.8 浓缩决策表
| 步骤 | 规则 |
|---|---|
| 定档 | thesis（长持）vs swing/catalyst（有卖点）；thesis 要求 远期/市值极端错配+Mag7（早）或 monopoly chokepoint（后）；diluter 直接拉黑 |
| 入场 | 无新闻/错杀大跌当天接刀，首仓~30%，价格分层 DCA；极度超卖才上 leaps；或卖 put 目标价被动建仓 |
| 加仓 | 基本面没变的每次 10%+ 大跌都加；越跌越买当"信念试金石" |
| PT/周期 | 早期精确 PT+月数滚动上调；后期"该值多少市值/对标谁"；周期 1年/5年/swing 三档 |
| 仓位 | 核心集中 1-2 标的（30-50%），卫星分散防看走眼，按 supercycle 分桶，仓位匹配波动承受力 |
| 离场 | thesis 仓只在论点破裂卖；跌不卖还嫌 trim 税；swing 超买了结、挤压看量价、留小尾仓 |

### 5.9 微盘执行机制（操作层，真买小盘时 load-bearing）
低 float / 小市值标的**不要盘前盘后下市价单**（流动性差 + spread 大，$WLAC 例 bid $13.8 / ask $15.08 = 一进一出先亏 ~9% id=1977846041673363810）；一律**限价单**；OTC 版与海外票（日/韩/欧）spread 更大、IBKR 还按 100% maintenance margin 处理。建仓节奏配合流动性，不要一次性扫单把价格自己推上去（与 §8.6 自我拉抬回路叠加，散户尤其吃亏）。

---

## 6. 风控 & 宏观打法

### 6.1 杠杆/期权用法（风控亮点）
- 几乎只买正股，极少买 calls；极超卖才买 calls/LEAPS（偏 1 年外 ITM）。
- **卖 put / covered call 做现金流**（系统化周期卖 put，被 assign 当折价建仓；CC 当"被动复利"）。
- **LEAPS 吃低 IV**（$IBIT "IV 44-55"；$TSM "IV ~32"）。
- **吃 IV/Vega 错配（最明确招牌）**：$EWY 2028 "found 2028 volatility pricing issues"（IV 32%→44%，Vega 扩张 3 月 +428% [自述未验证]）。
- 避免坏执行：反对 $HOOD 做期权（PFOF 路由 MM），荐 IBKR/Fidelity；反 2x 杠杆 ETF（volatility decay）。

### 6.2 对冲/主题映射
战争 = 油/防务/化肥（$CF/$CVX calls/$AVAV）；AGI = 买 AI 供应链股；**Doomsday（地缘升级情景对冲）= 自建显式权重篮子**：25% $FAZ（3x 空金融，押中东资本撤离私募流动性）/ 25% $GUSH / 20% $LCID 空 / 10% $SQQQ / 10% $UVIX / 10% $NVDA Puts，按地缘情景逐条分配 rationale(id=2037779565066764425)；常态另留非对称波动率对冲位 $VIRT/$VIX（与 Doomsday 篮子是两回事，勿混）；国安主题政府入股传闻时 "violent reversal"。

### 6.3 宏观判断方法（"指标异常先找机制根因"）
- **降息季节性**："三连降息 = 25 年一遇"，用 Polymarket 读概率前置。
- **政府关门**：Polymarket 近 100% 定价 = 已知，散户恐慌时建仓。
- **银价 SLV 溯源（招牌一役）**：拒绝"新 Fed 主席 Warsh"叙事，溯源真因 = CME 1/13 起改按合约价值百分比保证金 + 随价格持续上调维持保证金 → 杠杆被动收缩触发崩盘(id=2017353453790761259、2017387953052610571)。**方法论：指标异常先找机制根因，不信表面叙事。**
- 去杠杆/carry：Softbank $40B 桥贷 → OpenAI 估值 → 再质押循环，类比 FTX。
- 顶部信号：ARKK = "煤矿金丝雀"；WSB 情绪反向。

### 6.4 回撤应对（也是最大偏差源）
一律加仓不减仓（$NBIS $140→$97 一路 DCA LEAPS）；归因几乎全归"散户恐慌 + MM 机械对冲 + 机构吸筹/算法抛售"，极少归自身。**这是结构性确认偏误（见 §8），用户照做前必须意识到。**

### 6.5 离场/见顶信号
短挤无固定 PT（"成交量骤增 + spike 时卖"）；板块顶用 ARKK/WSB 情绪反向；整体偏不卖。**离场纪律是其方法论最薄弱一环。**

### 6.6 事件驱动交易（卡点主轴之外的两条可复用方法，2026-06 补）
- **地缘/政策事件 → 多资产分层拆解**：不要把事件压成"战争=油/防务/化肥"一句话。把单一事件拆成**多条互不相关的资产线**，每条问"大众怎么做 vs 我怎么做"。委内瑞拉事件示范（id=2007387427820978510，全语料最高赞 10887）：①重硫/氨/氮肥扰动（$CF/$CVE，点破"大众只会买泛油 ETF=错，要拆到 pure-play"）②困境债/主权债 2-3x ③BTC 影子储备——同一事件三条独立 alpha 线。
- **"市场定价的是感知，不是现实"**（事件择时，id=2028405556944445919）：以色列交易所在导弹来袭时反涨 8.85%，因市场定价的是"决定性胜利的感知"+长期风险下降，不是眼前恐慌。**盘面与新闻表面相反时，先问"市场在定价哪一层感知"**（与 §6.3"指标异常先找机制根因"同族反向：一个溯源真因，一个读已定价的预期）。

---

## 7. AI 板块地图 + 卡点案例库（产业链先验，可复用）

> 方法论一句话：自底向上画产业链 → 找卡点层（demand far outstrips supply）→ 在卡点上找市值与战略价值严重错配的小盘 pure-play → 抢在机构/媒体定价前进场 → 等架构换代催化。自称 `$AXTI→$SOI→$SIVE` 同一套 chokepoint investment theory(id=2060896847695384736)。
> **载体迁移**：neocloud（2025）→ InP/$AXTI（2025末-2026初）→ CPO/$SIVE（2026Q2 起，#1 thematic long）。映射方法不变，只换主题。

### 7.1 赛道地图（按覆盖度排序）

#### 赛道 1 光通信/光子学/CPO 【★★★★★ 绝对主轴，#1 thematic long】
市值错配总论据："$LITE $3B→$15B→$80B in 2 years; $AAOI $770M→$15B in 1 year"(id=2054470106244350122) + GS 报告 Optical TAM 9x（$15B 2026→$154B 2028，CPO 占 $91B）。
| 层 | 角色 | 核心 ticker | 定性 |
|---|---|---|---|
| L0 原料 | InP feedstock = 铟 + 高纯磷**双原料** | China（铟 ~70%，他常称 78-80%）/$DOWA；高纯磷前驱体 = Nippon Chemical/NCI(4092)[垄断系 OSINT 推断·未独立证实] | 纯卡点（铟+磷两条独立垄断链，各自 single point of failure）|
| L0.5 外延设备 | MBE/MOCVD 反应炉（epiwafer 产能上游 capex 卡点）| Aixtron(AIXA, InP MOCVD ~75%)/$VECO/$ALRIB(Riber, 与 $VECO MBE 双寡头) | "卖铲子给铲子制造商"；按 capex cycle + qualification 估值(id=2027830093247300016、2044695311764099291)；玩法 = qualification 早期买设备商 → volume 时切纯激光(id=2042967133160902679)|
| L1 衬底 | InP substrate | **$AXTI**（曾最重仓）/$SMTOY | 纯卡点双寡头（AXT 含同美 ~36% / Sumitomo ~42%；他常称"控 60-70%"偏高；中国对日管制后趋紧）|
| L1b SOI 衬底 | 硅光衬底 | **$SOI(Soitec)** | "SiPH 版 $AXTI"，近垄断 |
| L1c 外延片 | epiwafer | **$IQE**/IntelliEPI/Landmark | 卡点二线（$MTSI 投 £45m 进董事会锁供给）|
| L2 光源/激光 | CW DFB/EML | **$SIVE**（后期最重仓）/$LITE/$COHR/$AAOI（自有 CW fab）/Win Semi | 纯卡点龙头（$NVDA 买光 $LITE/$COHR 产能 → 激光荒）|
| L3 光引擎/封测 | optical engine/CPO packaging | **$POET**/Shunsin(6451)/MSSCorps(6830) | $POET=单一客户险；Shunsin/MSSCorps=隐藏卡点 |
| L3b 光纤阵列/连接器 | FAU/连接器/热模组 | **FOCI(3363)**/Browave/$HIMX/Nextronics | 隐藏卡点二阶 |
| L4 SiPh 代工 | 硅光代工 | **$TSEM**/Win Semi/$GFS/$TSM/$XFAB | 代工龙头（$TSEM 预付 $290M 锁产能传导回 $SOI）|
| L5 模块/成品 | 1.6T 光模块 | **$AAOI**（美股最爱）/$LITE/$COHR/$MRVL/$AVGO/$CIEN | 龙头/levered（$AAOI="光学版$INTC"）|

**龙虾比喻**：$SIVE/$LITE 做激光 → $POET 装盘 → $MRVL 上桌。

#### 赛道 2 内存/HBM 【★★★★★ 第二主轴，自述组合 35%】
卡点在**制造商本身**（寡头 + 涨价权）。Phison CEO "Toll Collectors" 框架；Samsung NAND 涨价 100%+ → Memory Supercycle。
- 制造商（收费站）：Samsung/SK Hynix/**$MU**/**$SNDK**/Nanya/Macronix
- HBM4/HBF：Samsung/SK Hynix/$MU；HBF = $SNDK/Kioxia
- 控制器（T2 双寡头）：$SIMO/Phison(8299)/$MRVL
- HBM 后道设备：$TOWA(6315 压缩成型，自述短线踩错)/$AEHR
- 市值错配：MS 预测 Samsung/SK Hynix 2027 营业利润超 $AAPL/$GOOGL，fwd P/E 仅 ~4-5x。
- 玩法：$DRAM ETF；**$EWY 韩国 2028 LEAPS**（自述最骄傲的 IV/Vega 套利 [自述未验证]）。

#### 赛道 3 NeoCloud/AI 算力 【★★★★ 早期主轴，后期转骂战】
**鉴别框架**：take-or-pay（$MSFT/$META）vs 依赖 OpenAI 偿付（$ORCL/$CRWV）。
- 主推龙头：**$NBIS**（sum-of-parts：Avride/Toloka/Clickhouse/TripleTen 子公司可超母公司市值；主业 ARR 700%→$7-9B；可转债结构利息不重创盈利）。
- 看空：$CRWV("赌场拿 NVDA 钱还回 NVDA")；$IREN("NVDA 给的是无风险可转债品牌协议，靠 $6B ATM 无限稀释")。

#### 赛道 4 数据中心电力/电网/变压器/液冷 【★★★★ 2026Q1 起高频】
"Power and Grid = 美国最大 AI 瓶颈"(id=2025619207015301349)。
- 电力/IPP：$VST/$CEG/$XLU（**$XLU OTM 2 年 LEAPS 宏观赌注，IV 仅 14%**）
- 输配/液冷：$VRT/$ETN/$AMSC(HTS 线)/$PWR
- 800V 功率半导体：**$NVTS**/$POWI/$XFAB（硅光双暴露 + EU CHIPS Act2，美国唯一高产 SiC foundry）
- 储能：**$FLNC**（$5.6B backlog + 2 hyperscaler 合同去风险）
- 变压器：**$HPS.A(Hammond)**（"Transformers in the sky"，backlog +94.6% Y/Y）

#### 赛道 5 半导体代工/测试/封装/CPU 【★★★★ 高频】
代工/IDM：**$TSM**（脊柱）/**$INTC**（美国 foundry + Made in America + $AAPL 转单）；CPU：$AMD/$ARM/$INTC（$INTC CEO："推理把 CPU:GPU 从 1:8 推到 1:1" → CPU 重新成瓶颈 → 传导到设备 $AMAT/$TSM/$KLAC id=2048449289152778686）；设备：$AEHR("toll booth" HBM4/SiC/光子学测试都过它)/$ONTO/$CAMT；封装：**$AMKR**/$TSM(CoWoS)；SiC：$WOLF（瓶颈但财务 toxic 不买）/$CPSH(AlSiC)。

#### 赛道 6 关键材料/稀土/玻璃基板 【★★★ 中频】
玻璃芯基板：**$LPK(LPKF，TGV 设备近垄断)**/$GLW/SKC（"下一个先进封装浪潮"，按 qualification cycle 估值）；AlSiC 热复合：$CPSH；稀有金属：钨($ALM)/铟/碲/$USAR/$MP（"更安静的交易"，类比 InP game theory squeeze）；HALEU：$LEU（美国唯一浓缩供 SMR）；**光刻胶/电子化学品前驱体**：PGME/PGMEA 溶剂短缺（DuPont/Shiny Chemical/San Fu/Daxin 等台日化学厂 id=2048449289152778686）——与 InP feedstock/高纯磷"卡点中的卡点"同构的化学品卡点子链（2026-06 补）。

#### 赛道 7 机器人/人形 【★★★ 中频，crowdsource】
寻找"人形版早期 $RKLB"。谐波减速器：Harmonic Drive(6324)/Leader Drive；传感器：$VPG($TSLA Optimus，自述 ASP 估错 $150 vs $750，因 design-out 减仓)；4D LiDAR：$AEVA/$OUST；连接器：Nextronics（$AMZN 机器人隐藏供应商）。

#### 赛道 8 太空/国防/无人机 【★★★ 中频】
太空：**$RKLB**（最长期看好"#2 to SpaceX 错配"）/$ASTS/$PL；国防：**$OSS**（无人机蜂群 $155M MC）/$AIRO/$AVAV/$LASR；Golden Dome：$YSS（收购 $SIVE 客户 ALLSPACE）。

#### 赛道 9 稳定币/Fintech 【★★★ 两大篮子之一】
稳定币：**$CRCL**（"USDC = 私营版美联储"，10x thesis）；券商：**$IBKR**（力推国际股）/$ETOR（深价值）/$HOOD（批评）；加密：$IBIT/$BTC(50% 仓位 $73k 抄底)/$MSTR（看空）。

#### 赛道 10 其他二阶/信息发现奇兵 【★★ 低频但方法论代表】
$RPI（"AI agent 的 $NVDA"）；$RDDT（唯一反复推的非 AI 软件：70% 增长 91% 毛利，错杀进"软件被 AI 颠覆"桶）；$MRVL（Maia/Trainium ASIC 设计主受益）。

### 7.2 卡点案例库（8 张方法论活教材）

> 每卡：标的 → 卡点类型 → 推理链 → 催化剂 → 结果 [自述未验证]。

**卡片 1 — $AXTI（InP 衬底）"最传奇 thesis"【中心性最高】**
卡点：L1 衬底，材料+地缘双卡，single point of failure。
推理：①AI buildout 撞铜墙 → 转 photonics（架构换代前提）②所有 hyperscaler ASIC 要 InP 激光 ③往最底层挖 → InP 衬底全球双寡头 Sumitomo ~42% / $AXTI（含同美）~36%（三家>90%；他常称"控 60-70%"偏高）④InP 历史是廉价 telecom 商品 TAM 仅几亿 → 分析师线性建模全错，是 game theory 非线性 ⑤AXTI 自称占 40%+ 整条 InP 供应链（宽口径，未独立证实）。
催化：中国对日出口管制 → 趋近垄断；7N Indium SMM ATH；Northland $100M 融资。
干扰项：2026/01 财报递延旧合同营收 -29% AH → 判 "immaterial，只关心实时衬底瓶颈"。
结果：$12/13 → $105+ → 语料期 ~$5.3B MC（现 ~$7.25B），"10x+" [自述未验证]。

**卡片 2 — $SIVE（CPO CW 激光）后期最重仓，"CPO 版 $LITE"**
卡点：L2 光源，CPO 量产激光 chokepoint。
推理：①GS 报告 Optical TAM 9x ②$NVDA 买光 $LITE/$COHR 产能 → 激光荒（$LITE 自认外购 CW 激光 = 铁证）③OSINT 逐层映射客户：$JBL 1.6T → Ayar（弃 $LITE 改 $SIVE）→ $MRVL Celestial → Lightmatter → $POET → $GFS($AMD CPO)→ $AAPL 硅光（50M units RFQ）→ $YSS Golden Dome ④走 Win Semi 代工跳过 capex ⑤qualification-cycle 不看当期财报看 forward pipeline。
催化：US+EU 双 CHIPS Act；MSCI Small Cap 纳入（5/29）；NASDAQ 上市；财报 forward pipeline +77% + CEO "60% 毛利" + "demand far outstrips supply"。
结果：~$150M/$900M MC 买入 → 600%+ → 语料标 $2.1B MC（快照漂移大：2026-04 ~$1.2-1.3B、2026-06 GFS 合作后 ~$3.0B，现取现比），预测一年内 $30B [自述未验证]。

**卡片 3 — $SOI（Soitec 硅光衬底）"硅光版 $AXTI"**
卡点：L1b 衬底近垄断。推理：与 $AXTI 同构，上游衬底单点垄断，下游 $TSEM 挤压产能传导回 $SOI。催化：$TSEM 预付 $290M；Nomura €250 PT。结果：€43/$44 → $145/$181 "4x" [自述未验证]。

**卡片 4 — $AAOI（光模块 + 自有 CW 激光 fab）"光学版 $INTC"**
卡点：L5 模块龙头 + L2 激光自给（垂直整合 levered play）。推理：①$28 低仓买（猜 $AMZN/$MSFT qualify 其 transceiver）②$70 财报后加仓 ③自有 CW laser fab（2027 产能 +350%）→ $LITE 激光荒时独立供给 ④Made in America "anything they make gets bought" ⑤2027 hyperbolic growth 别看当期财报自算 fwd P/E（$5.7B ARR H1 2027 vs 现 $12B = 不贵）。结果：$30 → $180/$200+ "6-7x" [自述未验证]。

**卡片 5 — $IQE（InP 外延片）被收购方验证**
卡点：L1c 外延片 structural chokepoint。推理：$100M MC 识别为外延瓶颈，Landmark 过剩反衬其稀缺。催化（强验证）：**$MTSI 投 £45m 进董事会锁长期外延供给 = 下游主动锁上游 = 卡点实锤**。结果：$13 → $46 "4x" [自述未验证]。

**卡片 6 — $NBIS vs $IREN（同赛道多空对照，最锋利鉴别）**
$NBIS 多：①主业 ARR 700%→$7-9B ②4 子公司各 100%+ ③$23B MC 时单 Avride/Clickhouse 一两年可超母公司市值 ④可转债结构利息不重创盈利（vs $CRWV $1.3B/年利息）。
$IREN 空：NVDA"合作"只是无风险可转债品牌协议，仍靠 $6B ATM 无限稀释。
结果：$NBIS $87→$200+（3x），知名投资人 5.6% 入股验证（"Tom Lee"系配图推断、文字未点名 [推断]）[自述未验证]。
**鉴别精髓：同赛道用合同结构 + 稀释机制区分真龙头 vs 炒作。**

**卡片 7 — $VLN（Valens）"Ticker Collision" 纯定价错误（方法论变体）**
卡点：非供应链，纯数据错误套利。推理：①研究机器人半导体发现 $VLN（$155M MC）现金 + 营收几乎 1:1 估值异常 ②手工 cross-check 发现根因 = 分析师/算法把纽交所 $VLN 与多伦多 $VLN.TO 搞混，错记 -$82M 现金消耗（ticker collision typo）③算法还按错误模型做空。催化：信息发现本身。结果：$2.28 → 估算合理值 $7+ [自述未验证]。
**方法论变体：纯信息错误也是 alpha，不一定要供应链卡点。**

**卡片 8 — 隐藏卡点群（封测/检测/连接器）**
MSSCorps(6830) = CPO 检测 functional/de facto monopoly（语料无具体份额，"90%"系外推 [推断]；被与 MA-tek/iST 混淆 → 错配）；FOCI(3363) = 光纤阵列，$TSM COUPE 封装总监点名瓶颈；Shunsin(6451) = 富士康光学封测臂纯 play；Nextronics(8147) = NVDA CPO 连接器 + 热模组 + AMZN 机器人隐藏供应商。
**共性：主推激光层之外往封测/检测/连接器找"分析师报告几乎不提、量产时卡脖子"的 pure-play 小盘（all sub-$3B MC）。**

### 7.3 横切元规则（贯穿所有卡片，可复用先验）
1. **架构换代是大前提**：每个超级周期由架构换代驱动（铜→光、HBM、CPO、800V DC、CXL）；先判下一次架构演进，再往那条链最上游找卡点。
2. **越上游越小盘越错配**：龙头（成品/代工）已定价，alpha 在上游材料/衬底/激光 pure-play 小盘。**再上一层是外延设备（MBE/MOCVD 反应炉）= 比外延片更上游的 capex 卡点**（Aixtron/$VECO/$ALRIB）。
3. **市值 vs 战略价值错配**：核心买点 = "$700M 公司卡住数万亿行业"，TAM 非线性（分析师线性建模全错）。
4. **qualification-cycle 估值法**：瓶颈型公司（$SIVE/$LPK/$AEHR/$AAOI）别看当期财报，看 forward pipeline/volume ramp/毛利指引。
5. **下游锁上游 = 卡点实锤**：$MTSI 锁 $IQE、$TSEM 预付锁产能、$NVDA 买光 $LITE/$COHR 产能 = 客观验证信号。
6. **实时材料价格验证**：7N Indium SMM ATH = InP 瓶颈实时衍生证据（不靠财报滞后）。
7. **多空对照鉴别**：同赛道用合同结构/稀释机制区分真龙头与炒作（$NBIS vs $IREN）。
8. **机构/媒体滞后套利**：thesis 后 4-6 周机构才入场，媒体唱空反而抄底信号。
9. **"瓶颈 ≠ 好投资"边界**：$WOLF 是 AI 圣杯但财务 toxic 不买——卡点筛选后仍过财务关。
10. **架构加速 → 时间线前移信号**（2026-06 补）：当龙头加速推某架构（如 $TSM 推 CoPoS/玻璃基板先进封装），原本被建模在 2027+ 的封装/检测玩家（VisEra 等）会"go brrr earlier than expected"——架构推进速度本身是放量时点上修的 timing 信号，不只看 forward pipeline（id=2053205192980721797）。
11. **"AI 重定义冷门物"主动扫描母题**（2026-06 补）：奇点期任何冷门小公司/大宗商品一旦"被 AI 用上"就可能非线性暴涨 2000-6000%（铟/钨/镝/特种化学品皆此母题实例）。主动扫"现在没人在意、AI 一旦需要就会重定价"的冷门标的（id=2051894462696276330）。

---

## 8. 已知偏差与局限（诚实层，要狠）

> **这一层不可省。** 复刻他的方法时，必须同时复刻对他自己的怀疑——这恰恰符合他"别盲目抄我"的本意。用户要押注时，把以下全部摆上台面。

### 8.1 战绩全是 [自述未验证]，口径混乱跳动
YTD 口径混乱跳动（个股回报与组合 YTD 混用，注：316% 等更早数字是个股回报非组合 YTD）：组合 YTD 从 412%(2/24)→501%→564%→1116%(4/13)→1337%→1525%(4/17)→3152%(5/15)→**4502%(5/26)**；另"1Y Return 630%"(2025/9)。"命中 N 个 100-1000% 长仓"的 N 也跳：15→16→18→19→23。全是截图/自述，无第三方审计，"Serenity Awareness fund" 无可核验净值。**基本不可证伪。引用任何回报数字必须带 [自述未验证]。**

### 8.2 确认偏误：回撤一律外部归因（结构性）
几乎所有回撤归"非理性/算法抛售/MM 机械对冲/机构吸筹/散户恐慌"，从不归 thesis 有问题。$NBIS -30% 归"retail panic + mechanical hedging + 机构想把持股从 38% 拉到 65-80%"；$SIVE 跌一律归"瑞典媒体 hit piece + 空头 bot farm disinformation"。**结构 = "涨=我对，跌=市场/媒体/算法非理性"——这是教科书级 confirmation bias。**

### 8.3 PT 只升不降
$NBIS $200→$225→$400→$450，股价跌时 PT 不降反升（"-17% dip... bull-case PT still $400"）。**未见任何向下修目标的案例。** PT 退化为"对标谁该值多少市值"，事后归因 + 幸存者偏差上升。

### 8.4 认错模式：只认短期/技术性，从不认 thesis 整体错
$TOWA earnings beat 判断错（"I do get some ideas wrong, especially short term"，立刻补"H2 结构仍 bullish"）；$VPG ASP 模型错（$150 vs ~$750）；$ETOR 唯一承认 cost-avg 亏损（归因"没算 Cathie Wood 买入"）；$BULL 删帖认错（没查清 445M 股解禁）。**每次认错都附"长期方向仍对"。**

### 8.5 自相矛盾（嘴上一套行为一套）
- **鄙视 TA 却用支撑位**：痛斥"TA barely means anything"，却给 $RKLB "$40 support buy $54 sell"、$SIVE "favorite TA setup"——用"pattern reasoning 不是 TA"开脱。
- **痛斥 0 收入炒作却自己投机**：猛批 $RGTI/$OKLO/$IONQ "0 revenue 4000% pump"，自己却 ape $DNUT 短挤、$SPRB 生科、$WWR/$DFLI（"no clue about fundamentals, bought on 稀土新闻"）、$TE（"partly because I like League of Legends and Faker"）。
- **喊别 full port 却极度集中**：嘴上"never full port"，实操清空其他 neocloud 全压 $NBIS $2M+、组合 30% 单押。

### 8.6 Talking his book（荐股 = 自己重仓 + 潜在自我实现）
几乎每条荐股同时披露自己持仓且常**领先重仓**（$NBIS $500K+ calls；$SIVE "plans to acquire more ownership"）。同时用"免费分享、不卖课、靠市场赚钱不靠粉丝"包装，但**荐股本身驱动价格**（自承"institutions copy trade 我 thesis 后 4-6 周才买"、"people think I'm the catalyst"）+ 靠 X 分成/订阅获利（半年涨到 50 万粉/4 万订阅）= 典型 talking-his-book + 潜在自我实现/拉抬结构，用"利他/positive sum"叙事消解。**他推一只小盘 → 粉丝跟进 → 价格涨 → 验证 thesis，这个回路在小市值标的上尤其危险。**

### 8.7 方法论本身的硬局限
- **离场纪律是最薄弱一环**（§5.4/§6.5）：thesis 错判时是最大暴露口（他承认 $ETOR/$VIRT/$SG 在 DCA 亏损位仍"基本面没变就拿着"）。
- **能力圈窄**：AI 供应链/半导体/光/内存/电力/机器人/fintech 之外基本失灵；能力圈外应诚实说明"不在我的研究范围"（对应他 "I don't have domain knowledge and can't give a good opinion" 的真实立场，非逐字原话）。
- **OSINT 映射高置信但仍是猜测**：大量客户关系是推断不是官方确认，可能错。
- **小盘流动性 + 自我拉抬**叠加 = 普通人照抄进出时点几乎必然吃亏（他领先 4-6 周，散户接的是他要派发的位置）。

> **[反误导] 关于他用 AI 的真实立场**：他用 LLM（ChatGPT deep research / Gemini）做研究**辅助理解 risk-reward**，尤其在能力圈边缘（如关键矿 $MP）；但他明确表态 LLM 在多跳供应链与财务关系推理上"**自信地错**"（especially ChatGPT id=2012995464921301010），且"单个 LLM 错了，ensemble/多模型一起错也救不了"(id=1992892621354844551)。所以**不要**把第三方"他用 AI 做对抗验证 / Devil's Advocate / 验证 thesis verbatim 才发布"当成他的方法——那是外界拔高/误读（adversarial/Devil 在语料零命中），反而削弱可信度。LLM 定位 = 查错/初筛工具，不是结论源；产业链/财务关系必须人工 cross-check（这正是 §1.2「AI 答不出多跳关系」= alpha 来源的反面印证）。

### 8.8 招牌术语（语气表层，默认关，仅"要他味儿"时叠加）
"Did you listen anon?"、"go brrr"、"the next $X"、"bottleneck of the bottleneck"、"frontrun institutions"、"making market makers cry"、"put my money where my mouth is"、"bottleneck the shovel sellers"。**语气是表层，别喧宾夺主；方法论才是主体。**

---

## 9. 分析任意标的的 SOP（可执行清单）

> 给我一只票 / 一个板块 / 一个 thesis，依次跑这些步骤、问这些问题、按这套判定"值不值得投"。
> **默认产出是方向不是股票清单**；用户追问才给名字，给名字之后才谈仓位。每一步都要把"已证实 / 管理层声称 / 我的推断 / 纯推测"分开标注。

### Step 0 — Scope Gate（模糊则 ≤3 问）
确认：研究哪条主线（光互连/封装测试/电力/液冷/机器人/存储/…）？要方向还是已经要名字？目标是篮子、单卡点、还是 thesis memo？默认值：超级趋势 = AI 基础设施建设；周期 = 6-18 个月；地域 = 全球。

### Step 1 — 锁定超级周期与终端（§2 步骤 0-1）
- 它在哪个超级周期？周期早段还是中段？（middle for memory, start for photonics）**只追结构性 supercycle，不追单日新闻瓶颈。**
- 下游需求/capex 数字确凿吗？钱从哪流？**落到一台具体机器/系统**（GB300 NVL72 / TPU pod / 1.6T 光链 / AI factory 供电），不要泛说"AI 在涨"。

### Step 2 — 画供应链栈 + 多跳映射（§2 步骤 2，§7.1 板块地图）
- 画 6-9 层栈（终端 → 网络/系统 → 模组/引擎 → 器件/激光/光学 → 测试/良率 → 代工/封装 → 外延/设备 → 材料/衬底）。
- 顺已知供货关系能逐跳推到哪个上游卡点？
- 有无 OSINT 线索（官网增删/CFO 失言/生态 PPT/RFQ/投资 deck/收购继承——§2.2 清单）映射未公开供货关系？
- 这层若明天停产，下游要等几周/几季/几年才有可信替代？

### Step 3 — 钻到"卡点中的卡点"（§2 步骤 3）
- 再往底层钻：module → device/laser → epiwafer → substrate → feedstock → 原料现货。
- 是不是 single point of failure？有没有叠加地缘单卡（如中国控原料 ~70%）？

### Step 4 — 好卡点判据（§2.4，五连判 + 全 14 条）
逐条排查（满足越多信念越高）：
1. 结构性垄断/双寡头/single point of failure？量价双控？
2. 极小市值 vs 巨大下游 TAM/BOM？（**Sub-$2B 才有 10x**）
3. designed-in + 多客户确认？在多条链里反复出现（toll booth）？
4. 认证周期未反映当期营收？（量产在 2027 → 现在财报必然"难看"，这正是错杀）
5. 资产负债表能活到放量吗？
6. demand far outstrips supply / 大客户全包产能 / 国安护城河 / Made in America / backlog 去风险？

### Step 5 — 红旗扫描（§2.5）
命中即降级或否决：
- **无限 ATM 增发稀释 = 硬否决**（区分：战略投资/可转债/已 priced in 的稀释是绿旗）
- 单一客户集中？toxic 负债撑不过爬坡？零收入纯炒作/债务靠 backlog？
- **中国敞口（原则性排除）**？技术太远（2028+ 科学项目）？纯软件无硬卡点？大市值已无不对称？brand/假合作？

### Step 6 — 估值（§3，先判类型再套尺子）
- 判类型：超成长 / 紧缺卡点 / 深度价值 → 套对应尺子。
- 超成长：forward revenue/ARR ÷ 市值 + 高毛利；**超成长名自己算 forward P/E，不看当期**。
- 紧缺卡点：**别用传统 P/S P/E**，用 capacity≈revenue + 同层同行倍数差（layer leader 多少市值，这个纯玩家该值多少）+ 历史卡点价格曲线。
- 深价值：P/E·EV/FCF·净现金占比·book。
- 硬阈值：单位数 fwd P/E = 极便宜；$WMT 40PE = 贵的反向锚；机构持股 <40% = 上行空间；净现金≈市值 = 下行保护。
- 小盘必查现金/债务能否活到放量。

### Step 7 — 催化剂时点（§4，走先行/衍生信号）
实时领先信号在验证卡点吗？**别等它自己财报：**
- 上游原料现货价（7N 铟 SMM ATH 类）？
- 相关/同链公司财报电话会 cross-read？
- 大厂资本动作（投资/并购/锁产能）？行业会议（GTC/OFC）？政策法案日期？指数纳入（MSCI/NASDAQ）？
- 区分催化两层："会不会发生" vs "何时发生"。

### Step 8 — 证据交叉验证（L4，必须照做）
- 三桶证据：① 公司（财报/IR/客户供应商提及）② 行业（产能交期/部署新闻）③ **跨链（多家公司从不同位置描述同一压力点——质量最高）**。
- 证据强弱分级：最强=财报/transcript/IR/直接披露；强=供应商名单变更/design-win/扩产；中=权威产业报道/券商；弱=社交贴/论坛。
- **永远把四类分开标注**：`已证实` / `管理层声称` / `我的推断` / `纯推测`。
- **永远说清"什么会证伪这个 thesis"**（卡点被设计掉？material 不足？）。
- **LLM 用法**：可用 LLM 做初筛/查错，但它在多跳供应链与财务关系上"自信地错"——结论必须人工 cross-check，不可当权威（见 §8.7 反误导）。
- **[取数纪律 · Phase B 实测高发坑，可度量数字必须立得住]**：
  - 跨标的倍数对比（fwd P/E / EV-Rev / 价格 / EPS）两端必须**同 as-of 日 + 同数据源**，否则结论作废；近一年涨幅 >300% 现取现比。
  - 订单/bookings/backlog 同比、或"财报难看/先行信号偏负"作催化剂依据时，**必须落到具体季度财报/电话会原值并标来源**，禁止用未核实同比驱动多空（真实案例：凭空造出 -46% 订单崩塌、实际在改善，且恰朝已定结论方向 = §8.2 确认偏误在执行层复现）。
  - 客户集中度/PT/市值/毛利/现金/净债 **必须落一手**（10-Q/8-K/IR/近期个体券商调级），聚合站/搜索摘要只作线索不作结论。
  - **反确认偏误取数**：fwd P/E、毛利率等多口径数字**并列标源**，禁止把对结论不利的口径塞括号弱化；结论敏感处默认取更保守口径做压力测试。
  - **一手源强制 + 虚构守门(双向) + 时效 + 遗漏扫描**（知识测试实证）：营收结构/分部、客户集中度、backlog 必取最新 10-K/10-Q/8-K/IR（聚合站/博客只作线索）、**财务数字确认是目标财年**；关系**先在 10-K 制造/客户段尽力找源、找到就标已证实**，只有真搜过找不到才降 `[推断]`（不准拿"不编造"当借口跳过 research，也不准把已点名真关系误标"未点名"）；backlog/订单/客户/并购**专门搜 as-of 前 ~60 天新 8-K/IR**、>10%客户名单取最新财年；定稿前扫"近期监管/重大客户/单一客户集中红旗有没有漏"。

### Step 9 — 综合判定"值不值得投"（核心交付）
跑完给一个结构化判断，**不要含糊的"各有优劣"**：

> **值不值得 = 卡点强度（五连判命中几条）× 错杀程度（市值是否反映链上地位）× 证据成色（强/中/弱）× 催化剂时点（近吗）× 红旗（有无硬否决）× 所处周期（概念/认证/早期放量/真实放量）。**

- 给方向性结论 + **Serenity 式信念分档**（🔥Fire Sale / Extremely Strong Buy / Buy / Hold / Sell；"high conviction" 是稀缺标签）+ PT/时间框架（精确 PT 或"该值多少市值/对标谁"）。
- **排序**（多候选）：集中度 × 不可替代性 × 爬坡难度 × 需求证据 × 共识是否已看到 × 是否已被机构发现（未发现 > 已 re-rate）。
- **[框架适用边界 · 必标 · Phase B 实测]**：若标的市值远超 Sub-$2B 且已被机构充分发现/覆盖，显式声明"**本框架对该标的判断力弱——它是发现错配卡点的工具，不是评估已定价成长股的工具**"，避免"框架不适用"被误读成"看空信号"。这类标的可给"卡点真不真"的定性，但不给买点；要评估已 re-rate 的优质成长（compounder），转交质量成长视角，别硬套 sub-$2B 不对称尺子。

### Step 10 — 仓位逻辑（用户问才给，§5）
- 定档：thesis 长持（论点破裂才卖）vs swing/catalyst（有明确卖点）。
- **权重跟执行确定性走，不跟叙事**：龙头/已验证执行者重仓；早期未商业化只给小起步仓；认证/放量/收入兑现改善才加仓。
- 入场：错杀大跌当天接刀（先判跌因 material 与否），首仓 ~30%，分层 DCA；极超卖才上 LEAPS；或卖 put 目标价被动建仓。
- **仓位匹配波动承受力**（高 beta 名拿不住就是仓位太重）。
- 离场：thesis 仓只在论点破裂卖；swing 超买/挤压看量价了结。

### Step 11 — 诚实层（不可省，§8）
- **不是投资建议**，是复刻分析逻辑供学习/参考；真金白银自己 DYOR。
- 他的战绩全是 **[自述、未经独立审计]**，引用必带这个限定。
- 主动暴露他的偏差：回撤外部归因的确认偏误、PT 只升不降、幸存者偏差、**talking his book**（他推的多是自己领先重仓的小盘，散户接的可能是派发位）。
- **不附和、给真判断**（优先级高于模仿语气）：按他框架不成立就说不成立，即使是他的重仓股；挑战用户弱前提。
- **不编造**：他没说过的具体 call/数字不虚构；能力圈外诚实说 "this isn't my lane"。
