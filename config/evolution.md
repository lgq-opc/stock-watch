# 盯盘自进化笔记

由「股市盯盘与三市总结」技能每轮追加。顶部「现行改进」为已验证、下轮必须遵守的短规则。

## 现行改进

-（尚无；首轮跑完后从下方条目提升）

---

## 运行日志

## 2026-09-23 16:55 · daily-summary
- 有效：Yahoo chart API（curl）补齐 yfinance 空 Close；新浪 hq 交叉核对港股/A股；美股用 metaPrice + 公开收盘页互证。
- 摩擦：① 四波例行从未跑过，无当日分波笔记可复用；② 智谱 `02513.HK` 在 yfinance history 为空，需改 chart/`2513.HK`；③ 美股 9/22 Yahoo history Close=NaN（有量），不能单信 history。
- 下轮试行：取数脚本优先 `query1.../chart` + 新浪 hq 双源；智谱固定用 `2513.HK` chart。
- 已自审：Tier-1 全覆盖；未编造；涨跌方向已核对；新闻标「转述/未证实」；无矛盾早前笔记（无）；文末免责已写。

## 2026-09-24 08:15 · intraday
- 有效：Yahoo chart + 新浪 hq 双源；美股 9/23 Close=NaN 时用 metaPrice 并对 Exa/TradingKey；韩股节前休市用公开报道判定，不硬拉实时。
- 摩擦：① 韩股 08:00 CST 已过首尔开盘点但无 9/24 bar（实为추석休市）；② A 股涨跌% 本波复用 9/23 日终总结以免 Yahoo prevClose 漂移；③ 美股涨跌必须相对历史 Close 手算，勿信 chartPreviousClose。
- 下轮试行：08:00 波先查韩/港/A 是否交易日（节假日表或「无当日 bar」），休市市场只写昨收一行。
- 已自审：Tier-1 全覆盖（亚盘未开用昨收，韩股标休市）；未编造；美股方向已与 TradingKey 核对；新闻标转述；与 9/23 日终无矛盾；免责已写。
