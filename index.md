layout: default
title: HW5 Visualization
---

# Visualization 1: Building Usage Distribution

<vega-lite spec="chart1.json"></vega-lite>

This visualization shows the distribution of buildings by their primary usage. The x-axis represents different building usage categories, while the y-axis shows the count of buildings in each category. I used color encoding to distinguish between categories, which improves readability and allows easier comparison. The data was aggregated by counting the number of buildings in each category.

---

# Visualization 2: Building Size vs Acquisition Year

<vega-lite spec="chart2.json"></vega-lite>

This visualization explores the relationship between building size and acquisition year. The x-axis represents the year acquired, and the y-axis represents square footage. I used an interactive selection feature that allows users to highlight points, making it easier to explore patterns and trends over time. This improves the user’s ability to focus on specific subsets of the data.

---

# Data

https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv

---

# Analysis

https://github.com/xuyiw2/is445_HW5/blob/main/IS445_HW5.ipynb
