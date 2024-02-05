FROM python:3.11-alpine3.19

LABEL maintainer="rkjnice@gmail.com"

RUN apk add --no-cache \
    gcc \
    musl-dev && \
    pip install pylint==3.0.3 \
    pylint_django==2.5.5 \
    pycodestyle==2.11.1 \
    flake8==7.0.0 \
    black==24.1.1 \
    mypy==1.8.0 \
    isort==5.13.2
