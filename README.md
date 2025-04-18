# Power BI Performance Report Template

![Power BI Logo](https://raw.githubusercontent.com/microsoft/PowerBI-visuals/master/assets/logo.svg)

A repository for managing and deploying Power BI performance analysis reports. Includes template files for rapid report generation in organizational environments.

## 📊 Features

- **Pre-built Performance Dashboard**  
  Track KPIs with interactive visuals for sales, operations, and financial metrics.

- **Template Structure**  
  `.PBIT` template files with pre-configured:  
  - Data model relationships  
  - DAX measures for common metrics  
  - Conditional formatting rules

- **Theme Support**  
  Includes JSON theme files for:  
  `Corporate Blue` | `Dark Mode` | `Accessibility High-Contrast`

## 🚀 Getting Started

### Prerequisites
- Power BI Desktop (April 2024 or newer)
- Basic understanding of Power Query/M

### Installation
1. Clone repo:
git clone https://github.com/Wodlfvllf/PowerBI.git

2. Open `Performance Report/PerformanceTemplate.pbit` in Power BI Desktop

### Configuration
When prompted:  
1. Enter **Data Source** parameters:
{
"SQL_Server": "your-database.windows.net",
"Dataset_Name": "SalesData"
}

2. Authentication: Use organizational account

## 🛠 Customization

### Modify Theme
1. Edit `Themes/Corporate_Blue.json`
2. Import through:  
**View** → **Themes** → **Import theme**

### Add New Metrics
1. Create measures in `DAX/PerformanceMeasures.dax`
2. Drag onto appropriate visual in `Report.pbix`

## 🤝 Contributing

1. Fork the repository
2. Create feature branch:
git checkout -b feature/new-visual

3. Commit changes following [Power BI Best Practices](https://learn.microsoft.com/en-us/power-bi/guidance/power-bi-implementation-planning-report-design)
4. Submit PR with description of changes

## 📜 License  
MIT License - See [LICENSE](LICENSE) for details

---

**Maintained by**: [Wodlfvllf](https://github.com/Wodlfvllf)  
**Report Issues**: [Issue Tracker](https://github.com/Wodlfvllf/PowerBI/issues)
