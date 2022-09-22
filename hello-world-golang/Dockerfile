FROM golang:1.19.1-alpine

WORKDIR /app

COPY go.mod ./
#COPY go.sum ./
#RUN go mod download

COPY *.go ./

RUN go build -o /hello-world-golang

EXPOSE 3002

CMD [ "/hello-world-golang" ]
