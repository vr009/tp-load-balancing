FROM golang:1.16 AS build

ADD . .

RUN go build ./main.go

EXPOSE 8080

CMD ./main
