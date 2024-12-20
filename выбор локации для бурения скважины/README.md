# Выбор локации для бурения скважины

[Открыть тетрадку](<https://github.com/lvs3822/projects/blob/main/выбор%20локации%20для%20бурения%20скважины/8a38c35b-48c6-42af-b7ab-00ca6786d6bb.ipynb>)

Добывающей компании нужно решить, где бурить новую скважину. 

Шаги для выбора локации обычно такие:
- в избранном регионе собирают характеристики для скважин: качество нефти и объём её запасов;
- строят модель для предсказания объёма запасов в новых скважинах;
- выбирают скважины с самыми высокими оценками значений;
- определяют регион с максимальной суммарной прибылью отобранных скважин.

Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. Нужно построить модель для определения региона, где добыча принесёт наибольшую прибыль, а также проанализировать
возможную прибыль и риски техникой Bootstrap.

Данные геологоразведки трёх регионов находятся в файлах: 
- /datasets/geo_data_0.csv.
- /datasets/geo_data_1.csv.
- /datasets/geo_data_2.csv.
 
- id — уникальный идентификатор скважины;
- f0, f1, f2 — три признака точек (неважно, что они означают, но сами признаки значимы);
- product — объём запасов в скважине (тыс. баррелей).

Используемые библиотеки:
- pandas
- numpy
- scipy
- matplotlib
- seaborn
- sklearn
