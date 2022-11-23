## JSON Auth Server
#### Установить все зависимости
    npm install
#### Создать файл с базой данных 
    db.json
#### Заполнить данными
    {
        "users": []
    }
#### Запуск сервера
    json-server-auth db.json
#### Команды curl
###### Регистрация
```PowerShell
    curl -d "email=test&password=test" -X POST http://localhost:3000/register
```
###### Авторизация
```PowerShell
    curl -d "email=test&password=test" -X POST http://localhost:3000/login
```