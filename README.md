<div align="center">
  <h1>📊 Structuring Company's Stock</h1>
  <p><i>Complete stock management system with strategic dashboard developed in Excel for LLC Electronics</i></p>
</div>

<p align="center">
  <a href="#-overview">Overview</a> •
  <a href="#-objective">Objective</a> •
  <a href="#-technologies-used">Technologies</a> •
  <a href="#-project-structure">Project Structure</a> •
  <a href="#-development-methodology">Methodology</a> •
  <a href="#-implemented-features">Features</a> •
  <a href="#-final-dashboard">Final Dashboard</a> •
  <a href="#-insights-and-results">Insights & Results</a> •
  <a href="#-technical-learnings">Technical Learnings</a> •
  <a href="#-license">License</a>
</p>

## 🔍 Overview

This project represents a complete **Business Intelligence** solution developed entirely in Microsoft Excel for LLC Electronics. The challenge consisted of transforming scattered and disorganized stock data into a consolidated management system, culminating in a strategic dashboard that enables data-driven decision making.

### 🎯 Problem Solved
LLC Electronics faced difficulties in stock control due to **information dispersion** across multiple separate spreadsheets, making it impossible to:
- Have a consolidated view of current stock
- Identify products with critical or negative stock
- Analyze performance by product category
- Make strategic decisions based on data

### ✅ Implemented Solution
Development of an **integrated stock management system** with:
- Automatic consolidation of input, output and registration data
- Intelligent classification of product status
- Interactive dashboard with strategic KPIs
- Graphical visualizations for trend analysis

## 🚀 Objective

**Transform raw stock data into business intelligence**, applying advanced Excel techniques to:

1) **Consolidate** input, output and product registration data
2) **Automate** calculations of balances, stock values and classifications
3) **Visualize** information through pivot tables and analytical charts
4) **Deliver** a functional strategic panel for executive meetings

> 💡 **SKU (Stock Keeping Unit)**: Stock Keeping Unit used to classify and organize items according to their specific characteristics (size, color, model, manufacturer).

## 💻 Technologies Used

### 🔧 Main Tools
- **Microsoft Excel** - Main development platform
- **Pivot Tables** - Data analysis and summarization
- **Dynamic Charts** - Interactive information visualization

### 📊 Advanced Excel Functions
- **`SUMIF`** - Conditional sum for calculating inputs and outputs
- **`VLOOKUP`** - Information search between different sheets
- **`IFS`** - Multiple conditional logic for status classification
- **Conditional Formatting** - Automatic visual highlighting of critical data
- **Data Validation** - Information integrity control

## 📋 Project Structure

```
📁 Structuring_Company-s_stock/
├── 📁 Database/
│   ├── 📄 [Template] Entrada.csv           # Input data
│   └── 📊 [Template] Excel.xlsx            # Original template (44 KB)
├── 📊 analysis.xlsx                        # Main spreadsheet (99 KB)
├── 📄 LICENSE.md                           # Project license (4 KB)
└── 📄 README.md                            # Documentation (1 KB)
```

### 🗂️ Excel Sheets Structure

| Sheet | Function | Content |
|-------|----------|---------|
| `📋 Register` | Product database | SKU, Name, Description, Category, Price |
| `📈 In` | Input records | Date, SKU, Product, Quantity |
| `📉 Out` | Output records | Date, SKU, Product, Quantity |
| `📊 Stock Summary` | Consolidation | Balances, values, status per product |
| `🎯 Bashboard` | Strategic dashboard | KPIs, pivot tables, charts |

## 🎯 Development Methodology

### Phase 1️⃣ - Data Relationship and Consolidation
**Objective**: Create consolidated information base
- ✅ Creation of `Resumo Estoque` sheet
- ✅ Import of SKU, Category and Price via `VLOOKUP`
- ✅ Calculation of input and output totals with `SUMIF`
- ✅ Determination of current balance (inputs - outputs)
- ✅ Calculation of stock value (balance × price)

### Phase 2️⃣ - Intelligent Status Classification
**Objective**: Categorize products by stock situation
- ✅ Implementation of logic with `IFS` function:
  - 🔴 **Obsolete**: stock = 0
  - ⚠️ **Negative Stock**: balance < 0  
  - 🟡 **Critical**: balance between 1-20
  - 🟢 **OK**: balance between 21-100
  - 🔵 **Excess**: balance > 100

### Phase 3️⃣ - Visual and Conditional Formatting
**Objective**: Facilitate visual identification of critical situations
- ✅ Red highlighting for negative values
- ✅ Currency formatting (R$) for value columns
- ✅ Color coding for different statuses
- ✅ Visual standardization and alignment

### Phase 4️⃣ - Validation and Structuring
**Objective**: Ensure integrity and usability
- ✅ Drop-down lists with data validation
- ✅ Panel freezing for navigation
- ✅ Visual organization and title standardization

### Phase 5️⃣ - Business Intelligence with Pivot Tables
**Objective**: Create automated strategic analyses
- ✅ Total stock value by category
- ✅ Number of SKUs by category  
- ✅ Average price by category
- ✅ Total outputs by category

### Phase 6️⃣ - Executive Dashboard
**Objective**: Strategic visualization for decision making
- ✅ Column chart: Stock value by category
- ✅ Bar chart: Total outputs by category
- ✅ Column chart: Average price by category

## ⚙️ Implemented Features

### 🔄 Process Automation
- **Automatic updating** of balances when modifying input/output data
- **Dynamic classification** of status based on business rules
- **Automatic calculations** of financial values in stock

### 📈 Strategic Analyses
- **Identification of critical products** with low or negative stock
- **Performance analysis by product category**
- **Monitoring of capital invested** in stock
- **Movement tracking** by category

### 🎨 Visual Interface
- **Intuitive dashboard** with main KPIs
- **Interactive charts** for trend analysis
- **Conditional formatting** for visual alerts
- **Professional layout** ready for presentations

## 🎯 Final Dashboard

The developed dashboard presents a complete executive view of LLC Electronics' stock:

### 📊 Main KPIs
- **💰 Total Stock Value**: R$ 10,102,026 - Total stock value
- **📦 SKU Count**: 120 unique registered products
- **💵 Average Price**: R$ 534.67 - Average product price
- **📤 Total Out**: 19,878 total output units

### 📈 Analysis by Category

**Stock Value by Category:**
- 🥇 **Networks**: R$ 2,073,021 (highest invested value)
- 🥈 **Peripherals**: R$ 1,779,518
- 🥉 **Image & Sound**: R$ 1,772,670

**Movement by Category (Total Out):**
- 🔝 **Accessories**: 3,674 units (highest turnover)
- **Peripherals**: 2,847 units
- **Image & Sound**: 2,601 units

**Average Price by Category:**
- 💎 **Networks**: R$ 586.83 (highest value products)
- **Hardware**: R$ 561.26
- **Peripherals**: R$ 568.89

### 🎯 Strategic Insights Identified

1) **⚠️ Capital Management**: "Networks" category concentrates highest stock value
2) **🔄 High Turnover**: "Accessories" shows highest movement
3) **💰 Pricing Opportunity**: "Networks" products have higher margin
4) **📊 Diversification**: Portfolio well distributed across 7 categories

## 🎓 Technical Learnings

### 💡 Excel Competencies Developed
- **Data relationships** between multiple sheets and sources
- **Advanced functions** for complex calculation automation
- **Pivot tables** for multidimensional analysis
- **Data visualization** through strategic charts
- **Professional dashboard design** for executive presentations

### 🔍 Business Intelligence Concepts
- **ETL Process**: Extract, transform and load data
- **KPI Design**: Definition of key performance indicators
- **Data Storytelling**: Narrative through visualizations
- **Executive Reporting**: Reports for decision making

### ⚙️ Implemented Best Practices
- **Clear documentation** of formulas and processes
- **Data validation** to maintain integrity
- **Consistent formatting** to facilitate reading
- **Modular structure** to facilitate maintenance

## 🚨 Alerts and Monitoring

> ⚠️ **Negative Stock**: The system automatically identifies products with more outputs than inputs, indicating possible:
> - Movement recording errors
> - Sales made without adequate replenishment  
> - Logistical problems in the supply chain

### 🔔 Implemented Alert Indicators
- 🔴 **Red**: Negative values (immediate action required)
- 🔵 **Blue**: Zero stock (obsolete products)
- 🟢 **Green**: Normal situation (21-100 units)

## 🚀 How to Use

1. **View online:** open the [shared Google Sheets version](https://docs.google.com/spreadsheets/d/1ASVNzQPtEpx3L61Q62m_8lls28T9e2KF/edit?usp=sharing) in your browser, with no installation.
2. **Open in Excel:** download [`analysis.xlsx`](analysis.xlsx), the main spreadsheet, and open it in Microsoft Excel. Start at the dashboard sheet and use the pivot tables to filter.
3. **Start from the raw data:** the [`Database/`](Database) folder has the original input files (CSV and XLSX) used to build the system.

---

## 🤝 Contributing

Contributions, ideas and feedback are welcome!

- 🐛 **Found a bug or something unclear?** [Open an issue](https://github.com/Laurentius96/Structuring_Company-s_Stock/issues/new) describing what happened and how to reproduce it.
- 💡 **Have an idea or a question?** [Open an issue](https://github.com/Laurentius96/Structuring_Company-s_Stock/issues/new) and tell me about it.
- 🔧 **Want to propose a fix?** Fork the repository, create a branch (`git checkout -b fix/short-description`), commit your changes and open a pull request explaining what changed and why.

By contributing, you agree that your contribution is shared under the same license as this project.

---

## 📜 License

This project was developed as part of the **DNC (Digital Nation Course)** educational program and is available for learning purposes and technical competency demonstration.

<details open>
<summary><b>📄 Creative Commons CC BY-NC-ND 4.0 License</b></summary>

This repository is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

### ✅ Permissions:
- **Share**: Copy and redistribute the material in any medium or format
- **Attribution**: Give appropriate credit to the original author

### ❌ Limitations:
- **Commercial Use**: Not permitted for commercial purposes
- **Modifications**: Not permitted to alter, transform or create derivatives
- **Warranties**: Provided "as is", without warranties of any kind

For complete terms, see [LICENSE.md](LICENSE.md).
</details>

## 🎓 Educational Resources

### 📚 Technical Documentation
- [Microsoft Excel - Functions and Formulas](https://support.microsoft.com/en-us/office/excel-functions-by-category)
- [Pivot Tables - Complete Guide](https://support.microsoft.com/en-us/office/create-a-pivottable)
- [Dashboard Design - Best Practices](https://www.microsoft.com/en-us/microsoft-365/excel)

### 🔧 Complementary Tools
- **Power Query**: For advanced data transformation
- **Power Pivot**: For complex data modeling
- **Power BI**: For more advanced dashboards

### 💡 Recovery Tips
> 🆘 **File Recovery**: In case of accidental closing without saving:
> 
> Access: `C:\Users\[YOUR_USERNAME]\AppData\Local\Temp\Microsoft`
> 
> ⏰ **Important**: Do this within 15 minutes to recover your work!

---

<div align="center">
  <h3>🏆 Project Developed with Excellence</h3>
  <p><b>👨‍💻 Developed by <a href="https://github.com/Laurentius96">Lorenzo C. Bianchi</a></b></p>
  <p><i>🎯 Transforming data into strategic decisions | 📊 Excel • Business Intelligence • Data Analysis</i></p>
  <p><b>🎓 DNC Educational Program</b></p>
</div>

<div align="center">
  <p><i>💙 "Data is the new oil, but insights are the fuel that drives business"</i></p>
</div>
