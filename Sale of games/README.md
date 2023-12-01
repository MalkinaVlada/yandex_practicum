# Анализ данных интернет-магазина / Online store data analysis
## Данные / Data

Name — название игры;

Platform — платформа;

Year_of_Release — год выпуска;

Genre — жанр игры;

NA_sales — продажи в Северной Америке (миллионы проданных копий);

EU_sales — продажи в Европе (миллионы проданных копий);

JP_sales — продажи в Японии (миллионы проданных копий);

Other_sales — продажи в других странах (миллионы проданных копий);

Critic_Score — оценка критиков (максимум 100);

User_Score — оценка пользователей (максимум 10);

Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.

Name — game name;

Platform - platform;

Year_of_Release — year of release;

Genre - game genre;

NA_sales - sales in North America (millions of copies sold);

EU_sales - sales in Europe (millions of copies sold);

JP_sales - sales in Japan (millions of copies sold);

Other_sales - sales in other countries (millions of copies sold);

Critic_Score - critics' score (maximum 100);

User_Score — user rating (maximum 10);

Rating - rating from the ESRB (Entertainment Software Rating Board). This association determines the rating of computer games and assigns them an appropriate age category.


## Задача / Task

необходимо выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании. Нужно отработать принцип работы с данными: спрогнозировать продажи на 2017 год по данным 2016-го.

It is necessary to identify the patterns that determine the success of the game. This will allow you to place a bet on a potentially popular product and plan advertising campaigns. We need to work out the principle of working with data: predict sales for 2017 based on 2016 data.

## Используемые библиотеки / Libraries used
*pandas*, *seaborn*, *matplotlib*, *scipy*

## Выводы / Conclusions
В ходе исследования определили, что:

PS4 является потенциально прибыльной платформой;
Платформы PS4, 3DS, PS3, X360, WiiU лидируют по продажам за последние 5 лет;
Продажи PS3, X360, Wii, XOne, PSV упали к 2016 году.
Также были приняты гипотезы: Средние пользовательские рейтинги жанров Action и Sports разные. Средние пользовательские рейтинги платформ Xbox One и PC также различаются.

На примере нескольких платформ убедились в слабой связи между продажами и оценками пользователей и критиков.

Определили самые прибыльные жанры: Shooter, Platform, Racing и Sports. А также жанры с низкими продажами: Puzzle, Adventure, Strategy.


The study determined that:

PS4 is a potentially profitable platform;
Platforms PS4, 3DS, PS3, X360, WiiU have been leading in sales over the past 5 years;
Sales of PS3, X360, Wii, XOne, PSV fell by 2016.
The following hypotheses were also accepted: Average user ratings for the Action and Sports genres are different. Average user ratings for the Xbox One and PC platforms also differ.

Using the example of several platforms, we were convinced of a weak connection between sales and ratings from users and critics.

The most profitable genres have been identified: Shooter, Platform, Racing and Sports. And also genres with low sales: Puzzle, Adventure, Strategy.
