# Data Schema

Each CSV file in this directory follows the format:

```
date,ticker,source,value,unit,delta_pct
2026-06-12,LME_CASH_3M,LME,2450.00,USD/MT,-0.82
2026-06-12,SHFE_AL_FRONT,SHFE,19890,CNY/MT,0.15
2026-06-12,CHANGJIANG_CNY_MT,CJ,19850,CNY/MT,-0.20
2026-06-12,USD_CNY,ECB,7.2341,,0.05
```

FX rows use ticker = currency pair (e.g. USD_CNY), unit is empty, value is the mid-point rate.

Source API: `https://www.aluminium-china.com/api/prices/today.csv`
