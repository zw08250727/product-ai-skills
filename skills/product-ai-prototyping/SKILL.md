---
name: product-ai-prototyping
description: Turn product ideas into structured requirements, solution options, AI-ready prompts, and prototype plans. Use when working on product discovery, feature expansion, PRD scoping, interaction design, role or state design, workflow definition, frontend-vs-backend boundary decisions, or when the user wants to convert product thinking into an AI prototype workflow.
---

# Product AI Prototyping

将产品经理的模糊想法，收敛为可执行的 AI 原型任务、产品方案与提示模板。

## Quick Start

按下面顺序工作，不要一开始就直接画页面：

1. 锁定母体产品：确认基于什么现有产品改，哪些能力必须保留，哪些不是本次目标。
2. 明确改造目标：先定义核心问题、关键动作、目标交付物。
3. 先拆场景，再拆角色：先区分用户处在哪个场景或页面，再定义不同身份能看什么、做什么。
4. 建对象模型：最少明确核心对象、关键状态、触发条件、约束规则、上下游依赖。
5. 串关键流程：把需求写成“谁在什么场景对什么对象做什么动作，结果如何，受什么规则约束”。
6. 判断系统边界：界面层承接高频使用，配置层承接规则来源，系统层承接数据与状态。
7. 输出原型：先结构，再逻辑，再状态，再细节，不要一次追求最终版。
8. 补方案文档：除了原型，还要输出功能调整、逻辑调整、角色/状态规则、系统边界、一期范围。

## Default Working Rules

- 优先保留原有产品骨架，不随意完全重构。
- 不把不同场景、不同身份、不同状态混在一个页面里。
- 不只列功能名，要写动作闭环。
- 先补逻辑，再打磨文案和按钮。
- 原型要体现状态差异，不只做静态页面。
- 只在用户明确要求时再细化后台、数据层或治理层。

## Recommended Output Order

默认按以下顺序输出：

1. 改造目标
2. 场景划分
3. 角色划分
4. 核心对象
5. 关键流程
6. 功能调整
7. 逻辑调整
8. 系统边界
9. 高保真原型建议
10. 一期/二期建议

## If Requirements Are Still Fuzzy

优先补齐这几类信息：

- 母体产品是什么
- 本次要保留什么
- 本次最核心的动作是什么
- 涉及几个场景
- 涉及几个角色
- 核心对象和状态有哪些
- 最终想要的是原型、方案、PRD，还是三者都要

## Reference Files

- 方法论完整版：见 `references/methodology.md`
- 可直接复制给 AI 的提示模板：见 `references/prompt-template.md`

