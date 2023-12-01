# Прогнозирование оттока клиентов / Customer Churn Forecasting
## Данные / Data
Данные: персональные данные о клиентах, информация об их тарифах и договорах.

Data: personal data about clients, information about their tariffs and contracts.
## Задача / Task
Необходимо научиться прогнозировать отток клиентов оператора связи. Если выяснится, что пользователь планирует уйти, ему будут предложены промокоды и специальные условия.

It is necessary to learn how to predict the outflow of telecom operator customers. If it turns out that the user is planning to leave, they will be offered promotional codes and special conditions.

## Используемые библиотеки / Libraries used
*pandas*, *matplotlib*, *seaborn*, *scipy*, *numpy*, *shap*, *sklearn*, *phik*, *catboost*
## Выводы / Conclusions
Была проведена предобработка данных, исследовательский анализ, составлен портрет клиента.

Также изучили корреляцию между признаками, для обучения модели отобрали параметры, сильно коррелирующие с целевым признаком.

На основе обученной модели, выявили наиболее важные параметры для целевого признака.

Data preprocessing, research analysis were carried out, and a client portrait was drawn up.

We also studied the correlation between features; parameters that were highly correlated with the target feature were selected for model training.

Based on the trained model, the most important parameters for the target feature were identified.
