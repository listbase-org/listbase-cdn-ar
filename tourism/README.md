# سياحة (Tourism)

1 datasets — 167 records

> Browse at [listbase.org/ar/tourism/](https://listbase.org/ar/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [الفنادق في المملكة العربية السعودية (Hotels of Saudi Arabia)](ar-sa-fanadiq.json) | 167 | 54 KB | [CSV](ar-sa-fanadiq_AR.csv) | [Excel](ar-sa-fanadiq_AR.xlsx) | [View](https://listbase.org/ar/tourism/ar-sa-fanadiq/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.ar.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.ar.listbase.org/tourism/ar-sa-fanadiq.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ar/tourism/)
