# TradingView Pine Zones Indicators

This repository contains TradingView Pine Script indicators for visualizing order-block style zones, fair value gaps, tap/entry conditions, and XAUUSD-focused scalping zones.

## Included Indicators

### Smart Money Zones PRO

Full zone-mapping indicator for buy/sell zones, fair value gaps, target levels, breakouts, and session-filtered trading zones.

```text
indicators/smart-money-zones-pro.pine
```

### Krishna Simple OB Scalper - XAUUSD

Lightweight XAUUSD-focused order-block scalper. It detects the last opposite-color candle before a displacement candle, scores zone quality using FVG, volume, OB cleanliness, and displacement strength, then marks whether price has tapped a buy or sell zone.

```text
indicators/krishna-simple-ob-scalper-xauusd.pine
```

## What It Provides

- Buy and sell zone detection from pivot, displacement, and volume conditions
- Higher-timeframe zone support
- Zone grading based on volume strength
- Tap tracking to mark fresh, weak, or exhausted zones
- Fair Value Gap zones
- Optional breakout and breakdown labels
- Next-zone target line with RR filtering
- Dashboard showing active buy/sell zones, FVG count, sweep state, and break status

## How To Use

1. Open TradingView.
2. Open the Pine Editor.
3. Copy one of the scripts from:

```text
indicators/smart-money-zones-pro.pine
indicators/krishna-simple-ob-scalper-xauusd.pine
```

4. Paste it into Pine Editor.
5. Click **Save**.
6. Click **Add to chart**.
7. Adjust inputs such as volume multiplier, pivot bars, session filter, FVG size, and target RR.

## Best Use Case

This indicator is designed for chart review, liquidity-zone mapping, session analysis, and trade planning. It can help traders visually study where price may react around high-volume zones and fair value gaps.

## Important Note

This is not financial advice and does not guarantee profitable trades. It is a charting and analysis tool. Traders should backtest, forward-test, and use risk management before making trading decisions.

## Tech Stack

- Pine Script v5
- TradingView
- Technical analysis
- Market structure visualization
