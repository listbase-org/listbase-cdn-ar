# ListBase CDN — العربية (ar)

Open dataset collection for **العربية** (Arabic).
423 datasets across 14 categories with 146,179 total records.

> Browse and download at [https://listbase.org/ar/](https://listbase.org/ar/)

## Categories

| Category | Datasets |
|----------|----------|
| [ثقافة ودين (Culture & Religion)](culture/) | 6 |
| [تعليم (Education)](education/) | 2 |
| [بيئة (Environment)](environment/) | 2 |
| [المالية والتجارة (Finance & Trade)](finance/) | 76 |
| [طعام (Food & Nutrition)](food/) | 1 |
| [جغرافيا (Geography)](geography/) | 204 |
| [تاريخ (History)](history/) | 1 |
| [لغة (Language)](language/) | 1 |
| [مرجع (Reference)](reference/) | 64 |
| [رياضة (Sports)](sports/) | 5 |
| [تكنولوجيا (Technology)](tech/) | 2 |
| [الوقت والتقويم (Time & Calendar)](time/) | 18 |
| [سياحة (Tourism)](tourism/) | 1 |
| [نقل (Transport)](transport/) | 40 |

## Usage

### Browse on the web
Visit [listbase.org/ar/](https://listbase.org/ar/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.ar.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.ar.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.ar.listbase.org/geography/th-central-provinces_AR.xlsx
curl -O https://cdn.ar.listbase.org/geography/th-central-provinces_AR.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.ar.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.ar.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_AR.csv   # CSV download
│   └── {dataset}_AR.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
