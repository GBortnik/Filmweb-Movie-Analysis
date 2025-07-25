# Filmweb Movie Analysis

This project focuses on analyzing the top 500 movies ranked on **[Filmweb](https://www.filmweb.pl/)**, a popular Polish film website. The dataset was independently created through web scraping, enabling a comprehensive exploration of movie attributes, genres, ratings, and production details. The analysis aims to uncover patterns and insights within this curated selection of films.

🇵🇱 Polish version of the document can be found [here](/README-PL.md) / Polską wersję dokumentu można znaleźć [tutaj](/README-PL.md). 🇵🇱

## Contents
- [Workflow](#workflow)
- [Technologies](#technologies)
- [Sample Visualizations](#sample-visualizations)
- [Insights](#insights)

## Workflow
1. **WebScraping**: Collecting raw data by extracting information from the Filmweb website using automated web scraping techniques. The process concludes with exporting a structured dataset as a CSV file, which serves as the foundation for further analysis.

2. **Data Transformation**: Cleaning and preprocessing the scraped data, including handling missing values, converting data types, and restructuring columns for analysis.

3. **EDA (Exploratory Data Analysis)**: Performing initial data exploration to understand distributions, detect outliers, and identify relationships between variables.

4. **Data Visualization**: Creating static and interactive visualizations to illustrate key findings and patterns within the dataset.

5. **Presenting Insights**: Summarizing the main discoveries and conclusions, supported by visualizations and analysis results.

## Technologies

This project was developed using the following technologies:
- **Programming Language**: Python  
- **Development Environments**: Visual Studio Code, Jupyter Notebook  
- **Web Scraping**: Requests, BeautifulSoup, urllib, RegEx  
- **Data Analysis**: Pandas, NumPy, RegEx, pycountry, ast, collections.Counter  
- **Visualization**: Matplotlib, Seaborn, Plotly

## Sample Visualizations

### Static Visualizations:

![Visualization Samples](/Data%20Visualization/Visualization%20Samples.gif)

![Visualization Samples](/Data%20Visualization/Visualization%20Samples2.gif)

*All visualizations are available directly in the notebooks or as PNG files in the [Data Visualization](/Data%20Visualization/) folder.*

### Interactive Visualizations:

[![World Map](/Data%20Visualization/Country%20Visualizations/map_count.png)](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/map_count.html)
*Click the image or [here](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/map_count.html) to open the interactive version.*

[![Regions Donut Chart](/Data%20Visualization/Country%20Visualizations/regions_donut.png)](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/region_donut.html)
*Click the image or [here](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Country%20Visualizations/region_donut.html) to open the interactive version.*

[![Genres Combinations Treemap](/Data%20Visualization/Genres%20Visualizations/genres_treemap.png)](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Genres%20Visualizations/genres_treemap.html)
*Click the image or [here](https://htmlpreview.github.io/?https://github.com/GBortnik/Filmweb-Movie-Analysis/blob/main/Data%20Visualization/Genres%20Visualizations/genres_treemap.html) to open the interactive version.*

## Insights

The key insights and findings from this analysis are summarized in the presentation, available in both **[PowerPoint](/Filmweb%20Movie%20Analysis.pptx)** and **[PDF](/Filmweb%20Movie%20Analysis.pdf)** formats.
Please refer to these files for a detailed overview of the results and visualizations.