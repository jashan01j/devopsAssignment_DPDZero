FROM golang:1.20-alpine

WORKDIR /app

COPY . .

RUN go mod download
RUN go build -o main .

EXPOSE 8001

CMD ["./main"]