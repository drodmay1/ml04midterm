# Peer Review – Mushroom Classification Project

**Project Reviewed:** Prince's Mushroom Classification Notebook 

**Notebook** https://github.com/don4ye/ml_classification_prince/blob/main/classification_prince.ipynb

**Reviewer:** David Rodriguez-Mayorquin

**Date:** March 24, 2025


### 1. Clarity & Organization

The notebook is clear and easy to read. Each part is labeled, and the charts help show the results in a simple way.

**Suggestion:** Prince could add a few short notes before big steps to help explain what is happening. This might make it easier for beginners to follow along.

### 2. Feature Selection & Justification

Prince used  all 22 features as inputs, which makes sense because they are all categories that might help the model. Using LabelEncoder to turn them into numbers was a good choice and clearly explained.

Prince dropped a lot of rows with missing values in the stalk-root column. That cleaned the data, but it also removed about 30% of the dataset. I wonder if it would have been better to drop just the stalk-root column, or to fill in the missing values with something like "unknown" so more data could be used. 

**Suggestion:** Instead of dropping rows with missing stalk-root values, it could be worth trying to fill them in with something like "unknown".

### 3. Model Performance & Comparisons

Both the Random Forest and Decision Tree models got perfect results (100% accuracy). Prince clearly showed the results and compared the two models in a fair way. It’s easy to see that both models worked well.

**Suggestion:** Since both models gave the exact same perfect result, Prince could explain why that happened. For example, maybe the features are very strong and make the predictions easy. It could also be interesting to test the models using only a few features (like odor or gill-size) to see if they still do a good job. That would help show which features are the most useful for making predictions.


### 4. Reflection Quality

The reflections in the notebook are clear and match what the Prince did in each step. Prince explains why some features (like odor) are important, and the final thoughts help wrap up the project in a good way.

**Suggestion:** It might be interesting if the Prince added a bit more about what he would try next. Even something simple like testing a different model or using new data could be a fun way to keep learning and exploring.