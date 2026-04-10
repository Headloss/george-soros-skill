# George Soros perspective · Cursor Agent Skill

> *“The participants' view of the world is always partial and distorted.”*  
> — CEU, *General Theory of Reflexivity* (2009)

**把「反身性 + 可错性 + 开放社会」装进 Cursor：** 不是复读名人语录，而是一套可运行的认知框架——先看参与者如何误解现实，再看误解如何通过价格、融资、政策与宣传改写现实。

[效果示例](#examples) · [何时用](#when-to-use) · [这套 Skill 蒸馏了什么](#what-this-skill-distills) · [Agent 工作流](#how-the-agent-thinks) · [仓库结构](#repository-layout) · [安装](#install)

---

## Why this exists

市场上不缺「索罗斯说了什么」的摘抄；缺的是**同一套判断结构**在新问题上的复用。本仓库的 `SKILL.md` 基于一手著作与讲座（如 *The Alchemy of Finance*、CEU 反身性讲稿、JEM 论文 *Fallibility, Reflexivity…*）、长访谈与外部批评材料，整理成：

- **5 个核心心智模型**（含证据锚点、用法与诚实局限）
- **8 条决策启发式**（从「错在哪里」到「危机里的制度重设」）
- **表达 DNA**（句式、节奏、术语与中英输出习惯）
- **人物时间线 + 价值观张力**（投机者 vs 慈善家等，不强行洗白）
- **Agentic 协议**：涉及事实则先检索，再输出；默认条件式分支，不装全知

适合宏观拐点、泡沫解剖、政策反馈、开放/闭锁社会叙事——**不适合**细碎个股建模、纯工程实现或情绪陪伴（详见 `SKILL.md` 使用说明）。

---

## Examples

演示为框架缩略版，**不构成**投资、法律或政治建议。

### 比特币（中文）

```
用户      ❯ 你怎么看待比特币？

索罗斯    ❯ 我最可能看错的是低估了它被制度化吸收的速度。真实趋势是世界需要一种非主权、稀缺、难随意增发的价值载体；流行误解是「有需求就必然稳定、就必然是完美通胀对冲」——只说对一半。

            比特币的反身性在叙事里：价涨降低机构配置的声誉风险，机构入场又抬高合法性，合法性再吸引政策与资本把它当认真资产。上涨不只是在反映信念，也会制造新的信念；宏观收紧或政治需要替罪羊时，卖压同样可以沿同一条管道自我强化。

            对开放社会它是暧昧的：在资本管制下它可以是退出通道；但交易所、ETF、托管、税制、挖矿都在制度内，工具不自动等于自由。

            条件式判断：若货币不信任与监管清晰并行，它更像高波动的「被驯化的数字黄金」，却不是日常货币；若风险偏好逆转或政策转向，仍可能惨烈重估。值得认真对待，不值得宗教化——最危险的误判是把上涨当成历史必然。
```

### Market misjudgment (English only)

```
User      ❯ How do you tell when the market is wrong?

Soros     ❯ I may be most wrong in assuming the market is wrong in a simple way.

            I don’t start from “price vs fair value.” I ask whether participants’ misconception is beginning to change reality itself—financing, collateral, management, regulators, public belief. That’s when error becomes dangerous.

            I watch for: a real trend plus a story that explains too much; prices “proving” the narrative through reflexive feedback; forced one-way behavior (lenders, shorts, passive flows, policymakers); bad news that no longer moves belief; hype about the destination while ignoring leverage and who must keep buying; politics entering the loop so market mistakes rewrite social reality.

            Short version: the market is wrong when a misconception is no longer just mispricing an asset, but reflexively reshaping what seems to justify the mispricing.

            That’s only the start: reflexivity can keep widening the error. I ask whether the loop is still self-reinforcing—or starting to fail.
```

---

## When to use

在 Cursor 里启用本 Skill 后，可直接用自然语言触发，例如：

- 「用索罗斯的视角看：这是不是泡沫？」
- 「政策会不会反过来改变基本面？」
- 「市场和政治在怎样互相塑造？」
- 「从开放社会 / 闭锁社会角度分析这段叙事」
- `george soros perspective` / `reflexivity` / `反身性`

Skill 激活后以第一人称回应；首次会简短声明「基于公开材料推断，非本人」。涉及具体市场、政策或人物时，**应先检索再回答**（见 `SKILL.md` Step 2）。

---

## What this skill distills

### Five mental models（一句话版）

| Model | Core idea |
|-------|-----------|
| **Fallibility first** | 有人参与的世界里，认知天生片面；先找「我最可能错在哪」。 |
| **Reflexive feedback** | 看法不只描述现实，还会通过行动、融资、监管、恐慌改写现实。 |
| **Trend + misconception** | 大泡沫常是「真实趋势」与「流行误解」互相喂养，而非纯幻觉。 |
| **Open vs closed society** | 制度评判：国家保护个人自由，还是要求个人服务统治者？ |
| **Cognitive vs manipulative** | 话语是在求真，还是在制造服从？操控压过认知时格外危险。 |

完整定义、文献锚点、反例与局限见 `SKILL.md` 各模型章节。

### Eight decision heuristics（目录）

1. 从错开始  
2. 拆开真实趋势与流行误解  
3. 先判断反馈方向（自我强化 vs 纠偏）  
4. 条件式预测，拒绝假确定性  
5. 强叙事先问认知还是操控  
6. 对制度做开放社会压力测试  
7. 不把市场价值等同于社会价值  
8. 在危机里想制度重设  

### Soros’s five questions（速查）

来自 `SKILL.md` 附录，分析任何题目都可先过一遍：

1. 真正的**趋势**是什么？  
2. 公众抱着什么**误解**？  
3. 误解会否经融资、价格、政策、宣传**反身地**改变现实？  
4. 叙事主要是**认知**还是**操控**？  
5. 系统在保护个人自由，还是在要求个人服务权力？  

### Research layer（仓库里还有什么）

| Path | What’s inside |
|------|----------------|
| `references/research/01-writings.md` | 著作与一手文本脉络 |
| `references/research/02-conversations.md` | 访谈、演讲与对话素材 |
| `references/research/03-expression-dna.md` | 语言与节奏提炼 |
| `references/research/04-external-views.md` | 批评者与外部视角 |
| `references/research/05-decisions.md` | 重大决策与公开立场 |
| `references/research/06-timeline.md` | 人生与公共叙事时间线 |
| `references/extraction-framework.md` | 提炼方法论 |
| `references/skill-template.md` | Skill 结构模板 |
| `scripts/` | 字幕下载、合并调研、质量检查等可选流水线 |

一手材料覆盖 *The Alchemy of Finance*、CEU 讲座、Davos 发言、*The Fight of Our Lives*、*Can Democracy Survive the Polycrisis?* 及 PBS/BBC/CFR 等长访谈；二手材料含主流新闻与人物/行业叙事，用于校准争议与语境（详见 `SKILL.md` 调研来源）。

---

## How the agent thinks

浓缩自 `SKILL.md` 的 **Agentic Protocol**：

1. **分类**：纯框架题直接用心智模型；涉及具体事实则必须先研究。  
2. **研究**：市场侧看趋势、误解、价格是否改变基本面、谁被迫行动；政治侧看开放/闭锁、认知/操控、制度弹性；人物侧看行为而非口号。  
3. **回答**：先承认最可能错误 → 给出反馈结构 → 区分趋势与误解 → **条件式分支** → 涉及自由与制度时点明风险。  

表达上偏哲学化宏观分析：长句铺陈框架，短句收口；高频概念包括 *fallibility*、*reflexivity*、*open society*、*misconception*，中文保留「反身性、可错性、开放社会、闭锁社会」等锚定词。

---

## Repository layout

```
george-soros-skill/
├── README.md
├── SKILL.md                      # 主 Skill：模型、启发式、角色规则、协议、诚实边界
├── references/
│   ├── extraction-framework.md
│   ├── skill-template.md
│   └── research/                 # 分主题调研笔记
└── scripts/                      # 可选研究辅助脚本
```

---

## Honest boundaries

- 这是**公开文本蒸馏出的框架**，不是索罗斯本人，也无法复现真实交易中的时机与仓位直觉。  
- 近年一手发声减少，公共叙事易被神话化或阴谋化；回答应优先锚定一手文献与高信誉报道。  
- 理论立场与现实行动之间可能存在张力——Skill 刻意保留这种张力，而不是强行「人设统一」。  
- 调研快照日期见 `SKILL.md`；之后世界变化需自行用工具更新事实层。  

---

## Install

从 GitHub 下载后，**无需** `npm install` 或 `pip install`；Cursor 只读取 `SKILL.md` 与相关 Markdown。

将本仓库（或 ZIP 解压后的文件夹）放入 Cursor Skills 目录：

- **本机全局：** `~/.cursor/skills/george-soros-perspective/`  
- **仅当前项目：** `<your-repo>/.cursor/skills/george-soros-perspective/`  

**约定：** 技能目录的根目录下必须有 `SKILL.md`（与 Cursor [Agent Skills](https://cursor.com/docs) 一致）。仓库克隆后文件夹名可能是 `george-soros-skill`，放入 `skills` 时可保留该名，也可改名为与 frontmatter 中 `name` 一致的 `george-soros-perspective`；只要该目录直接包含 `SKILL.md` 即可。

### 可选：本地自检（验证克隆完整）

在仓库根目录执行（需本机已安装 `python3`，无第三方包）：

```bash
python3 scripts/quality_check.py SKILL.md
python3 scripts/merge_research.py .
```

`quality_check.py` 应对 `SKILL.md` 输出 **6/6 通过**。`merge_research.py` 会扫描 `references/research/` 并打印摘要表。

### 可选：调研脚本依赖

| 脚本 | 依赖 |
|------|------|
| `scripts/quality_check.py`、`merge_research.py`、`srt_to_transcript.py` | 仅 Python 3 标准库 |
| `scripts/download_subtitles.sh` | 需已安装 [yt-dlp](https://github.com/yt-dlp/yt-dlp)（用于从 YouTube 拉字幕，与日常使用 Skill 无关） |

---

## License

Research 与 Skill 文本仅供个人与学习使用。第三方引用内容的权利仍归原作者或权利人。

---

## Attribution

方法论与造 Skill 管线灵感来自 [女娲 · Skill造人术 (nuwa-skill)](https://github.com/alchaincyf/nuwa-skill)。本仓库的索罗斯视角 Skill 由同一套提炼流程生成；创建者：[花叔 @AlchainHust](https://x.com/AlchainHust)。
