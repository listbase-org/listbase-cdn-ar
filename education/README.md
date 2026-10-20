# تعليم (Education)

2 datasets — 86 records

> Browse at [listbase.org/ar/education/](https://listbase.org/ar/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Saudi Arabia — Universities (جامعات)](ar-jamiat.json) | 63 | 20 KB | [CSV](ar-jamiat_AR.csv) | [Excel](ar-jamiat_AR.xlsx) | [View](https://listbase.org/ar/education/ar-jamiat/) |
| [المدارس في المملكة العربية السعودية (Schools of Saudi Arabia)](ar-sa-madaris.json) | 23 | 11 KB | [CSV](ar-sa-madaris_AR.csv) | [Excel](ar-sa-madaris_AR.xlsx) | [View](https://listbase.org/ar/education/ar-sa-madaris/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.ar.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.ar.listbase.org/education/ar-jamiat.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ar/education/)
