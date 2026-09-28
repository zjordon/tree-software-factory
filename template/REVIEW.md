# Review instructions

## Passes

Run three passes and tag each finding with its pass:

- Bugs: logic errors, broken edge cases, subtle regressions
- Security: authentication gaps, authorization / IDOR (ownership checks
  on every data access), PII in logs, injection risks
- Compliance: the change matches intent.md, spec.md and plan.md —
  "did it do what the plan said", not "re-read the whole codebase"

## What Important means here

Reserve Important for findings that would break behavior, leak data
or breach a policy. Style and naming are nits.

## Cap the nits

Report at most five nits per review; summarize the rest as a count.

## Do not report

Generated files and anything CI already enforces.

## 工作室加注（高于本文件其余部分）

- 安全项（认证 / 越权 / 数据隔离）无论 pass 结果如何，树哥亲自看——CrossBeam 教训
- 本文件由订单仓派生自工厂 FACTORY.md，改动回写工厂
