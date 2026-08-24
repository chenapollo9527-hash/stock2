# 2026-08-24 运行审计日报（SLA）

生成时间：2026-08-24T15:34:51+08:00

## 汇总

- 正常或已发送阶段：0 / 4
- 阻塞阶段：0900, 0945, 1445
- 应发但漏发邮件：-
- 无需发送邮件：0900, 0945, 1315, 1445
- 明确禁止发送：-

## 各阶段

| 阶段 | 状态 | 邮件 | 数据就绪 | Runner 开始 | LLM 秒 | 完成秒 | 原因 |
|---|---|---|---|---|---:|---:|---|
| 0900 | blocked_insufficient_preopen_deep_research | not_required | 2026-08-24T08:12:55+08:00 | 2026-08-24T08:12:55+08:00 | - | 14.0 | only 0 stock deep research results succeeded |
| 0945 | blocked_llm_http_error | not_required | 2026-08-24T09:46:01+08:00 | 2026-08-24T09:46:02+08:00 | - | 0.0 | LLM HTTP 402 |
| 1315 | missing | not_required | - | - | - | - | - |
| 1445 | blocked_llm_http_error | not_required | 2026-08-24T14:52:46+08:00 | 2026-08-24T14:52:50+08:00 | - | 47.0 | LLM HTTP 402 |
