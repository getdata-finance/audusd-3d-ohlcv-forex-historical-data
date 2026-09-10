# AUDUSD 3d OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_722_rows-blue)](https://getdata.finance/datasets/audusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/audusd)

### -> [**Download the full AUDUSD dataset on getdata.finance**](https://getdata.finance/datasets/audusd)

**AUDUSD 3d OHLCV forex historical data** — ultra high-quality 3d OHLCV for **Australian Dollar / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3d OHLCV** for **Australian Dollar / US Dollar** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/audusd) · **1,722** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `AUDUSD_3d.csv` (244 rows, `2024-09-08` -> `2026-09-07`, 26.96 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/audusd)** — **1,722** `3d` rows (full `1m`: 5,263,475), **11 timeframes**, `2012-06-22` -> `2026-09-07`.

## Download sample

**[AUDUSD_3d.csv](https://github.com/getdata-finance/audusd-3d-ohlcv-forex-historical-data/blob/main/AUDUSD_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/audusd-3d-ohlcv-forex-historical-data/main/AUDUSD_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/audusd-3d-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/audusd-3d-ohlcv-forex-historical-data/](https://getdata-finance.github.io/audusd-3d-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/audusd](https://getdata.finance/datasets/audusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/audusd))** |
|---|--:|---|
| Instrument | Australian Dollar / US Dollar · Forex | Australian Dollar / US Dollar · Forex |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **1,722** |
| Size | 26.96 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Period | `2024-09-08` -> `2026-09-07` | `2012-06-22` -> `2026-09-07` |
| File | `AUDUSD_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Coverage report | — | [AUDUSD coverage](https://getdata.finance/coverage/audusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/audusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/audusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUDUSD_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-08T00:00:00+00:00 | 0.66674 | 0.6689 | 0.6641 | 0.66563 | 369245.10226 |
| 2024-09-11T00:00:00+00:00 | 0.66563 | 0.67327 | 0.66254 | 0.6701 | 659505.46366 |
| 2024-09-14T00:00:00+00:00 | 0.6707 | 0.67536 | 0.67013 | 0.67515 | 166466.99873 |
| 2024-09-17T00:00:00+00:00 | 0.67515 | 0.68361 | 0.67347 | 0.68117 | 789978.9018 |
| 2024-09-20T00:00:00+00:00 | 0.68117 | 0.68314 | 0.67856 | 0.68095 | 233641.28601 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-26T00:00:00+00:00 | 0.71641 | 0.72074 | 0.71555 | 0.71591 | 429657 |
| 2026-08-29T00:00:00+00:00 | 0.71518 | 0.71708 | 0.71518 | 0.71707 | 152077 |
| 2026-09-01T00:00:00+00:00 | 0.71707 | 0.7208 | 0.71213 | 0.71999 | 561626 |
| 2026-09-04T00:00:00+00:00 | 0.71999 | 0.72146 | 0.71732 | 0.72062 | 164185 |
| 2026-09-07T00:00:00+00:00 | 0.72062 | 0.72308 | 0.71976 | 0.72219 | 268279 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUDUSD_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUDUSD_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('AUDUSD_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **AUDUSD** archive on **[getdata.finance](https://getdata.finance/datasets/audusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,722** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full AUDUSD dataset on getdata.finance](https://getdata.finance/datasets/audusd)**

---
*GetData · AUDUSD 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/audusd)*
