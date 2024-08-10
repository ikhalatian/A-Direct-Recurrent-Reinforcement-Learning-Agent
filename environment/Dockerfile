# hash:sha256:323866c9d57b14dd7614a9c916c03750763f8ffa5cdcd55d23a4a27a869c0314
FROM registry.codeocean.com/codeocean/miniconda3:4.9.2-python3.8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

RUN conda install -y \
        jupyter==1.0.0 \
        jupyterlab==3.2.1 \
    && conda clean -ya

RUN pip install -U --no-cache-dir \
    joblib==1.1.0 \
    matplotlib==3.5.1 \
    numpy==1.22.0 \
    pandas==1.3.5 \
    seaborn==0.11.2 \
    tqdm==4.62.3
