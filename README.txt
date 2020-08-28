
-Данный проект разрабатывался в IDE Intellij IDEA.

-Для запуска программы необходимо иметь предустановленный JDK.

-В разработанном приложении используется база данных H2, 
все данные хранятся в тестовой базе данных и имеют следующий формат:


// Таблица ГОРОДОВ
CREATE TABLE cities(
	id INT PRIMARY KEY not null, 
	city VARCHAR(50) not null);


// Таблица УЛИЦ
CREATE TABLE streets(
	id INT PRIMARY KEY not null, 
	street VARCHAR(50) not null, 
	city_id INT not null);


// Добавление записей в таблицу ГОРОДОВ
INSERT INTO cities VALUES (1, 'city');


// Добавление записей в таблицу УЛИЦ
INSERT INTO streets VALUES (1, 'street', city_id);
