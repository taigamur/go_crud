Go,PostgreSQLのCRUD処理

```
createuser -P -d test
createdb test
psql -U test -f setup.sql -d test
go get -u github.com/lib/pq
go run main.go
```
