# GreenplumBasic

# SQL в Greenplum
Создан кластер в Yandex Cloud. Настроено соединение через DBeaver. 
На основе датасетов из https://github.com/aleaugustoplus/tpch-data/blob/master/README.md созданы таблицы.
Загружены данные через интерфейс DBeaver.
Проведены эксперименты, связанные с партицированием: как оно влияет на скорость выполнения запросов с учетом применения фильтров по партициям (range и list)
