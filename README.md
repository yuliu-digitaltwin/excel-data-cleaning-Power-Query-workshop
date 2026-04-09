# Excel Data Cleaning Workshop

## Overview
This project provides a ready-to-use Excel Power Query template that automatically cleans messy CSV/Excel files. It removes duplicates, standardizes formats, fixes errors, and generates a cleaning log.

**Perfect for:** Upwork portfolio, freelancer showcase, or internal team use.

---

## Requirements

| Platform | Minimum Version |
|----------|-----------------|
| Windows Excel | 2016 or later |
| Mac Excel | 365 (version 16.57 or later) |

> ⚠️ Power Query is NOT available in Excel 2013 or earlier, or Mac Excel 2019.

---

## What This Template Cleans

| Problem | Solution |
|---------|----------|
| Duplicate rows | Removed by CustomerID |
| Missing email | Row deleted |
| Missing name | Filled with "Unknown" |
| Inconsistent case (john/JOHN) | Proper Case (John Smith) |
| Mixed date formats | YYYY-MM-DD |
| Messy phone numbers | +86 XXX XXXX XXXX |
| Negative amounts | Converted to absolute value |
| Outliers (>10000) | Flagged as "Yes" |
| Inconsistent status (Done/Finished) | Unified to "Completed" |

---

## File Structure
excel-data-cleaning-workshop/
├── README.md ← This file
├── raw_data_dirty.xlsx ← Sample dirty data (50 rows)
├── clean_data.xlsx ← Cleaned result example
├── cleaning_log.xlsx ← Cleaning log example
├── data_cleaning_template.xlsx ← Power Query template
└── docs/
├──── cleaning_steps.md ← Technical cleaning steps
└──── power_query_guide.md ← End-user tutorial

text

---

## Quick Start

### 1. Download the template
- Download `data_cleaning_template.xlsx`

### Step 2: Set up the FolderPath (IMPORTANT!)

The template needs to know where your files are located.

**What to do:**

1. Click the **ConfigTable** worksheet tab (at the bottom of Excel)

2. You will see this table:

| Parameter | Value |
|-----------|-------|
| FolderPath | (empty) |

3. Click on the empty cell under **Value** (cell B2)

4. Enter the folder path where your files are located:

   **Windows example:**
D:\YourExcelDirectory\

### 3. First-time setup (2 minutes)
- Go to **Data** tab → Click **Queries & Connections**
- Right-click `GetCleanData` → **Load To** → **Table** → **New worksheet** → **OK**
- Right-click `GetCleaningLog` → **Load To** → **Table** → **New worksheet** → **OK**
- Check `GetCleanData` and `GetCleaningLog` worksheets

---

## Files Included

| File | Description |
|------|-------------|
| `raw_data_dirty.xlsx` | Sample dirty data with 50 rows, 8 columns, 6 types of problems |
| `clean_data.xlsx` | Expected output after cleaning |
| `cleaning_log.xlsx` | Log showing what was fixed |
| `data_cleaning_template.xlsx` | Power Query template - use this on your own data |

---

## Documentation

| Document | Purpose |
|----------|---------|
| `docs/power_query_guide.md` | **End-user guide** - How to use the template |
| `docs/cleaning_steps.md` | **Technical reference** - Each cleaning step explained |

---

## Upwork Proposal Template

Use this when bidding on data cleaning jobs:

> *"I have a ready-to-use Excel Power Query template that cleans messy CSV/Excel files in one click. It removes duplicates, standardizes dates/phones/names, handles missing values, flags outliers, and generates a cleaning log. I can deliver clean, analysis-ready data within 24 hours. Demo: [GitHub Link]"*

---

## Keywords for Job Search

- data cleaning Excel
- data formatting
- deduplicate CSV
- clean up spreadsheet
- Power Query data transformation

---

## License

MIT
