# Clinical Notes Text Classification (NLP)

This project classifies short synthetic clinical notes into three categories — Diabetes, Hypertension, and General Check-up — using TF-IDF features and a Logistic Regression model in scikit-learn.









# What This Project Shows

- Basic NLP pipeline for healthcare-style text
- TF-IDF vectorization with uni-grams and bi-grams
- Supervised classification with Logistic Regression
- Model evaluation using accuracy and a classification report









# Methods (Brief)

- Synthetic notes written to mimic real outpatient documentation  
- TfidfVectorizer(stop_words="english", ngram_range=(1,2))`  
- Stratified train–test split  
- LogisticRegression(max_iter=1000)` for training  









# Note

The dataset is synthetic and used for learning and demonstration only. The focus is on building and evaluating an NLP + ML pipeline, not on real clinical conclusions.
