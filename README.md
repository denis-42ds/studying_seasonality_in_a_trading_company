# Название проекта: Изучение сезонности данных (тестовое задание)
## Статус проекта: завершён
## Описание проекта:
- предоставлены три отдельные таблицы, по каждой нужно выполнить своё задание
	1. В таблице представлены количественные показатели продаж Модели №1. Посчитайте коэффициент сезонности.
	2. Таблица ниже содержит результаты продаж в разрезе клиентской базы. Задания:
	2.1. присвоить статус клиенты по АВС-анализу (критерии групп разработайте самостоятельно)
	2.2. посчитать суммарный объем продаж по каждому клиенту;
	2.3. используя формулу, подсчитать суммарный объём реализации ежемесячно и по итогам года
	3. Средний товарооборот компании в месяц 500 000 руб. 
	<br>Среднее количество проданного товара 500 штук. Торговая наценка этого товара — 20 %. 
	<br>На какую сумму компания должна продать товар, чтобы получить скидку в размере 5 или 7 %, при условии, что компания для скидки 5 % хочет получить дополнительную прибыль в 2 000 руб., а для 7 % — 5 000 руб. 
	4. В представленной таблице необходимо в целом по сети:
	4.1. выявить наличие сезонности;
	4.2. численно выразить сезонные колебания:
	4.2.1. метод абсолютных разностей;
	4.2.2. метод относительных разностей;
	4.2.3. индексный метод;
	4.2.4. методом скользящей средней;
	4.2.4. методом постоянной средней;
	4.3. оценить последствия сезонных колебаний.
## Цель проекта: изучение сезонности продаж группы магазинов торговой компании
## Ход исследования:
- предобработка данных
- выявление клиентских групп (по ABC анализу)
- расчёт сумм для получения скидки 5% или 7%
- трансформирование датасета во временной ряд
- изучение тренда, сезонности и распределения целевого признака
- выводы
## Использованные в проекте инструменты:
- matplotlib.pyplot
- seaborn
- pandas
- statsmodels
## Выводы:
- посчитан суммарный объём продаж по каждому клиенту
- клиентам присвоены категории значимости
- посчитаны необходимые суммы продаж для предоставления скидки 5% или 7%
- посчитан коэффициент сезонности: он говорит о сезонном росте в декабре и снижении в июле
- датасет преобразован в числовой ряд
- распределение прибыли близко к нормальному
- график тренда свидетельствует об общем росте прибыли
- на графике сезонности отчётливо наблюдается спад продаж в летние месяцы с минимумом в июле
- рост продаж начинается осенью и продолжается до новогодних праздников с пиком в декабре
