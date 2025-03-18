FROM registry.access.redhat.com/ubi9/python-312:latest

RUN dnf install -y make gcc gcc-c++ && \
    dnf clean all
x
RUN pip install poetry

