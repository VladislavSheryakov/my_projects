# Анализ программы лояльности строительного магазина

## Цель проекта
Имеется датасет с данными о покупках в магазине. Любой покупатель может приобрести карту лояльности за 200 рублей (в программу включены скидки, промоакции и прочее). 
Необходимо провести анализ этой программы, сформулировать и проверить гипотезы о ней.

## Вывод:
Сформулированы и проверены три гипотезы:
 - средний чек участников программы лояльности отличается от среднего чека остальных клиентов
 - выручка от участников программы лояльности отличается от выручки остальных клиентов
 - количество покупок участников программы лояльности отличается от количества покупок остальных клиентов.

Ни одна из них не получила статистической значимости и мы пришли к выводу что разницы в выбранных метриках между "лояльными" и "нелояльными" покупателями нет различий.

## Стек:
 - pandas
 - seaborn
 - matplotlib.pyplot
 - sklearn
 - scipy
 - numpy
 - datetime
 - math

## Статус проекта
Завершен
