# Best-Selling-Steam-Games-of-All-Time-Prediction-Using-Machine-Learning
Built predictive machine learning models on the Steam Games dataset to analyze factors driving downloads and success, applying preprocessing, feature engineering, and advanced classification techniques validated through cross-validation and performance metrics.

Task 1:
Data Cleaning, Preprocessing And EDA:
○ Convert release_date to datetime format and extract year/month.
○ Handle missing/null values in price, difficulty, and rating.
○ Convert price to float; bin into ranges (Free, <$10, $10–30, >$30).
○ Parse user_defined_tags, supported_os, other_features into binary columns using multi-label binarization.

Task 2:
Exploratory Data Analysis (EDA):
○ Relationship between reviews, ratings, and downloads.
○ Top genres/tags associated with high downloads.
○ Price distribution vs. download volume.
○ Correlation matrix of numerical features.

Task 3:
Feature Engineering:
○ Create a binary flag for is_free from price == 0.
○ Create review_volume_bucket for low, medium and high based on review count.
○ Count of tags, languages and platforms supported.
○ Calculate review_score = reviews_like_rate * all_reviews_number.

Task 4:
Modeling:
○ Split into training and test sets.
○ Apply Logistic Regression, Random Forest and Gradient Boosting.
○ Use cross-validation.
○ Evaluate using accuracy, precision, recall, F1-score and AUC-ROC.



