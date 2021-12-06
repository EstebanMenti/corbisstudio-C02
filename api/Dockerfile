FROM golang:1.14

WORKDIR /go/src/app

COPY main.go /go/src/app/

# Download all the dependencies
RUN go get -d -v ./...

# Install the package
RUN go install -v ./...

#EXPOSE 5000

CMD ["app"]
