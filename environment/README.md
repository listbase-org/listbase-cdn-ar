# بيئة (Environment)

2 datasets — 494 records

> Browse at [listbase.org/ar/environment/](https://listbase.org/ar/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [محطات الطاقة في الدول العربية](ar-mahattat-altaqa.json) | 487 | 225 KB | [CSV](ar-mahattat-altaqa_AR.csv) | [Excel](ar-mahattat-altaqa_AR.xlsx) | [View](https://listbase.org/ar/environment/ar-mahattat-altaqa/) |
| [محطات الطاقة النووية في الدول العربية](ar-mahattat-nawawiya.json) | 7 | 7 KB | [CSV](ar-mahattat-nawawiya_AR.csv) | [Excel](ar-mahattat-nawawiya_AR.xlsx) | [View](https://listbase.org/ar/environment/ar-mahattat-nawawiya/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.ar.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.ar.listbase.org/environment/ar-mahattat-altaqa.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ar/environment/)
