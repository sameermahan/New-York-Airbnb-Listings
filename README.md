# **📊 NYC Airbnb Listings 2024: EDA Project Overview**

## **✨ Objective**

To explore New York City Airbnb data using EDA techniques to uncover patterns in pricing, availability, reviews, and host behavior.

---

## **📂 Dataset**

- 20,765 listings across NYC’s five boroughs.
- 22 features including `price`, `room type`, `availability`, `reviews`, and `geolocation`.

---

## **⚙️ Workflow**

✅ **1. Data Cleaning**
- Handled missing data in `price`, `neighbourhood`, `beds`.
- Converted `last_review` to datetime.
- Capped outliers for prices above \$1,000.

✅ **2. Exploratory Data Analysis (EDA)**
- **Distribution:** Plotted histograms to show price and availability trends.
- **Correlations:** Heatmap revealed weak correlation between price and reviews, but stronger trends with availability and room type.
- **Neighborhoods:** Bar charts showed Manhattan has the highest prices; Brooklyn is next.
- **Room Types:** Entire home/apartments dominate listings, but private rooms are popular budget options.
- **Reviews:** Pairplots and scatter plots showed listings with more availability tend to get more reviews.

✅ **3. Visualization Highlights**
- 📌 **Heatmaps:** For numerical correlations.
- 📌 **Pairplots:** To check variable relationships.
- 📌 **Scatterplots & Maps:** Visualized geographic distribution and room type clusters.
- 📌 **Barplots:** Compared price dependencies across boroughs and room types.

---

## **🔑 Key Insights**

- 💵 **Price Trends:**  
  - Manhattan commands the highest average prices.  
  - Entire homes cost significantly more than private rooms.

- 🏘️ **Room Types:**  
  - Entire homes/apartments are the most common.  
  - Private rooms provide affordable alternatives.

- 📈 **Availability:**  
  - Listings with higher availability are often lower priced and have more reviews — possible indicator of good guest experience.

- 👥 **Host Behavior:**  
  - Some hosts have multiple listings — indicating professional property management.

---

## **✅ Recommendations**

**For Guests:**  
- Private rooms in Brooklyn provide budget-friendly stays.
- Listings with higher availability and good reviews can offer better experiences.

**For Hosts:**  
- Increase availability and responsiveness to reviews.
- Optimize pricing to stay competitive within each neighborhood market.

---

## **🔮 Next Steps**

- Use machine learning to predict prices based on room type, location, and other factors.
- Apply sentiment analysis on reviews to capture guest satisfaction.
- Build an interactive dashboard using Plotly or Tableau for dynamic insights.

---

## **🏆 Conclusion**

This EDA project provides clear insights for both Airbnb guests and hosts, helping them make informed decisions.  
It demonstrates strong data analysis, visualization, and storytelling skills — a valuable addition to any data analyst portfolio.


