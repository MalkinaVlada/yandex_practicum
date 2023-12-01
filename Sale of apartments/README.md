# Исследование объявлений о продаже квартир / Research of advertisements for the sale of apartments
## Данные / Data
Архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет.
Archive of advertisements for the sale of apartments in St. Petersburg and neighboring settlements for several years.

## Задача / Task
Требуется определить рыночную стоимость объектов недвижимости.
Установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.
По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма.

It is required to determine the market value of real estate.
Set options. This will allow you to build an automated system: it will track anomalies and fraudulent activity.
For each apartment for sale, two types of data are available. The first ones are entered by the user, the second ones are obtained automatically based on cartographic data. For example, the distance to the center, airport, nearest park and pond.

## Используемые библиотеки / Libraries used
*pandas*

## Выводы / Conclusions
В ходе исследования было установлено: общая площадь, кухонная площадь влияют на цену объекта. Чем больше эти площади, тем выше цена на объект. Существует зависимость между удаленностью от центра и ценой. Чем ближе к центру находится жильё, тем оно дороже.
Количество комнат, жилая площадь и этаж не влияют на цену недвижимости.
Год публикации, месяц и день также не влияют на цену.
Можно проследить закономерность между годом, днем недели, временем и публикациями. Большая часть объявлений приходится на 2017-2018 года, в первый и последний месяцы, в будние дни.

The study found that the total area and kitchen area affect the price of the property. The larger these areas, the higher the price of the object. There is a relationship between distance from the center and price. The closer to the center the housing is, the more expensive it is.
The number of rooms, living area and floor do not affect the price of the property.
The year of publication, month and day also do not affect the price.
You can trace a pattern between the year, day of the week, time and publications. Most of the announcements occur in 2017-2018, in the first and last months, on weekdays.
