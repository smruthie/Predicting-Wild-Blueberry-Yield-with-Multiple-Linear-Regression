# Using Multiple Linear Regression to Predict Wild Blueberry Yield

The "Wild Blueberry Pollination Simulation Data" has a couple of potential predictors of Wild Blueberry yield and the resulting yields, a simulation dataset produced from a Wild Blueberry Pollination Model. In other words, this is not a real-life data, but generated through a simulation model authenticated by field observations and experimental data accumulated over several years. This dataset was taken from a research entitled "Wild blueberry yield prediction using a combination of computer simulation and machine learning algorithms", which attempts to shed light into the possibility that simulation data can also be useful for crop yield predictions besides real-life data using machine learning. I ran multiple linear regression (MLR) on this data with choosing fruit set, fruit mass, and seeds as best predictors of Wild Blueberry yield in the model. 

While the research does suggest clone size, honey bees, bumble bees, mining bees (Andrena), mason bees (Osmia), maximum upper-temperature range, and raining days as the best predictors of Wild Blueberry yield, these predictors would not be appropriate in a linear regression model as their scatterplots do not suggest a linear relationship to Wild Blueberry yield. Amusingly, these predictors contributed to a stronger R-Squared value for the MLR model despite their absence of linearity. However, fruit set, fruit mass, and seeds show a strong linear relationship to yield in scatterplots, and also contributes to a strong R-Squared value with negligible reduction. 

Kindly do refer to the Jupyter Notebook for clearer justifications.

Data License: https://opendatacommons.org/licenses/dbcl/1-0/.
Data Sources: 
1) Mendeley Data: https://data.mendeley.com/datasets/p5hvjzsvn8/1
2) Science Direct / Computers and Electronics in Agriculture: https://www.sciencedirect.com/science/article/abs/pii/S016816992031156X?via%3Dihub
3) Kaggle: https://www.kaggle.com/saurabhshahane/wild-blueberry-yield-prediction
