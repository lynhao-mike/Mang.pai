# 会话交接文档（Handoff · 2026-05-20 · v11）

> **⚠️ 本文件用途**：AI 助手会话交接专用，每次新会话覆写。非面向普通读者。
> **Skill 版本**：v7.0 Phase 11 | **提示词版本**：v2.3

---

## 一、当前状态快照

| 维度 | 状态 |
|---|---|
| 高派理论入库 | 10/10 份完成 · 261 条候选 · **249 条已晋级** · 12 条高风险暂留 |
| 回归验证 | 4 案例（CASE-001~004）· 有效命中率 96.1% |
| Phase 进度 | Phase 1~11 全部完成 · 等 Phase 12 启动 |
| 仓库结构 | 2026-05-20 优化完成（提示词冻结/案例分目录/INDEX瘦身/module-c拆分） |

### 剩余候选池（12 条 · 全高风险）

| 前缀 | 剩余 | 内容 |
|---|---|---|
| GP-SS | 2 | 飞刃倒戈 / 四大空亡短命 |
| GP-CH | 3 | 死期 / 空亡断死 / 追魂铲度 |
| GP-MG | 5 | 命宫看寿限 / 马倒禄斜 / 取名 |
| GP-BD | 1 | 冲天煞短命 |

> 以上 12 条必须 ≥3 反例校验后方可晋级。

---

## 二、下一步方向（Phase 12+）

| # | 方向 | 推荐度 |
|---|---|---|
| A | 新案例入库验证（车祸灾厄+财运新条目） | ⭐⭐⭐⭐ |
| B | 串宫十二神/十九星专项验证 | ⭐⭐ |
| C | 高风险铁律反例校验（11 条） | ⭐⭐⭐⭐⭐ |
| D | P1/P2 低优先候选清理（13 条） | ⭐⭐ |

---

## 三、关键约束

1. 每条候选必带原文锚点（禁凭印象编造）
2. 五件套必须同步（pending-queue / source-trace / coverage-matrix / cases-index / extracted）
3. 高风险铁律必须 ≥3 反例校验
4. 阶段 5 严禁跳：候选必须人审 + 案例验证才能写主模块

---

## 四、用户偏好

| 项 | 说明 |
|---|---|
| 语言 | 纯简体中文 |
| 风格 | 高强度结构化（表格+编号+铁律级条目） |
| 节奏 | 简洁指令 → 立即执行 + 完整成果报告 |
| 避免 | 过度自夸 / 表情堆砌 / 流水账 |
| git | **直接 push main，不走 PR** |
| 接班 | 先 pull 最新 + 看 commit log → 核对状态 → 说"已就绪" |

---

## 五、沙箱环境

```
工作目录：/projects/sandbox/Mang.pai/
仓库：lynhao-mike/Mang.pai
git push：必须用 mcp_sandbox_github_push_to_remote
```

---

## 六、文件速查

```
.kiro/skills/blind-bazi-analyst.md           # 主入口路由层
.kiro/skills/modules/module-a-paipan.md      # 排盘+神煞+三垣
.kiro/skills/modules/module-b-geju.md        # 格局+财运+理法
.kiro/skills/modules/module-c-yunqi.md       # 大运流年+命宫应期
.kiro/skills/modules/module-c2-zaihou.md     # 车祸灾厄专题（从module-c拆出）
.kiro/skills/modules/module-d-hehun.md       # 合婚+婚姻
.kiro/skills/modules/module-e-zeri.md        # 择日
.kiro/skills/META/pending-extraction-queue.md # 候选规律队列（唯一真实来源）
.kiro/skills/META/source-trace.md            # 来源追溯
.kiro/skills/META/rule-changelog.md          # 规律修正追踪
```

---

## 七、续推指令模板

```
[选 A] 我有新案例反馈，验证车祸灾厄+财运新条目
[选 B] 用新案例推演串宫十二神体系
[选 C] 提供 ≥3 反例，校验高风险铁律（GP-CH-12~14 / GP-MG-07/19~21 / GP-SS-15/21 / GP-BD-30）
[选 D] 清理 v1/v2.0 来源的 13 条低优先候选
```

---

*v11 · 2026-05-20 · 替代 v10（瘦身去重·从 252 行压缩至 ~95 行）*
