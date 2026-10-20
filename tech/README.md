# تكنولوجيا (Technology)

2 datasets — 255 records

> Browse at [listbase.org/ar/tech/](https://listbase.org/ar/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [أعلام البلدان (إيموجي)](ar-buldan-emoji-aalam.json) | 249 | 41 KB | [CSV](ar-buldan-emoji-aalam_AR.csv) | [Excel](ar-buldan-emoji-aalam_AR.xlsx) | [View](https://listbase.org/ar/tech/ar-buldan-emoji-aalam/) |
| [المكتبات في المملكة العربية السعودية (Libraries of Saudi Arabia)](ar-sa-maktabat.json) | 6 | 5 KB | [CSV](ar-sa-maktabat_AR.csv) | [Excel](ar-sa-maktabat_AR.xlsx) | [View](https://listbase.org/ar/tech/ar-sa-maktabat/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.ar.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.ar.listbase.org/tech/ar-buldan-emoji-aalam.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ar/tech/)
