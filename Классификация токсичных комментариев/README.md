# <a href="">Классификация токсичных комментариев.<br></a>
Задача: Модель классификации токсичных комментариев. <br>
Выполнено: Данные очищены от разделителей, приведены к регистру, проведена векторизация TfidfVectorizer. Список стоп слов загружен из nltk. Параметры подобраны кроссвалидацией, использовалась логистическая регрессия, BERT не использовалась в связи с нехваткой ресурсов. <br>
Инструменты: pandas, numpy, WordNetLemmatizer, re, TfidfVectorizer, stopwords, train_test_split, f1_score, confusion_matrix, cross_val_score, GridSearchCV.
