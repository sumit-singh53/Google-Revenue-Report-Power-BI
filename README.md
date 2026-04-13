<p align="center">
  <img src="revenue.png" width="100%" alt="Google Revenue Analysis Banner" />
</p>

<h1 align="center">📊 Google Revenue Analysis (2014 - 2024)</h1>

<p align="center">
  An insightful analysis of Google's revenue trends using Power BI.<br>
  This dashboard covers year-wise, segment-wise, and region-wise earnings from 2014 to 2024.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-PowerBI-yellow?style=for-the-badge&logo=powerbi" />
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge" />
  <img src="https://visitor-badge.laobi.icu/badge?page_id=rkstm7.google-revenue-analysis" />
</p>

---

## 📌 Project Overview

The **Google Revenue Analysis** Power BI project aims to visualize and analyze Google's financial performance over the past decade. Using a clean and dynamic interface, the dashboard provides deep insights into business segments, global revenue sources, and patterns in growth.

---

## 🎯 Objectives

- 🗓️ Track Google’s revenue from **2014 to 2024**
- 🌐 Understand revenue by **region** and **business segment**
- 📉 Identify trends, dips, and peaks in income
- 📈 Forecast growth patterns using historical data

---

## 🛠️ Tools & Technologies

| Tool       | Description                           |
|------------|---------------------------------------|
| Power BI   | For creating interactive dashboards   |
| Excel      | Data collection & transformation      |
| DAX        | For calculations & KPIs               |
| Power Query| Data shaping and modeling             |

---

## 📈 Dashboard Highlights

- 📊 Year-wise Revenue Bar Charts
- 🌍 Geo Maps: Region-wise Distribution
- 🔍 Filters & Slicers (Year, Region, Segment)
- 📉 Trendline Analysis & Growth Rates
- 📥 Download Option for Reports

---

## 🗂️ File Structure

```text
Google-Revenue-Analysis/
├── GOOGLE REVENUE ANALYSIS-2014 to 2024.pbix   # Power BI report file
├── Google Revenue From 2014 to 2024.xlsx        # Source dataset (Excel)
├── revenue.png                                  # Dashboard banner image
├── social-preview.png                           # GitHub social preview image
├── Bis Final Doc.docx                           # Supporting project documentation
├── LICENSE                                      # MIT license
├── CONTRIBUTING.md                              # Contribution guidelines
└── README.md                                    # Project documentation
```

---

## 🧾 Dataset Details

### Dataset Name

`Google Revenue From 2014 to 2024.xlsx`

### Grain

One row per year.

### Time Range

2014 to 2024 (11 records).

### Data Dictionary

| Column | Type | Unit | Description |
|---|---|---|---|
| Year | Whole Number | Year | Fiscal calendar year |
| Total Revenue (in billions USD) | Decimal Number | USD (Billions) | Alphabet/Google total annual revenue |
| Advertising Revenue | Decimal Number / Text | USD (Billions) | Revenue from advertising business |
| Google Cloud Revenue | Decimal Number / Text | USD (Billions) | Revenue attributed to Google Cloud |
| Other Revenue | Decimal Number / Text | USD (Billions) | Other non-core revenue streams |
| YouTube Ads | Decimal Number / Text | USD (Billions) | YouTube advertising revenue |
| Google Network | Decimal Number / Text | USD (Billions) | Google Network revenue |
| Subscriptions, Platforms & Devices | Decimal Number / Text | USD (Billions) | Revenue from subscriptions/platform/device businesses |

> **Note:** `DNS` appears in early years for some columns and means **Data Not Specified**.

---

## 🔁 How to Replicate the Dataset in Power BI

1. Open Power BI Desktop.
2. Load `Google Revenue From 2014 to 2024.xlsx`.
3. In Power Query:
  - Replace `DNS` with `null` (or keep as text if needed for display-only use).
  - Set numeric data types to **Decimal Number**.
  - Keep `Year` as **Whole Number**.
4. Close & Apply.
5. Build visuals using yearly trend comparisons across revenue streams.

---

## 🧠 Suggested DAX Metrics

- **Total Revenue** = `SUM([Total Revenue (in billions USD)])`
- **YoY Growth %** = `DIVIDE([Total Revenue] - [Previous Year Revenue], [Previous Year Revenue])`
- **Cloud Share %** = `DIVIDE(SUM([Google Cloud Revenue]), [Total Revenue])`
- **Ad Share %** = `DIVIDE(SUM([Advertising Revenue]), [Total Revenue])`

---

## ✅ Key Output Insights (From Current Data)

- Revenue grows from **66.00B (2014)** to **350.02B (2024)**.
- Advertising remains the largest contributor over the period.
- Cloud contribution becomes materially larger from 2020 onward.
- Subscriptions/Platforms/Devices and YouTube Ads show strong late-period growth.

---

## 📸 Output

- Power BI report: `GOOGLE REVENUE ANALYSIS-2014 to 2024.pbix`
- Source data: `Google Revenue From 2014 to 2024.xlsx`
- Banner/preview image: `revenue.png`

---

## 🚀 How to Use This Project

1. Clone/download the repository.
2. Open the `.pbix` file in Power BI Desktop.
3. Refresh data if needed (Excel source should remain in the same relative location).
4. Use slicers and filters to explore year-wise and segment-wise trends.

---

## ⚠️ Limitations

- Some segment values for early years are marked `DNS`.
- Dataset is annual (not quarterly/monthly), so short-term seasonality is not modeled.
- Accuracy depends on source financial disclosures and manual preparation.

---

## 📌 Future Improvements

- Add source links for each metric (annual reports / investor relations).
- Add quarterly-level data for deeper trend analysis.
- Build forecast scenarios in Power BI using decomposition and confidence bands.
- Publish report to Power BI Service for web sharing.

---

## 👤 Author

**Sumit Singh**

If you found this project useful, feel free to ⭐ the repository.

---

## 🤝 Contributing

Contributions are welcome. Please read `CONTRIBUTING.md` for setup, data rules, and PR expectations.

---

## 📄 License

This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## 🌐 GitHub Social Preview

Use `social-preview.png` as the repository social preview image:

1. Open your repository on GitHub.
2. Go to **Settings** → **General** → **Social preview**.
3. Upload `social-preview.png`.

