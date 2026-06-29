![NYC Skyline](New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2.jpg)

# 🗽 NYC Airbnb Market Analytics: A Geospatial & Pricing Study

## 📋 Project Overview
This project is a high-level Exploratory Data Analysis (EDA) investigating the 2024 New York City Airbnb landscape. Moving beyond basic statistics, I utilized Python to analyze pricing dynamics, borough-wise cost efficiency, and the professionalization of the short-term rental market.

> **💡 Key Takeaway:** This study reveals a market shift where professional, full-time hosts dominate the NYC landscape, challenging the original "home-sharing" ethos of the platform.

---

## 🛠️ Technical Workflow
* **Data Cleaning:** Handled missing coordinates, corrected data types for 20k+ records, and resolved duplication issues to ensure 100% analytical accuracy.
* **Fixing Outliers:** Identified and mitigated price outliers (reaching up to $100,000) using boxplot analysis, setting a ceiling of $2,000 to focus on core market trends.
* **Feature Engineering:** Developed a custom **"Price per Bed"** metric to identify true cost-efficiency across different neighborhood groups.
* **Geospatial Mapping:** Leveraged Latitude and Longitude data to visualize listing density and room-type distribution across NYC.

## 🎨 Data Visualization & Insights
* **Correlation Heatmaps:** Analyzed relationships between price, availability, and review frequency using Seaborn Heatmaps.
* **Borough Distribution:** Proved **Manhattan** as the luxury leader ($208 avg) vs. the **Bronx** as the budget-friendly alternative ($108 avg).
* **Host Behavior Analysis:** Identified a massive spike in 365-day availability, proving the market is dominated by **professional, full-time hosts** rather than casual home-sharers.
* **Inverse Feedback Loop:** Discovered that lower-priced units attract significantly higher review volumes, suggesting higher guest turnover.

## 🧰 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Tool:** Jupyter Notebook

---

## 🚀 How to Run this Project
1. **Clone the repository:** `git clone https://github.com/unpredictableuser/NYC-Airbnb-Data-Analysis.git`
2. **Install dependencies:** `pip install pandas numpy matplotlib seaborn`
3. **Launch the analysis:** Open `AirBnb.ipynb` in Jupyter Notebook or VS Code to see the step-by-step cleaning and visualization process.

## 🔮 Future Improvements
* **Sentiment Analysis:** Extracting common themes from the `name` column to see how listing descriptions affect price.
* **Interactive Dashboard:** Converting these static Seaborn plots into an interactive **Tableau** or **Power BI** dashboard.

---

## 👋 Let's Connect!
* **LinkedIn:** [Mohammad Gazali Sultan](https://www.linkedin.com/in/mohd-gazali-980158289?utm_source=share_via&utm_content=profile&utm_medium=member_android)
* **Portfolio:** [Check out my other projects](https://github.com/unpredictableuser)
