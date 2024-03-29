# Прогнозирование оттока клиентов из банка

## Задача
Необходимо спрогнозировать, уйдет клиент из банка или нет, используя исторические данные о поведении клиентов.

## Данные
В наличии были следующие данные о клиентах банка:
* RowNumber — индекс строки в данных
* CustomerId — уникальный идентификатор клиента
* Surname — фамилия
* CreditScore — кредитный рейтинг
* Geography — страна проживания
* Gender — пол
* Age — возраст
* Tenure — сколько лет человек является клиентом банка
* Balance — баланс на счёте
* NumOfProducts — количество продуктов банка, используемых клиентом
* HasCrCard — наличие кредитной карты
* IsActiveMember — активность клиента
* EstimatedSalary — предполагаемая зарплата
* Exited — факт ухода клиента

Источник данных: [kaggle](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Используемые библиотеки
*pandas, matplotlib, sklearn*