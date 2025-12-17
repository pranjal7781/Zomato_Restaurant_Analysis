# Zomato Restaurant Data Analysis with Power BI  

An interactive dashboard built in Microsoft Power BI to analyze and visualize data from Zomato. This project aims to uncover trends and insights related to restaurant ratings, pricing, locations, and cuisines.

---
  
## 🎯 Project Overview

This dashboard provides a detailed analysis of Zomato's restaurant data. The goal is to empower users to explore key metrics through interactive visuals. By filtering data by city, rating, or cuisine, one can gain a deeper understanding of the restaurant landscape in different regions.

### Key Analyses & Insights:
* **Geographical Distribution:** Visualizes the concentration of restaurants across different countries and cities using a map visual.
* **Rating Analysis:** Segments restaurants into rating buckets (e.g., Poor, Average, Good, Excellent) to identify performance trends.
* **Cost vs. City:** A donut chart illustrating the distribution of restaurants based on their price range within top cities.
* **Cuisine Popularity:** A bar chart showcasing the top 10 most frequently offered cuisines.
* **Service Availability:** Analyzes the percentage of restaurants that offer online delivery and table booking services.

---

## 🛠️ Tech Stack & Tools

* **Microsoft Power BI:** Used for data modeling, transformation (Power Query), creating DAX measures, and building the interactive report.
* **Microsoft Excel :** Used as the primary data source for this project.

---

## 📂 Dataset 

The dataset used for this analysis contains detailed information for thousands of restaurants, including:
* `RestaurantID`: Unique identifier for each restaurant.
* `CountryCode`: Code for the country where the restaurant is located.
* `City`: The city of the restaurant.
* `Cuisines`: The types of cuisines offered.
* `Average_Cost_for_two`: The average cost for a meal for two people.
* `Price_range`: A categorical rating for the price (1 for cheap, 4 for expensive).
* `Aggregate_rating`: The average rating of the restaurant.
* `Has_Online_delivery`: Indicates whether online delivery is available.

---

## 🚀 How to Use

To explore this dashboard on your local machine:

1.  **Prerequisites:**
    * Make sure you have **Microsoft Power BI Desktop** installed.

2.  **Clone the repository:**
    ```sh
    https://github.com/pranjal7781/Zomato_Restaurant_Analysis.git
    ```

3.  **Open the Project:**
    * Navigate to the project folder and open the `Zomato restaurants analysis dashboard.pbix` file.

4.  **Interact:**
    * Once the file is open, you can interact with all the visuals, apply filters, and drill down into the data to explore insights.

---

## 📁 Repository Files

* `Zomato restaurants analysis dashboard.pbix`: The main Power BI project file.
* `zomato data - Sheet1.xlsx`: The primary dataset file.
* `zomato data - Sheet2.xlsx`: The country code mapping file.
* `README.md`: This file, providing an overview of the project.
* `Report Images` : An Image of the Power BI report.
