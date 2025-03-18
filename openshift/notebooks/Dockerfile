FROM registry.access.redhat.com/ubi9/python-312:latest

RUN dnf install -y make gcc gcc-c++ libmagic-devel libmagic-libs && \
    dnf clean all

RUN pip install poetry

