# hash:sha256:1817ea88ae725abfc8f13db0a123e4b35fa8f252537823111c3f61fd1a8975d5
FROM registry.codeocean.allenneuraldynamics.org/codeocean/jupyterlab:3.0.9-miniconda4.9.2-python3.8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip3 install -U --no-cache-dir \
    numpy \
    pandas
