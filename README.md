# 📊 Marketing Funnel & Conversion Performance Analysis

**Data Science & Analytics Internship — Task 3 (2026) | Future Interns**

Analysis of how leads move through a marketing/sales funnel — from being contacted, to engaging in a
real conversation, to converting into a customer — using the **Bank Marketing Campaign dataset**
(UCI Machine Learning Repository).

---

## 🔍 About the Project

This project analyzes 41,188 client records from a Portuguese bank's phone-based term deposit marketing
campaigns to answer:

- Where are leads dropping off in the funnel?
- Which contact channel converts best?
- Which campaign periods and customer segments are highest quality?
- What actionable steps can improve conversion rates?

## 📁 Dataset

**Bank Marketing Campaign Dataset** — UCI Machine Learning Repository
🔗 https://archive.ics.uci.edu/dataset/222/bank+marketing

- 41,188 rows × 21 columns
- File used: `bank-additional-full.csv`

## 🧭 The Funnel

| Stage | Definition | Count | % of Total |
|---|---|---|---|
| 1. Total Leads Contacted | Every client called | 41,188 | 100% |
| 2. Engaged Leads | Call duration ≥ 3 minutes | 20,600 | 50.0% |
| 3. Converted Customers | Subscribed to term deposit (`y = yes`) | 4,640 | 11.3% |

## 🎯 Key Insights

- **Biggest drop-off is at first contact** — ~50% of leads never engage in a 3+ minute call.
- **Cellular contact converts ~3x better than landline** (14.7% vs 5.2%).
- **Quality beats quantity** — low-volume campaign months (Mar, Sep, Oct, Dec) convert at 44–51%,
  vs. 6–10% in high-volume months (May–Aug).
- **Retargeting past successful customers is the highest-value segment** — 65.1% conversion rate.
- **Students (31.4%) and retirees (25.2%)** convert far above average; blue-collar and services
  workers convert below average.
- **Longer calls convert dramatically better** — from ~0% under 1 minute to 48.6% for 10+ minute calls.

## 🛠️ Tools Used

- **Python** — pandas, matplotlib
- **Jupyter Notebook** — exploratory analysis & documentation
- **Word/Report generation** — for the stakeholder-facing summary report

## 📂 Repository Structure

```
├── data/
│   └── bank-additional-full.csv         # Source dataset
├── notebook/
│   └── Marketing_Funnel_Analysis.ipynb  # Full exploratory analysis with charts
├── charts/
│   ├── 01_funnel_overview.png
│   ├── 02_conversion_by_channel.png
│   ├── 03_conversion_by_month.png
│   ├── 04_conversion_by_prev_outcome.png
│   ├── 05_conversion_by_job.png
│   └── 06_duration_vs_conversion.png
├── report/
│   └── Marketing_Funnel_Report.docx     # Stakeholder-facing report
└── README.md
```

## 📤 Deliverables

- ✅ Funnel analysis notebook with conversion rates at each stage
- ✅ Key drop-off insights across channel, time, segment, and engagement
- ✅ Stakeholder report with actionable recommendations

## 💡 Recommendations

1. Prioritize **cellular contact** over landline wherever possible.
2. Build a **systematic retargeting flow** for previously successful customers.
3. Shift budget toward **smaller, targeted campaigns** instead of mass outreach in peak months.
4. **Segment campaigns by occupation**, leading with students and retirees.
5. Invest in **call-opening scripts** to keep prospects engaged past the first 1–2 minutes.

---

### 🚀 About Future Interns

This project was completed as part of the [Future Interns](https://futureinterns.com/) Data Science &
Analytics internship program.

📌 Connect: [LinkedIn](https://www.linkedin.com/company/future-interns/)
