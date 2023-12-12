# BML-Final-Project
1. Project Title: DS6040 - Final Project
2. Authors: Abhi Singh, Gwen Powers, Tripat Panesar
3. Introduction and Background:
* Obesity is a pressing global health concern with profound implications for individuals and healthcare systems. The project aims to develop Bayesian models for predicting obesity based on habits and physical conditions. The importance of this endeavor lies in the significant health and societal consequences of obesity, necessitating effective predictive models to understand and address contributing factors. Predicting obesity is crucial for public health, and accurate models are needed to identify significant factors, enabling preventive measures and interventions. The rising prevalence of obesity worldwide underscores the urgency of this research.
4. Dependencies and Setup:
* To use this file, some installations and imports or libraries are important. Some libraries that will be used are: numpy, pandas, sklearn, arviz, pymc, and seaborn.
* Please make sure that these libraries are up to date.
5. Notebook Structure:
* Set working directory
* Import Data: dataset can be found on Kaggle or copy and past this link: https://www.kaggle.com/datasets/ankurbajaj9/obesity-levels/discussion/193986 
* Exploratory Data Analysis: Involves exploring and understanding the dataset through various analytical techniques. Some variables of the data set are explored through visualizations.
* Preprocessing the Data: Some variables are processed to ease modeling
* Splitting Data (Train and Test): Details the division of the dataset into training and testing subsets.
* Model 1 + Metrics: Model 1 is created which is all betas without any interactions. Its metrics are calculated and visualized.
* Model 2 + Metrics: Model 2 is created which is the reduced model without any interactions. Its metrics are calculated and visualized.
* Model 3 + Metrics: Model 3 is created which is the full model with five interactions. Its metrics are calculated and visualized.
* Model 4 + Metrics: Model 4 is created which is the reduced model with the interactions. Its metrics are calculated and visualized.
* Comparison of Models: Models are compared using a variety of different metrics.
6. Usage Instructions:
* Download the file and open in your app of choice. This code was coded through Google Colab so we recommend using that. 
7. Results and Conclusion:
* Although not explicitly mentioned, results can be extrapolated from the file. Further analysis of results will be stated in the report. 
8. Acknowledgements and References:
* Code structure is provided through DS 6040 HW’s by Professor Don Brown.
* Fabio Mendoza Palechor and Alexis de Manotas. 2019. Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico. Data in Brief 25 (August 2019), 104344. DOI:http://dx.doi.org/10.1016/j.dib.2019.104344
* Guillermo Garcia-Garcia. Obesity and overweight populations in Latin America . Retrieved December 7, 2023 from https://www.thelancet.com/campaigns/kidney/updates/obesity-and-overweight-populations-in-latin-america
* World Health Organization. 2021. Obesity and overweight. (June 2021). Retrieved December 6, 2023 from https://www.who.int/news-room/fact-sheets/detail/obesity-and-overweight
