# Weather_Paterns_to_Forecast_Cafe_Sales

## **Description**
The "Weather_Patterns_to_Forecast_Cafe_Sales" project investigates the connection between weather variables and consumer behavior using LST, LGBM, Simple RNN, and Ridge Regression models. By deciphering how weather influences cafe sales, this study aids Small and Medium-sized Enterprises (UMKM) in optimizing inventory and resource management. The project empowers businesses to make informed decisions, reducing excess stock during low demand periods. Ultimately, it enhances UMKM operational efficiency, minimizing waste and maximizing effectiveness. This endeavor showcases data-driven decision-making, merging predictive techniques and weather insights to elevate cafe performance in varying climatic conditions.

**Note:** Please be aware that due to the sensitive nature of the sales data, the dataset used for this project cannot be publicly disclosed as it involves private information.

## **Project Code:**
Steps:
1. Define Problem
2. Installing needed Libraries
3. Data Collection
4. Data Pre-Processing
   - Fix the Dtype
   - Splitting data
   - Fixed Outlier
   - Feature Selection
   - Standard Scaler
5. Moddeling
    - LGBM
    - Ridge Regression
    - LSTM
    - Simple RNN
6. Measure accuracy of models
7. Conclusion

## **Installation**
1. Clone the repository: `git clone https://github.com/Lexuz17/Sentiment_Education_Analysis_Clustering.git`
2. Install the required dependencies: `pip install -r requirements.txt`

## **Results and Findings**

Following the analysis, several notable discoveries have surfaced, guiding the path for future projects:
1. **Importance of External Factors**, during Exploratory Data Analysis (EDA), notable outliers were identified in the point of sales data. This stemmed from not considering external aspects beyond weather, such as promotions and other factors. Future analyses should encompass these variables for a more holistic view.
2. **Weather-Point of Sales Correlation**, the correlation between weather conditions and point of sales was found to be low in the correlation matrix. This suggests limited influence of weather on sales. Consider shifting focus to variables like daily footfall or specific items sold, potentially showing stronger correlations.
3. **LGBM Model Superiority**, among the models employed, the LGBM model demonstrated superior sales forecasting performance. This standout performance can provide valuable insights for future decision-making.
4. **Further Projects**, despite the prominence of the LGBM model, further analysis remains essential. Future steps could involve ensemble methods to leverage the strengths of multiple models, as well as delving deeper into external factors and their impact on sales.
5. **Recommendations**, based on these findings, it's recommended to factor in external variables like promotions and events in future analyses. Additionally, exploring variables like daily footfall or specific product types could yield more accurate insights into sales patterns.

In conclusion, these findings shed light on the dataset's characteristics, model performance, and challenges encountered in the attempt to classify diseases based on the existing experiments.

## Contact
For any questions or inquiries, please contact jason.susanto1703@gmail.com