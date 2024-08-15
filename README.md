# Title:
Spam Detection Model using NLP

## About Dataset:
This dataset consists of 5,573 emails, each labeled as either spam or ham (not spam). The dataset is available on Kaggle. 

The goal of this project is to preprocess the text data and explore various approaches to build an effective spam detection model.

## Table of Comtent:
1. Data Analysis
2. Data preprocessing
3. Splitting Dataset
4. Feature Extraction using CountVectorizer and TF-IDF
5. Model Training with default parameters
6. Model Training and hyperparameter optimization using GridSearchCV
7. Model Evaluation
8. Prediction
9. Final Conclusion


## Results:

**Defaul pramateter models with BOW (CountVectorizer)**

![image](https://github.com/user-attachments/assets/dc6459d1-7877-43c9-be6b-774685ab72d0)


**Default parameter models with TF-IDF vectorizer**

![image](https://github.com/user-attachments/assets/12ea92b2-4821-4cd7-816b-8790655031d0)

**Hyperparameter tuning with BOW vectorizer**

![image](https://github.com/user-attachments/assets/6dd08730-1cd7-430a-a815-4b2618ad4104) 

![image](https://github.com/user-attachments/assets/f0485e5c-28a0-4e3b-883f-de37e13a19fa)

**Hyperparameter tuning with TF-IDF vectorizer**

![image](https://github.com/user-attachments/assets/00ab00c8-ac18-4b37-9230-6fe35881fbb3) 

![image](https://github.com/user-attachments/assets/e5845826-aeae-4287-88cb-bff69e308eac)

** Prediction Results:

![image](https://github.com/user-attachments/assets/06b04e55-706d-495b-9481-c1c1e419da9c)


## Final Conclusion

The texts analyzed are written in everyday conversational language, often featuring informal expressions and shorthand. This informal style may affect the model's performance. Since the texts originate from emails, they vary in tone—some being professional and others more conversational. To potentially enhance performance, incorporating a broader range of text types and improving the text cleaning process could be advantageous.


