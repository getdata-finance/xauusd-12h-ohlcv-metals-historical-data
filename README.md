# XAUUSD 12h OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-9_683_rows-blue)](https://getdata.finance/datasets/xauusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xauusd)

### -> [**Download the full XAUUSD dataset on getdata.finance**](https://getdata.finance/datasets/xauusd)

**XAUUSD 12h OHLCV metals historical data** — ultra high-quality 12h OHLCV for **Gold / US Dollar**. Global spot sessions — Asia, Europe and US coverage for precious metals trading. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **Gold / US Dollar** (Metals)
- **Global spot sessions — Asia, Europe and US coverage for precious metals trading**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/xauusd) · **9,683** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `XAUUSD_12h.csv` (327 rows, `2026-01-05` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/xauusd)** — **9,683** `1m` rows (~0.79 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2009-02-24` -> `2026-07-31`.

## Download sample

**[XAUUSD_12h.csv](https://github.com/getdata-finance/xauusd-12h-ohlcv-metals-historical-data/blob/main/XAUUSD_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xauusd-12h-ohlcv-metals-historical-data/main/XAUUSD_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/xauusd-12h-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xauusd-12h-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xauusd-12h-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xauusd](https://getdata.finance/datasets/xauusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xauusd))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Metals | Gold / US Dollar · Metals |
| Timeframes | `12h` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 327 | **9,683** |
| Size | 0.03 MB | ~0.79 MB |
| Period | `2026-01-05` -> `2026-07-31` | `2009-02-24` -> `2026-07-31` |
| File | `XAUUSD_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Coverage report | — | [XAUUSD coverage](https://getdata.finance/coverage/xauusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xauusd)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/xauusd) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-05T12:00:00+00:00 | 4419.16 | 4462.02 | 4396.15 | 4442.39 | 860773.5294246336 |
| 2026-01-06T00:00:00+00:00 | 4442.39 | 4477.68 | 4429.43 | 4465.33 | 564492 |
| 2026-01-06T12:00:00+00:00 | 4465.33 | 4504.75 | 4456.09 | 4497.63 | 608095.6610921038 |
| 2026-01-07T00:00:00+00:00 | 4497.63 | 4499.95 | 4445.45 | 4451.66 | 572095 |
| 2026-01-07T12:00:00+00:00 | 4451.66 | 4472.48 | 4427.6 | 4468.82 | 808640.5816864758 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-29T12:00:00+00:00 | 4042.795 | 4126.365 | 4005.965 | 4098.325 | 789186.8764333497 |
| 2026-07-30T00:00:00+00:00 | 4098.325 | 4106.695 | 4042.035 | 4091.215 | 590541 |
| 2026-07-30T12:00:00+00:00 | 4091.215 | 4133.475 | 4078.695 | 4119.015 | 497350.8967008328 |
| 2026-07-31T00:00:00+00:00 | 4119.015 | 4120.185 | 4063.415 | 4066.825 | 292323 |
| 2026-07-31T12:00:00+00:00 | 4066.825 | 4072.435 | 4034.265 | 4064.025 | 383472 |

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

df = pd.read_csv('XAUUSD_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAUUSD_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xauusd)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **9,683** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full XAUUSD dataset on getdata.finance](https://getdata.finance/datasets/xauusd)**

---
*GetData · XAUUSD 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xauusd) · 2026-08-05 UTC*
