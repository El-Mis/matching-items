# matching-items
## Матчинг товаров

**Описание**: В данном проекте необходимо создать такой алгоритм, который для запрашиваемого товара найдет несколько наиболее подходящих вариантов.

**Цель**: 
- разработать алгоритм, который для всех товаров из валидацонной выборки предложит несколько вариантов наиболее похожих товаров из базовой выборки;
- оценить качество алгоритма по метрике _accuracy@5_ .

**Набор данных**:
- базовый анонимизированный набор товаров. Каждый товар представлен как уникальный id и вектор признаков размерностью 72.
- обучающий датасет. Каждая строчка - 1 товар, для которого известен уникальный id , вектор признаков и id товара из базового набора товаров, который максимально похож на него (по мнению экспертов).
- валидационный датасет с товарами (уникальный id и вектор признаков), для которых надо найти наиболее близкие товары из базовой выборки.
- правильные ответы к валидационной выборке.

**Используемые библиотеки**:
* _faiss, pandas, numpy, seaborn, matplotlib, sklearn, catboost, machine learning_

**Итог**: проект в работе.
