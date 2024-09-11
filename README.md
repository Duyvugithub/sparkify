# Sparkify Churn Prediction Analysis

## Project Motivation
The goal of this project is to perform an in-depth analysis of user interactions with the Sparkify application. By examining log files and user behaviors, we aim to develop a predictive model for churn rates. This will help Sparkify identify at-risk users and improve their application to enhance user retention.

I also make article in this link: https://medium.com/@vu38988/analyzing-user-churn-at-sparkify-a-data-driven-approach-f55fcc2d2566

## Libraries Used
- **pandas**: For data manipulation and analysis.
- **matplotlib**: For creating static, animated, and interactive visualizations.
- **seaborn**: For statistical data visualization.
- **pyspark**: For large-scale data processing and machine learning tasks.

## File Structure
- **Sparkify.ipynb**: The Jupyter notebook containing the main analysis. This file includes data preprocessing, exploratory data analysis, feature engineering, and model training. The notebook provides detailed insights into user behavior and churn prediction.

## Results
Our analysis identified several key areas where Sparkify can improve:
- **User Interaction Insights**: High interaction with certain pages like "Settings" and "Save Settings" among churners suggests potential issues with user customization and UI. Enhancements in these areas could improve user experience and reduce churn.
- **Content and Advertising**: Increased engagement with pages related to upgrades and advertisements indicates areas where Sparkify could refine content and advertising strategies.
- **Model Performance**: A Random Forest model was deployed, achieving an F1-score of approximately 63%. This model serves as a baseline for future improvements in predicting churn rates.

## Acknowledgements
- **Sparkify Team**: For providing the dataset and supporting the project.
- **Community Resources**: For tutorials and documentation on PySpark, pandas, matplotlib, and seaborn that facilitated the data analysis and modeling processes.
