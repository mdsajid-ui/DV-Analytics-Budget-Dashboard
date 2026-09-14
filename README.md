# DV Analytics · Enterprise Financial & Budget Management Suite 📊

An interactive, institutional-grade financial analytics, daily cash/bank ledger, and budget management dashboard built for data analysts, finance controllers, chartered accountants, and enterprise leadership.

---

## 🚀 Key Modules & Navigation

The navigation menu places **Profit & Loss**, **Balance Sheet**, and **Daily Transactions** directly alongside **Budgets**, with instant live tab switching:

1. **↗ Profit & Loss (`pnl`)**:
   - **Metrics**: Total Revenue, Total Expenses, Net Profit (PAT), Profit Margin %, Gross Profit, EBITDA, Operating Profit, COGS, Cash Balance, Receivables, Payables.
   - **Visuals**: Revenue vs Expenses Trend, Expense Breakdown Donut, Financial P&L Statement Table (Schedule III), Monthly Profit Margin SVG Sparkline, Hierarchy and Expense Meters.
2. **▤ Balance Sheet (`balance`)**:
   - **Metrics**: Total Assets, Total Liabilities, Total Equity ($Assets - Liabilities$), Current Ratio, Debt-to-Equity Ratio, Working Capital, Retained Earnings.
   - **Visuals**: Assets vs Liabilities Trend, Asset Composition Donut (Cash, Receivables, Inventory, Fixed Assets), Balance Sheet Summary Table, Liquidity Current Ratio Curve, Solvency Meters.
3. **💳 Daily Transactions — Cash & Bank Book (`daily`) — *NEW***:
   - **Features**: Real-time recording of daily incoming receipts and outgoing payments with modal dialogs, inline ledger editing, and deletion.
   - **Double-Entry Auto-Sync**: Every receipt and payment automatically flows into the Cash & Bank balance, Balance Sheet ($Assets = Liabilities + Equity$), P&L Statement, Cash Flow Statement, and Budgets in real-time.
   - **Ledger Controls**: Live text search, transaction type filters (Receipts vs Payments), payment mode filters (Bank Transfer, UPI, Cash, Cheque), and single-entry or bulk spreadsheet imports.
4. **▣ Budgets & Variance (`budget`) — *Under-Budget Control***:
   - **Metrics**: Total Budget, Actual Spend (dynamically updated from daily payments), Variance (Under-Budget Surplus / Over-Budget Deficit), Budget Utilization %, EOM Forecast.
   - **Visuals**: Monthly Budget vs Actual Bar Comparison with Savings Line, Budget Allocation Donut, Line Item Performance Table, Monthly Utilization Curve, Top Savings & Overrun Sparklists.
5. **◉ Cash Flow Statement (`cashflow`)**:
   - **Metrics**: Operating Cash Flow, Investing Cash Flow, Financing Cash Flow, Net Cash Flow, Ending Cash Balance.
   - **Reconciliation**: 100% reconciled to the Balance Sheet cash and bank reserves.
6. **⚖ GST & Statutory Compliance Hub (`gst`) — *NEW (Auto-File)***:
   - **Metrics**: Gross Taxable Turnover, Total Output GST (CGST, SGST, IGST), Eligible Input Tax Credit (ITC), Net Cash Tax Liability (Rule 88A Electronic Cash Ledger), GSTR-2B Reconciliation Health %.
   - **4-Sub-Tab Center Console**:
     - **GSTR-1 Outward Supplies**: Multi-table registers for B2B Registered, B2CL Inter-State Large (>₹2.5L), B2CS Consumer Small, CDNR Credit/Debit Notes, and HSN 6-Digit Summary.
     - **GSTR-3B Tax Offset Matrix (Rule 88A)**: Statutory cascading credit setoff sequence preventing illegal cross-utilization (IGST $\rightarrow$ CGST/SGST; CGST $\neq$ SGST) and computing exact challan cash liability.
     - **GSTR-2B ITC Auto-Reconciliation (Section 16(2)(aa))**: Cross-verification of inward purchase invoices against portal 2B data to classify entries as `MATCHED`, `VARIANCE`, or `MISSING_IN_2B`.
     - **E-Invoice & E-Way Bill Engine**: Interactive Luhn Mod-36 GSTIN checksum validator, Rule 138(10) transit validity calculator, and NIC v1.1 CBIC JSON schema generator.
   - **Statutory Filing Exports**:
     - 📥 **Export GSTR-1 Portal JSON**: Official GSTN offline tool JSON upload format ready for direct import to `gst.gov.in`.
     - 📥 **Export GSTR-3B Summary JSON**: Standardized Table 3.1 & Table 4 tax offset settlement file.
     - 📊 **Download GSTR-1 Audit (.xlsx)**: Comprehensive multi-sheet statutory return workbook.
     - 📊 **Download GSTR-3B Statement (.xlsx)**: Formatted tax computation and cash ledger offset schedule.
7. **✥ Reports & Download Center (`reports`) — *ENHANCED***:
   - **Dedicated Statutory Download Fields**:
     - 📥 **Download Profit & Loss Report (`.xlsx`)**: Professional Schedule III format with Revenue, COGS, OpEx, EBITDA, PBT, Tax, and PAT.
     - 📥 **Download Balance Sheet Report (`.xlsx`)**: Formatted Double-Entry Balance Sheet with Shareholders' Funds, Liabilities, Assets, and Balance Parity Check.
     - 📥 **Download Cash Flow Report (`.xlsx`)**: AS-3 Indirect Method covering Operating, Investing, and Financing activities.
     - 📥 **Download Daily Ledger (`.xlsx`)**: Full chronological Cash & Bank Book audit trail with voucher numbers and running balances.
     - 📥 **Download GSTR-1 Audit (`.xlsx`)**: Multi-sheet outward supplies audit register.
     - 📥 **Download GSTR-3B Statement (`.xlsx`)**: Rule 88A tax credit offset and settlement statement.
     - 📥 **Download Master Statutory Dossier (`.xlsx`)**: 6-sheet consolidated workbook bundling P&L, Balance Sheet, Cash Flow, Daily Cash Book, GSTR-1, and GSTR-3B.

---

## 🛠️ Interactive Features

- **Live Navigation Switching**: Click any sidebar button (**Profit & Loss**, **Balance Sheet**, **Daily Transactions**, **Budgets**, **Reports**) to switch dashboards without page reloads.
- **Dynamic Multi-Level Filtering**:
  - **Date Period Filter**: Filter by specific months or view all historical periods.
  - **Branch Filter**: Filter by Headquarters, North Branch, South Branch, or aggregated scope.
  - **Department Filter**: Drill down into Operations, HR & Payroll, Marketing, Administration, Technology, Finance, Commercial, etc.
- **Client-Side Excel Engine**:
  - Drag & drop `.xlsx` / `.xls` / `.csv` files for instant browser-based parsing with zero server upload.
  - Automatic column detection: auto-routes uploaded sheets into Daily Ledger, P&L, Balance Sheet, or Budget views.
- **Universal LocalStorage Persistence**:
  - Daily transactions, user modifications, and active visual theme preferences are safely retained in browser `localStorage`.
- **Dynamic Multi-Theme Engine (4 Themes) — *NEW***:
  - 🌙 **Midnight Navy (Default)**: Deep midnight navy glassmorphism with vivid cyan and green neon accents.
  - ☀️ **Executive Light (Pro)**: High-contrast, clean daylight corporate theme with crisp white cards, slate typography, and subtle shadows.
  - 💎 **Emerald Onyx (Wealth)**: Bloomberg Terminal / wealth management theme in deep obsidian forest green with mint accents.
  - 🔮 **Obsidian Violet (Cosmic)**: High-contrast midnight black and royal amethyst violet with electric cyber highlights.
- **One-Click Multi-Format Export**:
  - Download individual statement reports or the entire multi-tab master audit dossier with formatted columns and formulas.

---

## 📁 File Structure

- Application Entry Point: [`index.html`](index.html)
- Schedule III Annual Report Reference: `Schedule_III_Annual_Report.xlsx`
