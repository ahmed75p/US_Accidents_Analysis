🚗 US Accidents Analysis

📌 Overview

This project analyzes road accidents in the United States using a dataset that contains detailed information about each accident, including location, severity, weather conditions, and time.
The goal is to clean and prepare the data, then build interactive dashboards to explore accident patterns and understand the impact of weather and time on accident severity.



🎯 Objectives

1. Identify accident-prone states, cities, and streets.
2. Analyze the distribution of accident severity levels.
3. Explore the impact of weather conditions on accidents.
4. Visualize trends over time (daily, monthly, yearly).
5. Provide insights for road safety and policy recommendations.



📊 Dataset

The dataset includes:
Accident ID: Unique identifier for each accident
Location: Street, city, and state
Severity Level: Four levels indicating accident severity
Weather Conditions: Temperature, humidity, pressure, visibility, wind direction, weather status
Time & Date: Date and time of the accident

⚠️ Due to file size, the full dataset is not included in this repository.
A sample dataset is provided, and the original data can be found at: [https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents]



🛠️ Data Cleaning (Python)

Data preprocessing and cleaning steps included:
Removing missing values
Renaming columns and removing spaces
Removing duplicate records
Converting data types
Preparing the dataset for visualization
Tools used: Python (Pandas, NumPy, Matplotlib, Seaborn)



📈 Data Visualization (Power BI)

Two interactive dashboards were created in Power BI:

1-Location & Datetime Dashboard

 * Total number of accidents
 * State with the highest number of accidents
 * Peak times for accidents
 * Graphs showing accident distribution by location, date, and time

2-Weather Effect Dashboard

 * Temperature, humidity, visibility, and pressure levels linked to the highest accident counts
 * Graphs showing how weather conditions affect accident frequency



📂 Project Structure

📁 US_Accidents_Project

│── data/ # Raw and cleaned datasets


│── notebooks/ # Jupyter notebooks for analysis


│── images/ # Screenshots of dashboards


│── report/ # Power BI dashboard and final report


│── README.md # Project documentation



🚀 Tools & Technologies

Python: Data cleaning and preprocessing
Power BI: Data visualization and dashboards
Excel/CSV: Data storage format
GitHub: Project hosting and version control



📌 Key Insights
Most accidents occur in specific states and during peak traffic times.
Weather conditions such as low visibility, high humidity, and certain temperatures have a strong correlation with accident frequency.




📷 Sample Dashboard:

[Location & Datetime](https://github.com/ahmed75p/US_Accidents_Analysis/blob/main/images/Screenshot%20.png)


[Weather Effect](https://github.com/ahmed75p/US_Accidents_Analysis/blob/main/images/Screenshot%202025-09-10%20033948.png)


🔮 Future Work
- Build a predictive model to estimate accident severity.
- Enhance dashboard with real-time accident data streams.



🤝 Contributing
Contributions, issues, and feature requests are welcome.




📬 Contact
Ahmed Mostafa
📧 ahmedmostafa75p@gmail.com


🌐 [LinkedIn Profile](https://www.linkedin.com/in/ahmed-mostafa-841412250/)









