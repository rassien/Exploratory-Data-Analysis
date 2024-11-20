# Predict Purity and Price of Honey - Exploratory Data Analysis (EDA)
### Proje Özeti:
Bu projede, balın saflığı ve fiyatı arasındaki ilişkiyi anlamak amacıyla yapılan Keşifsel Veri Analizi (EDA) süreci ele alınmıştır. "Predict Purity and Price of Honey" veri seti, balın çeşitli özelliklerini ve bu özelliklerin saflık ve fiyat üzerindeki etkilerini analiz etmek için kullanılmıştır. Veri setindeki çeşitli kategorik ve sayısal değişkenler üzerinden çıkarımlar yapılmış, görselleştirmeler ve istatistiksel analizler ile ilişkiler incelenmiştir.

### Veri Seti Hakkında:
Veri seti, balın saflığı ve fiyatı hakkında bilgi sağlayan özellikler içerir. Özellikler arasında pH, renk, yoğunluk gibi fiziksel parametreler yer almaktadır. Bu parametrelerin balın saflığını ve fiyatını nasıl etkileyebileceği üzerine çalışmalar yapılmıştır.

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


### Amaç:
Bu projedeki ana hedef, balın saflık seviyeleri ile fiyatı arasındaki ilişkiyi analiz etmek ve hangi faktörlerin bu değişkenler üzerinde daha fazla etkili olduğunu belirlemektir. Ayrıca, bu EDA süreci, veri setinde eksik verileri ve potansiyel anormallikleri ortaya çıkarmayı amaçlamaktadır.

### Yapılan Çalışmalar:
- #### Veri Temizleme ve Ön İşleme:

    - Eksik veri kontrolü ve temizliği.
    - Kategorik verilerin düzenlenmesi ve sayısal verilere dönüştürülmesi.
    - Verilerdeki uç değerlerin analizi.
- ### Keşifsel Veri Analizi (EDA):
    
    - Veri setindeki temel istatistiklerin çıkarılması (ortalama, medyan, standart sapma vb.).
    - Kategorik verilerin görselleştirilmesi (pH seviyeleri, saflık grupları vs.).
    - Sayısal verilerin korelasyon analizi ve dağılımlarının incelenmesi.
    - Farklı pH gruplarına göre saflık dağılımının karşılaştırılması.
- ### Görselleştirmeler:

    - Box plot, histogram ve scatter plot gibi grafiklerle değişkenlerin dağılımlarının ve ilişkilerinin görselleştirilmesi.
    - Pie chart ve bar chart kullanarak kategorik değişkenlerin görsel olarak analiz edilmesi.
- ### İstatistiksel Testler:

    - pH gruplarına göre saflık ortalamalarının karşılaştırılması için ANOVA testi yapılması.
    - Farklı pH aralıklarındaki balın saflık ve fiyat üzerindeki etkilerinin analiz edilmesi.
- ### Sonuçlar:
    - pH değeri ile saflık arasında anlamlı bir ilişki olduğu gözlemlenmiştir.
    - Farklı pH gruplarındaki balın saflık ortalamaları karşılaştırıldığında, bazı pH aralıklarının diğerlerine göre daha yüksek saflık seviyelerine sahip olduğu tespit edilmiştir.
    - Fiyat ile saflık arasında doğrusal bir ilişki olduğu ve saflığı yüksek balın genellikle daha pahalı olduğu gözlemlenmiştir.
- ### Çıkarımlar:
    Bu EDA süreci, balın saflığının ve fiyatının belirli özelliklerle olan ilişkisini anlamaya yönelik değerli bilgiler sunmaktadır. Özellikle pH ve diğer fiziksel özelliklerin balın saflığı ve fiyatı üzerindeki etkileri, bal üreticileri ve tüketiciler için önemli karar destek araçları sunmaktadır.

### Gelecek Adımlar:
Bu analiz, daha ileri düzeyde modelleme çalışmalarına (örneğin, doğrusal regresyon veya makine öğrenimi algoritmaları) ve balın saflığını tahmin etmeye yönelik prediktif analizlere temel teşkil edebilir. Ayrıca, balın fiyat tahminlemesi için daha karmaşık özellik mühendisliği ve modelleme yöntemleri uygulanabilir.




### English
---

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

