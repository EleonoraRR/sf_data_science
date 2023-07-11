# ML-7. Прогнозирование биологического ответа (HW-3)

## Оглавление
[1. Описание проекта](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#описание-проекта)  
[2. Какие задачи решаем?](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#какие-задачи-решаем)  
[3. Краткая информация о данных](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#краткая-информация-о-данных)  
[4. Этапы работы над проектом](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#этапы-работы-над-проектом)  
[5. Результат](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#результат)  
[6. Выводы](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#выводы)

### Описание проекта
Предсказание биологическиого ответа молекул по их химическому составу.

:arrow_up: [к оглавлению](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#Оглавление)


### Какие задачи решаем
Необходимо обучить две модели: логистическую регрессию и случайный лес и сделать подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации.

**Условия соревнования:**
- Выполнить практику в юпитер-ноутбуке или Kaggle-ноутбуке.
- Приложить ссылки или прикрепить файл на обучающей платформе.


**Метрики качества** 
- Использовано четыре метода (GridSeachCV, RandomizedSearchCV, Hyperopt, Optuna).
- Максимальное количество итераций не должно превышать 50
- Качество решения: результат метрики $F_1$.



**Что практикуем?**
- Подбор гиперпараметров с помощью базовых и продвинутых методов оптимизации.

:arrow_up: [к оглавлению](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#Оглавление)

### Краткая информация о данных
Данные представлены в формате CSV. Каждая строка представляет молекулу. 

- Первый столбец Activity содержит экспериментальные данные, описывающие фактический биологический ответ [0, 1]; 
- Остальные столбцы D1-D1776 представляют собой молекулярные дескрипторы — это вычисляемые свойства, которые могут фиксировать некоторые характеристики молекулы, например размер, форму или состав элементов. 

:arrow_up: [к оглавлению](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#Оглавление)


### Этапы работы над проектом
1. Обучение модели (логистическая регрессия).

2. Подбор гиперпараметров.

3. Обучение модели (случайный лес).

4. Подбор гиперпараметров.



:arrow_up: [к оглавлению](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#Оглавление)

### Результат
[См. ноутбук](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/ML-7_практика.ipynb#ноутбук) 

:arrow_up: [к оглавлению](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#Оглавление)


### Выводы
[См. ноутбук](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/ML-7_практика.ipynb#ноутбук) 
 
:arrow_up: [к оглавлению](https://github.com/EleonoraRR/sf_data_science/tree/main/HW/README.md#Оглавление)