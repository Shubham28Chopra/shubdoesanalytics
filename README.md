# Data Analyst
### with a background in engineering and business consulting

#### Technical Skills: Python, R, Advanced Excel, Tableau, Power BI, Hadoop, JIRA, VISIO, and MS Office

## Education
- Post Graduate, Data Analytics for Business Decision Making | Durham College, Canada (_2023_)								       		
- B. Eng. (Hons.), Electronics and Communications Engineering	| The University of Sheffield, U.K. (_2013_)	 			        		

## Work Experience (recent)
**Consultant @ Global Innovation & Technology Alliance (GITA) (_September 2019 - December 2022_)**
- Managed international industrial R&D funding programs, overseeing a 250,000 CAD budget while also conducting exploratory data analysis for 4500 Indian companies, cleaning and transforming data into actionable insights for the program design.
- Led a team, coordinated annual innovation events, and facilitated India-Europe technology transfer under Horizon 2020 call.

**Canadian Technology Accelerator Analyst @ The High Commission of Canada (_January 2022 - August 2022_)**
- Led Technology Accelerator program by selecting entities, conducting exploratory data analysis, and preprocessing industry data for program design.
- Translated data into insights through dashboards and reports, automated pipelines, and facilitated market connections, focusing on Waste to Wealth, Deep Tech, Clean Tech, and Digital industries.

## Projects
### Water potability analysis using Logistic Regression, Naïve Bayes, and Ada Boost models.

My client had requested assistance in predicting the potability of water and provided me with a dataset that contained 2007 records and 10 features. This was a case of classification and was conducted in **Python** by preparing the models by splitting the data into a training and testing set, using the Isolation Forest technique to remove outliers, scaling the data to avoid weighted presence of any features, plotting the learning curves to understand the biases and variances, model analysis of Logistic Regression, Naïve Bayes, and AdaBoost models against their recall, running the optimized Logistic regression and Naïve Bayes model, and finally creating the voting model using voting classifies, repeated k-fold, and cross-validation.
Based on my findings, I recommended the AdaBoost model based on the comparative results. It's important to note that the performance differences were relatively small, suggesting that all three models provide somewhat similar prediction capabilities on this dataset. AdaBoost model is known to be consistent, robust, and versatile and works well on various types of datasets  with fewer assumption requirements. Also, interpretations and explanations from this model are relatively easier.

Since none of the models performed particularly well, adding hyperparameter tuning and enhancing ensemble diversity would improve the model by improving its generalization capability.
![BoxPlot and Voting Model](images/AdaBoost model.png)

### Possum regularization using optimized Lasso, Ridge, and Elastic Net models.

### Advertising Analysis for Apple

Apple recently launched a new advertisement to boost sales of the new Apple product. At the moment, ad1 sells an average of 30,000 pieces per week. Apple has compiled the Ad2 sales information over the last 15 weeks and wanted to see if the average sales for Ad2 are 30,000 units and test the impact on sales from Ad2.
Using **R**, I conducted the t-Test and concluded that since the p-value 9.651 x 10-5 was lower than α i.e., 0.05, we have strong evidence to reject the null hypothesis that that the average mean sale was 30,000 units.
![Apple ad analysis](images/Apple ad analysis - 1 sample t test.png)

### Rasin categorization using Optimized Decision Trees, Random Forests, Logistical Regression, and Discriminant Analysis (LDA and QDA)

I classified a categorization problem of segregating raisins using optimized Decision Trees, Random Forests, Logistic Regression, and Discriminant Analysis (LDA and QDA) using **Python**. Out of all, the Optimized QDA showed the best performance with an 89% accuracy, a higher precision of 96% for Besni in comparison to 84% for the Kecimen class. This is a measure of correctly predicting positive samples relative to the total samples predicted as positive.
The dataset had only 900 observations. Although difficult to monitor the collection of data, and expensive, a larger and normally distributed dataset would suffice the assumption for both LDA and QDA (better-performing models).
![Raisin Classification](images/Raisin classification.png)

### House price prediction using multivariate regression modeling

My client was curious to know the housing price prediction in a neighborhood using a multiple regression model in **Python**. Unfortunately, the model was not feasible as the RMSE and MAE both were greater than 10% of the mean price i.e., 68,121.59. Regularization techniques such as Lasso or Ridge could possibly help improve the model's performance.
![Housing prices prediction using linear regression](images/Housing prices - Linear regression.png)
Using feature engineering, selecting appropriate features or a combination of features could result in an improved model. For example, exploring a combination of the basement & garage together as a variable could possibly give us further insights. Additionally collecting more data: This dataset only compromises of 546 observations. A larger dataset would be helpful in training the model and would also provide us with a bigger test set, which in return would give us a more accurate representation of the underlying patterns in the data.

### Multi Regression Analysis on the effect of smoking on one’s expenses

To analyze the effect of smoking on one’s expenses I conducted an analysis using **R**. Starting off with a Histogram (to check the skewness, variance, and distribution of the expenses), I conducted a t-Test, and analyzed the data set using a simple linear regression model (to analyze the effect of smoking on expenses to check the establishment of a relationship, validity of the model, and predict), and a multiple linear regression model (to analyze the effect of all input variables on expenses).

Based on our performance measures, specifically the p-value, I concluded that since our p-value i.e., 2 x 10e-16 is smaller than the significance level 0.05, I reject the null hypothesis H_0 and conclude that there is a correlation between the variables. At least 1 of the independent variables (if not more) is correlated with the dependent output variable.

![Smoking expenses](images/Smoking expenses.png)
Model equation: Y(expenses) = -11942 + 257*age + b2*sex + 339*bmi + 476*no.ofchildren + b5*smokeryes + b6*region

The t-test revealed that at a 5% significance level, we have enough evidence that the mean expenses are not 10,000 units.
The simple linear regression model showed that at a 5% significance level, the model was not statically significant and there is indeed a relationship between the smoker variable and the output expense variable.
The multiple linear regression model showed that at a 5% significance level, the model IS statically significant and there is indeed a relationship between the input independent variables age, bmi, children, smokeryes, regionsoutheast, and regionsouthwest and the output expense variable.

### Canadian Crime Analysis Report for The Royal Canadian Mounted Police
This analysis highlights the utilization of **Power BI** to create professional visualizations for crime analysis for the Royal Canadian Mounted Police (RCMP). This could help improve the collaboration and support with provincial police departments in Ontario, Quebec, and British Columbia.
![Canadian Crime Analysis](images/Robbery forecast.png)
*Insights*: Ontario showcased the highest crime rates, followed closely by Quebec and British Columbia. Cities such as Toronto, Montreal, and Vancouver consistently report the highest crime rates within their respective provinces. Additionally, a strong positive correlation in Quebec and Ontario was observed.
![Canadian Crime Analysis](images/Robbery analysis correlation.png)
Forecasts conducted for the year ahead suggest a further decline in crime rates for Quebec, a moderate increase for Ontario, and a stable trend for British Columbia. The stability in crime rates should enable law enforcement agencies in British Columbia to focus on maintaining current crime prevention strategies and addressing specific localized issues.

### Predicting standardized scores post-training for students
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Response model to enhance marketing campaigns
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Predictive Modelling (regression models) for the weight of fish
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Predictive Modelling for rice identification using Decision Trees
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Infant Mortality Analysis
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### ETL using Spark Streaming and Kafka
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Analyzing New York City 311 Calls using Spark Structured API
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Tulip Executive Health Group Data Analysis
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### HR Data Analysis
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Profit & Loss analysis for a sample superstore
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)





### Additional projects -
Linear regression analyzing stock returns
Chi-Squared Analysis on a car-related database
Graphical analysis on Detrimental effects of smoking





























## Business Analysis Projects
Tulip Executive Health Group Data Analysis Case Study



## Executive Presentation (academic)
Executive analytical conference pitch to enhance tourism in India (2023)








































































## Talks & Lectures
- Causality: The new science of an old question - GSP Seminar, Fall 2021
- Guest Lecture: Dimensionality Reduction - Big Data and Machine Learning for Scientific Discovery (PHYS 5336), Spring 2021
- Guest Lecture: Fourier and Wavelet Transforms - Scientific Computing (PHYS 5315), Fall 2020
- A Brief Introduction to Optimization - GSP Seminar, Fall 2019
- Weeks of Welcome Poster Competition - UTD, Fall 2019
- A Brief Introduction to Networks - GSP Seminar, Spring 2019

- [Data Science YouTube](https://www.youtube.com/channel/UCa9gErQ9AE5jT2DZLjXBIdA)

## Publications
1.	Risk & Impact of Advanced Technologies AI, IoT, Cloud Computing
2.	Data Collection and Management Map - Process Flows
3.	Choosing technology for six sigma-type analysis
4.	Data Technology Plan for a printing and packaging unit
5.	Data flow impact analysis for a printing and packaging unit





1. Talebi S., Lary D.J., Wijeratne L. OH., and Lary, T. Modeling Autonomic Pupillary Responses from External Stimuli Using Machine Learning (2019). DOI: 10.26717/BJSTR.2019.20.003446
2. Wijeratne, L.O.; Kiv, D.R.; Aker, A.R.; Talebi, S.; Lary, D.J. Using Machine Learning for the Calibration of Airborne Particulate Sensors. Sensors 2020, 20, 99.
3. Lary, D.J.; Schaefer, D.; Waczak, J.; Aker, A.; Barbosa, A.; Wijeratne, L.O.H.; Talebi, S.; Fernando, B.; Sadler, J.; Lary, T.; Lary, M.D. Autonomous Learning of New Environments with a Robotic Team Employing Hyper-Spectral Remote Sensing, Comprehensive In-Situ Sensing and Machine Learning. Sensors 2021, 21, 2240. https://doi.org/10.3390/s21062240
4. Zhang, Y.; Wijeratne, L.O.H.; Talebi, S.; Lary, D.J. Machine Learning for Light Sensor Calibration. Sensors 2021, 21, 6259. https://doi.org/10.3390/s21186259
5. Talebi, S.; Waczak, J.; Fernando, B.; Sridhar, A.; Lary, D.J. Data-Driven EEG Band Discovery with Decision Trees. Preprints 2022, 2022030145 (doi: 10.20944/preprints202203.0145.v1).
6. Fernando, B.A.; Sridhar, A.; Talebi, S.; Waczak, J.; Lary, D.J. Unsupervised Blink Detection Using Eye Aspect Ratio Values. Preprints 2022, 2022030200 (doi: 10.20944/preprints202203.0200.v1).
7. Talebi, S. et al. Decoding Physical and Cognitive Impacts of PM Concentrations at Ultra-fine Scales, 29 March 2022, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-1499191/v1]
8. Lary, D.J. et al. (2022). Machine Learning, Big Data, and Spatial Tools: A Combination to Reveal Complex Facts That Impact Environmental Health. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_12
9. Wijerante, L.O.H. et al. (2022). Advancement in Airborne Particulate Estimation Using Machine Learning. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_13

- [Data Science Blog](https://medium.com/@shawhin)

- # shubdoesanalytics.github.io

