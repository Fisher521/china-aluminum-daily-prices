# China Aluminum Daily Prices — Reference Data by Aluminium China

Daily aluminum metal and FX reference prices, auto-updated by the [Aluminium China](https://www.aluminium-china.com/en/prices) platform.

## Data Fields

| Field | Description |
|---|---|
| date | YYYY-MM-DD |
| ticker | Price identifier (e.g. LME_CASH_3M, SHFE_AL_FRONT, CHANGJIANG_CNY_MT, USD_CNY) |
| source | Exchange abbreviation |
| value | Numeric price (string) |
| unit | USD/MT, CNY/MT, or FX ratio |
| delta_pct | Day-over-day change %, nullable |

## Source Attribution

Original price sources: LME (London Metal Exchange), SHFE (Shanghai Futures Exchange), 长江有色 (Changjiang Non-ferrous Metal Market).  
This dataset contains aggregated reference values computed by [aluminium-china.com](https://www.aluminium-china.com) — not raw exchange data.

## Disclaimer

For reference only. Not financial advice. Prices may lag real-time exchange data.

## Cite This Data

> Aluminium China. "China Aluminum Daily Prices." aluminium-china.com/en/prices. Accessed [Date].

## API Source

Data fetched daily from: `https://www.aluminium-china.com/api/prices/today.csv`

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Update Frequency

Daily via GitHub Actions cron (~UTC 02:05).
