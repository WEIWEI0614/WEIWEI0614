# 魏威 · David Wei

**用代码把复杂的东西讲清楚。**

宾夕法尼亚大学 · 应用数学与计算机 硕士
犹他大学 · 金融 / 数学 / 工商管理 学士

在做三件事：把自适应学习做成一整套可运行的系统；把具身智能的技术脉络整理成中文；把一个说不清对错的领域做成说得清对错的引擎。

---

## 在维护的项目

### math-bank — 自适应习题与学情系统

面向国际课程（A-Level / IAL / 竞赛）的刷题与学情系统，跑在老师自己的电脑上，学生数据不出本机。

| | |
|---|---|
| 题库规模 | **12,030 道真题 · 29 个单元 · 1,142 个知识点 · 270 章**（1993–2026） |
| 覆盖范围 | CIE 9709 / 9231 · Edexcel IAL · UKMT SMC · BMO · TMUA · ESAT |
| 自适应引擎 | Elo 变体 + 章节收缩 + 60/25/15 选题配比，含 5 个变体的 A/B 实测数据 |
| 工程取舍 | 零运行时依赖（标准库 `http.server`）· 零 LLM 调用 · 零构建步骤 |
| 数据隐私 | 只监听 `127.0.0.1`，作答写入本地 SQLite，七层安全防护 |
| 许可 | MIT |

题库 100% 可被自适应出题选中；判分、评估、反馈全部是确定性代码，可复现、可解释。

→ [github.com/WEIWEI0614/math-bank](https://github.com/WEIWEI0614/math-bank)

### robot-learning-desk — 机器人 / 数学 / AI 中文资料库

21 个面板，纯静态 HTML，全部可离线打开。内容分三层：知识层（补懂）→ 实践层（做出来）→ 规划层（排顺序）。

含强化学习基础四篇（TRPO / A3C / DDPG / MPC）、21 篇论文的演进地图、SO-101 造机选型与 BOM、仿真训练算力实测、30 天游戏化学习计划。引用数值均标注页码 / 章节号来源。

→ [github.com/WEIWEI0614/robot-learning-desk](https://github.com/WEIWEI0614/robot-learning-desk)

### bazi-ziwei-engine — 八字与紫微交叉验证的命理引擎

两套通常各说各话的体系，从同一个出生时刻排出，再互相印证。**关键不是算得更准，而是这个模型敢被检验**：填几条真实经历，它给自己打分，并列出算错的年份。

| | |
|---|---|
| 历法 | 截断 VSOP87 求太阳视黄经（含章动 / 光行差 / FK5 修正），节气牛顿迭代，不查表 |
| 校验 | 四柱 3,000 例对 lunar-python 零误差；紫微 700 张盘对 iztro，除 1 张朔日临界外全对 |
| 评分 | 格位（成格 / 破格 / 救应）与强度（七维）分开算，不取平均 |
| 交付 | 零依赖 CLI · 深色双语 Web · Agent Skill · MCP server |
| 许可 | MIT |

在线演示 → [weiwei0614.github.io/bazi-ziwei-engine](https://weiwei0614.github.io/bazi-ziwei-engine/)

→ [github.com/WEIWEI0614/bazi-ziwei-engine](https://github.com/WEIWEI0614/bazi-ziwei-engine)

---

## 关注的题目

- **具身智能** — VLA 模型、机器人学习、仿真到现实的迁移
- **强化学习** — 从 TRPO / PPO 到现代对齐流水线
- **自适应学习** — 能力评估、知识追踪、选题策略
- **学习科学** — 反馈回路、间隔重复、认知负荷

## 工具链

Python · JavaScript · SQLite · Git · 强化学习

---

## 经历

- 国际数学教育 — 竞赛与牛剑笔试方向（A-Level / BMO / SMC / ESAT / TMUA）
- 国内一级投资 · FA
- 新加坡并购

---

<sub>如果你对自适应学习系统或具身智能中文资料有想法，欢迎开 issue 讨论。</sub>
