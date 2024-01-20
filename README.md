# IVision_hack
## ⌛ Task
We needed to solve the problem of binary classification for "Citylink" customers in order to predict which people would leave, which ones would stay

## 💾 Data + Models
We were given a checklist of all transactions for the last 2 months, where in each line it was written: [contract_id], [event_date], [event_type]. I did the preprocessing, compiled a table (Value_count + TF-IDF) and trained CatBoost to classify users.

# 📣 To import
- test.csv - файл с ответами
- main.ipynb - главный ноутбук, где обучалась модель + создавался test.csv
- catboost.cbm - обученная модель catboost
- Open_model.ipynb - ноутбук для открытия модели и создания test.csv
- vectroizer_1.pkl, vectroizer_2.pkl - обученные модели TfidfVectorizer для Feature Engineering


