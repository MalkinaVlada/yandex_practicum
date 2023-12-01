# Восстановление золота из руды / Recovery of gold from ore
## Данные / Data
Используются данные с параметрами добычи и очистки.
Data with production and purification parameters are used.

## Задача / Task
Подготовить прототип модели машинного обучения для компании, разрабатывающей решения для эффективной работы промышленных предприятий.
Модель должна предсказать коэффициент восстановления золота из золотосодержащей руды.

Prepare a prototype of a machine learning model for a company developing solutions for the efficient operation of industrial enterprises.
The model must predict the recovery rate of gold from gold ore.

## Используемые библиотеки / Libraries used
*pandas*, *sklearn*, *joblib*, *matplotlib*, *scipy*

## Выводы / Conclusions
В ходе работы была проведена проверка эффективности обогащения. Выполнена предобработка данных; посмотрели, как меняется концентрация металлов (Au, Ag, Pb) на различных этапах очистки. Сравнили распределения размеров гранул сырья на обучающей и тестовой выборках и исследовали суммарную концентрацию всех веществ на разных стадиях. Были обучены разные модели и оценено их качество кросс-валидацией. Выбрали лучшую модель и проверили её на тестовой выборке.

During the work, the efficiency of enrichment was checked. Data preprocessing completed; We looked at how the concentration of metals (Au, Ag, Pb) changes at different stages of purification. We compared the size distributions of raw material granules on the training and test sets and examined the total concentration of all substances at different stages. Different models were trained and their quality was assessed by cross-validation. We chose the best model and tested it on a test sample.
