```bash
migrate create -ext sql -dir db/migrations -seq create_users_table
```

```bash
migrate --path db/migrations --database 'postgresql://root:password@localhost:5432/mydb?sslmode=disable' -verbose up
```