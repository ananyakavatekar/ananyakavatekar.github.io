
---
layout: default
permalink: /
---

# IS 445 Homework 5.1
Ananya Kavatekar

## Chart 1: License Counts by Status

<iframe src="/chart1.html" width="100%" height="750" style="border:none;"></iframe>

This visualization shows the number of license records by status for a selected state and license type. The X-axis uses nominal encoding for license status, while the Y-axis uses quantitative encoding for the number of records. A single bar color avoids misleading associations between colors and statuses. The data was prepared by selecting the State, License Type, and License Status columns, with counts calculated in Altair.

Two dropdown menus allow users to select a state and license type, with Illinois selected by default. This allows users to explore the distribution of license statuses across different categories.

## Chart 2: Active Licenses in Illinois

<iframe src="/chart2.html" width="100%" height="460" style="border:none;"></iframe>

This visualization showcases the percentage of active licenses for each of the ten most common license types within Illinois in the dataset. The license types are ordered in descending order from top to bottom, with the greatest proportion of active licenses at the top and the lowest at the bottom. The Y-axis uses nominal encoding for license type, while the X-axis uses quantitative encoding for the percentage of active licenses. A single bar color is used throughout. I filtered the data to Illinois, selected the ten most common license types, and calculated the proportion of active licenses in each category.

## Data and Analysis

[The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/licenses_fall2022.csv)

[The Analysis](https://github.com/ananyakavatekar/ananyakavatekar.github.io/blob/main/python_notebooks/HW5_1.ipynb)
