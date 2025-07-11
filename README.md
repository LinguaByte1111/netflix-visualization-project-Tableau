# 📊 Netflix Visualization Project (Tableau)

This project showcases interactive data visualizations of Netflix content using **Tableau**. The goal is to uncover insights into Netflix's content catalog, such as trends by genre, release year, country, and more, to better understand how Netflix's library has evolved over time.

---

## 📌 Project Overview

Netflix has become a global leader in streaming entertainment. This dashboard project explores:

- Content distribution by type (Movie vs. TV Show)
- Trends in release years
- Genre popularity
- Country-wise content production
- Ratings and duration breakdown
- Temporal trends (e.g., what years had the most releases)

All visualizations were built using **Tableau Desktop** based on a publicly available dataset.

---

## 📁 Repository Structure

\`\`\`
netflix-visualization-project/

├── data/
      │ 
│     └── netflix_titles.csv

├── images/
      │ 
│     └── dashboard_screenshots.png

├── Tableau/
      │ 
│     └── Netflix_Dashboard.twbx

├── README.md
\`\`\`

---

## 📊 Tableau Dashboard

> You can view the interactive dashboard here: [**Tableau Public Link**](https://public.tableau.com/app/profile/yourusername/viz/netflix_dashboard)

*Note: Replace the above link with your actual Tableau Public link.*

### Dashboard Highlights:
- **Interactive Filters** for country, content type, and years.
- **Time Series Charts** for release trends.
- **Bar Charts & Maps** showing top-producing countries and most common genres.

---

## 🧾 Dataset

- **Source**: [Netflix Titles Dataset - Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Fields Included**:
  - \`title\`, \`type\`, \`director\`, \`cast\`, \`country\`, \`date_added\`, \`release_year\`, \`rating\`, \`duration\`, \`listed_in\`, \`description\`

---

## 🛠 Tools Used

- **Tableau Desktop**
- **Microsoft Excel / Google Sheets** (for minor cleaning)
- **Kaggle Dataset** (for data source)

---

## 🚀 Getting Started

To explore the dashboard locally:
1. Clone the repo:
   \`\`\`bash
   git clone https://github.com/yourusername/netflix-visualization-project.git
   \`\`\`
2. Open the \`.twbx\` file in **Tableau Desktop**.
3. Make sure \`netflix_titles.csv\` is available in the same folder for data linkage.

---

## 📷 Preview

![Netflix Dashboard Preview](images/dashboard_screenshots.png)

---

## 🙋‍♂️ Contact

Feel free to connect or reach out:
- GitHub: [yourusername](https://github.com/yourusername)
- Tableau Public: [yourusername](https://public.tableau.com/app/profile/yourusername)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

⭐ If you found this helpful, feel free to star the repo and share your feedback!
EOF

cd netflix-visualization-project && git init && git add . && git commit -m "Initial commit: Added README and folder structure"
