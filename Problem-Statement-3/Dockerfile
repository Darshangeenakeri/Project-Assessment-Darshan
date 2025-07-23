FROM golang:1.22.12


WORKDIR /app

COPY . .

RUN go build -o datetime-app

CMD ["./datetime-app"]

EXPOSE 8080
