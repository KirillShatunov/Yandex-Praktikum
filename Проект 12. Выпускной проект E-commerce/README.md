# Проект 12. "E-commerce — Выявление профилей потребления".
# Задачи проекта:
Необходимо сегментировать товары входящие в основной и в дополнительный ассортимент, сформулировать и проверить статистические гипотезы.

# Описание проекта:
По результатам анализа разделили товарные позиции в каждой категории на основные и дополнительные. Деление происходит за счет сравнения цены товара с медианой цены в данной категории, если цена меньше медианы , то данный товар помечается как дополнительный, если больше медианы - основной.Также были выдвинуты и проверены 2 гипотезы. По результатам проведенной работы были даны рекомендации для работы маркетинг отдела.

# Краткий результат:
* Подготовили полученные данные:
   * Исследовали пропущенные значения;
   * Исследовали соответствие типов;
   * Исследовали дубликаты;
   * Привели к корректной дате.
* Провели исследовательский анализ данных:
   * Построили гистограммы, ящики с усами;
   * Нашли выбросы;
   * Создали новый столбец с категориями;
   * Разделили в категориях товары на основные и дополнительные;
   * Исследовали продажы товаров по неделям и месяцам.
* Проверили гипотезы
* Написали общий вывод о проведённом анализе

# Использованные библиотеки и инструменты:
Python, Pandas, Matplotlib, Plotly, PyMystem3, лемматизация, проверка статистических гипотез.
