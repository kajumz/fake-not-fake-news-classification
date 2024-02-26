# fake-not-fake-news-classification

Разработана модель, которая будет способна различать заголовки реальных и выдуманных новостей.
Для обучения модели используйте данные из файла `train.tsv`. В файле находится таблица, состоящая из двух колонок. 
В колонке title записан заголовок новости. В колонке is_fake содержатся метки: 0 – новость реальная; 1 – новость выдуманная.
Для демонстрации работы модели используйте данные тестового набора из файла `test.tsv`. В нем также есть колонка title, данные которой являются входными для вашей модели.
Метрика F1 score

What i've done:
- Preprocessed words and deleted stop-words
- Used stemming and lemmatization to words
- For training used stack of SVM, Naive Bayes, Random Forest and Logistic Regression
- F1-score ~ 0.87
