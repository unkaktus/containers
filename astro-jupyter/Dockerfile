FROM python:3.10
ENV DEBIAN_FRONTEND=noninteractive
RUN apt-get -yqq update \
 && apt-get -yqq install --no-install-recommends \
      curl \
      ffmpeg \
      git \
      vim-tiny \
      make \
      libhdf5-dev \
  && apt-get clean
RUN pip install astropy h5py scipy matplotlib jupyterlab
EXPOSE 8888
ENTRYPOINT [ "jupyter-lab", "--no-browser", "--allow-root"]