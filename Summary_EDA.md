
# <div style="background-color: white; text-align: center;"><img src="heart_image.png" alt="Heart" title="Heart Image" width="50" height="50" /><font color=red> <span style="font-size: 95%; background-color: white;">Summary of Heart Disease Analysis and Modeling</span> </font><img src="heart_image.png" alt="Heart" title="Heart Image" width="50" height="50" /></div>

## Data Exploration and Analysis
- **Imports & Reading in the Data**: Necessary libraries are imported, and the dataset is read into a DataFrame.
- **Data Analysis**: 
  - Basic information about the dataset is examined using `info()` and `describe()` methods.
  - No missing values are found.
  - Unique values in each column are counted.
- **Visualizations**:
  - The target variable distribution (`output`) is visualized using a count plot.
  - Continuous features are explored through boxplots and KDE plots, showing their distributions and potential relationships with the target variable.
  - Correlation analysis is performed using heatmaps and pair plots.
- **Chi-Square Test**:
  - Chi-square tests are conducted between pairs of categorical variables to assess their association.
  - Statistically significant associations are identified.


## Insights
- Gender (sex), chest pain (cp), number of major vessels (caa), and Thal rate (thall) are identified as influential features in predicting heart disease.
- Statistically significant associations are found between certain pairs of categorical variables.


In conclusion, the notebook provides a comprehensive analysis of heart disease data, exploring various aspects such as data distributions and correlation. It offers insights that can be valuable for understanding heart disease occurrences.
