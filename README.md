# TikTok Machine Learning Project  
*Adapted from Google’s Nuts and Bolts of Machine Learning Course*

## Overview  
This project focused on building a machine learning model to classify TikTok videos as either a **claim** or an **opinion**. The purpose was to explore how ML could assist platforms like TikTok in automating moderation, prioritizing potentially harmful claims, and improving response efficiency.  

The dataset, provided by Google through the course, was clearly simplified and curated for teaching. As a result, the models achieved unusually high performance metrics. While not representative of the messiness of real-world data, the project illustrates my ability to carry out a full machine learning workflow with both structured data and natural language processing.  

## Project Steps  
1. **Ethical considerations**  
   - Considered implications of automating claim detection.  
   - Highlighted risks of false negatives (dangerous claims missed) and false positives (opinions mislabeled).  

2. **Data exploration**  
   - Worked with extracted data points from ~19,000 TikTok videos.  
   - Identified patterns such as claims being far more popular than opinions based on views, likes, and shares.  

3. **Feature engineering**  
   - Applied log transformations to skewed engagement features.  
   - One-hot encoded categorical variables.  
   - Extracted transcript lengths.  
   - Built a simple bag-of-words probability model as an additional feature.  

4. **Modeling**  
   - Trained Logistic Regression, Random Forest, XGBoost, and SVM.  
   - Evaluated performance using precision, recall, F1 score, and accuracy.  

## Results  
All models performed at a very high level, with recall and F1 scores close to 1.0 and precision at 1.0. 

- **Random Forest (final model):**  
  - F1 Score: 0.9997  
  - Precision: 1.0000  
  - Recall: 0.9995  
  - Accuracy: 0.9997  

These results are not realistic for a production environment but demonstrate solid execution of the ML process.  

## Tech Stack  
- Python  
- Pandas, NumPy, Matplotlib  
- Scikit-learn  
- NLTK (for text processing)  
- XGBoost  

## Key Takeaways  
- Completed an end-to-end machine learning project from EDA to final evaluation.  
- Applied both structured data methods and NLP techniques.  
- Reflected on the ethical challenges of using ML for social media moderation.  
- Showcased ability to engineer features, build multiple models, and compare results effectively.  

---

*Dataset provided by Google’s Nuts and Bolts of Machine Learning course (Coursera).*
