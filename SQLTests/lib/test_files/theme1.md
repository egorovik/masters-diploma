
Основные конструкции

Q
Сопоставьте началам запросов их конец так, чтобы получилась
     синтаксически верная конструкция. Предполагается, что если в
     запросе используется какой-то объект, то он существует в БД.
     Кроме того, считается, что каждому названию соответсвует
     опредленный вид объектов: table1 и т.д. - таблица, field1 и т.д. - поле,
     view1 - представление, func1 - функция, aggreg1 - агрегатная функция,   
     trig1 - триггер, index1 - индекс, schema1 - схема, user1 - пользователь.

R

R1
DROP VIEW

R2
view1

R

R1
DELETE

R2
FROM table1 WHERE  field1 > field2 AND field3 like '\%F\%'

R

R1
DROP TRIGGER

R2
trig1 ON table1

R

R1
CREATE AGGREGATE

R2
aggreg1 ( BASETYPE = integer, SFUNC = func1, STYPE = integer)

R

R1
DROP SCHEMA

R

R2
schema1

Q
Сопоставьте началам запросов их конец так, чтобы получилась
     синтаксически верная конструкция. Предполагается, что если в
     запросе используется какой-то объект, то он существует в БД.
     Кроме того, считается, что каждому названию соответсвует
     опредленный вид объектов: table1 и т.д. - таблица, field1 и т.д. - поле,
     view1 - представление, func1 - функция, aggreg1 - агрегатная функция,
     trig1 - триггер, index1 - индекс, schema1 - схема, user1 - пользователь.

R

R1
CREATE INDEX

R2
index1 ON table1 USING btree

R

R1
DROP INDEX

R2
index1

R

R1
DROP AGGREGATE

R2
aggreg1 (integer)

R

R1
DROP SCHEMA

R

R2
schema1

R

R1
CREATE USER

R

R2
user1