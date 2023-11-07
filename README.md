
# Mars Exploration Data Scraper

This repository hosts Python code for gathering and examining data on Martian weather patterns. The work is partitioned into two sections:

## Part 1: News Article Scraper

The script in `part_1_mars_news.ipynb` employs Splinter and Beautiful Soup to automate the extraction of article titles and summaries from a Mars-focused news outlet. The collected entries are stored as Python dictionaries and displayed.

## Part 2: Meteorological Data Analysis

Utilizing Beautiful Soup in `part_2_mars_weather.ipynb`, we collect meteorological data from a dedicated Mars data source. Analysis performed includes:

- Determining the count of Martian months.
- Assessing the volume of sols (Martian days) captured in the dataset.
- Identifying months with extreme temperature variances.
- Analyzing atmospheric pressure trends.
- Estimating the equivalent of a Martian year in Earth days.

Data visualization is accomplished through bar charts, and a comprehensive DataFrame is compiled and exported as a CSV file for potential further analysis.
