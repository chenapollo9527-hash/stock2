# 2026-08-05 运行审计日报（SLA）

生成时间：2026-08-05T15:19:20+08:00

## 汇总

- 正常或已发送阶段：1 / 4
- 阻塞阶段：0945, 1315, 1445
- 应发但漏发邮件：-
- 无需发送邮件：0945, 1315, 1445
- 明确禁止发送：-

## 各阶段

| 阶段 | 状态 | 邮件 | 数据就绪 | Runner 开始 | LLM 秒 | 完成秒 | 原因 |
|---|---|---|---|---|---:|---:|---|
| 0900 | ok | disabled_no_recipients | 2026-08-05T08:13:17+08:00 | 2026-08-05T08:13:17+08:00 | 1120.0 | 1139.0 | - |
| 0945 | blocked_validator_failed | not_required | 2026-08-05T09:46:38+08:00 | 2026-08-05T09:46:39+08:00 | 182.0 | 204.0 | validate_recommendations failed |
| 1315 | blocked_validator_failed | not_required | 2026-08-05T13:16:15+08:00 | 2026-08-05T13:16:20+08:00 | 37.0 | 431.0 | validate_recommendations failed |
| 1445 | blocked_market_batch | not_required | - | - | - | - | - |
