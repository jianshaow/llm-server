ARG BASE_IMAGE=jianshao/torch-rt-base
ARG TAG=2.2.1-cpu

FROM ${BASE_IMAGE}:${TAG}

ARG REQUIREMENTS=requirements.txt
COPY ${REQUIREMENTS} .
RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir -r ${REQUIREMENTS}
