Для работы через PostgreSQL, нужно установить сервер этой СУБД на ПК, 
или указать url адрес базы данных на удаленном сервере. 
Иначе, использовать engine на sqlite+aiosqlite.

Шаблон для файла .env
'''
TOKEN=<ваш токен>
DB_LITE=sqlite+aiosqlite:///db.sqlite3
'''