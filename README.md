# Running the server

Run
```bash
go run server.go
```
This should start the server and make the GraphQL playground available at http://localhost:8080

# Making changes to the API

Any change to the schema should be followed with
```bash
go run github.com/99designs/gqlgen generate
```