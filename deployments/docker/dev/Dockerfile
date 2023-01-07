FROM golang:1.19.2-alpine3.16

RUN apk update && apk add git

RUN go install github.com/cosmtrek/air@latest

WORKDIR /app

CMD ["air", "-c", ".air.toml"]
