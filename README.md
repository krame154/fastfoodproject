
title: "Fast Food Unhealthiness vs. Popularity Analysis"

short_summary: >
  Analyzed the relationship between fast-food menu unhealthiness and restaurant popularity
  using real-world datasets. Built a custom health scoring system and visualizations to explore
  whether more unhealthy menus correlate with higher sales and brand success.

tech_stack:
  - Python
  - pandas
  - seaborn
  - matplotlib
  - Jupyter Notebook
  - Kaggle Datasets

problem_statement: >
  Fast food is widely consumed, yet its popularity is often driven by factors beyond nutrition.
  This project investigates whether there is a measurable relationship between how unhealthy
  a restaurant’s menu is and its overall popularity, using data-driven analysis.

approach: >
  Combined two datasets: a fast-food nutrition dataset and a dataset of top U.S. fast-food chains.
  Selected key nutritional variables (calories, sugar, saturated fat, trans fat, sodium) to represent
  unhealthiness. Developed a custom health score inspired by the Nutrient Profile Model (NPM),
  normalizing nutrient values relative to calories and comparing them to standard thresholds.

  Calculated average unhealthy scores for major chains including McDonald's, Burger King,
  Subway, Taco Bell, Chick-fil-A, Sonic, Dairy Queen, and Arby's. Compared these scores to
  popularity metrics such as systemwide sales, average sales per unit, and total store count.
  Created visualizations including scatter plots, heatmaps, and bar charts to identify patterns.

results_impact: >
  The analysis showed that there is no perfect direct correlation between unhealthiness and
  popularity. While many high-revenue chains had moderately high unhealthy scores, the most
  popular chain (McDonald's) did not have the highest unhealthiness rating. This suggests that
  factors such as brand recognition, pricing, and accessibility play a larger role in success
  than nutrition alone.

  This project demonstrates the ability to merge datasets, engineer meaningful metrics, and
  analyze real-world trends using data science techniques. It reflects practical skills in data
  cleaning, feature engineering, and visualization. :contentReference[oaicite:0]{index=0}

repo_url: "https://github.com/krame154/fastfoodproject"
image_path: "img/placeholder_project_1.png"
