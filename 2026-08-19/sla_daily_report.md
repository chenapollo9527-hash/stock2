# 2026-08-19 运行审计日报（SLA）

生成时间：2026-08-19T15:32:21+08:00

## 汇总

- 正常或已发送阶段：0 / 4
- 阻塞阶段：0900, 0945, 1315, 1445
- 应发但漏发邮件：-
- 无需发送邮件：0900, 0945, 1315, 1445
- 明确禁止发送：-

## 各阶段

| 阶段 | 状态 | 邮件 | 数据就绪 | Runner 开始 | LLM 秒 | 完成秒 | 原因 |
|---|---|---|---|---|---:|---:|---|
| 0900 | blocked_preopen_pool | not_required | - | - | - | - | - |
| 0945 | blocked_market_input_quality | not_required | - | 2026-08-19T09:45:58+08:00 | - | 0.0 | 08:00 research pool status=blocked_daily_kline_coverage; 08:00 daily-Kline quality gate did not pass: status=coverage_low, coverage=0.852506; 08:00 Top30 main pool is incomplete: 0 |
| 1315 | blocked_market_input_quality | not_required | - | 2026-08-19T13:15:57+08:00 | - | 0.0 | 08:00 research pool status=blocked_daily_kline_coverage; 08:00 daily-Kline quality gate did not pass: status=coverage_low, coverage=0.852506; 08:00 Top30 main pool is incomplete: 0 |
| 1445 | blocked_market_input_quality | not_required | - | 2026-08-19T14:46:32+08:00 | - | 0.0 | 08:00 research pool status=blocked_daily_kline_coverage; 08:00 daily-Kline quality gate did not pass: status=coverage_low, coverage=0.852506; 08:00 Top30 main pool is incomplete: 0 |
