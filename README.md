# DV Analytics · Unified Financial & Budget Suite 📊

An interactive, high-performance financial analytics and budget management dashboard built for data analysts, finance controllers, and enterprise leadership.

---

## 🚀 Key Modules & Navigation

The navigation menu places **Budgets** directly under **Profit & Loss** and **Balance Sheet**, with instant live tab switching:

1. **↗ Profit & Loss (`pnl`)**:
   - **Metrics**: Total Revenue, Total Expenses, Net Profit, Profit Margin %, Gross Profit, EBITDA, Operating Profit, COGS, Cash Balance, Receivables, Payables.
   - **Visuals**: Revenue vs Expenses Trend, Expense Breakdown Donut, Financial P&L Statement Table, Monthly Profit Margin SVG Sparkline, Position and Expense Meters.
2. **▤ Balance Sheet (`balance`)**:
   - **Metrics**: Total Assets, Total Liabilities, Total Equity ($Assets - Liabilities$), Current Ratio, Debt-to-Equity Ratio, Working Capital, Retained Earnings.
   - **Visuals**: Assets vs Liabilities Trend, Asset Composition Donut (Cash, Receivables, Inventory, Fixed Assets), Balance Sheet Summary Table, Liquidity Current Ratio Curve, Solvency Meters.
3. **▣ Budgets & Variance (`budget`) — *Under-Budget Control***:
   - **Metrics**: Total Budget, Actual Spend, Variance (Under-Budget Surplus / Over-Budget Deficit), Budget Utilization %, EOM Forecast.
   - **Visuals**: Monthly Budget vs Actual Bar Comparison with Savings Line, Budget Allocation Donut, Line Item Performance Table, Monthly Utilization Curve, Top Savings (Under Budget) & Overrun Sparklists.

---

## 🛠️ Interactive Features

- **Live Navigation Switching**: Click any sidebar button (**Profit & Loss**, **Balance Sheet**, **Budgets**) to switch dashboards without page reloads.
- **Dynamic Multi-Level Filtering**:
  - **Date Period Filter**: Filter by specific months or view all historical periods.
  - **Branch Filter**: Filter by Headquarters, Regional branches, or aggregated scope.
  - **Department Filter**: Drill down into Operations, HR, Marketing, Administration, Technology, Finance, etc.
- **Client-Side Excel Engine**:
  - Drag & drop `.xlsx` / `.xls` files for instant browser-based parsing with zero server upload.
  - Automatic column detection: auto-routes uploaded sheets into P&L, Balance Sheet, or Budget views.
- **One-Click Excel Export**:
  - Export filtered datasets directly into formatted `.xlsx` workbooks.

---

## 📁 File Location

- Entry point: [`index.html`](index.html)
