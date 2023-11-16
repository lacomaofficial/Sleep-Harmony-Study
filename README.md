# Sleep in Mammals Analysis and Modeling

## Overview:
Explore mammalian sleep patterns using the "Sleep in Mammals" dataset, covering 39 species across 13 orders. Investigate key variables such as body weight, brain weight, sleep stages, life span, gestation, predation risk, exposure, and danger.

![image](https://github.com/lacomaofficial/Sleep-Harmony-Study/assets/132283879/97ca850a-9c82-4c24-9870-579751517e11)

## Data Exploration and Functions:
- **Libraries Used:** Pandas, NumPy, SciPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Plotly.
- **Data Source:** "mammals.csv."
- **Exploration:** Import, impute missing values, and calculate mutual information scores.
- **Visualizations:** Seaborn for distribution and correlation, Plotly for interactive exploration.

## Data Analysis and Preprocessing:
- **Info:** Shape, duplicates, data types, and missing data.
- **Mutual Information Scores:** Evaluate and plot top features.
- **Analysis:** Explore relationships, correlations, and summary statistics.
- **Preprocessing:** Handle missing values, drop redundant features.

## Model Building and Evaluation:
- **Model:** XGBoost for predicting total sleep duration.
- **Evaluation Metrics:** Mean Squared Error (MSE) and R-squared.
- **Outlier Analysis:** Visualize outliers using boxplots.

## Recommendations:
- Consider feature engineering and further investigation based on analysis insights.
- Evaluate model performance using additional metrics and fine-tune parameters if needed.

## Conclusion:

1. **Gestation Period Dominance (Importance: 0.63):**
   - *Insight:* Extended time to adulthood influences sleep patterns.
   - *Significance:* Indicates a connection between maturity and sleep regulation.

2. **Environmental Impact (Importance: 0.10):**
   - *Insight:* Environmental danger affects sleep behavior.
   - *Significance:* Highlights the adaptive nature of sleep in response to external threats.

3. **Dreaming Sleep Significance (Importance: 0.10):**
   - *Insight:* Dreaming sleep is a predictor of overall sleep patterns.
   - *Significance:* Suggests cognitive and emotional involvement in sleep architecture.

4. **Life Span's Impact (Importance: 0.09):**
   - *Insight:* Longer life spans correlate with specific sleep adaptations.
   - *Significance:* Indicates potential influence of aging processes on sleep regulation.

5. **Weight's Modest Role (Importance: 0.09):**
   - *Insight:* Body weight plays a role, but other factors exert more substantial influences.
   - *Significance:* Weight is a contributing factor, sparking curiosity for further investigation.

In summary, our XGBoost model predicts sleep duration, unveiling nuanced relationships between biological factors and mammalian sleep. The study lays the groundwork for deeper exploration into the intricate dynamics of sleep in different species.



