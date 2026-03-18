# Banking Insurance Product Adoption - XGBoost, Random Forest, Neural Network, GAM, Logistic Regression, MARS

In this project, the Commercial Banking Corporation (the "Bank") seeks to improve its marketing efficiency for a variable rate annuity product by leveraging data-driven decision making. Rather than relying on broad or standard outreach strategies, the Bank aims to proactively identify customers who are most likely to purchase this product.

To address this challenge, our team developed and evaluated six different models which include: XGBoost, Random Forest, Neural Network, GAM, Logistic Regression, MARS. Overall, we found that there was pretty consistent performance across the board for predicting the product adoption of the annuity product, with all models sitting around 78-79.7% AUC. The model that struck the best balance between true positive rate and specificity is the Random Forest Model. Our other models leaned too heavily towards one or the other, reducing their overall average rank on our scoreboard, thus we recommended the Bank utilize the Random Forest model for distinguishing which customers do and do not buy the variable rate annuity product.

## Tools Used:
- R
- dplyr
- ggplot2
- splines
- tidyverse
- magick
- ROCit
- DescTools
- caret
- earth
- rpart
- randomForest
- xgboost
- Ckmeans.1d.dp
- pdp
- glmnet
- mgcv
