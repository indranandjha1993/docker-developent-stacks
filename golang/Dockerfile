FROM golang:latest

COPY src/ /golang

WORKDIR /golang

RUN go build -o main .

CMD ["./main"]
