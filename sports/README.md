# رياضة (Sports)

5 datasets — 100 records

> Browse at [listbase.org/ar/sports/](https://listbase.org/ar/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [الملاعب والمدن الرياضية في المملكة العربية السعودية (Stadiums & Sports Cities of Saudi Arabia)](ar-sa-malaib.json) | 30 | 15 KB | [CSV](ar-sa-malaib_AR.csv) | [Excel](ar-sa-malaib_AR.xlsx) | [View](https://listbase.org/ar/sports/ar-sa-malaib/) |
| [أندية كرة القدم المصرية (Egyptian football clubs)](ar-misr-andiyat-kurat-qadam.json) | 28 | 11 KB | [CSV](ar-misr-andiyat-kurat-qadam_AR.csv) | [Excel](ar-misr-andiyat-kurat-qadam_AR.xlsx) | [View](https://listbase.org/ar/sports/ar-misr-andiyat-kurat-qadam/) |
| [أندية كرة القدم السعودية (Saudi Arabian football clubs)](ar-sa-andiyat-kurat-qadam.json) | 21 | 8 KB | [CSV](ar-sa-andiyat-kurat-qadam_AR.csv) | [Excel](ar-sa-andiyat-kurat-qadam_AR.xlsx) | [View](https://listbase.org/ar/sports/ar-sa-andiyat-kurat-qadam/) |
| [أندية كرة القدم المغربية (Moroccan football clubs)](ar-maghreb-andiyat-kurat-qadam.json) | 16 | 6 KB | [CSV](ar-maghreb-andiyat-kurat-qadam_AR.csv) | [Excel](ar-maghreb-andiyat-kurat-qadam_AR.xlsx) | [View](https://listbase.org/ar/sports/ar-maghreb-andiyat-kurat-qadam/) |
| [أندية كرة القدم التونسية (Tunisian football clubs)](ar-tunis-andiyat-kurat-qadam.json) | 5 | 4 KB | [CSV](ar-tunis-andiyat-kurat-qadam_AR.csv) | [Excel](ar-tunis-andiyat-kurat-qadam_AR.xlsx) | [View](https://listbase.org/ar/sports/ar-tunis-andiyat-kurat-qadam/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.ar.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.ar.listbase.org/sports/ar-sa-malaib.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/ar/sports/)
