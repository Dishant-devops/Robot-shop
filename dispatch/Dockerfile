FROM golang:1.22

WORKDIR /go/src/app

COPY *.go .

RUN go mod init dispatch && go mod tidy
RUN go install

CMD ["dispatch"]
