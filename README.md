# cognifyz_internship
# 🍽 Restaurant Data Analysis & Visualization

## 📌 Project Overview
This project analyzes a dataset of restaurants (`restaurants.csv`) to uncover trends in customer reviews, votes, pricing, cuisines, services, and geographic locations.  
It includes multiple analytical tasks, each producing insights and visualizations.

---

## 📂 Dataset
- **File:** `restaurants.csv`
- **Encoding:** `utf-8` or `latin-1` (depending on the source)
- **Key Columns Used:**
  - `Restaurant Name`
  - `Cuisines`
  - `Aggregate rating`
  - `Votes`
  - `Price range`
  - `Has Online delivery`
  - `Has Table booking`
  - `Reviews` or similar column
  - `Longitude`, `Latitude`, `City`

---

## 📝 Tasks Performed

### **Task 1: Review Length vs Rating**
- Extracted review text length.
- Compared review length against aggregate ratings using a boxplot.
- **Output:** `output/level3_review_length_vs_rating.png`

### **Task 2: Votes Analysis**
- Identified highest and lowest voted restaurants.
- Calculated correlation between votes and ratings.
- Scatter plot of votes vs aggregate rating.
- **Output:** `output/level3_votes_vs_rating.png`

### **Task 3: Price Range vs Services**
- Analyzed how online delivery and table booking availability vary across price ranges.
- Generated stacked bar charts.
- **Outputs:**
  - `output/level3_delivery_by_price.png`
  - `output/level3_booking_by_price.png`

### **Task 4: Restaurant Ratings Distribution**
- Counted frequency of each aggregate rating.
- Identified most common rating.
- Calculated average votes per restaurant.
- Bar chart of rating distribution.

### **Task 5: Cuisine Combinations**
- Found top 10 cuisine combinations.
- Calculated average ratings for each top cuisine.
- Horizontal bar chart for ratings by cuisine.

### **Task 6: Geographic Analysis**
- Plotted restaurant locations on a longitude-latitude scatter plot, colored by city.

### **Task 7: Restaurant Chains**
- Identified restaurants with multiple outlets.
- Calculated and plotted average ratings for top chains.

### **Task 8: General Insights**
- Found top 3 cuisines by percentage.
- Identified the city with most restaurants.
- Found the city with highest average rating.
- Analyzed price range distribution.
- Compared ratings between restaurants with and without online delivery.

---

## 📊 Visualizations
Generated visualizations include:
- Review length vs rating (boxplot)
- Votes vs rating (scatterplot)
- Online delivery & table booking by price range (stacked bar charts)
- Rating distribution (bar chart)
- Cuisine ratings (bar chart)
- Restaurant locations (scatter plot)
- Top chain ratings (bar chart)
- Price range distribution (bar chart)

---

## ▶️ How to Run
1. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
