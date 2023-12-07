# <center>Data Visualization 2 -  Assignment</center>

-----------------------------------------------------------------------------------------------------------

**1. Dataset description:**

`The World Happiness Report` is a landmark survey of the state of global happiness. This report reviews the state of happiness in the world in 2021. The dataset measures happiness through:
- `economic production`,
- `social support`,
- `life expectancy`,
- `freedom`,
- `absence of corruption` and
- `generosity`.

`Dystopia`: a hypothetical country that has values equal to the world’s lowest national averages for each of the six factors. These dimensions contribute to making life evaluations higher in each country than they are in the Dystopia column.

`Ladder score`: The main scale that I am considering in the analysis. The Cantril ladder asks respondents to think of a ladder, with the best possible life for them being a 10 and the worst possible life being a 0. They are then asked to rate their own current lives on that 0 to 10 scale.

`Social support score`: Another significant measurement I take into account in the analysis. Social support is the national average of the binary responses (0=no, 1=yes) to the Gallup World Poll (GWP) question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”

- Data source: [Kaggle](https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021/)
- Further information on the dataset: [World Happiness Report](https://worldhappiness.report/ed/2023/world-happiness-trust-and-social-connections-in-times-of-crisis/)

----------------------------------------------------------------------------------------------------------

**2. Workflow:**
- Importing the required libraries and loading data from my [GitHub Repo](https://github.com/zsofiarebeka/DataViz2)
- Data wrangling: renaming columns, filtering and checking for missing values
- Choosing the dimensions and variables for visualization
- Creating a variable and a unique list for Dash filtering purposes
- Creating the dash app and customizing the charts

-----------------------------------------------------------------------------------------------------------

**3. Output:**
- The scatter plot shows the level of happiness compared to GDP per capita by regions
- The bar chart shows the level of support for each country
- The aim of this dashboard is to compare how GDP per capita and the level of social support define the level of happiness of a country
- The aim of the multi dropdown list is to compare more regions
- To see the correct spacing of the charts, please see: http://127.0.0.1:8050/
