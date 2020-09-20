# Проект «Складской учёт»

## Описание предметной области

Складской учёт является одним из разделов бухгалтерского учёта. В его рамках фиксируется целый ряд событий из деятельности предприятий со складами, в том числе:

* поступление на склад партии товара (каждая партия товара характеризуется количеством единиц товара и конкретной ценой за единицу, разные партии вполне могут отличаться по цене);
* убытие определённого количества единиц товара (одним из традиционных способов учёта убытия является метод FIFO, когда считается, что при убытии товара расходуется та партия, которая поступила на склад раньше).

Складской учёт позволяет в актуальном режиме выяснять следующие текущие параметры финансово-хозяйственной деятельности предприятия:

* общая стоимость всех находящихся на складе товаров;
* общая стоимость всех имеющихся в наличии единиц конкретного товара;
* стоимость требуемых к расходу единиц товара (с учётом того, что требуемое количество может происходить из разных партий);
* общее количество имеющихся в наличии единиц конкретного товара.

Также в рамках складского учёта можно получать итоговые отчёты, например:

* перечень товаров с указанием количества имеющихся в наличии единиц и их общей стоимостью;
* история поступлений и убытий.


## Задание

В рамках этого проекта требуется разработать интерактивное консольное приложение, представляющее собой автоматизированное рабочее место (АРМ) бухгалтера, ответственного за ведение складского учёта. Приложение должно позволять учитывать конкретные виды товаров (по артикулам), которые предполагаются к хранению на складе, поступление партий товаров, убытие единиц товара со склада, а также вести историю по этим операциям. Должны также быть предусмотрены возможности по выяснению текущих параметров финансово-хозяйственной деятельности предприятия, а также вывод итоговых отчётов по запросу пользователя.

* Язык программирования: Python
* Внешние библиотеки: SQLite

### Самостоятельно принимаемые решения

Необходимо придумать и реализовать дополнительно к указанному в описании предметной области:

* три текущих параметра финансово-хозяйственной деятельности;
* один итоговый отчёт.