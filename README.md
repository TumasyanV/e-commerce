### 1. При помощи Python (pandas) анализ данных 
* Пользователи, совершившие только один заказ
* количество недоставленных заказов (детализация причин), построение графика кол-ва недоставленных заказов в разрезе месяцев
* частота покупок в разрезе дней недели, в какой день недели товар чаще всего покупается
### 2. Проведение когортного анализа пользователей
* выводим когорты пользоватлей соверших первый заказ
* считаем кол-во дальнейших покупок этих пользоватлей по месяцам
* выявляем когорты с самым высоким Retention
### 3. Построение RFM-сегментации пользователей
 3.1 Группируем по пользователям, считаем:  
* Recency - время от последней покупки пользователя до текущей даты
* Frequency - суммарное количество покупок у пользователя за всё время
* Monetary - сумма покупок за всё время
 3.2 Создаем функции для присвоения необходимого ранга
 3.3 Считаем итоговый рейтинг пользователей
 3.4 Проводим сегментацию пользователей в зависимости от итогового рейтинга
 3.5 Визуализируем данные по сегментам пользователей
