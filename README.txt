
-������ ������ �������������� � IDE Intellij IDEA.

-��� ������� ��������� ���������� ����� ����������������� JDK.

-� ������������� ���������� ������������ ���� ������ H2, 
��� ������ �������� � �������� ���� ������ � � ����� ��������� ������:


// ������� �������
CREATE TABLE cities(
	id INT PRIMARY KEY not null, 
	city VARCHAR(50) not null);


// ������� ����
CREATE TABLE streets(
	id INT PRIMARY KEY not null, 
	street VARCHAR(50) not null, 
	city_id INT not null);


// ���������� ������� � ������� �������
INSERT INTO cities VALUES (1, 'city');


// ���������� ������� � ������� ����
INSERT INTO streets VALUES (1, 'street', city_id);