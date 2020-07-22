# BaggingAndBoosting

Задача – иследовать различные модификации метода boosting для задачи распознавания лиц.
В качестве модели берется ResNet18. Необходимо обучить базовые модели и их ассемблировать boost - методами (AdaBoost, LogitBoost, GentleBoost, Stochastic Gradient Boosting). Путем наращивания сложности базовой модели (увеличение количества сверток и/или слоев, исследовать зависимость качества ассемблирования (точности ансамбля) от сложности базовых моделей. Необходимо привести анализ каждой модификации boost – метода и сравнение ROC кривых для ансамблпей, полученных каждым методом.
