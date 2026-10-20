# طعام (Food & Nutrition)

1 datasets — 51 records

> Browse at [listbase.org/ar/food/](https://listbase.org/ar/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [مطاعم دليل ميشلان في السعودية](ar-mataim-michelin-saudia.json) | 51 | 59 KB | [CSV](ar-mataim-michelin-saudia_AR.csv) | [Excel](ar-mataim-michelin-saudia_AR.xlsx) | [View](https://listbase.org/ar/food/ar-mataim-michelin-saudia/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.ar.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.ar.listbase.org/food/ar-mataim-michelin-saudia.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ar/food/)
