FROM golang:1.20

WORKDIR /app

RUN go mod init feedme

COPY *.go ./

RUN go build -o /fullcycle

ENTRYPOINT ["/fullcycle"]