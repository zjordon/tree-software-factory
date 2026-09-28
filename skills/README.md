# skills/ — 工作室级 skills

经验法则（手册）：**必须一致应用的机构知识写成 skill；属于 CLAUDE.md 的组件不要写成 skill。** skill 是建议性控制，必须无条件成立的要配 hook。

## 候选池（遇到第二次再立，不预建——铁律 4）

- 技术栈红线（第一张订单定栈后立）
- 安全基线（认证 / 越权 / 数据隔离的最低要求——CrossBeam 教训）
- API 设计约定
- 部署检查单

## 约定

- 每个 skill 一个目录：`SKILL.md`（frontmatter 写清何时触发）+ 必要脚本
- 政策变化改 skill，改动像代码一样审查后合并
- 订单仓需要时从工厂仓分发（`.claude/skills/` 或 plugin）
