FROM python:2-alpine3.10
LABEL maintainer="Farshad Nematdoust <farshad@nematdoust.com>"
RUN apk add gcc make libffi-dev openssl-dev  musl-dev openssh
RUN pip install ansible
ENTRYPOINT [ "ansible" ]