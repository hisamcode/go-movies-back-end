## dont forget to change middleware enableCORS

## to linux
```bash
CGO=ENABLED=0 GOOS=linux GOARCH=amd64 go build -o gomovies ./cmd/api
```