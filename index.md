---
layout: default
title: HW5 Visualization
---

<script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-lite@5"></script>
<script src="https://cdn.jsdelivr.net/npm/vega-embed@6"></script>

# Visualization 1: Building Usage Distribution

<div id="vis1"></div>

<script>
vegaEmbed('#vis1', 'chart1.json');
</script>

This visualization shows the distribution of buildings by their status. The x-axis represents different building usage categories, while the y-axis shows the count of buildings in each category. I used color encoding to distinguish between categories, which improves readability and allows easier comparison. The data was aggregated by counting the number of buildings in each category.

---

# Visualization 2: Building Size vs Acquisition Year

<div id="vis2"></div>

<script>
vegaEmbed('#vis2', 'chart2.json');
</script>

This visualization explores the relationship between building size and acquisition year. The x-axis represents the year acquired, and the y-axis represents square footage. I used an interactive selection feature that allows users to highlight points, making it easier to explore patterns and trends over time. This improves the user’s ability to focus on specific subsets of the data.

---

# Data

[building_inventory.csv](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/building_inventory.csv)

---

# Analysis

[IS445_HW5.ipynb](https://github.com/xuyiw2/is445_HW5/blob/main/IS445_HW5.ipynb)
