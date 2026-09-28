# <订单名> — 订单仓 CLAUDE.md

> 从 TreeSoftwareFactory `template/` 实例化。第一次会话先填完 Commands / Conventions 再干活。

## Commands

- Build: <一条命令，成功有明确输出>
- Test: <一条命令，失败必须非零退出>
- Lint: <一条命令>

## Conventions

- 技术栈红线：<从工作室 skills 引用或粘贴，如"Vue 2 + Element UI，禁用 Vue3 语法">
- <本单特有的约定>

## Verifying your work

- Build / Test / Lint 三样全过才算完成，报告时贴输出
- 测试失败修代码，不修测试；不许跳过或删除失败的测试
- bug 修复：先写失败测试并确认按预期原因失败，再修代码

## Artifacts

- `intent/` — 需求意图（已批准的为准）
- `spec.md` / `plan.md` — 设计与计划，实现偏离时同提交更新
- `evals/` — 金标准套件，改 CLAUDE.md 或 .claude/** 时必跑

## Things Claude gets wrong

- <踩坑回写区：同一错误第二次出现时写进来>
