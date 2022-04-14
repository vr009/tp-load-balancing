FROM golang:1.16 AS build

ADD . .

RUN rm $HOME/go/go.mod

RUN go mod tidy

RUN go build ./main.go

EXPOSE 8080

CMD ./main
