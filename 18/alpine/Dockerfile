FROM node:18-alpine

LABEL maintainer="me@codingoncatnip.de"

ENV PYTHONUNBUFFERED=1
RUN apk add --update --no-cache python3

RUN apk --no-cache add curl bash
RUN curl -sSL https://sdk.cloud.google.com | /bin/bash
ENV PATH="/root/google-cloud-sdk/bin:${PATH}"