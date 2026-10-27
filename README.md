# 魏威 · David Wei

**用代码把复杂的东西讲清楚。**

宾夕法尼亚大学 · 应用数学与计算机 硕士
犹他大学 · 金融 / 数学 / 工商管理 学士

在做两件事：把自适应学习做成一整套可运行的系统；把具身智能的技术脉络整理成中文。

---

## 在维护的项目

### math-bank — 自适应习题与学情系统

面向国际课程（A-Level / IAL / 竞赛）的刷题与学情系统，跑在老师自己的电脑上，学生数据不出本机。

| | |
|---|---|
| 题库规模 | **12,030 道真题 · 29 个单元 · 1,142 个知识点 · 270 章**（1993–2026） |
| 覆盖范围 | CIE 9709 / 9231 · Edexcel IAL · UKMT SMC · BMO · TMUA · ESAT |
| 能力估计 | 多变量 Elo（知识点维度 + 章节维度加权融合），对单链 Elo 基线做过 A/B 对比 |
| 工程取舍 | 零运行时依赖（标准库 `http.server`）· 零 LLM 调用 · 零构建步骤 |
| 数据隐私 | 只监听 `127.0.0.1`，作答写入本地 SQLite，七层安全防护 |
| 许可 | MIT |

题库 100% 可被自适应出题选中；判分、评估、反馈全部是确定性代码，可复现、可解释。

→ [github.com/WEIWEI0614/math-bank](https://github.com/WEIWEI0614/math-bank)

### robot-learning-desk — 机器人 / 数学 / AI 中文资料库

21 个面板，纯静态 HTML，全部可离线打开。内容分三层：知识层（补懂）→ 实践层（做出来）→ 规划层（排顺序）。

含强化学习基础四篇（TRPO / A3C / DDPG / MPC）、21 篇论文的演进地图、SO-101 造机选型与 BOM、仿真训练算力实测、30 天游戏化学习计划。引用数值均标注页码 / 章节号来源。

→ [github.com/WEIWEI0614/robot-learning-desk](https://github.com/WEIWEI0614/robot-learning-desk)

### build-next 与 gh-discoverability — 两个零依赖的小工具

**build-next**：用「需求减供给」给下一个项目找方向——读 GitHub 热榜的注意力信号，减去仓库数与技能注册表的拥挤度。
**gh-discoverability**：给一个仓库的可搜索面打分，按「能捞回多少」排序给出修改项。

两个都不依赖第三方包，也不调用大模型。

→ [build-next](https://github.com/WEIWEI0614/build-next) · [gh-discoverability](https://github.com/WEIWEI0614/gh-discoverability)

---

## 关注的题目

- **学习控制器的可靠性** — 动作分块（action chunking）的开环执行有效期：一个策略执行一整段动作、中途不再决策，这段能维持多久，能不能事先算出来而不是靠扫参数试出来
- **具身智能** — VLA 模型、机器人学习、仿真到现实的迁移
- **强化学习** — 从 TRPO / PPO 到现代对齐流水线
- **自适应学习** — 能力评估、知识追踪、选题策略

## 工具链

Python · JavaScript · SQLite · PyTorch · MuJoCo · LaTeX

---

## 经历

- 国际数学教育 — 竞赛与牛剑笔试方向（A-Level / BMO / SMC / ESAT / TMUA）
- 国内一级投资 · FA
- 新加坡并购

---

<sub>如果你对自适应学习系统或具身智能中文资料有想法，欢迎开 issue 讨论。</sub>
