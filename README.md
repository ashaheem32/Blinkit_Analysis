# Blinkit Grocery Analytics Dashboard (Power BI) 🛒

## Overview

This Power BI dashboard provides **end-to-end analytics for Blinkit’s grocery sales data**, enabling business users and analysts to visualize, filter, and explore key performance indicators (KPIs), outlet performance, product categories, and more. All sales and financial figures are displayed in Indian Rupees (₹) for local business relevance.

---

## Features

* **Key Metrics**:

  * Total Sales (₹), Average Sales (₹), Number of Items, and Average Ratings—displayed prominently as KPI cards.
* **Dynamic Filtering**:

  * Filter panel for Outlet Location Type, Outlet Size, and Item Type for quick, custom insights.
* **Sales & Trends**:

  * Visualizations of sales breakdown by item type, fat content, outlet size, and outlet location.
  * Year-wise outlet establishment trend line.
* **Outlet Analysis**:

  * Sales and performance segmented by outlet type and tier, including comparisons between supermarkets and grocery stores.
* **Category Insights**:

  * Identify best-selling product categories and spot inefficiencies or growth areas.
* **Interactive Visuals**:

  * All visuals are fully interactive and linked for seamless data exploration.

---

## Data Source

* **File**: `BlinkIT Grocery Data.xlsx`
* **Columns**: Sales, Avg Sales, No. of Items, Avg Rating, Outlet Type, Outlet Size, Item Type, Location, Fat Content, Year Established, and more.
* **Currency**: All monetary values have been converted from USD (\$) to INR (₹) using the exchange rate **1 USD = 83 INR**.

---

## How to Use

1. **Open** the Power BI dashboard (`.pbix` file) in Power BI Desktop.
2. **Interact** with the filter panel to view metrics for different outlet types, sizes, and item categories.
3. **Explore** KPIs and trend charts for detailed business insights.
4. **Hover** over visuals to see tooltips with additional breakdowns.

---

## Customization

* To update the currency rate, modify the related measures in Power BI (e.g., `Total Sales (INR) = [Total Sales] * <new_rate>`).
* To add new columns or analytics, use the Power Query Editor and DAX for calculated columns/measures.
* Visual formatting and colors can be easily changed via the Format pane in Power BI.

---

## Screenshots

*(Include relevant screenshots here. Example below)*

![Dashboard Overview](![Blinkit-analysis_page-0001](https://github.com/user-attachments/assets/0cfee363-4d33-4e9c-87e4-2036513d3f1e)
)

---

## Getting Started

1. Clone or download this repository.
2. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3. Open the `.pbix` file to begin exploring.

---

## Credits

* **Data & Analysis**: Blinkit Team / \[Your Name]
* **Visualization**: Power BI
* **Conversion Rate**: XE.com as of \[Date]

---

## License

This project is for educational and internal analytics purposes only.

---

**Feel free to further customize this README as per your organization or portfolio needs!**
If you want it even more tailored (e.g., add “How to add your own data,” or specific DAX sample code), let me know!
