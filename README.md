
<div style="width: auto; height: 600px; overflow: hidden; text-align: center;">
  <img src="https://img.freepik.com/premium-photo/nature-bee-insect-pollen-yellow-background-macro-apiculture-honey-gold-closeup-generative-ai_163305-184072.jpg" alt="Melting Honey" style="width: 100%; height: 100%; object-fit: cover;">
</div>

# Predict Purity and Price of Honey - Exploratory Data Analysis (EDA)
#### Project Summary:
This project deals with the Exploratory Data Analysis (EDA) process to understand the relationship between the purity and price of honey. The “Predict Purity and Price of Honey” dataset was used to analyze various properties of honey and their effects on purity and price. Inferences were made on various categorical and numerical variables in the dataset and relationships were examined through visualizations and statistical analysis.

#### About Dataset:
The dataset contains attributes that provide information about the purity and price of honey. The attributes include physical parameters such as pH, color, density. Studies have been conducted on how these parameters can affect the purity and price of honey.

- **CS (Color Score):**
    - Represents the color score of the honey sample, ranging from 1.0 to 10.0. Lower values indicate a lighter color, while higher values indicate a darker color.

- **Density:**
    - Represents the density of the honey sample in grams per cubic centimeter at 25°C, ranging from 1.21 to 1.86.

- **WC (Water Content):**
    - Represents the water content in the honey sample, ranging from 12.0% to 25.0%.

- **pH:**
    - Represents the pH level of the honey sample, ranging from 2.50 to 7.50.

- **EC (Electrical Conductivity):**
    - Represents the electrical conductivity of the honey sample in milliSiemens per centimeter.

- **F (Fructose Level):**
    - Represents the fructose level of the honey sample, ranging from 20 to 50.

- **G (Glucose Level):**
    - Represents the glucose level of the honey sample, ranging from 20 to 45.

- **Pollen_analysis:**
    - Represents the floral source of the honey sample. Possible values include Clover, Wildflower, Orange Blossom, Alfalfa, Acacia, Lavender, Eucalyptus, Buckwheat, Manuka, Sage, Sunflower, Borage, Rosemary, Thyme, Heather, Tupelo, Blueberry, Chestnut, and Avocado.

- **Viscosity:**
    - Represents the viscosity of the honey sample in centipoise, ranging from 1500 to 10000. Viscosity values between 2500 and 9500 are considered optimal for purity.

- **Purity:**
    - The target variable represents the purity of the honey sample, ranging from 0.01 to 1.00.

- **Price:**
    - The calculated price of the honey.


### Objective:
The main objective in this project is to analyze the relationship between the purity levels and the price of honey and determine which factors have more influence on these variables. Furthermore, this EDA process aims to uncover missing data and potential anomalies in the dataset.

#### Studies Conducted:
- #### Data Cleaning and Preprocessing:

    - Missing data checking and cleaning.
    - Organizing and converting categorical data into numerical data.
    - Analysis of outliers in data.
- ### Exploratory Data Analysis (EDA):
    
    - Extraction of basic statistics from the data set (mean, median, standard deviation, etc.).
    - Visualization of categorical data (pH levels, purity groups, etc.).
    - Correlation analysis of numerical data and examination of their distributions.
    - Comparison of purity distribution according to different pH groups.
- ### Visualizations:

    - Visualization of distributions and relationships of variables using graphs such as box plots, histograms and scatter plots.
    - Visual analysis of categorical variables using pie charts and bar charts.
- #### Statistical Tests:

    - ANOVA test to compare purity averages across pH groups.
    - Analyzing the effects of different pH ranges on the purity and price of honey.
- #### Results:
    - A significant relationship was observed between pH value and purity.
    - When the purity averages of honey in different pH groups were compared, it was found that some pH ranges had higher purity levels than others.
    - There was a linear relationship between price and purity, with higher purity honey generally being more expensive.
- ### Conclusions:
    This EDA process provides valuable insights into understanding the relationship of honey purity and price with certain characteristics. In particular, the effects of pH and other physical properties on honey purity and price provide important decision support tools for honey producers and consumers.

### Next Steps:
This analysis can serve as a basis for further modeling studies (e.g., linear regression or machine learning algorithms) and predictive analyses to estimate honey purity. Furthermore, more sophisticated trait engineering and modeling methods could be applied for honey price prediction.


[Kaggle Account](https://www.kaggle.com/rassiem)

[Project Notebook](https://www.kaggle.com/code/rassiem/purity-and-price-of-honey-eda)
