# Анализ лояльности клиентов банка

## Оглавление

[1.Описание проекта](https://github.com/A1eksandraa/sf_homework#%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5)

[2.Какой кейс решаем?](https://github.com/A1eksandraa/sf_homework#%D0%BA%D0%B0%D0%BA%D0%BE%D0%B9-%D0%BA%D0%B5%D0%B9%D1%81-%D1%80%D0%B5%D1%88%D0%B0%D0%B5%D0%BC)

[3.Краткая информация о данных](https://github.com/A1eksandraa/sf_homework#%D0%BA%D1%80%D0%B0%D1%82%D0%BA%D0%B0%D1%8F-%D0%B8%D0%BD%D1%84%D0%BE%D1%80%D0%BC%D0%B0%D1%86%D0%B8%D1%8F-%D0%BE-%D0%B4%D0%B0%D0%BD%D0%BD%D1%8B%D1%85)

[4.Этапы работы над проектом](https://github.com/A1eksandraa/sf_homework#%D1%8D%D1%82%D0%B0%D0%BF%D1%8B-%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%8B-%D0%BD%D0%B0%D0%B4-%D0%BF%D1%80%D0%BE%D0%B5%D0%BA%D1%82%D0%BE%D0%BC)

[5.Результат](https://github.com/A1eksandraa/sf_homework#%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D1%8B)

[6.Выводы](https://github.com/A1eksandraa/sf_homework#%D0%B2%D1%8B%D0%B2%D0%BE%D0%B4%D1%8B)

### Описание:

Банк хочет разработать кампанию лояльности по удержанию клиентов, но для этого ему необходимо выяснить основные причины оттока клиентов. 

:arrow_up:[К оглавлению](https://github.com/A1eksandraa/sf_homework#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)

### Какой кейс решаем?

Нужно установить, чем ушедшие клиенты отличаются от лояльных и как между собой связаны различные признаки, определяющие клиентов.

**Условие соревнования**

- В файле должно содержаться 10 графиков — 10 ответов к заданиям.

- Каждый график и преобразования к нему выполняются в отдельной ячейке.

- Под графиком вы должны предоставить свой ответ на вопрос по нему и, если это требуется, выводы, которые вы можете сделать, исходя из графика.

**Метрика качества**

Максимальное количество баллов за одно задание — 1. Если в задании требуется сделать выводы по графику, а вы предоставляете только график, за данное задание выставляется 0 баллов.

**Что практикуем**

Учимся делать визуализацию данных и выводы по ним.

### Краткая информация о данных
Вам представлены данные об оттоке клиентов некоторого банка.
Столбцы таблицы:

1. RowNumber — номер строки таблицы (это лишняя информация, поэтому можете сразу от неё избавиться)
2. CustomerId — идентификатор клиента
3. Surname — фамилия клиента
4. CreditScore — кредитный рейтинг клиента (чем он выше, тем больше клиент брал кредитов и возвращал их)
5. Geography — страна клиента (банк международный)
6. Gender — пол клиента
7. Age — возраст клиента
8. Tenure — сколько лет клиент пользуется услугами банка
9. Balance — баланс на счетах клиента в банке
10. NumOfProducts — количество услуг банка, которые приобрёл клиент
11. HasCrCard — есть ли у клиента кредитная карта (1 — да, 0 — нет)
12. IsActiveMember — есть ли у клиента статус активного клиента банка (1 — да, 0 — нет)
13. EstimatedSalary — предполагаемая заработная плата клиента
14. Exited — статус лояльности (1 — ушедший клиент, 0 — лояльный клиент)

:arrow_up:[К оглавлению](https://github.com/A1eksandraa/sf_homework#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)

### Этапы работы над проектом

:arrow_up:[К оглавлению](https://github.com/A1eksandraa/sf_homework#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)

### Результаты:

Созданно 10 графиков и прописаны к ним выводы. 

:arrow_up:[К оглавлению](https://github.com/A1eksandraa/sf_homework#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)

### Выводы:

- Один из пяти клиентов отказывается от услуг данного банка.

- В основном клиенты банка это люди среднего класса. 

- Медианная и максимальные суммы ушедших клиентов выше чем у лояльных.

- Банку следует обратить внимание на группу от 40 до 50 лет.

- В банке практически не покупают более 2 продуктов

- 63% из не активных клиентов лояльны к банку.

- В Германии самая большая доля оттока клиентов.

:arrow_up:[К оглавлению](https://github.com/A1eksandraa/sf_homework#%D0%BE%D0%B3%D0%BB%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5)
