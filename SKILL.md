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

Recent additions to preserve in future analyses:

- `模式切换优先`: first decide whether the tape has switched regime; do not reuse yesterday's playbook automatically.
- `单边下跌里的小V`: in a one-way down tape, the trade is often `急跌吸 -> 小V先出一半 -> 夜盘/下一波再看是否接回`, not blind diamond-hands.
- `3:30 pm 尾盘确认`: tail-session structure is a core filter; when the day tends to end near the low, earlier hero entries carry less edge.
- `真空期 vs 落地日`: event windows can have a relatively safer "nothing-happens-yet" session before the real decision day; distinguish pre-event calm from post-event distribution risk.
- `被动减是时间窗`: passive-reduction is not just a headline; treat it as a multi-session window where gap fills, lower retests, and phased rebuilding matter more than chasing the first rebound.
- `被动减前先规避`: if a passive-reduction window is near and the catalyst result is still unknown, default to `先不做/只留底仓`, then reassess after the first real outcome.
- `周内节奏记忆`: treat `周一周二 / 周三 / 周四周五 / 周末夜盘` as a live rhythm hypothesis when the same tape behavior keeps repeating, but invalidate it quickly if the week breaks pattern.
- `亚洲先行链`: `韩国/A股/港股 -> 夜盘 -> 盘前 -> 美股开盘` can act as a lead-lag filter for risk appetite, especially in macro- or crypto-sensitive tapes.
- `开盘冲高与尾盘强平`: many tapes have `开盘前30-60分钟冲高减` and `3:00-3:30 pm 强平小V吸` behavior; use these as execution windows, not blind signals.
- `转弯/直线语言`: distinguish `直线拉升可分批减` from `转弯确认再回吸`; the framework should preserve this tape-reading vocabulary in reusable form.
- `结果驱动，不赌过程`: for talks, votes, and weekend speeches, separate `等待结果` from `结果落地后再选方向`; many sessions are best handled with reduced risk or only a base position.
- `IPO价差失真不参与`: if IPO pricing, auction pricing, or access tiers create an obviously unfair ladder, prefer `不参与` over chasing after listing.

## Required Safety Rules

- For `current` / `today` / `latest` prices, news, earnings, Fed events, calendars, or options data, verify with current sources first.
- Output `price zones + conditions`, not unconditional instructions.
- If key data is missing, state what is missing and switch to a conditional framework.
- Always include `失效条件`, `不追价区`, and `仓位约束`.
- Treat leveraged ETFs, crypto-related equities, and options as high-volatility instruments.
- If the setup depends on earnings, dilution, insider selling, lockup, macro speeches, holidays, or monthly expiration, say that the framework can be invalidated by event flow.
- If using channel/chat-derived rules, convert them into reusable conditions; do not repeat stale one-day prices as current instructions.

## Core Use Pattern

Read [references/framework.md](references/framework.md) when the user wants a full explanation, a learning plan, a deep review, or the full ZhaoGe methodology.

Default analysis order:

1. Classify the instrument and timeframe.
2. Decide whether the market is `存量震荡 / 单边下跌 / 事件驱动 / 情绪过热`.
3. Find `第一低点 L1`, but do not assume it is the final low.
4. Check whether tail-session behavior, especially after `3:30 pm` local market time, supports stabilization.
5. Wait for `二次握手`: a second pullback near `L1` that does not effectively break it.
6. Check whether there is a gap, passive-reduction window, weekend risk, or known selling-overhang event.
7. Confirm with index, sector, leaders, turnover, night/pre-market, and event context.
8. Scale by phases; do not let one name dominate the account.

Regime notes:

- `存量震荡`: intraday reversals can be tradable; small pullbacks and open retests matter more.
- `单边下跌`: assume the first drop is not enough; late-day confirmation and next-session retest matter more than early dip-buying.
- `事件驱动`: separate `预期阶段 / 真空期 / 落地日 / 落地后分配期`.
- `情绪过热`: treat strong pops as potential inventory distribution unless they can digest and reclaim.

## Non-Negotiable Trading Logic

- Do not rush into the first drop.
- First low is for `记录` first, not for full-size entry.
- Tail-session confirmation matters more than intraday noise.
- No second handshake, no confident add.
- In a single-side downtrend, late entries are usually safer than early hero trades.
- In a single-side downtrend, do not confuse a small intraday V with a full regime repair.
- If the tape is `单边下跌 + 尾盘继续走弱`, default to `先等确认` over averaging down.
- In a choppy market, prefer stock or smaller sizing over short-dated options.
- If price already bounced far away from `L1` without retest, mark it `不追，等回踩`.
- For names with selling-overhang, dilution, insider/fund trimming, or post-catalyst distribution risk, focus on lower gaps and retests; do not buy strength just because the story is good.
- In a slow bull tape, prefer simple pullbacks at/near the open over complicated late chase entries.
- Before weekends or holidays, reduce the burden of proof for avoiding new risk; if crypto or futures continue trading while stocks are closed, use the next session to confirm.
- If a binary result will only be knowable after local market close or after a weekend speech, treat the session as `真空期` first and raise the bar for new entries.

## Tactical Pattern Rules

Use these as conditional patterns, not fixed signals:

- `被动减/节日减仓`: after a strong event-driven high, assume US funds may reduce around holiday or passive-flow windows. Prefer taking strength first, then watch whether the passive-reduction gap is filled before rebuilding.
- `被动减时间窗`: when a catalyst date overlaps with holiday flow, policy uncertainty, fund rebalance, or forced/passive selling, think in a `multi-day to multi-week` window rather than one candle. The first drop may only open the window.
- `减持/出货标的`: random intraday sell pressure can appear on rallies. Mark the first and second lower gaps, wait near gap-fill zones, and prefer stock over leveraged ETFs or options on the first bad-news day.
- `缺口回补`: a near-fill is not a full fill. If the low stops just above the gap, label it `接近缺口` and wait for the next event, retest, or tail-session reclaim before treating it as complete.
- `财报堆高出货`: when a name rallies into earnings or rises on non-operating news while fundamentals are weak, treat the first pop as inventory-distribution risk. Wait for post-event digestion or a lower reclaim.
- `慢牛开盘回踩`: in a narrowing slow-bull tape, the cleaner buy point is often the open pullback. If missed and price has already lifted far from the pullback, mark `不追`.
- `单边下跌小V`: in a one-way down tape, a usable play is often `急跌试探 -> 小V减半 -> 等夜盘/次日再判断`, instead of converting immediately into a swing thesis.
- `3:30最低点记忆`: if the market repeatedly prints late-session lows around `3:30 pm` or later, treat that as a live pattern memory. Demand stronger evidence before calling the low early.
- `真空期安全感`: when a major event has not yet resolved, the session before the resolution can sometimes be calmer than the resolution day itself. Do not treat that calm as proof that the post-event tape is safe.
- `结果后再做`: when talks, policy votes, or leadership speeches have not yet produced a usable conclusion, default to `等结果，不抢跑`; after the result, trade the first clean direction instead of the rumor phase.
- `币圈预警`: for crypto-related equities, BTC/ETH turning points and straight-line warning moves are leading context. A first crypto alert often needs repeat testing; use Monday or the next equity session for second confirmation after weekend movement.
- `投票机制分阶段`: treat `第一阶段通过` and `最终通过` as different states. Stage one can create a relief move, but it does not automatically complete the thesis.
- `投票失败未必最难做`: in repeated crypto-policy tapes, a failed vote can reset price toward old support and restore the previous swing template rather than making the name untradeable.
- `只做弹性大`: when market opportunity narrows, prioritize liquid names with obvious elasticity and clear catalysts; avoid unrelated consumer/defensive names when the macro input hurts their demand or margins.
- `硬件强于软件`: if AI capex, export approvals, or data-center headlines are the active driver, prefer chips, infra, and hardware elasticity; many software names need separate proof and should not be assumed to follow.
- `先调整先到位`: when a basket is rolling over together, the name that started adjusting earlier can reach a usable zone earlier; laggards may still have room to fall.
- `整数位/事件高点`: large round numbers and obvious event highs should be treated as candidate distribution or control zones, not automatically as breakout proof.
- `周内节奏`: if the same environment repeatedly shows `周一周二偏修复 / 周三看讲话 / 周四周五偏回调`, keep it as a working rhythm, but only until price action breaks it.
- `亚洲先行观察`: when macro tension is driving the tape, compare `韩国/A股/港股` open-to-close behavior with US night/pre-market. `低开低走` and `低开高走` imply different US execution plans.
- `A股港股提前规避`: when Asia cash markets sell first because they cannot wait for late headlines, treat that as an early warning rather than dismissing it because US equities are still holding.
- `开盘冲高减 / 尾盘强平吸`: after panic sessions or passive-reduction windows, an opening squeeze can be for trimming, while the better rebuy often comes near forced-liquidation timing late in the session.
- `直线转弯`: a straight-line move into resistance is often a partial-take-profit zone; a meaningful `转弯` after retest is stronger than a mid-move guess.
- `低吸两份，冲高卖一份`: when the tape is still tradable but not fully repaired, use phased inventory management instead of all-in/all-out thinking.
- `重复敞口择一`: when two vehicles express nearly the same catalyst exposure, prefer the cleaner or more liquid one rather than doubling risk through duplicated proxies.

## Market Context Checklist

Before giving buy zones, check:

- Instrument type: stock / ETF / leveraged ETF / crypto-related equity / option
- Timeframe: intraday / swing / event trade / earnings trade
- Current price, recent low, and recent bounce distance from low
- `QQQ / SPY / sector / leaders` direction
- Whether `QQQ` is weaker than `SPY` or leaders are weakening faster than the broad tape
- Seven sisters behavior when analyzing US tech
- Whether crypto is acting as a risk-on / risk-off leading indicator
- Turnover / volume reversal quality
- Tail-session behavior
- Night session / pre-market behavior
- Whether `韩国 / A股 / 港股` are leading risk appetite or confirming a reversal
- Whether the market is still in `结果未落地的真空期`
- Earnings, dilution, lockup, insider/fund selling, passive reduction, Fed speech, holiday, option expiration
- Whether a catalyst is `单次结果` or `多阶段投票/多轮讲话`
- Gaps below/above current price and whether each gap is fully filled or only nearly touched
- Weekend/holiday exposure and whether futures or crypto will keep trading while equities are closed
- Options activity and IV: whether large money is still active in options or has shifted back to stock
- Existing position, core-vs-trading inventory, and cash reserve if provided

## Decision Levels

- `回避`: active bad news, dilution risk, repeated breakdowns, major index weakness, or missing context
- `观察`: first drop happened, but no valid low or no valid second test
- `试探`: first low appears and market context is stabilizing; only small size
- `等二次握手`: first bounce happened; wait for retest near `L1`, especially if the first bounce came inside a one-way down tape
- `确认后小仓`: second handshake holds and index/sector/tail-session/turnover agree
- `失效`: retest breaks down, leaders confirm weakness, gap-fill fails, or event risk changes the trade

## Price-Zone Heuristics

Use these defaults only when the user has not provided a better rule:

- `L1`: the meaningful intraday or recent swing low after a sharp drop
- `二次回踩区`:
  - ordinary large-cap stocks: `L1` to `L1 + 1.5%`
  - leveraged ETFs / crypto-related equities: `L1` to `L1 + 3%`
- `试探区`: near `L1`, only if the broader market is no longer accelerating lower
- `确认区`: after second handshake holds and price starts reclaiming intraday reference levels; late-session reclaim is stronger than midday noise
- `失效价`: clear break below `L1`, especially with index/sector weakness and failed reclaim
- `不追价区`: any fast rebound materially above the retest zone without a second test
- `缺口回补区`: lower gap zone for selling-overhang names. Treat exact fill/reclaim as stronger than a near-touch.
- `事件高点区`: strong post-catalyst rally into expected passive reduction, holiday risk, or distribution; prefer trimming/reviewing risk over adding.

For high-volatility names, widen the zone and reduce the size. Do not widen the zone and keep the same size.

## Position-Sizing Defaults

- First touch / first test: `轻仓试探`
- Second handshake confirmed: add only in phases, not all at once
- Single name default ceiling: do not let one name dominate the account
- Separate `主仓` and `T仓` when the user is already holding
- In unstable but tradable tapes, a useful default is `低吸的仓位先按一部分做T，一部分保留观察`, rather than deciding everything with one order
- If the trade is driven by event uncertainty, keep more cash than usual
- In binary event windows, `2-3成底仓 + 结果后再决策` is often cleaner than trying to optimize every rumor swing
- If the name is a leveraged ETF or crypto-related equity, reduce size relative to ordinary large caps
- If the instrument is options, size smaller again
- For selling-overhang or first-day bad-news setups, default to `先正股、再分批`; avoid leveraged versions until the gap/retest structure is clear.
- A rough tactical ceiling like `三成左右` can be used only when the user asks for aggressive trading and confirms risk tolerance; otherwise keep the default lighter.
- For intraday trades after sharp drops, require an exit plan before the close unless the setup has converted into a confirmed swing.
- In `单边下跌小V` trades, default to `先当日T思维`, not automatic overnight conviction.

## Options Rules

When the setup involves options:

- First answer whether options are suitable at all.
- Avoid short-dated options unless the user explicitly wants day trading and understands the risk.
- Default carry preference: expiration at least two months away.
- Avoid sawtooth/choppy markets because time decay can dominate.
- Discuss IV explicitly when relevant.
- If IV is high and options volume dries up or large money shifts to stock, say stock is preferred.
- For intraday options, require an explicit stop and very small size.
- If the underlying has not confirmed a second handshake, be stricter with options than with stock.

## Instrument Bias Notes

- `TSLL / TSLA`: more sensitive to Tesla, QQQ, event rhythm, fund/passive-flow windows, sales data, and turnover; better after large drops than after small dips. In slow-bull mode, open pullbacks are cleaner than late chase. Intraday sharp-drop trades need a close plan.
- `CRWV / IREN / CIFR`-style elastic names: often better for `急跌吸 + V减半` than for passive holding through unclear event windows; keep them in the `弹性日内 / 轻仓隔夜` bucket unless the broader tape confirms.
- `SOXL / leveraged ETFs`: wider swings, smaller size, stricter chase discipline
- `Crypto-related equities`: watch BTC/ETH direction, crypto turnover, weekend behavior, alert/retest behavior, and gap/reclaim structure
- `Crypto vote names`: separate `第一阶段投票博弈` from `最终立法博弈`; a stage-one pass can justify relief, while failure can mean a reset toward old support and another swing cycle.
- `Macro-sensitive or war-headline tapes`: compare BTC with `韩国/A股/港股` and US pre-market; if all lead markets stay weak, demand more patience before calling a low.
- `Selling-overhang names`: LITE/HOOD-style patterns should prioritize lower gaps, full gap-fill quality, and random rally selling risk.
- `Event-pop names`: IREN/RKLB-style earnings or partnership pops can be distribution first and buyable only after digestion/reclaim.
- `Hardware / export-license themes`: when export approvals or capex headlines hit, treat chip, infra, and data-center names as the primary expression; slower software names need separate proof.
- `Policy-dependent names`: SOFI-style edge sectors need policy support or a return near the low; otherwise keep at `观察`.
- `Slow-bull large caps`: when several large caps are all weak, pick one clear oversold leader rather than scattering across many similar names.
- `Seven sisters / US tech leaders`: use them as confirmation, not as decoration
- `New issues / small caps`: raise the burden of proof; event and liquidity risk matter more. If auction pricing is clearly unfair or too far from indicated value, default to `不参与`.

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
- 缺口/事件区：

确认条件：
- 大盘/QQQ/SPY：
- 板块/七姐妹/龙头：
- 亚洲先行链：
- 真空期/落地日：
- 成交额/量能：
- 尾盘：
- 夜盘/盘前：
- 事件：
- 期权成交/IV：

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
- 亚洲先行链有没有转弱/转强
- 当前是在等结果，还是结果已落地
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
- 周内所处节奏
- 是第几阶段投票/哪一类讲话
- 盘前反应
- 盘中是否转弯
- 是否需要等三日消化
- 是否存在被动减、减持、缺口回补或周末/节日风险

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

When relevant, explicitly say:

- `现在是哪种模式`
- `这更像日内T，还是能转成波段`
- `如果今天尾盘继续弱，为什么不能抢早`

Avoid vague encouragement. Avoid saying `可以买` unless the exact conditions are stated.
