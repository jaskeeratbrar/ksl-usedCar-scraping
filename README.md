# Toyota Used Car Popularity Analysis in Utah

## Insights into Toyota Popularity for Used Car Dealer in Utah

### Introduction

In my latest endeavor, I have undertaken a personal project that fuses the intricacies of web scraping with the analytical examination of consumer behavior in the used car market. This project aims to provide actionable insights to Toyota car dealers, focusing on the determinants that influence vehicle views and, consequently, customer attention.

### Project Context

Operating in Utah's competitive automotive industry as a dealer of Toyota hybrid and gas vehicles, it is paramount to stay abreast of market trends and consumer preferences. This initiative is a proactive step towards capturing a significant share of the local market by identifying and purchasing vehicles that resonate most with potential buyers.

### Data Collection

The data central to this analysis was meticulously harvested from KSL Cars — Utah's premier online marketplace for automotive trade. By employing Python's robust libraries, Selenium and BeautifulSoup, I automated the browser interaction and data extraction processes to compile a dataset rich in detail. This dataset encompasses various attributes of Toyota vehicles, including but not limited to, price, mileage, year, make, model, drivetype, and title status.

### Business Insights and Strategic Application

The analysis of this dataset serves multiple strategic purposes:

- **Popularity by Vehicle Attributes:** Understanding which attributes (year, model, mileage, title status) correlate with higher view counts can unveil consumer preferences for specific Toyota vehicles.

- **Price Sensitivity:** Analyzing the impact of pricing on view counts enables competitive vehicle pricing.

- **Inventory Optimization:** Leveraging historical data trends aids in forecasting demand and optimizing inventory.

- **Targeted Marketing:** Crafting marketing campaigns that emphasize the most viewed vehicle attributes and leveraging less popular features to bolster interest in other inventory.

### Conclusion

The methodologies I've employed — from scraping to data storage in an SQL database — were designed with a view to support not just the present analysis but also future machine learning applications. This dataset is the cornerstone of providing updated market insights to used car dealers and a foundation for further research into customer preferences over time.

### How to Run the Notebooks

Before running the notebooks, make sure you have the following prerequisites installed:

- Python 3.6 or higher
- Jupyter Notebook or JupyterLab
- Required Python packages: `pandas`, `numpy`, `selenium`, `beautifulsoup4`, `sqlalchemy` (and any others that the notebooks depend on)

To install the required Python packages, you can use the following command:

```bash
pip install pandas numpy selenium beautifulsoup4 sqlalchemy
```
