FROM golang:alpine as builder

WORKDIR /go/src/app
COPY . .

RUN GOOS=linux go build -ldflags="-w -s" -o /app app.go