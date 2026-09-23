# stock-watch

港股 / AI 相关标的盯盘笔记库（Asia/Shanghai）。

由小青按工作日四波扫描写入 `notes/`，观察名单见 `config/watchlist.md`。

## 扫描时刻（工作日 周一至周五）

| 时刻 | 用途 |
|------|------|
| 08:00 | 开盘前：隔夜外盘/新闻/今日关注 |
| 10:00 | 早盘：开盘后约半小时走势与异动 |
| 12:30 | 午休：午前半日复盘 |
| 14:30 | 午后：收盘前约 1.5 小时再扫 |

周末与港股休市日：例行任务不发空报（简要记下休市即可，可不推送用户）。

## 文件约定

- `config/watchlist.md` — 观察名单（可改）
- `notes/YYYY-MM-DD.md` — 当日四波合并或分节归档
- `notes/YYYY-MM-DD-HHMM.md` — 单波快照（可选）

远程：`https://github.com/lgq-opc/stock-watch`

## 三市下午总结

工作日约 **16:44**（Asia/Shanghai）生成当日总结：`notes/YYYY-MM-DD-daily-summary.md`（A股收盘 + 港股收盘 + 美股昨夜）。
