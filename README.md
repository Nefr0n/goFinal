Simple REST API
LOCAL SETUP
1.  go mod tidy
2.  go install github.com/pressly/goose/v3/cmd/goose@latest
3.  Source .env
4.  Make migrate-up
5.  go run main.go
6.  
   ![image](https://github.com/user-attachments/assets/b8ca5ad1-7487-4442-a9b4-eeefce8b11c3)
Register a new user
run a database->email/password/nickname
GET USER/UPDATE/DELETE/SOFT DELETE by ID
Стек технологий:
*Go (Golang)
*Gin (HTTP-фреймворк)
*GORM (ORM для работы с PostgreSQL)
*PostgreSQL (Реляционная база данных)
*Goose (Миграции базы данных)
*Docker (Контейнеризация)
*Swagger (Документация API)

