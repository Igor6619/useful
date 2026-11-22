1. Откройте в браузере http://localhost:5051 (подождите пару секунд, если страница только прогружается).
2. Войдите в pgAdmin:
	• Email: admin@admin.com
	• Password: admin
3. Нажмите Add New Server:
	• General -> Name: shpi-db
	• Connection -> Host name/address: host.docker.internal
	• Port: 5832
	• Maintenance database: shpi-db
	• Username: postgres
	• Password: postgres
4. Нажмите Save — теперь дерево таблиц откроется без ошибок, и вы сможете проверить созданную таблицу product_type после теста эндпоинта.Здесь будут храниться полезные материалы

