FROM golang:1.21
WORKDIR /app
COPY . .
RUN go build -o worker
CMD ["./worker"]
