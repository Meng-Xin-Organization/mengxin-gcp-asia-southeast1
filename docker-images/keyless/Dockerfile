# FROM ubuntu:21.10

# RUN apt-get update
# RUN apt-get install curl gnupg gpgv -y
# RUN curl -C - https://pkg.cloudflare.com/pubkey.gpg | apt-key add -
# RUN echo 'deb http://pkg.cloudflare.com/ xenial main' | tee /etc/apt/sources.list.d/cloudflare-main.list
# RUN curl -C - https://pkg.cloudflare.com/pubkey.gpg | apt-key add -
# RUN apt-get update
# RUN apt-get install gokeyless -y

FROM golang:alpine
# RUN go get -u github.com/cloudflare/gokeyless/...
RUN go install github.com/cloudflare/gokeyless/cmd/gokeyless/...