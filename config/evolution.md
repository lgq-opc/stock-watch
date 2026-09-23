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
