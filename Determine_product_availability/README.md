# Название проекта

### Определение наличия товаров на полке

# Описание

Система GoodsForecast.OSA* анализирует историю продаж в сети магазинов и определяет товары с наибольшей вероятностью отсутствия на полке. 
Сотрудники магазинов по каждой позиции проверяют наличие товара и корректность ценника, при необходимости выставляя продукцию со склада и/или корректируя ценник.
В задаче определяем наличие товаров на полке в интервалах без продаж с оценкой производительности по метрике AUC-ROC. 
 
*OSA (On  Shelf Availability) – показатель представленности продукции на полке магазина.

# Библиотеки

_pandas_, _seaborn_, _sklearn_, _pyodbc_, _ydata_profiling_, _LightGBM_

# Выводы

Проведен исследовательский анализ данных, отбор признаков для использования в модели. 
Построены модели на основе нескольких классических алгоритмов классификацииалгоритмов. Победителем по результатам тестовой выборки стал LightGBM.