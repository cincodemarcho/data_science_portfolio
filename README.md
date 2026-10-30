# Leo L. | Data Science Project Portfolio

## About
Leo is experienced in agile methodologies, software development, process engineering, product development, and innovation.  He enjoys utilizing his diverse background and competence to solve business problems. In addition, he speaks three languages: Business, IT, and Spanglish.  

## Skills/Tools
- **Languages:** Python, SQL
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn
- **Platforms:** Jupyter, Git, Spark, Hadoop, Google cloud

## Projects

The projects below come from my MS in Data Science (Bellevue University) program and are listed in the order I completed them, so the table doubles as a record of how my skills have grown.

I started with **exploratory analysis**: summarizing data, visualizing distributions, and testing hypotheses. Next came the less glamorous but essential work of **cleaning and combining messy data** from flat files, websites, and APIs into one usable dataset. From there I moved into **machine learning**, building regression and classification models and learning to choose metrics that fit the business problem instead of defaulting to accuracy. Along the way I focused on **communicating results**, turning analyses into data stories, interactive Tableau dashboards, and presentations tailored to specific audiences. My most recent work brings these skills together at a larger scale, with an **end-to-end big data pipeline** in the cloud and a predictive model built to avoid data leakage by using only information available before each game.

One lesson runs through all of it: an honest result is worth more than an impressive one. Several of these projects found weaker relationships than I expected, and I've learned to explain why, identify what the data is missing, and lay out what I'd try next.

| Project | Date | Description |
|---------|------|-------------|
| [Electric Vehicle Charging EDA](https://github.com/cincodemarcho/ev_charging) | March 2025 | Explored 1,000 EV charging sessions and found that no single factor (state of charge, charging cycles, current, or fast vs. slow mode) meaningfully explains charging time. Near-uniform distributions suggested a likely synthetic dataset missing key drivers like battery capacity. |
| [NBA player performance vs pay](https://github.com/cincodemarcho/nba_perf_vs_pay) | Aug 2025 | Combined a flat file, a scraped website, and an API into one SQLite database to compare 2025-26 salaries with on-court performance. Players earning over ~$20M are almost all elite scorers, but many lower-paid players score just as well. |
| [Video game global performance](https://github.com/cincodemarcho/video_game_perf) | Nov 2025 | Built regression models to predict a game's global sales from pre-release traits like platform, genre, publisher, and review scores. A tuned Random Forest performed best (18% lower error than linear regression), though blockbuster outliers kept overall accuracy modest (R² 0.20). |
| [Identifying and improving telco customer churn](https://github.com/cincodemarcho/telco_customer_churn) | March 2026 | Built classification models to flag at-risk customers, finding month-to-month contracts and short tenure to be the strongest churn signals (43% churn vs. 3% on two-year contracts). A Random Forest reached 0.84 ROC-AUC and informed four retention recommendations. |
| [TikTok car theft epidemic](https://github.com/cincodemarcho/tiktok_car_thefts) | April 2026 | A six-chart data story showing Kia/Hyundai thefts rising ninefold from 2019 to 2022, starting in Milwaukee more than a year before TikTok spread the trend nationwide. Ends with a call to action for affected owners. |
| [TSA Complaints](https://github.com/cincodemarcho/tsa_complaints) | May 2026 | An interactive Tableau dashboard showing TSA complaints falling during COVID-19, then surging to record highs in 2022-23, with Atlanta's complaints more than doubling. Drilling into subcategories reveals TSA PreCheck as a leading complaint driver. |
| [The childcare affordability crisis](https://github.com/cincodemarcho/childcare_affordability_crisis) | May 2026 | Analyzed county-level childcare prices and found infant care rose to 16.1% of household income by 2018, more than double the federal affordability benchmark, in 99.8% of counties with data. Told through a presentation, infographic, and Tableau dashboard, each tailored to a different audience. |
| [Big Data architecture](https://github.com/cincodemarcho/dsc650-final-project) | Aug 2026 | Built an end-to-end pipeline on Google Cloud and Docker that moves web-traffic data through NiFi, HDFS, Hive, Spark MLlib on YARN, and HBase. A K-Means model grouped suspicious traffic into three distinct clusters (silhouette score 0.99), with record counts verified at every stage. |
| [Predicting NBA player injury risk from in-season workload patterns](https://github.com/cincodemarcho/dsc680-project1) | Oct 2026 | Predicted whether players will be injured within 7 days using only pre-game workload data and a season-based train/test split. Workload showed a real but weak signal (0.59 ROC-AUC), independently supporting the NBA's own finding that schedule density has little link to injury. |
| Coming soon | Nov 2026 | DSC 680 Project 2 |

## Contact
[LinkedIn](https://www.linkedin.com/in/leoluera/)

