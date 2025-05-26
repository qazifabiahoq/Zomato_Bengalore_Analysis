

# Zomato Restaurants in Bangalore: In-Depth Analysis

## Objective

This project explores the dining landscape of Bangalore using Zomato data, aiming to uncover trends in online ordering behavior, customer sentiment, and cuisine preferences. The objective is to generate insights that support entrepreneurs, food service strategists, and urban planners in making data-informed decisions.

### Who Will Benefit and Why?

* **Restaurant Owners** can learn where to set up shop and what customers value in dining experiences.
* **Food Entrepreneurs** can discover what cuisines are in demand and where.
* **Marketers** can use review sentiment and keyword patterns for targeted messaging.
* **Urban Planners & Investors** gain clarity on food density and location strategy.

---

## Dataset Overview

Sourced from [Kaggle](https://www.kaggle.com/code/manzoormahmood/analysis-of-zomato-restaurants-in-bangalore), this dataset contains information about restaurants in Bangalore, including:

* **Restaurant Name**
* **Location and Area**
* **Online Order Availability**
* **Rating**
* **Cuisine Types**
* **Customer Reviews**

The project was guided by the Udemy course:
[Data Analytics: Real World Project in Python](https://www.udemy.com/course/data-analytics-projects-python/)

---

## Methodology

* **Tools Used**: Python, Pandas, Matplotlib, Seaborn, NLP (Natural Language Processing), Folium
* **Preprocessing**: Cleaned missing values, categorized cuisine types, and tokenized text for sentiment analysis
* **Key Analyses Conducted**:

  * Correlation between **online ordering** and **ratings**
  * **Text mining** of customer reviews
  * **N-gram analysis** (Unigram, Bigram, Trigram)
  * **Geospatial mapping** of cuisine clusters
  * **Function-based automation** for cuisine-specific heatmaps

---

## 🔍 Key Findings

### 🍽️ Does Online Ordering Lead to Higher Ratings?

Yes. Restaurants that **accept online orders** and have a rating above **4.0** tend to receive **higher average ratings**. This suggests that digital convenience directly enhances customer satisfaction.

### 💬 What Do Customers Talk About Most?

Text analysis of **Quick Bites** restaurant reviews shows frequent mentions of:

* **“Place”**, **“Food”**, **“Good”**, **“Chicken”**, and **“Taste”**
  These keywords highlight that **ambience and flavor** are key factors in customer experiences.

### 🧠 What Phrases Keep Reappearing?

* **Top Unigrams**: food, place, good
* **Top Bigrams**: good food, nice place
* **Top Trigrams**: good place food
  This reveals that **concise and consistent language** in reviews aligns with customer satisfaction and reinforces branding strategies.

### 📍 Where Are Most North Indian Restaurants Located?

The highest concentration of **North Indian restaurants** is in **Central Bangalore**, making it a hot zone for that cuisine. This can guide expansion strategies for similar food offerings.

### 🔄 Can This Analysis Be Applied to Other Cuisines?

Yes. A **custom function** was created to automate heatmap generation by cuisine type—allowing **scalable exploration** across South Indian, Chinese, Italian, and more.

---

## 🧾 Conclusion

The project uncovers a rich narrative of Bangalore's dining scene. Higher ratings are tied to online accessibility, customer reviews highlight what matters most, and certain cuisines dominate specific geographic clusters. This analysis supports both micro (restaurant-level) and macro (city-level) decision-making.

---

## 💡 Recommendations

* Emphasize **online ordering options** to attract more favorable reviews.
* Use **keyword insights** to shape promotional content and menu descriptions.
* Consider **location-based expansion** in Central Bangalore for North Indian and Quick Bites-style outlets.
* Apply the **automated heatmap tool** to evaluate new cuisine trends in other city zones.

---

## 📂 Project Source & Attribution

* **Dataset**: [Kaggle - Zomato Bangalore](https://www.kaggle.com/code/manzoormahmood/analysis-of-zomato-restaurants-in-bangalore)
* **Course Reference**: [Udemy - Data Analytics: Real World Project in Python](https://www.udemy.com/course/data-analytics-projects-python/)

The `pics` folder contains **geospatial maps** for North Indian and South Indian restaurant concentrations. Feel free to explore or download the findings.

---

