# insilico

1. Выбор метрики для классификации:
  * Классификация бинарная
  * Trade-off между precision/recall неизвестен
  * Классы не сбалалансированы
  
  __Следовательно, будем использовать ROC AUC как более-менее устойчивую метрику.__

2. Кросс - валидация на три фолда, так как данных и так мало.

3. Из моделей - Lasso, RandomForest, XGBoost + DFS.

4. Проверка на статистическую значимость модели должна была произоводиться по соответственным тестам на стат. значимость, но этого я реализовать пока не успел.
