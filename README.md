# Pizza Sales Analysis Report

This repository contains a Power BI dashboard that provides insights into pizza sales data, including top-selling pizzas, quantity sold by category and size, transaction analysis over time, most-used ingredients, and more.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data Model](#data-model)
- [Insights](#insights)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The **Pizza Sales Analysis Report** is a Power BI dashboard designed to help stakeholders understand:
- Which pizzas are top sellers and how much revenue they generate.
- Transaction patterns by time of day and month.
- Ingredient usage trends (via word cloud).
- How quantity sold varies by category (e.g., Classic, Supreme, Veggie, Chicken) and size.

![Pizza Dashboard Screenshot](pizza%20dashboard.png)

> **Note**: The above screenshot shows the main landing page of the Power BI report.

---

## Features

- **Top-Selling Pizzas:** Identify pizzas that generate the highest revenue.
- **Time-based Transaction Analysis:** Visualize how sales fluctuate throughout the day and by month.
- **Ingredient Word Cloud:** Understand the most commonly used ingredients.
- **Quantity by Category and Size:** Compare how different pizza categories and sizes perform.
- **Slicers and Filters:** Segment sales data by time of day, season, category, and size to get more granular insights.

---

## Getting Started

1. **Clone or Download this Repository**
   ```bash
   git clone https://github.com/your-username/pizza-sales-analysis.git
Open the Power BI File

Locate the chuks pizza.pbix file (or similar) in the repository.
##  Open it using Power BI Desktop.
Data Refresh (Optional)

If you have updated source data, you can refresh the dataset in Power BI to reflect the latest information.
## Usage
Once opened in Power BI Desktop:

Navigate Through Pages: Explore different report pages to see the various visualizations.
Interact with Filters and Slicers: Filter data by time of day, season, size, and pizza category to see how metrics change.
Drill Down in Visuals: Click on bars or charts to drill deeper into the data for detailed insights.
Export or Share: Export the report or share it within your organization for collaborative analysis.

## Data Model
The underlying data model (not shown here for brevity) typically includes:

- Orders Table: Contains order IDs, timestamps, and sales figures.
Pizza Details Table: Includes pizza names, categories, sizes, and ingredient lists.
Calendar/Date Table: Facilitates time intelligence (e.g., month names, day of week, etc.).
This star schema approach ensures efficient slicing and dicing of data for optimal Power BI performance.

## Insights
Key takeaways from the analysis may include:

- Peak Sales Time: The busiest hours for pizza orders (e.g., evening).
- Top-Selling Category: Which category (e.g., Classic, Supreme) generates the highest revenue.
-  Seasonal Trends: Whether certain seasons see higher demand.
- Ingredient Popularity: The most frequently used or popular ingredients.
- Use these insights to drive marketing strategies, optimize inventory, and improve operational efficiency.

## Contributing
Contributions are welcome! To propose changes:

## Fork this repository.
- Create a new branch (git checkout -b feature/my-feature).
- Commit your changes (git commit -m "Add a new feature").
- Push to the branch (git push origin feature/my-feature).

## Open a Pull Request on GitHub.
##License
This project is licensed under the MIT License. Feel free to use and modify this code for your own purposes.
