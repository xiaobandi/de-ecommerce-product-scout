# 选品打分卡 · 速查

| 项 | 内容 |
|---|---|
| slug | `wf-ecom-scout-selection-scorecard` |
| 层级 | L2-workflow |
| 归属 | 选品与竞品情报（`de-ecommerce-product-scout`） |
| 复杂度 / 阶段 | S / P1 |
| 能力族 | — |
| 定义出处 | — |
| 复用情况 | — |

## 调用的 SKILL

| 技能 | slug | 来源 |
|---|---|---|
| 利润测算 | `profit-calculator` | 本仓 |
| 选品打分卡 | `product-selection-scorecard` | 本仓 |

## 字段

| 项 | 内容 |
|---|---|
| 必需输入 | 本工作流的起始材料（见 `SKILL.md`「执行步骤」第 1 步）；用户身份与目标平台/渠道 |
| 可选输入 | 历史产出；账号人设；渠道规则；上一周期的数据 |
| 产出 | 结论 |
| 脚本 | 无 |
