# DV Analytics - Budget Dashboard 📊

An interactive, dark-neon financial and budget analytics dashboard built for data analysts and finance teams to plan smarter, control spending, and track performance in real-time.

## 🚀 Features

- **Interactive Dynamic Filters**:
  - **Date Period Filter**: Filter by specific months or view the entire aggregated timeframe.
  - **Department Filter**: Filter data by Operations, HR, Marketing, Administration, Technology, Finance, or All Departments.
  - **Branch Filter**: Filter by Headquarters, Regional branches, or All Branches.
- **Real-time Recalculations**:
  - 5 Core Financial KPIs (Total Budget, Actual Spend, Variance, % Utilization, EOM Forecast).
  - Categorized expense allocation with interactive donut breakdown.
  - Monthly Budget vs Actual and Forecast trends.
  - Top Budget Overruns & Savings sparkline rankings.
  - Auto-generated narrative Key Insights and Quick Stats.
- **Client-Side Excel Engine**:
  - Drag & drop `.xlsx`/`.xls` workbook upload powered by SheetJS.
  - Zero server upload required (100% in-browser privacy).
- **Export Filtered Data**:
  - Export filtered datasets directly back to Excel format with one click.

## 🛠️ Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/mdsajid-ui/DV-Analytics-Budget-Dashboard.git
   ```
2. Open `index.html` directly in any modern web browser.
3. (Optional) Upload your own Excel budget sheet using the **"↑ Upload Excel"** button in the top right.

## 📋 Excel Template Columns

| Date | Department | Category | Budget | Actual | Forecast | Branch |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| `YYYY-MM-DD` | `Marketing` | `Marketing` | `100000` | `85000` | `105000` | `Headquarters` |
