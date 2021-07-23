FROM golang:1.15
WORKDIR /go/src/hello
COPY . .
COPY main.go /main.go
RUN go get -d -v ./...
RUN go install -v ./...
ENTRYPOINT ["/main.go"]
