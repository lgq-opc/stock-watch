# stock-watch 写入约定

- 仓库用途：港股 / AI 相关标的盯盘归档。
- 观察名单：`config/watchlist.md`（用户或助手可改）。
- 每波扫描后：写入 `notes/YYYY-MM-DD.md`（按 08:00 / 10:00 / 12:30 / 14:30 分节追加），并 push 到 `origin`（`lgq-opc/stock-watch`）。
- 向用户汇报：简体中文、可扫读；休市日可静默。
- Git 作者：小青（Grok Bot）。

## 三市下午总结

- 工作日约 16:44（Asia/Shanghai，港股收盘后）生成 `notes/YYYY-MM-DD-daily-summary.md`
- 覆盖 A股收盘 + 港股收盘 + 美股昨夜（及盘前如有）
- 必覆盖 `config/watchlist.md` Tier-1；Tier-2 仅异动
- push 后向用户发简体中文总结
