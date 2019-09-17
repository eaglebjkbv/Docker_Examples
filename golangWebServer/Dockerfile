FROM golang:1.13.0-buster
WORKDIR $GOPATH/src
ADD . $GOPATH/src
RUN echo $GOPATH
RUN go build -o main .
EXPOSE 8000
CMD ["./main"]
