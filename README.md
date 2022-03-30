# Отток клиентов #

Учебный проект выполненный в рамках курса "Специалист по Data Science плюс" (Яндекс Практикум).

## Описание проекта ##

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Был спрогнозирован уход клиента из банка в ближайшее время. Проект построен на исторических данных о поведении клиентов и расторжении договоров с банком.
Исследованы следующие модели: Логистическая регрессия, Классификатор дерева решений, Случайный лес. Построена модель с предельно большим значением F1-меры равным 0.594.  

Источник данных: [https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling](https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling)

## Описание данных ##

Данные находятся в файле /datasets/Churn.csv (англ. «отток клиентов»). Скачать датасет

**Признаки**
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
**Целевой признак**
* Exited — факт ухода клиента
