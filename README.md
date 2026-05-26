# linear-regression-experiments

Подборка учебных ноутбуков по классическому ML в **scikit-learn**: пайплайны и кросс-валидация, EDA, линейные модели, логистическая регрессия для табличных и текстовых данных, а также несколько задач бинарной и многоклассовой классификации из учебных кейсов Яндекса.

## Зависимости

Python, pandas, numpy, scikit-learn; в отдельных ноутбуках также используются `matplotlib`, `seaborn`, `category_encoders`, `joblib` и другие стандартные библиотеки для EDA, препроцессинга и сериализации моделей.

## Файлы

| № | Ноутбук | Тема |
|---|---------|------|
| 1 | `1. sklearn_pipeline_scaling_cv.ipynb` | Pipeline, масштабирование, CV, Lasso и Ridge |
| 2 | `2. california_housing_eda.ipynb` | EDA California Housing |
| 3 | `3. bag_of_words_with_logistic_regression.ipynb` | BoW и логистическая регрессия |
| 4 | `4. tf_idf_with_logistic_regression.ipynb` | TF‑IDF и логистическая регрессия |
| 5 | `5. yandex-tortilla-turtle.ipynb` | Задача «черепахи» |
| 7 | `7. yandex_customer_churn_coffee_delivery_logistic_regression.ipynb` | Прогноз оттока клиентов сервиса доставки кофе: EDA, дисбаланс классов, feature engineering, логистическая регрессия и PR-AUC |
| 8 | `8. svm_first_try.ipynb` | Первый эксперимент с SVM для бинарной классификации отмены заказа |
| 9 | `9. yandex-advandex-click-probability.ipynb` | Оценка вероятности клика по рекламе (CTR): EDA, препроцессинг, отбор признаков, Logistic Regression / Linear SVC, калибровка вероятностей |
| 10 | `10. yandex-marketing-classification.ipynb` | Определение возрастной категории пользователя по цифровому поведению для рекламного таргетинга |

## Дополнительно

- `7. model.joblib`, `9. model.joblib`, `10. model.joblib` — сохранённые обученные модели для соответствующих ноутбуков.
