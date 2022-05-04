![](_attachments/Pasted%20image%2020211224121511.png)

Ошибка:  
Ошибка при формировании отчета: HTTP 413.0 - слишком большой объект запроса.
 

Причина: Отчет формируется большой и на сервере срабатывает блокировка запроса.

  
Решение: Зайти в настройки сервера и увеличить uploadReadAheadSize.

[Описание решение](https://techcommunity.microsoft.com/t5/iis-support-blog/solution-for-request-entity-too-large-error/ba-p/501134)