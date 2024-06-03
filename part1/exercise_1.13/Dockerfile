FROM golang:1.22.3

EXPOSE 8080

WORKDIR /usr/src/app

COPY . .

ENV REQUEST_ORIGIN="http://localhost"

RUN go build

CMD ["./server"]