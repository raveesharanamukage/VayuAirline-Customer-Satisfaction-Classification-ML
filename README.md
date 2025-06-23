# VayuAir Customer Satisfaction Analysis

This project is a consulting engagement with VayuAir, a new airline in Australia, focused on analyzing customer satisfaction to improve service quality. Using a customer survey dataset, I performed exploratory data analysis, data preprocessing, and predictive modeling to identify factors influencing satisfaction and predict customer outcomes. Key tasks included:

- **Data Exploration**: Analyzed the dataset (11,006 records, 25 features) to understand customer demographics, travel details, and satisfaction levels (56.61% satisfied, 43.39% dissatisfied).
- **Data Preprocessing**: Handled missing values, encoded categorical variables (e.g., Gender, Customer Type) using LabelEncoder, standardized numerical features, and split data into training (80%) and test (20%) sets.
- **Correlation Analysis**: Computed a correlation matrix to identify relationships between numerical features (e.g., strong correlations between Cleanliness, Seat Comfort, and Satisfaction).
- **Visualization**: Used `missingno` for missing data visualization and `seaborn`/`matplotlib` for correlation heatmaps to highlight feature relationships.
- **Modeling**: Implemented a Logistic Regression model to predict satisfaction, achieving an accuracy of 87.42% on the test set, evaluated using a confusion matrix.
- **Insights**: Identified key drivers of satisfaction (e.g., Inflight Entertainment, Online Check-in, Flight Distance) and dissatisfaction (e.g., Departure/Arrival Delays), providing actionable recommendations for improving booking, airport services, and in-flight experiences.

These insights support VayuAir’s goals of enhancing customer engagement and retention through targeted service improvements.

## Google Colab Notebook
Explore the full analysis and code in the [Google Colab Notebook](https://colab.research.google.com/drive/1vMKClck0gW9WlHlyZ0S66_XmZqA_7pjB?usp=sharing).
