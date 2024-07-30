# Дипломный проект - Сайт

В данном репозитории представлена часть программного комплекса онлайн магазина бытовой техники, а именно основное веб приложение. 
Приложение было разработано с использованием следующих технологий:
- Backend: в основе использовался язык Golang с использованием сторонних библиотек для обеспечения защиты (gorilla), связи с базами данных (sqlx, go-redis) и преобразования данных (excelx, struct2csv). 
- Frontend: писался на основном наборе HTML/CSS/JS с использованием CSS-фреймворка Bootstrap 5 и JS библиотек JQuery, DataTables и PurePajinate. 
- Для хранения данных использовались СУБД PostgreSQL (основная) и Redis (для логов и сессий). Связб с основной базой данных осуществлялось через отдельное API приложение. 

Данное приложение поддерживает разделение на 4 роли (неавторизованный пользователь, клиент, товарный менеджер и администратор) с возможностями: 
- Просмотра каталога товаров и подробной информации о каждом товаре
- Добавления/изменения/удаления товаров в корзине (только для клиента)
- Оформления заказов (только для клиента)
- Просмотр истории заказов и статусов текущих
- Изменения персональных учётной записи
- Смены пароля
- Оформления скидочной карты (только для клиента)
- Просмотр и изменение данных о товарах и заказах через информационную систему (только для менеджера и администратора)
- Просмотр и изменение данных о пользователях через информационную систему (только для администратора)
- Просмотр статистики продаж в виде диаграмм (только для менеджера и администратора)
- Просмотр системных логов (только для менеджера и администратора)
