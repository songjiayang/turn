ARG CI_GO_VERSION
FROM golang:${CI_GO_VERSION}

ADD . /go/src/github.com/gortc/turn
WORKDIR /go/src/github.com/gortc/turn/e2e/turn-client
RUN go install .

CMD ["turn-client"]
