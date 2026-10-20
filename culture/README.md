# ثقافة ودين (Culture & Religion)

6 datasets — 37,718 records

> Browse at [listbase.org/ar/culture/](https://listbase.org/ar/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [الأسماء العربية ومعانيها](ar-asmaa.json) | 37,080 | 7083 KB | [CSV](ar-asmaa_AR.csv) | [Excel](ar-asmaa_AR.xlsx) | [View](https://listbase.org/ar/culture/ar-asmaa/) |
| [متاحف في الدول العربية (Museums in Arab countries)](ar-matahif.json) | 342 | 74 KB | [CSV](ar-matahif_AR.csv) | [Excel](ar-matahif_AR.xlsx) | [View](https://listbase.org/ar/culture/ar-matahif/) |
| [Saudi Arabia — Museums (متاحف المملكة العربية السعودية)](ar-saudia-matahif.json) | 137 | 108 KB | [CSV](ar-saudia-matahif_AR.csv) | [Excel](ar-saudia-matahif_AR.xlsx) | [View](https://listbase.org/ar/culture/ar-saudia-matahif/) |
| [المساجد البارزة في المملكة العربية السعودية (Notable Mosques of Saudi Arabia)](ar-sa-masajid.json) | 106 | 40 KB | [CSV](ar-sa-masajid_AR.csv) | [Excel](ar-sa-masajid_AR.xlsx) | [View](https://listbase.org/ar/culture/ar-sa-masajid/) |
| [القلاع والحصون في المملكة العربية السعودية (Castles & Forts of Saudi Arabia)](ar-sa-qila.json) | 35 | 15 KB | [CSV](ar-sa-qila_AR.csv) | [Excel](ar-sa-qila_AR.xlsx) | [View](https://listbase.org/ar/culture/ar-sa-qila/) |
| [القصور في المملكة العربية السعودية (Palaces of Saudi Arabia)](ar-sa-qusur.json) | 18 | 10 KB | [CSV](ar-sa-qusur_AR.csv) | [Excel](ar-sa-qusur_AR.xlsx) | [View](https://listbase.org/ar/culture/ar-sa-qusur/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.ar.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.ar.listbase.org/culture/ar-asmaa.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ar/culture/)
