# Предсказание оттока клиентов банка
## Данные
Предоставлены данные о примерно 10000 клиентов банка, среди которых 20% уже расторгли договор. 
## Задача
Построить модель оттока клиентов, добиться качества модели по метрике F1 0.59
## Описание
Исследованы различные методы повышения качества модели при несбалансированных классах. Целевая метрика доведена до 0.62 на тестовой выборке. Дополнительно измерялся AUC-ROC, продемонстрирована связь определения порога по ROC-кривой с оптимальными бизнес показателями. 
## Использованные библиотеки
pandas, sklearn, matplotlib.pyplot
