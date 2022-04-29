FROM golang:1.16 AS build

ENV GOPATH=/

ADD . .


RUN go mod tidy

RUN go build ./main.go

EXPOSE 8080

CMD ./main
