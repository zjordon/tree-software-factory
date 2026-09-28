# TreeSoftwareFactory

单人质检的 AI 软件工厂（一人接单工作室）：围绕 AI-native SDLC，把客户需求加工成"软件 + 完整出处链 + 持续维护"。

- 本仓是**工厂本体仓**：放工厂资产（订单仓模板、工作室 skills、客户前台 bundle），不放任何订单的代码
- 订单仓从 `template/` 实例化的独立 git 仓（建议放 `D:\dev\git\z_jordon\orders\<订单名>`），七站流水线全程在订单仓发生
- 宪法见 [FACTORY.md](FACTORY.md)，概念基线见 [docs/founding-baseline.md](docs/founding-baseline.md)
- 状态：2026-09-28 初始化，等待第一张真实订单（第一张订单同时是工厂 v1 的验收）
