## Build
docker build -t go-example .

## Run
docker run -it --rm --name go-instance -p 8084:8084 -v ./go-example:/go/src/MathApp -w /go/src/MathApp go-example