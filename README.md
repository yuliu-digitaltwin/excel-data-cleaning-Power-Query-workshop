# Excel Data Cleaning Workshop(Excel/CSV files)

## Overview
This project provides a ready-to-use Excel Power Query template that automatically cleans messy CSV/Excel files. It removes duplicates, standardizes formats, fixes errors, and generates a cleaning log.

This template was originally built for my own use on Upwork — handling lightweight data cleaning gigs efficiently. It's also suitable for users with basic technical skills who want to clean their own data.

---

## Need Data Cleaning Services?

Based on this template, I also take **custom data cleaning projects**. I help businesses and freelancers clean messy Excel/CSV files quickly.If your data structure is different, or you need a tailored solution, feel free to contact me.

**What I offer:**
- Remove duplicates, fix missing values, standardize formats
- Deliver clean, analysis-ready data within 24 hours
- Custom Power Query or Python solutions

**Contact me:**
- 📧 Email: `liuyu.digitaltwin@outlook.com`
- 💼 Upwork: [upwork.com/freelancers/~01a0894654bb597848](https://www.upwork.com/freelancers/~01a0894654bb597848)
- ⏱️ Response time: Within 12 hours

**Or use this template for free** (see instructions in USER_GUIDE.md)

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

├── USER_GUIDE.md ← This file

├── raw_data_dirty.xlsx ← Sample dirty data (50 rows)

├── clean_data.xlsx ← Cleaned result example

├── cleaning_log.xlsx ← Cleaning log example

└── data_cleaning_template.xlsx ← Power Query template 
