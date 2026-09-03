# JPN225 1m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-5_192_657_rows-blue)](https://getdata.finance/datasets/jpn225) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/jpn225)

### -> [**Download the full JPN225 dataset on getdata.finance**](https://getdata.finance/datasets/jpn225)

**JPN225 1m OHLCV index historical data** — ultra high-quality 1m OHLCV for **Nikkei 225**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Nikkei 225** (Index)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/jpn225) · **5,192,657** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `JPN225_1m.csv` (55,440 rows, `2026-07-07` -> `2026-09-02`). **Full archive on [getdata.finance](https://getdata.finance/datasets/jpn225)** — **5,192,657** `1m` rows, **11 timeframes**, `2008-09-01` -> `2026-09-02`.

## Download sample

**[JPN225_1m.csv](https://github.com/getdata-finance/jpn225-1m-ohlcv-index-historical-data/blob/main/JPN225_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/jpn225-1m-ohlcv-index-historical-data/main/JPN225_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/jpn225))** |
|---|--:|---|
| Instrument | Nikkei 225 · Index | Nikkei 225 · Index |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **5,192,657** |
| Period | `2026-07-07` -> `2026-09-02` | `2008-09-01` -> `2026-09-02` |
| File | `JPN225_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/jpn225) |
| Coverage report | — | [JPN225 coverage](https://getdata.finance/coverage/jpn225) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/jpn225)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`JPN225_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-07T10:47:00+00:00 | 68421.47 | 68421.48 | 68396.96 | 68411.96 | 49 |
| 2026-07-07T10:48:00+00:00 | 68411.96 | 68431.48 | 68411.96 | 68421.98 | 32 |
| 2026-07-07T10:49:00+00:00 | 68421.98 | 68426.47 | 68371.96 | 68381.47 | 79 |
| 2026-07-07T10:50:00+00:00 | 68381.47 | 68401.48 | 68361.96 | 68401.48 | 58 |
| 2026-07-07T10:51:00+00:00 | 68401.48 | 68401.48 | 68376.98 | 68376.98 | 44 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:56:00+00:00 | 64344.01 | 64351.51 | 64296.51 | 64301.5 | 117 |
| 2026-09-02T01:57:00+00:00 | 64301.5 | 64301.51 | 64242 | 64246.5 | 76 |
| 2026-09-02T01:58:00+00:00 | 64246.5 | 64276.49 | 64241.99 | 64266.99 | 90 |
| 2026-09-02T01:59:00+00:00 | 64266.99 | 64306.51 | 64246.99 | 64291.5 | 57 |
| 2026-09-02T02:00:00+00:00 | 64291.5 | 64291.5 | 64257 | 64261.49 | 17 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full JPN225 archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full JPN225 dataset on getdata.finance](https://getdata.finance/datasets/jpn225)**
