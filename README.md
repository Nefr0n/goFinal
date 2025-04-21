Simple REST API

1st service:

Register a new user

run a database->email/password/nickname

2nd service:

GET USER/UPDATE/DELETE/SOFT DELETE by ID

![image](https://github.com/user-attachments/assets/b8ca5ad1-7487-4442-a9b4-eeefce8b11c3)
LOCAL SETUP
1.  go mod tidy
2.  go install github.com/pressly/goose/v3/cmd/goose@latest
3.  Create .env file

DB_HOST=localhost
DB_USER=postgres
DB_PASSWORD=yourpassword
DB_NAME=yourdb
DB_PORT=5432

4.  Source .env
5.  Make migrate-up
6.  go run main.go

Стек технологий:
Go (Golang)
Gin (HTTP-фреймворк)
GORM (ORM для работы с PostgreSQL)
PostgreSQL (Реляционная база данных)
Goose (Миграции базы данных)
Docker (Контейнеризация)
Swagger (Документация API)

