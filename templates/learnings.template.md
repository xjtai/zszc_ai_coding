---
specId: SPEC-<组名>-001
type: learnings
parent_spec: spec.md
plan_ref: plan.md
tasks_ref: tasks.md
eval_ref: eval.md
domain: 客服
system: <组名>-customer-service-agent
owner: <组名 / 组员姓名>
status: 草稿           # 草稿（Coding Agent 自动生成）/ 已确认（人评审后）
confirmed: false
version: 0.1
updated_at:
writeback_status: N/A     # 本次没有真实知识库可写回，见下方说明
writeback_pr: N/A
related_specs: []
score: {}
---

<!-- ──────────────────────────────────────────────────────────────
  learnings.md ｜ 经验沉淀（这次实战真正想沉淀下来的东西）

  这份文件怎么产生      跟其他四份一样，也是 Coding Agent 起草、人
        评审确认——但起草方式不同：Agent 不是凭空写，而是**自动读取
        spec.md / plan.md / tasks.md / eval.md 各自的"变更记录"**
        （评审 spec/plan/tasks 时人纠正、补充的内容都记在那里；eval.md
        的变更记录里还有编码/评测阶段发现的问题），从这些真实发生
        过的修正里提炼出 L-01~L-05。人评审的重点不是"有没有记全"，
        而是"提炼得准不准、回流去处具体不具体"。

  所以人在评审 spec/plan/tasks/eval 时要做的唯一一件事      把每处
        纠错和补充老老实实记进那份文件自己的"变更记录"里，不用另外
        再写一份日志——这份 learnings.md 会在最后自动从那四处收集
        齐全。跳过这一步，Agent 起草 learnings.md 时就无米下锅。

  "回流"是什么意思      本次工作坊没有真实知识库可写回，"回流"改成：
        这条经验应该被写进你们以后自己的 AI Coding checklist，还是
        这次 plan.md 的"不改清单"，还是反馈给培训教学组改进下次的
        题目设计——挑一个具体去处，不要写"以后注意"这种没有落点的话。
────────────────────────────────────────────────────────────── -->

# LEARNINGS-\<组名\>-001｜经验沉淀

## 这五条是怎么被找出来的

Coding Agent 起草时填写：从 spec.md / plan.md / tasks.md / eval.md 的变更记录里各挑了几条、依据什么标准挑（比如影响范围大、或者最容易在下次项目里重犯）。

## 回流入口对照

| 经验编号 | 回流去处 |
|---|---|
| L-01 | |
| L-02 | |
| L-03 | |

## L-01　〔一句话描述现象〕

- 问题：
- 根因：
- 修复：
- 回流：➜（写进哪份文档的哪一节，或反馈给谁）
- 可复用性：（这个坑下次做类似系统还会不会踩？值不值得写成团队规范？）

## L-02　〔一句话描述现象〕

- 问题：
- 根因：
- 修复：
- 回流：➜
- 可复用性：

## L-03　〔一句话描述现象〕

- 问题：
- 根因：
- 修复：
- 回流：➜
- 可复用性：

（时间允许可补 L-04、L-05）

## 度量回填

| 阶段 | 计划耗时 | 实际耗时 |
|---|---|---|
| spec.md 起草 | 10min | |
| spec.md 评审（触发 plan.md / eval.md 起草） | 10min | |
| eval.md 评审 | 10min | |
| plan.md 评审（触发 tasks.md 起草） | 15min | |
| tasks.md 评审 | 10min | |
| AI Coding | 80min | |
| eval.md 实测 | 20min | |
| 部署发布 | 15min | |
| learnings 生成确认 + 演示 | 10min | |

| 指标 | 目标 | 实测 |
|---|---|---|
| 路由准确率 | ≥85% | |
| 性能 | 10 QPS | |
