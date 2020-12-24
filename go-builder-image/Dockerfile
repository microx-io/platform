############################
# step 1 prepare builder image
############################
FROM golang:alpine3.12 AS builder
RUN apk update && apk add --no-cache git

RUN apk update && apk upgrade