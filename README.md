# COPPER 30m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-174_652_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full COPPER dataset on ork.ad**](https://ork.ad/)

**COPPER 30m OHLCV Commodities historical data** — ultra high-quality 30m OHLCV for **Copper**. Extended-session energy and industrial metals — beyond US cash hours. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 30m OHLCV** for **Copper** (Commodities)
- **Extended-session energy and industrial metals — beyond US cash hours**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **174,652** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `COPPER_30m.csv` (8,744 rows, `2025-10-03` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **174,652** `30m` rows (~8.84 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2011-08-28` → `2026-07-03`.

## Download sample

**[COPPER_30m.csv](https://github.com/ork-ad/copper-30m-ohlcv-commodities-historical-data/blob/main/COPPER_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/copper-30m-ohlcv-commodities-historical-data/main/COPPER_30m.csv)) · [GitHub Releases](https://github.com/ork-ad/copper-30m-ohlcv-commodities-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/copper-30m-ohlcv-commodities-historical-data/](https://ork-ad.github.io/copper-30m-ohlcv-commodities-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Copper · Commodities | Copper · Commodities |
| Timeframes | `30m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 30m rows | 8,744 | **174,652** |
| Size | 0.46 MB | ~8.84 MB |
| Period | `2025-10-03` → `2026-07-03` | `2011-08-28` → `2026-07-03` |
| File | `COPPER_30m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`30m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `30m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`COPPER_30m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-03T16:30:00Z | 5.1094 | 5.1138 | 5.0972 | 5.1073 | 1187.0 |
| 2025-10-03T17:00:00Z | 5.1073 | 5.1183 | 5.1011 | 5.1131 | 942.0 |
| 2025-10-03T17:30:00Z | 5.1131 | 5.1193 | 5.0813 | 5.0868 | 1134.0 |
| 2025-10-03T18:00:00Z | 5.0868 | 5.0968 | 5.0741 | 5.0954 | 740.0 |
| 2025-10-03T18:30:00Z | 5.0954 | 5.0983 | 5.0829 | 5.0848 | 400.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T14:30:00Z | 6.2191 | 6.2234 | 6.2098 | 6.2202 | 928.0 |
| 2026-07-03T15:00:00Z | 6.2202 | 6.226 | 6.2064 | 6.2072 | 883.0 |
| 2026-07-03T15:30:00Z | 6.2072 | 6.2092 | 6.2017 | 6.2081 | 604.0 |
| 2026-07-03T16:00:00Z | 6.2081 | 6.218 | 6.2074 | 6.2152 | 455.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('COPPER_30m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('COPPER_30m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('COPPER_30m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **COPPER** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **174,652** rows at `30m`, plus all other timeframes in the same ZIP.

**[→ Get the full COPPER dataset on ork.ad](https://ork.ad/)**

---
*GetData · COPPER 30m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*