# Farm-Yeild-Prediction-System-Using-Machine-Learning-ALgorithms
Repository for a Crop Prediction System. The aim of this project is to build a Crop type Classification Model predicts the type of Crop to be planted based on given Weather and Soil conditions.

# INTRODUCTION
Crop yield is the amount of crop harvested per unit of land area. It is a common measurement for grains, cereals, and legumes and is typically expressed in bushels, pounds, or tons per acre. A major component in determining the long-term viability of agriculture is crop output. Environmental factors have a significant impact on crop productivity. Weather affects crop growth and development, which has an impact on intra-season production variability. Variability in crop yield is a result of the interaction between space weather and soil quality.

One of the most difficult issues in smart agriculture is crop production forecasting. Several models have been suggested and tested up to this point. Since a variety of elements, including weather, climate, seed, fertilizer, and soil type, have an impact on crop output, this endeavor necessitates the use of various datasets. This demonstrates that predicting agricultural production is a complex process that requires numerous intricate phases. Crop yield prediction methods may currently substantially approximate the actual yield, while greater yield forecast accuracy is still needed. I consequently want to add weather and soil nutrient location in order to forecast crop yield.

# Data Minning and Crop Yeild 
Everywhere there are datasets, data mining methodology is a well-established field of computing that can be used. It is a multidisciplinary computer domain (statistics, machine learning, and soft computing computational intelligent) that use the understanding it has learned from various disciplines to discover significant, entertaining, and useful patterns in specific domain data.

Due to inadequate consideration of environmental factors, employing the traditional crop yielding technique has various disadvantages. This sparked a resurgence in interest for the use of machine learning techniques to estimate crop yields with greater precision, such as the random forest regression algorithm. Because of this, I want to combine soil nutrients with local weather information to anticipate crops early on, even before they are planted.

High-dimensional and multimodal agriculture data can be analyzed using sophisticated, automated, and objective algorithms thanks to machine learning (ML), an AI technology. Making predictions using machine learning techniques has been increasingly popular in precision agriculture in recent years. For the majority of these crop yield predictions, supervised learning was applied.

# Metodology
The Cross-Industry Standard Process for Data Mining (CRISP-DM) approach was used for the objectives of this project. The CRISP-DM approach describes the six steps needed to carry out data science tasks for this crop type prediction project, from the business need to the deployment phase.

This methodology consists of six main steps. With regard to the crop yield forecast model, they are mentioned and explained below.

1. Business Understanding:Here, I learnt everything there is to know about the crops we're categorizing and their effects on overall crop productivity. The required phase is comparable to this. I extracted the information required to create a crop categorization model. Crop.csv is the name of the data set that was gathered for this project.

2. Data Understanding: The crop.csv data gathered in the previous phase is shown or shown in this phase to aid in comprehension. Some of the techniques to comprehend data in Python include crop.shape, crop.info, crop.nunique, crop.describe, and others. To determine how helpful the data will be to the project, I simply want to know everything about it.

3. Data Preparation: The goal of this phase is to clean up the obtained crop data so that it is ready for the modelling phase, which comes after. I looked for missing data so that I can replace them with the mean or random values. I also remove columns that don't improve the model's accuracy.

4. Modelling: For creating categorization models, there are many different machine learning algorithms available. For this project, xgboost was used as the classifier. A model's accuracy can be raised by using the ensemble classifier Xgboost. The data will be divided into a train set and a test set. The crop classification model will be constructed and trained using the xgboost classifier.

5. Evaluation: To assess the model's performance, test data that was not used during training will be used to compare it to the model. The outcomes will be compared to the phase 1 identified business requirement. To make sure that the model findings are precise and usable in accordance with the project objective, subject matter experts from the business will be involved.

# Result
The crop type classification model produced a value of 99%. When creating the model, we employed a Random Forest classifier, and we tested the accuracy using a Confusion Matrix. Using the test data, we eventually forecasted several types of crops, and the model performed very well. All of the forecasts came true.
