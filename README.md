# Zomato Restaurant Data Analysis & Recommendation System

This project performs **Exploratory Data Analysis (EDA)** and builds a **content-based restaurant recommendation system** using Zomato’s global restaurant dataset. It helps users gain deep insights into food preferences, restaurant quality, pricing, and makes intelligent restaurant suggestions based on city, cuisine, and ratings.

---

## Project Objectives

- Analyze restaurant trends across countries and cities
- Answer 25+ business-critical EDA questions
- Visualize cuisine popularity, cost trends, and customer engagement
- Build a restaurant recommender based on user preferences

---

## Key Insights & Business Value

This content-based recommendation system leverages restaurant name, cuisines, city, and aggregate rating to suggest similar restaurants using TF-IDF and cosine similarity. It supports partial name matching and filters by city to ensure contextually relevant suggestions. By incorporating ratings into vectorization, it prioritizes quality over just textual similarity.

From a business perspective, this solution enhances user experience by enabling personalized discovery, improving engagement on food platforms, and increasing retention. It can be integrated into restaurant review apps, food delivery platforms (like Zomato or Swiggy), or smart city dining guides to recommend high-quality, relevant alternatives — boosting both customer satisfaction and platform stickiness.

---

## EDA Questions Answered

1. Which locations have the most restaurants?  
2. Which cuisines are most popular?  
3. Top-rated restaurants in major cities  
4. Cost vs Rating — is expensive food better rated?  
5. Online delivery vs Rating  
6. Type of restaurants (Casual, Fine Dining, etc.)  
7. Restaurants with max votes  
8. Cities with highest average ratings  
9. Which city has the widest variety of cuisines?  
10. Localities with top-rated restaurants in major cities  
11. Are low-cost restaurants well-rated in some cities?  
12. Cities with most votes per restaurant  
13. Cities with highest % of fine-dining places  
14. Which cuisines are most highly rated on average?  
15. Cuisines commonly found in low-rated restaurants  
16. Cuisine preferences in Bangalore, Delhi, Mumbai  
17. Average cost across cuisines  
18. Cuisines with most average votes  
19. Most popular restaurant types by city  
20. Best cost-efficiency by type (high rating, low cost)  
21. Cities with best-rated food at lowest average cost  
22. Does price range correlate with votes or ratings?  
23. Underrated restaurants (high votes, low rating)  
24. Controversial restaurants (low rating, high votes)  
25. Feature correlation with rating (heatmap)  
26. Clustering by cost & rating (KMeans, Scatter Plot)  
27. Do tourist cities perform better in rating than metros?

---

## Recommendation System

- **Input**: Restaurant name (partial/full) + city  
- **Output**: Suggests top similar restaurants in the same city  
- **Technique**: TF-IDF + Cosine Similarity  
- **Smart Matching**: Works even if only part of the name is entered (`"barbeque nation"` will also match `"The Barbeque Company"`, etc.)

---

## Project Structure

```
📁 Zomato-Restaurant-EDA
│
├── zomato_analysis.ipynb       # Jupyter Notebook with code, EDA, and recommender
├── zomato.csv                  # Dataset file
├── images/                     # Folder containing all saved plots
└── README.md                   # This file
```

---

## Tech Stack

- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Modeling**: TF-IDF, Cosine Similarity, KMeans Clustering
- **Visualization**: Matplotlib & Seaborn

---

## How to Run This Project

1. Clone the repository or download the folder  
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the Jupyter Notebook:

```bash
jupyter notebook zomato_analysis.ipynb
```

4. All plots are saved in `images/` folder using `plt.savefig()`

---

## Sample Visualizations

You can find all the generated charts in the `images/` folder:
- Top cuisines across cities
- Cost vs Rating heatmap
- Votes distribution by city
- Clustering of restaurants by cost and rating

---

## Conclusion

This project showcases the power of **EDA combined with machine learning** to solve real-world business problems in the food & hospitality sector. From **customer behavior analysis** to **intelligent restaurant suggestions**, this project is a complete data science solution.

---

## Author

 **Mansi Varshney** 

--- 
© 2025 Mansi Varshney. All rights reserved.  
This project is for educational and demonstrative purposes only.  
Unauthorized copying or distribution of any part of this project is strictly prohibited.
"""
---

⭐ *If you liked this project, don't forget to give it a star on GitHub!*
