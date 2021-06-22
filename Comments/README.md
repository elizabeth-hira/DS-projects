# Comments - классификация текстов

## 1. Обработка текста
Технологии: *WordNetLemmatizer, re*.

## 2.  Подготовка текста к обучению
Технологии: *TfidfVectorizer, nltk: stopwords*.

## 3. Обучение моделей
Технологии: *GridSearchCV, CatBoostClassifier, LGBMClassifier, sklearn: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression*.

## 4. BERT
Технологии: *DistilBERT: transformers, torch*. 

## 5. Анализ моделей
Технологии: *sklearn.metrics: f1_score*.

### Результат: f1_score 82% c DistilBERT на текстах длиной до 50 символов.