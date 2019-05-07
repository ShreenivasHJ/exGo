# go samples
A sample go microservice blocks for [kintohub](http://kintohub.com)

It is using go `1.10.0`

# First time setup
* `go build main.go`

# Run
- `./main` will launcrhs the server on port `80`

# Run in docker
- `docker build -t go-test .`
- `docker run -d --name=go-test -p 80:80 go-test` 
