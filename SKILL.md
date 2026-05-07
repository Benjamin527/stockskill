---
name: zhaogeskill
description: Use when analyzing stocks, ETFs, leveraged ETFs, crypto-related equities, or options with a ZhaoGe-style trading-learning framework, especially buy zones, second-handshake confirmation, tail-session entries, event-risk filters, T-plus-trading rhythm, and position sizing.
---

# zhaogeskill

## Purpose

Use this skill to turn a market idea into a ZhaoGe-style decision frame:

- `回避`
- `观察`
- `试探`
- `等二次握手`
- `确认后小仓`
- `失效`

This is a trading-learning framework, not a signal service. Do not promise returns. Do not present any price as guaranteed. Do not encourage oversized or emotional trades.

## Required Safety Rules

- For `current` / `today` / `latest` prices, news, earnings, Fed events, calendars, or options data, verify with current sources first.
- Output `price zones + conditions`, not unconditional instructions.
- If key data is missing, state what is missing and switch to a conditional framework.
- Always include `失效条件`, `不追价区`, and `仓位约束`.
- Treat leveraged ETFs, crypto-related equities, and options as high-volatility instruments.
- If the setup depends on earnings, dilution, insider selling, lockup, macro speeches, holidays, or monthly expiration, say that the framework can be invalidated by event flow.

## Core Use Pattern

Read [references/framework.md](references/framework.md) when the user wants a full explanation, a learning plan, a deep review, or the full ZhaoGe methodology.

Default analysis order:

1. Classify the instrument and timeframe.
2. Decide whether the market is `存量震荡 / 单边下跌 / 事件驱动 / 情绪过热`.
3. Find `第一低点 L1`, but do not assume it is the final low.
4. Check whether tail-session behavior, especially after `3:30 pm` local market time, supports stabilization.
5. Wait for `二次握手`: a second pullback near `L1` that does not effectively break it.
6. Confirm with index, sector, leaders, turnover, night/pre-market, and event context.
7. Scale by phases; do not let one name dominate the account.

## Non-Negotiable Trading Logic

- Do not rush into the first drop.
- First low is for `记录` first, not for full-size entry.
- Tail-session confirmation matters more than intraday noise.
- No second handshake, no confident add.
- In a single-side downtrend, late entries are usually safer than early hero trades.
- In a choppy market, prefer stock or smaller sizing over short-dated options.
- If price already bounced far away from `L1` without retest, mark it `不追，等回踩`.

## Market Context Checklist

Before giving buy zones, check:

- Instrument type: stock / ETF / leveraged ETF / crypto-related equity / option
- Timeframe: intraday / swing / event trade / earnings trade
- Current price, recent low, and recent bounce distance from low
- `QQQ / SPY / sector / leaders` direction
- Seven sisters behavior when analyzing US tech
- Whether crypto is acting as a risk-on / risk-off leading indicator
- Turnover / volume reversal quality
- Tail-session behavior
- Night session / pre-market behavior
- Earnings, dilution, lockup, insider selling, Fed speech, holiday, option expiration
- Existing position, core-vs-trading inventory, and cash reserve if provided

## Decision Levels

- `回避`: active bad news, dilution risk, repeated breakdowns, major index weakness, or missing context
- `观察`: first drop happened, but no valid low or no valid second test
- `试探`: first low appears and market context is stabilizing; only small size
- `等二次握手`: first bounce happened; wait for retest near `L1`
- `确认后小仓`: second handshake holds and index/sector/tail-session/turnover agree
- `失效`: retest breaks down, leaders confirm weakness, or event risk changes the trade

## Price-Zone Heuristics

Use these defaults only when the user has not provided a better rule:

- `L1`: the meaningful intraday or recent swing low after a sharp drop
- `二次回踩区`:
  - ordinary large-cap stocks: `L1` to `L1 + 1.5%`
  - leveraged ETFs / crypto-related equities: `L1` to `L1 + 3%`
- `试探区`: near `L1`, only if the broader market is no longer accelerating lower
- `确认区`: after second handshake holds and price starts reclaiming intraday reference levels
- `失效价`: clear break below `L1`, especially with index/sector weakness and failed reclaim
- `不追价区`: any fast rebound materially above the retest zone without a second test

For high-volatility names, widen the zone and reduce the size. Do not widen the zone and keep the same size.

## Position-Sizing Defaults

- First touch / first test: `轻仓试探`
- Second handshake confirmed: add only in phases, not all at once
- Single name default ceiling: do not let one name dominate the account
- Separate `主仓` and `T仓` when the user is already holding
- If the trade is driven by event uncertainty, keep more cash than usual
- If the name is a leveraged ETF or crypto-related equity, reduce size relative to ordinary large caps
- If the instrument is options, size smaller again

## Options Rules

When the setup involves options:

- First answer whether options are suitable at all.
- Avoid short-dated options unless the user explicitly wants day trading and understands the risk.
- Default carry preference: expiration at least two months away.
- Avoid sawtooth/choppy markets because time decay can dominate.
- Discuss IV explicitly when relevant.
- For intraday options, require an explicit stop and very small size.
- If the underlying has not confirmed a second handshake, be stricter with options than with stock.

## Instrument Bias Notes

- `TSLL / TSLA`: more sensitive to Tesla, QQQ, event rhythm, and turnover; better after large drops than after small dips
- `SOXL / leveraged ETFs`: wider swings, smaller size, stricter chase discipline
- `Crypto-related equities`: watch BTC/ETH direction, crypto turnover, weekend behavior, and gap/reclaim structure
- `Seven sisters / US tech leaders`: use them as confirmation, not as decoration
- `New issues / small caps`: raise the burden of proof; event and liquidity risk matter more

## Preferred Output Formats

### A. Buy-Zone Analysis

Use this when the user asks `什么时候能买`, `什么价格可以买`, `哪里试探`, or similar:

```text
结论分级：
- 回避 / 观察 / 试探 / 等二次握手 / 确认后小仓 / 失效

关键价格：
- 第一低点 L1：
- 二次回踩区：
- 试探区：
- 确认区：
- 失效价：
- 不追价区：

确认条件：
- 大盘/QQQ/SPY：
- 板块/七姐妹/龙头：
- 成交额/量能：
- 尾盘：
- 夜盘/盘前：
- 事件：

仓位：
- 首次试探：
- 二次确认：
- 主仓/T仓：
- 期权限制：

风险：
- 哪些情况说明判断失败
- 哪些新闻或事件需要暂停
```

### B. Existing Position Review

Use this when the user already holds the name:

```text
持仓判断：
- 先减风险 / 继续观察 / 留主仓做T / 只做防守 / 失效离场

你现在最该看：
- 大盘与板块是否同步
- 当前价相对 L1 的位置
- 是否已经出现二次握手
- 尾盘和夜盘是否支持回补

操作框架：
- 主仓：
- T仓：
- 不能做的事：
- 失效条件：
```

### C. Event or Earnings Setup

Use this when the user asks around earnings, dilution, lockup, or macro risk:

```text
事件判断：
- 可以观察 / 只轻仓博弈 / 等落地 / 回避

关键变量：
- 市场原预期
- 实际结果或消息强度
- 盘前反应
- 盘中是否转弯
- 是否需要等三日消化

风险控制：
- 仓位上限
- 是否禁用期权
- 哪些条件下不能硬抗
```

## Response Style

Be direct and operational. Use Chinese by default.

- Start with a one-line conclusion.
- Then give `价位区间 + 条件 + 仓位`.
- End with `失效条件 + 不追理由 + 风险控制`.

Avoid vague encouragement. Avoid saying `可以买` unless the exact conditions are stated.
