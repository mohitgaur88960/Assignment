# Power BI Dashboard - Orders and Metrics

This repository contains a Power BI dashboard that visualizes key metrics and insights related to orders, meal types, and user activity. Below are the details about the dashboard and its components.

---

## Overview

The dashboard is designed to provide insights into:
- **Order Status**: Tracking completed and canceled orders.
- **Meal Types**: Analyzing the distribution of orders by meal types (Breakfast, Lunch, Dinner).
- **Order Details**: A detailed breakdown of users, meal preferences, locations, and dish-specific metrics.
- **Key Metrics**: Total orders, total amount, and averages for user spending and dish pricing.
- **Visualization**: Bar charts and tables to analyze trends and patterns in the data.

---

## Findings

Here are the key insights from the dashboard:

1. **Meal Type Distribution**:
   - **Dinner** is the most frequently ordered meal, followed by **Lunch**, with **Breakfast** being the least ordered.
   
2. **Revenue Generation**:
   - The total revenue generated is **$156.50** across 14 orders, with an average order value of **$11.18**.

3. **Top Performing Dishes**:
   - **Grilled Chicken** has the highest revenue ($38.50) among all dishes, while **Spaghetti** has the highest average order value ($13.88).
   
4. **User Activity**:
   - **Alice Johnson** and **Bob Smith** placed the highest number of orders (3 each), contributing significantly to the total revenue.
   - **Breakfast** is preferred by younger users, while **Dinner** is more popular with older age groups.

5. **Location Insights**:
   - **Los Angeles** and **New York** have the highest number of orders (3 each), contributing $31 and $35 in revenue respectively.

6. **Time Duration by Age**:
   - Users aged **25** spend the most time per order, with a gradual decline in duration among other age groups.

---

## Components of the Dashboard

### 1. Filters
- **Order Status**: A slicer to filter orders by "Canceled" or "Completed" status.
- **Meal Type**: A slicer to filter orders by meal type (Breakfast, Lunch, Dinner).

### 2. Key Performance Indicators (KPIs)
- **Total Amount**: Displays the total revenue generated ($156.50).
- **Total Orders**: Shows the total number of orders (14).

### 3. Tables
- **User Details**:
  - User ID
  - User Name
  - Total Orders
  - Total Amount
  - Average Order Value
  - Favorite Meal
- **Dish Details**:
  - Dish Name
  - Total Orders
  - Total Amount
  - Average Price
- **Location Details**:
  - Location
  - Count of Users
  - Total Amount

### 4. Visualizations
- **Total Order by Meal Type**:
  - A bar chart showcasing the distribution of orders across Breakfast, Lunch, and Dinner.
- **Average of Duration (mins) by Age**:
  - A bar chart visualizing average time spent (in minutes) by age group.

---

## Usage Instructions

1. **Data Source**
   - The dashboard is powered by a dataset containing user details, order data, and meal preferences.
   - Ensure the dataset is updated and connected in Power BI Desktop to reflect real-time insights.

2. **Customization**
   - Add more filters or metrics based on your requirements.
   - Modify visuals or styles to match your branding or presentation needs.

3. **Sharing**
   - Export the dashboard to Power BI Service or PDF for sharing with stakeholders.
   - Publish it to Power BI Workspace for online access.

---

## How to Contribute

1. Fork this repository.
2. Make modifications to the Power BI file as needed.
3. Submit a pull request for review.

---

## Contact

For questions or feedback, feel free to reach out to the repository maintainer.

---

## Source Code

The Power BI dashboard file and related scripts are stored in this repository. Ensure you have the following tools to open and edit:
- **Power BI Desktop**: To view and modify the `.pbix` file.
