# Исследование надежности заемщиков / Borrower reliability research
## Данные / Data
Входные данные от банка — статистика о платёжеспособности клиентов.

Input data from the bank - statistics on the solvency of clients.

## Описание данных / Data Description

children — number of children in the family;

days_employed — total length of service in days;

dob_years — client age in years;

education — client’s education level;

education_id — education level identifier;

family_status — marital status;

family_status_id — marital status identifier;

gender—client gender;

income_type — employment type;

debt - whether there was a debt to repay loans;

total_income - monthly income;

purpose — purpose of obtaining a loan.

## Задача / Task
Разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок.
Understand whether the client’s marital status and number of children affect the fact of repaying the loan on time.

## Используемые библиотеки / Libraries used
*pandas*

## Выводы / Conclusions
В ходе исследования было проверено и установлено: Семейное положение клиента влияет на факт погашения кредита в срок. Наибольшее число долгов у клиентов из категорий не женат/не замужем и гражданский брак, меньше всего долгов у клиентов из категории вдовец/вдова.

Существует зависимость между наличием детей у клиентов и задолженностями. Клиенты-должники с детьми составляют большую долю от заемщиков, чем клиенты без детей.

Также присутствует зависимость между уровнем дохода и возвратом кредита в срок. Больше всего задолженностей у клиентов, относящихся к категории Е. Меньше всего долгов у клиентов из категории D. Клиенты-должники из категорий А, B и С составляют примерно равные доли от общего числа заемщиков.

During the study, it was checked and established: The client’s marital status affects the fact of repaying the loan on time. Clients from the unmarried and civil marriage categories have the largest number of debts, clients from the widower/widow category have the least debts.

There is a relationship between the presence of children of clients and debt. Debtor clients with children make up a larger share of borrowers than clients without children.

There is also a relationship between income level and loan repayment on time. Clients belonging to category E have the most debts. Clients from category D have the least debts. Clients-debtors from categories A, B and C make up approximately equal shares of the total number of borrowers.
