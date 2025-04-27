UNICEF Global Water & Health Insights

This project explores the intersection of water access and youth health using UNICEF datasets. It was developed as part of a university data science assignment focused on storytelling with data, leveraging Python, Polars, and Plotnine.

Project Summary

Title: Pipes, Pounds & Progress: A Global Look at Water Access and Youth Health**

Objective:
Analyze and visualize how piped water access correlates with public health indicators in youth populations globally.


Files

| File                          | Description                                         |
|-------------------------------|-----------------------------------------------------|
| `unicef_water_health_analysis.ipynb` | Google Colab Notebook with full analysis and visualizations |
| `unicef_water_health_analysis.html` | Exported Quarto HTML version of the report |
| `unicef_indicator_1.csv`      | UNICEF dataset on piped water access |
| `unicef_indicator_2.csv`      | UNICEF dataset on childhood overweight rates |
| `unicef_metadata.csv`         | Metadata and contextual socio-economic indicators |

Visualizations Included

- Choropleth Map: Global map showing % of population using piped water (by country)
- Bar Chart: Top 10 and Bottom 10 countries ranked by piped water access
- Line Plot: Time series trends of piped water access by UNICEF regional classification (2000–2020)
- Scatter Plot with Regression Line: Exploring the relationship between piped water access (%) and childhood overweight rates (%)
- Faceted Scatterplots: Regional comparisons of water access vs child health (small multiples for each region)


Tools & Libraries

- [Python](https://www.python.org/)
- [Plotnine](https://plotnine.readthedocs.io/)
- [Polars](https://pola-rs.github.io/polars/)
- [Quarto](https://quarto.org/) for publishing


Key Insights

- Limited water infrastructure correlates strongly with poor health outcomes among youth.
- Significant disparities exist across countries and regions, as well as over time.
- Data-driven storytelling enhances the understanding of global water and health challenges.


License

This project is for educational purposes only.  
Data is sourced from [UNICEF](https://data.unicef.org/) and [World Bank Open Data](https://data.worldbank.org/).


 Created by Yash Ghadigaonkar with student number (A00013230)