# Домашнее задание к занятию "`«Кеширование Redis/memcached»`" - `Бакулев Евгений`

### Задание 1
### Что нужно сделать:

1. Приведите примеры проблем, которые может решить кеширование.
Приведите ответ в свободной форме.

### Решение 1

Кеширование может решить следующие проблемы:
1. Уменьшение времени ответа сервера: Когда данные часто запрашиваются, кеширование позволяет уменьшить время, необходимое для их получения, так как они уже находятся в памяти и доступны мгновенно.
2. Снижение нагрузки на базу данных: Если данные часто запрашиваются, кеширование позволяет уменьшить количество запросов к базе данных, что снижает нагрузку на нее и ускоряет обработку запросов.
3. Улучшение производительности веб-сайта: Кеширование статических файлов, таких как изображения, CSS и JavaScript, позволяет уменьшить время загрузки страниц, что улучшает пользовательский опыт и повышает рейтинг сайта в поисковых системах.
4. Уменьшение использования ресурсов сервера: Кеширование позволяет сократить использование процессорного времени и оперативной памяти сервера, так как не требуется каждый раз обрабатывать одни и те же запросы.
5. Обеспечение доступности при сбоях базы данных: В случае сбоя базы данных кешированные данные могут быть использованы для обеспечения временной доступности приложения до тех пор, пока база данных не будет восстановлена.

### Задание 2
### Что нужно сделать:

1. Установите и запустите memcached.
Приведите скриншот systemctl status memcached, где будет видно, что memcached 

### Решение 2

![Скрин](https://github.com/garrkiss/redis_mem/blob/main/img/image.png)

### Задание 3
### Что нужно сделать:

1. Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.
Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.

### Решение 3

![Скрин](https://github.com/garrkiss/redis_mem/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2029.06.24_16.42.44.png)

### Задание 4
### Что нужно сделать:

1. Запишите в Redis несколько ключей с любыми именами и значениями.
Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.

### Решение 4

![Скрин](https://github.com/garrkiss/redis_mem/blob/main/img/%D0%A1%D0%BA%D1%80%D0%B8%D0%BD%D1%88%D0%BE%D1%82%2029.06.24_16.50.52.png)
