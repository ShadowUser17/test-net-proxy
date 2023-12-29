#### Build binary file:
```bash
go mod tidy
```
```bash
go build -ldflags="-s -w" -o ./server ./cmd/main.go
```
